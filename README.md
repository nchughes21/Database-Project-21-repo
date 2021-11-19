# Database-Project-21-repo

## Team Name
#### NHJO

## Team Members
### Nikolas Hughes
### John Oxce 

## Outline For Project:

### Deliverable 1
#### - Make github site 
#### - Include Readme file for project overview

### Deliverable 2
#### - Reverse enginier Caampus eats script for the EERD diagram
#### - Revise EERD to make it more presentable
#### - Add 10 more loacal resturants to the EERD
#### - Implement ratings table for drivers and resturanst within the EERD diagram  

### Deliverable 3
#### - Create queries listed in Deliverable 3
#### - update github site with all information
#### - include a narrative powerpoint demonstrating the project

## Project Introduction
#### In this project we are given an existing database and are task to update the database with a rating system. While implementing the rating system we will add 20 local resturants to the database to help exicute queries at the end of the project. This project will test our skills and understanding on how to edit a EERD diagram and exicute queries based on the updated database. 

## Business Rules
#### - only Faculty, staff and students are included (Persons)
#### - Persons have accounts in the system with personid (PK), name, email, cell, etc.
#### - only students can deliver 
#### - Faculty is represented by title, highest degree, and degree college.
#### - Staff includes Position and Admin (Y or N).
#### - specified location on campus for food drop off(dorms, student center)
#### - only approved resturansts used for pick up
#### - there will be seperet ratings for the driver and resturant that will combine to make the order rating.
#### - the order rating will only be seen by the company
#### - the resturant order will only be seen by the resturant
#### - the driver rating will only be seen by the driver.
#### - it is not manditory for the customer to rate the order.

## EERD

![Screenshot (14)](https://user-images.githubusercontent.com/93001002/141687113-658a500e-84d9-4655-bde0-9524caed4f59.png)


## Data Dictionary
![Screenshot (12)](https://user-images.githubusercontent.com/93001002/141235800-97eebee7-c089-4f7f-a4b9-9e512444a048.png)


## SQL Code for Queries, Stored Procedures, Views (screen shots)
###part(a)
//This is not the correct way of doing part(b) but i kept getting errors when joining multiple tables.\\ I just implemented the restaurant_id to its appropriate position in the ratings table.\\//

![Screenshot (24)](https://user-images.githubusercontent.com/93001002/142276885-52287255-30df-4878-a900-0f1a67aeda25.png)

![Screenshot (29)](https://user-images.githubusercontent.com/93001002/142643077-8bebe25f-c174-47ad-bfd4-4eceaad898f5.png)

###part(b)
//This is not the correct way of doing part(b) but i kept getting errors when joining multiple tables.\\ I just implemented the driver_id to its appropriate position in the ratings table.\\//

![Screenshot (25)](https://user-images.githubusercontent.com/93001002/142276907-aefa13b4-40a5-4277-96d5-042833db63ed.png)

![Screenshot (28)](https://user-images.githubusercontent.com/93001002/142643099-8a910a82-efa4-472b-8e0d-cc95d153c677.png)

###part(c)
this screenshot gets the right data but the data within this database the current dates are years apart not weeks so there will usually only be one row of data
![Screenshot (21)](https://user-images.githubusercontent.com/93001002/142276926-46f20d68-6659-452d-9469-c5d5659fad97.png)

this screenshot better shows the data used as the dates are more spread out.
![Screenshot (35)](https://user-images.githubusercontent.com/93001002/142649807-550ad59c-f0cf-4fcd-a255-135c685d8e0f.png)


###part(d)
again just to mention this is a good example of the right query but the data is to spread out to fall wihtin a specified week of values and will only return a count of 1
![Screenshot (27)](https://user-images.githubusercontent.com/93001002/142291450-450a20d8-7d68-4b54-8d89-c037e2b4be12.png)

### part(e)

![Screenshot (31)](https://user-images.githubusercontent.com/93001002/142643946-393512ae-6fc4-479c-b1ab-f6470c230816.png)

### part(f)

### Trigger for Restaurants Table


## Future Work
####- create approval system within database for drivers and resturants

Have folders for images, code.
Turn in Github URL.
