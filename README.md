# sql-challenge
SQL Boot Camp Assignment
Basic SQL Commands. Relational Databases

This assignment wasn't too bad. I attacked the ERD first after gaining a comfortable understanding of the contents of each table. I had a bit of difficulty remembering the nuances between Primary, Foreign, and Composite keys, but I think I've come to understand it now since the composite key uses more than one column to refer to information in another table. The relationships were also challenging, but I think I now understand the relationships between the tables and their keys. 

Once the ERD was complete, I actually worked on the questions next and then wrote out the Drop and Create Table codes starting with the least dependencies first. I then had a bit of difficulty importing the tables, but eventually figured it out. I am using the browser version on my mac, so when it promted me to provide a filepath for the csv files, it added a hidden filepath prior to any filepath I tried to paste, so I kept getting 'file not found in directory'. I then found how to upload the actual files as opposed to providing the filepath and that worked well once I imported the data in the right order according to the keys. 

As I run through the codes and inspect the final result, I had inor problems getting the wildcards to operate with repsect to the dates, but then discovered it had to do with the quotations around the parameter. Once that quotation was replaced, the code ran fine. The current issue has to do with the browswer version only letting me save sql files online and not on my hard drive. When I go to 'Save As', the filepath cannot be adjusted to any location on my computer, so I'm not able to produce an actual sql file. If I try to add my own filepath, no matter how far back it extends, it is not recognized. 

As you can see below, there is a previous extension '/var/lib/pgadmin/storage/mdcummings86_gmail.com' prior to my filepath, preventing me from using 'save as' or 'back up' with just the schema. 

<img width="721" alt="image" src="https://github.com/MDCummings86/sql-challenge/assets/126340452/01bf1018-6a1b-4496-bb3a-5918559a5374">
