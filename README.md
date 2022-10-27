# PostHub

PostHub is a full stack social media app built using the MERN stack.

## How to use

**1.** Use **`git clone`** or download this repository.

2. ###MongoDB Setup
- Create a [MongoDB](https://www.mongodb.com) account and set up a database. To do this go to **Databases -> Create a cluster -> Browse collections -> Create Database**.
- To use this databse we also need to create a database user which we can do on the **Database Access** tab; afterwards go to **Network Access** and add your current IP Address. 
- The last thing we have to do here is to go to **Databases -> Connect** and get the connection string for VS Code. The string will look something like this `mongodb+srv://<user>:<password>@cluster.gidso.mongodb.net/<Database>?retryWrites=true&w=majority` and this is where we put the username and password from the user we created (Note: if no database name is provided a new one will be created).

**3.** Go to the `.../server/` folder, create an empty file and name it **`.env`**. Here we will make the connection to the database.

   - On the first line of the file put **`PORT = <number>`**, where `<number>` is a port of your choosing, witohut the `<>`.

   - On the second line put **`CONNECTION_URL = <connection string>`**, and for `<connection string>` we will be using the one we got from MongoDB. After this we can save and close the file.

**4.** Open two terminals and:
   - On one terminal navigate to **`.../client/`**.

   - On the other terminal navigate to **`.../server/`**.

   - Use the command ###`npm start` on both of them.
  
**5.** Done!
