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
