# DynamicFoodCartApplicationUsingFirebase

This is a React Single Page Project that allows users to interact with a dynamic food cart, where available food items are loaded from a Firebase database. Users can add items to their cart, modify quantities, and have all changes reflected in the database.

# Features
Real-time Database Integration: Available food items are loaded from and synchronized with a Firebase database in real-time and The users cart is also refllected in the database.

Add Items to Cart: Users can add food items to their cart and these additions are immediately updated in the database.

Cart Modification: After adding items, users can view their cart, adjust quantities, and have these changes synchronized with the database.

Responsive Design: The application is designed to work on various screen sizes, making it accessible from both desktop and mobile devices.

# Getting Started

Clone the Repository: git clone https://github.com/Prathihaspodduturi/DynamicFoodCartApplicationUsingFirebase.git

Navigate to the Project Directory: cd project-name

Install Dependencies: npm install

Set Up Firebase: 
- create firebase project on Firebase Console.
- Set up a Realtime database in your firebase project.
- update the Firebase configuration in the project (In place of my firebase URL replace it with your firebase URL) at each fetch method usage.

Start the Development Server: npm start.

The application will open in the default web browser at http://localhost:3000.

# Technologies Used
React: A popular JavaScript library for building user interfaces.

Firebase RealTine Database: For storing and retrieving food data.

