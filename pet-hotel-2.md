# Multi Table Pet Hotel (Group Refactor)
Your client is loving the work you did for them to build their pet hotel app. You have a bit more time to refactor the data model to give them more functionality and practice your new pSQL JOIN chops.

The MVP will remain the same as the previous assignment, but the data model will change and the queries to get at the data will too.

## Implementation Details
### Database Schema
Use the database schema we used in the Data Modeling and Joins Lecture. 

### Entity Relational Diagram

![Entity Relational Diagram](erd.png)

Create these tables locally. Then update your `database.sql` file in your repo with the new schema CREATE TABLE syntax you used. 

### Views
The views and the client side behavior should remain the same as the previous assignment. See the mockup below for a reminder or refer to the first assignment description.

See [this image for a mockup of the page.](https://drive.google.com/file/d/0B10Wu-zrSBwMZ1E0Y2ZYazVXdlE/view?usp=sharing) 

NOTE: Ignore the "Visits" link you see on the image . This is reserved for Hard mode from the first version of this assignment.

### How to Start

Start by building your database locally. You can use the Entity Relation Diagram above and the `CREATE TABLES` queries from lecture. 

Then start updating your server routes to interact with the new database. Do one route at a time. This is really hard stuff. It isn't about finishing the entire refactor, but working through each route in a systematic way and everyone learning together.

Do the `GET` pets and owners route first. Insert some test data into the new database to see it work. You can use the `JOIN` queries from lecture when applicable.

After getting read from the database working, move on to create, update and delete.

