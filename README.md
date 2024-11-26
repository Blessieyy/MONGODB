CodeTribe DataBase Mongo

## Installing the DataBase
# First install MongoDB and MongoDB Shell(Shell as an .msi)

# After that open up the CMD to check if the version is the latest
"Mongod --v"

# Run the program to begin the test
"mongosh"
![Project](/screenshots/mongo_cmd.jpg)

## Add collecions

First Create a document that will populate he collections and document

# Add the collection using db.collecionName and using the Data Fields for the document to fill in the details

# collections are, Facilitators, Trainees and Projects

# For Facilitators
School> db.Facilitators({name: "", location:"", course:""})

# For Trainees
School> db.Trainees({name: "", location:"", course:""})

# For Project
School> db.Projec({name: "", location:"", course:""})



![Project](/screenshots/mongo_cmd2.jpg)