[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/2xEWLklS)
Summary of Changes from Part 2 to the final POE.
So first and foremost, I’d like to start with what will be in the final POE.
1.	Home.tsx : Will display the average price of menu items by course.
2.	Manage Menu.tsx: Allows the chef to add and remove menu items.
3.	Filter 9Menu.tsx: Allows the customers to filter menu items by course.
4.	App.tsx: Integrates the components and sets up routing.

Sign In Screen.
•	State Management: I used “useState” to manage the state of the username and password inputs.
•	Text Input Components: These components allow the users to input their username and password. 
•	Button Component: This component triggers the “handleSignIn” function when pressed.
•	Alert: I used the “Alert” component to display messages to the user, such as errors or success messages.
•	Styles: The Style Sheet object is used to define styles for the components. 

This basic login screen provides a simple user interface for entering a username and password, with basic validation to ensure both fields are filled out before proceeding.












Menu Screen

•	State Management: I used “useState” to manage the state of the menu items and the new item being added to the menu.
•	Text Input Components: These components allow the chef to input the dish name, description, and price.
•	Radio Buttons: I used “TouchableOpacity” component to create radio buttons for selecting the course. The selected course is highlighted.
•	Button Component: This component triggers the add Item function to add the new item to the menu and the remove Item function to remove an item from the menu.
•	FlatList Component: This component displays the list of menu items, with each item showing its name, description, course, and price, along with a remove button.
•	Styles: The Style Sheet object is used to define styles for the components.

This screen provides a user-friendly interface for the chef to manage the menu items, including adding new items and removing existing items.




Home Screen.
•	State Management: Used the “use State” to manage the state of the menu items.
•	Calculate Average Price Function: This function calculates the average price of menu items for a given course.
•	Text Component: These components display the total number of menu items and the average price of menu items broken down into different courses.
•	Flat List component: this component displays the complete menu, with each item showing its name, description, course, and price.
This home screen provides a comprehensive view of the menu, including the total number of items, average prices by course, and the complete list of menu items.

Here's an overview of what the app will look like and how it will run:
App Overview
1.	Home Screen:
o	Displays the total number of menu items.
o	Shows the average price of menu items broken down into different courses (Starters, Mains, Desserts).
o	Lists all the menu items with their details (name, description, course, price).
o	Includes navigation buttons to other screens (Menu, Manage Menu, Filter Menu, Sign In, Login).
2.	Menu Screen:
o	Allows the chef to add new menu items by entering the dish name, description, selecting the course (using radio buttons), and price.
o	Displays the list of added menu items with options to remove them.
3.	Manage Menu Screen:
o	Like the Menu Screen but focused on managing existing menu items.
o	Allows the chef to add, edit, and remove menu items.
4.	Filter Menu Screen:
o	Allows guests to filter menu items by course (Starters, Mains, Desserts).
o	Displays the filtered list of menu items based on the selected course.
5.	Sign In Screen:
o	Provides a simple sign-in form with fields for username and password.
o	Includes a sign-in button to handle the sign-in process.
6.	Login Screen:
o	Like the Sign in Screen, but can be used for a different purpose, such as admin login.


How the App Will Run
1.	Navigation:
o	The app uses React Navigation to handle navigation between different screens.
o	The App.tsx file sets up the stack navigator with all the screens.
2.	State Management:
o	The app uses Reacts useState hook to manage the state of menu items and form inputs.
o	Each screen manages its own state and updates it based on user interactions.
3.	User Interactions:
o	Users can navigate between screens using buttons on the Home Screen.
o	Chefs can add new menu items on the Menu Screen by filling out the form and clicking the "Add Item" button.
o	Chefs can manage existing menu items on the Manage Menu Screen, including adding, editing, and removing items.
o	Guests can filter menu items by course on the Filter Menu Screen.
o	Users can sign in using the Sign in Screen and Login Screen
