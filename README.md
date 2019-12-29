# Worker-Server-Tracks-tweets
Worker Server Tracks tweets

This is a C# Worker Service in Visual Studio 2019 done by Louay AYADI, Every time the service runs it has to contact the twitter api and download the newest tweets to “#startup” (you can change it..).

These tweets are stored in a mongo database (mlab). just the text of the tweet and an identification id are stored inside the database.

I limited the tweets number to 30.

Here are the steps to start the service:

1- Install visual Studio (The free Community Version can be downloaded on the Microsoft website).

2- Clone the project

3- Install packages needed such as Tweetinvi and MongoDb Driver.

4- Create a developer application on twitter to get the keys to contact the API of twitter.

5- Create an account on mlab.com and create a database and a collection and replace them in my code.

And finally you can start the project and see the tweets you tracked appearing in the console output and stored in your database.
