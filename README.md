# PostHub

PostHub is a full stack social media app built using the MERN stack.

## How to use

1. Use **`git clone`** or download this repository.

2. Create a [MongoDB](https://www.mongodb.com) account and set up a database. To do this go to **Databases -> Create a cluster -> Browse collections -> Create database**.
To use this databse we also need to create a database user which we can do on the **Database Access** tab, and we also need to go to **Network Access** and add your current IP Address.

3. Go to the `.../server/` folder, create an empty file and name it **`.env`**. Here we will make the connection to the database.

   - On the first line of the file put **`PORT = <number>`**, where `<number>` is a port of your choosing, witohut the `<>`.

   - On the second line
