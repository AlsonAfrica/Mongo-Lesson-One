# Mongo-Lesson-One
## OverView:
MongoDB is a noSQL database, which means it stores data differently than traditional relational database, thus it stores data in documents instead of tables and rows

## Mongosh:
Is a command-line interface that allows you to interact with MongoDB database.

#### Installations
Ensure you have MongoDB and MongoShell on your machine before proceeding or install MongoDB and MongoShell from:
* https://www.mongodb.com/try/download/community
* https://www.mongodb.com/try/download/shell

## Getting Started
* On your Windows Terminal run the following commands to start MongoDB shell by typing:

   ```bash
      mongosh


* Switch to the database you want to create by typing the following command, in my instance i will be creating a CodeTribe database:

   ```bash
       use CodeTribe


* To verify that the database was created successfully, you must insert collections into the database. Run the following command:

   ```bash
       db.collection.insertMany([{name: "Facilitators"}, {name: "Trainees"}, {name: "Projects"}])





* Verify if the database is present

    ```bash
        show dbs





* Insert Documents within the collections

    ```bash
        db.Facilitators.insertOne({ Name: "", Location:"" , Course: "" })





* Insert Documents within the collections

    ```bash
        db.Trainees.insertOne({ Name: "", Location: "" , Facilitator: "" })




* Insert Documents within the collections
   
    ```bash
        db.Projects.insertOne({ Name: "", Course: "" , Lesson: "" })
