# MiniBlocksApp

This application will allow you to login and do the following:
  1. Go to items page and be able to create, sort, update and delete items 
  2. Got to Exhibitions page and be able to create new exhibition, sort, update list items or dates and delete items or exhibitions 

TABLES 
 
Companies I buy the items from 
1. ID  --> PH 
2. Name  
3. ItemID   --> FK 
4. Price 
5. PurchaseDate 

Items 
1. ID   --> PK 
2. Name 
3. Number 
4. AgeLevel 
5. DifficultyLevel 
6. NumberOfPieces 
7. DateBuilt 
8. Photo 
9. OverallComments 

Exhibition Locations 
1. ID 
2. LocationName 
3. Address 
4. Town 
5. PostCode 
6. ExhibitionDate 
7. Duration 

Exhibitions Halls (where you can see the items created) 
1. ID 
2. Name 
3. Description 
4. ItemsList 
5. Photos 

RELATIONSHIPS ????????
a.	An item can be sold by many Companies ==> 1 to many
b.	A Company can sell many Items ==> 1 to many

 

4.	USER STORIES
  a.	Create a database & tables
    i.	As the owner I want to create a database so I can organise and keep a record of my items
    ii.	As the owner I want to create tables so I can hold the information for my items
  b.	Create a new repo in GitHUb
    i.	As the project owner I want to create a repo in Github so I can keep all my documentation accessible and be able to share it.
  c.	Website 
    i.	As the project owner I want to have a website so I can CRUD my items
  d.	Creating Items
    i.	As a user I want to click on a button so I can create entries
  e.	Reading Items
    i.	As a user I want to click on a button so I can search for items and sort them in any way I want
  f.	Updating items
    i.	As a user I want to click on a button so I can update my items
  g.	Delete items
    i.	As a user I want to click on a button so I can delete items I do not longer have
 

 

 


WEB PAGES 

Create new User (* Required field) 
1. Name * 
2. Password * 
3. Confirm Password * 
4. Email Address * 
5. Confirm Email Address * 
6. Create button 
7. Cancel button 

Sign in page (* Required field)
1. Email Address * 
2. Password * 
3. Login button 

New Item 
1. Name of the item  
2. Number 
3. AgeLevel 
4. DifficultyLevel 
5. NumberOfPieces 
6. DateBuilt 
7. Photo 
8. OverallComments 
9. Save & Close Button 
10. Cancel Button 
