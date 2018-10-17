# meteor-mongo-practice

http://courses.ics.hawaii.edu/ics314f18/morea/mongo/experience-meteor-mongo.html
http://courses.ics.hawaii.edu/ics314f18/morea/mongo/experience-simple-schema.html

# Summary
### If you’ve followed along, you should now have a basic idea of how Meteor and Mongo work together. In brief:

- Define a variable that is bound to your Meteor collection in a directory that will be loaded on both client and server. Use this variable to manipulate your collection whether the manipulation occurs on the client-side or on the server-side.

- You can initialize collections with documents by running code on the server-side that inserts documents. Since Meteor synchronizes the client and server-side databases, these documents will be available on both the client and server side.

- Use meteor reset if you need to reset your application’s database to the empty state.

### If you’ve followed along, you should now have a basic idea of how to use Simple Schema. In brief:

- You must install both the Simple Schema and Collection2 packages.

- Define a schema for your collections. In this case, our schema was super simple. Read the documentation to learn about all of the possible approaches to constraints.

- Attach the schema to your collection. Then, whenever you do an insert or update, Meteor will throw an error if the document is not structured correctly.

- If you want to check to see if a document is valid before doing the insert, you can use the `validate()` method. See the documentation for more details.
