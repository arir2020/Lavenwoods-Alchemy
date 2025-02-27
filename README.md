# Lavenwoods-Alchemy

## App name: Lavenwoods Alchemy
Short app description
User chooses between 4 mages of an element class.  The mage they choose will craft them a potion based on their element, and the user will be able to define the effects of their potion. Once the potion is created, it will be added to their potion bag.


## Basic low-fidelity wireframes

![20220124_101519](https://user-images.githubusercontent.com/95322104/150819360-daf3cc97-42ed-4b6f-8718-9dc54c964d52.jpg)


![20220124_101553](https://user-images.githubusercontent.com/95322104/150820116-5a7d5186-eb85-4d5a-b425-325798373d4f.jpg)


![A31BC3DE-14F5-463D-9061-45857229A7BB_1_105_c](https://user-images.githubusercontent.com/95322104/150820354-191d1557-60c9-450c-b09d-821e986a1615.jpeg)






## User stories
As a user, I want to enter Lavenwoods and find out what’s Lavenwoods is about!
As a user, I want to see the shop available in Lavenwoods.
As a user, I want to see what the shop has to offer.
  3.a. As a user, I want to see the categories of products
  3.b. As a user, I want to see the properties of products
  3.c. As a user, I want to be able to request a product
4. As a user, I want to know my product request has been received
5. As a user, I want to leave the shop with a product
6. As a user, I want to be able to reenter the shop
12:05


## Stretch Goals
I want to be able to see the mage’s specialities
I want to be able to create my own potion from stratch
I want to be able to visit our parts of Lavenwoods
I want to be able to view my inventory throughout my transactions


## MVP goals list
Main page with clickable list of Mages
Create Mage button
View Potion bag button
Going back button
Click on mage: Brought to a page with information about that mage
Request Potion button
Request Potion: brought to a page with a form
POTION NAME
Text field
RadioButton for predetermined potion element
Earth
Fire
Water
Air
TextArea for custom potion effects
“Create Potion” button

Potion index page with list of potions you created

Click on potion to “show” potion name and effects.
Back to main page button


## Stretch goals:


Separate “Create” Page for each mage
Ingredient list on create page that intelligently creates potion effects based on ingredient combo.



## Database ERD diagrams


![Screen Shot 2022-01-21 at 3 02 51 PM](https://user-images.githubusercontent.com/95322104/150820966-1bc46ed4-943b-4981-a690-503f631a09f6.png)













## RESTful routing chart for each database resource

![Screen Shot 2022-01-24 at 10 22 34 AM](https://user-images.githubusercontent.com/95322104/150822426-94e23d33-615e-4986-b2de-151aa9c08cde.png)



Api ideas: On potion create page, wizard says “ Ok let’s get this potion started.  You know, I heard the weirdest thing the other day.  [Random fact api here]”Returns the plain text version of a random fact.
Request type:
GET https://ffa.aakhilv.me/text
