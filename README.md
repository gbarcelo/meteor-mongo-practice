# meteor-mongo-practice

http://courses.ics.hawaii.edu/ics314f18/morea/mongo/experience-meteor-mongo.html

# Summary
If you’ve followed along, you should now have a basic idea of how Meteor and Mongo work together. In brief:

- Define a variable that is bound to your Meteor collection in a directory that will be loaded on both client and server. Use this variable to manipulate your collection whether the manipulation occurs on the client-side or on the server-side.

- You can initialize collections with documents by running code on the server-side that inserts documents. Since Meteor synchronizes the client and server-side databases, these documents will be available on both the client and server side.

- Use meteor reset if you need to reset your application’s database to the empty state.
