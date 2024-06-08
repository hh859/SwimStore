# Swim Store
## Full Stack Frameworks with Django Milestone Project 4 

  ![alt text](https://github.com/hh859/SwimStore/blob/main/pictures/website/main%20page.png)

Swim Store is a premier online destination catering to professional swimmers, enthusiasts, and parents. We offer a comprehensive range of swimming attire and equipment suitable for every occasion—from rigorous training sessions and open water meets to regular swimming activities. Our selection includes professional suits for men, women, and children of all ages, as well as specialised training gear and casual swim accessories.

Our website provides a browsing and purchasing experience featuring a diverse choice of brands, sizes, and colours. Enjoy a fast and efficient checkout process, easy order management, and the ability to create a personalised profile for future purchases.

Swim Store is dedicated to serving swimmers of all ages, helping them find the perfect gear to enhance their swimming experience - [click here to visit](https://swim-store-45c460b85d20.herokuapp.com)


## User Stories 
 - As a user, I want to find the right size easily
 - As a user, I want to sort items using search criteria
 - As a user, I want to be able to create a personal profile
 - As a user, I want to save my card details for future purchases
 - As a user, I want to be able to update my basket
 - As a user, I want to be able to make an order at any time convenient for me

## UX/UI Aims 
- To provide an easy and interactive search process and site navigation
- To offer the opportunity to checkout with or without creating an account
- To attract users with appealing design and visuals
- To offer users the option to manage and update their account

## Design and Wireframes 
1. **Front page**
   -  ![alt text](https://github.com/hh859/SwimStore/blob/main/pictures/figma/Front%20page.png)
  
2. **Store page**
   - ![alt text](https://github.com/hh859/SwimStore/blob/main/pictures/figma/store%20page.png)
  
3. **Shopping basket**
   - ![alt text](https://github.com/hh859/SwimStore/blob/main/pictures/figma/Shopping%20basket.png)

4. **Mobile View**
   - ![alt text](https://github.com/hh859/SwimStore/blob/main/pictures/figma/mobile%20view.png)

## Website Features
1. **Front Page**
The front page of Swim Store is designed to provide a user-friendly and engaging experience for all visitors. It includes the following features:
   - Search Box: A well-placed search box allows users to effortlessly search for specific items by keywords, brands, sizes, colours, or categories. This feature ensures that visitors can quickly locate the products they need.
   - Login/Account Link: A convenient login/account link enables users to access their profiles with a single click. Registered users can manage their accounts, view order history, track current orders, and save their favourite items for future purchases.

2. **Profile Page**
   -  Users can update and manage their personal information, including contact details, shipping addresses, and payment methods. This ensures that all information is current and accurate for seamless transactions. They can also save their details. The ability to save and manage personal details allows for faster checkout processes for future purchases. Users can store multiple shipping addresses and preferred payment methods securely.
   - Users can view their order history, track the status of current orders, and access details of past purchases. This feature provides transparency and convenience, helping users stay informed about their orders.

3. **Checkout Page**
   - The checkout page's streamlined design ensures that users can complete their purchases quickly and securely with minimal hassle.
   - Registered users can easily utilize their previously saved information, such as shipping addresses and payment methods, for a quicker checkout experience.
   - The checkout page allows new users or those who prefer to use different details to enter shipping and payment information. This flexibility ensures that all customers can complete their transactions according to their preferences.
   - Before finalising the purchase, users can review their order details, including selected items, quantities, and total cost, to ensure accuracy.

## Future Improvements
- **Product Account Management** - to allow users to manage their product preferences and saved items, making it easier to revisit and purchase their favourite products. This would include the ability to create wishlists and set notifications for restocks or sales on specific items
- **Multiple Payment Options** - to allow the checkout page to support various payment methods, providing customers with the convenience of choosing their preferred option

## Testing 

### Known Bugs 
There was an issue with Python version compatibility, which required an update for the older version. Currently, when opening the project and running the command, the terminal returns the following:
  ![alt text](https://github.com/hh859/SwimStore/blob/main/pictures/website/Python%20version.png)
To resolve it, the following commands are used: pyenv install 3.9.19, then pyenv local 3.9.19, and then the project is running. 


## Deployment 
The site is hosted on Heroku and deployed from GitHub. To host the products, the site is connected to AWS storage, which holds the static files. PostgreSQL is used as the database for storing data:

1. Go to Code Institute and input email to create a new database
2. Receive a link with your newly created account credentials.
3. Copy the link to the workspace.
4. Update settings.py in the project directory with this URL.


Deployment to Heroku:
1. Register and log in to Heroku.
2. Navigate to New > Create New App.
3. Select a unique name for the app.
4. Go to Settings > Reveal Config Vars.
5. Add all variables from env.py to the Config Vars of the Heroku app.
6. Add the Heroku app URL to ALLOWED_HOSTS in settings.py.
7. Create a file named Procfile in the root directory.
8. Navigate to Deploy > GitHub > Connect.
9. Navigate to Deploy > Deploy Branch.
10. Use the 'Open App' button at the top of the page to open the site.

## Validations
 - **HTML**
   - main page 
  ![alt text](https://github.com/hh859/SwimStore/blob/main/pictures/website/main%20page%20validator.png)
   - shopping bag
  ![alt text](https://github.com/hh859/SwimStore/blob/main/pictures/website/shopping%20bag%20validator%20.png)
   - login page
  ![alt text](https://github.com/hh859/SwimStore/blob/main/pictures/website/login%20validtor.png)
   - register page
  ![alt text](https://github.com/hh859/SwimStore/blob/main/pictures/website/register%20validator.png)
   - profile page
  ![alt text]((https://github.com/hh859/SwimStore/blob/main/pictures/website/profile%20validator.png)
   - producs page
  ![alt text](https://github.com/hh859/SwimStore/blob/main/pictures/website/products%20page%20validator%20.png)
   - product management page
  ![alt text](https://github.com/hh859/SwimStore/blob/main/pictures/website/product%20management%20valdator%20.png)


 - **CSS**
  ![alt text](https://github.com/hh859/SwimStore/blob/main/pictures/website/CSS%20validator.png)


## Credits 
### Technologies 
#### Frameworks and Libraries 
- [Bootstrap](https://getbootstrap.com/) was used to create design and stylign for the website 
- The icons were supplied by [Font Awesome](https://fontawesome.com/)
- [jQuery](https://jquery.com/) was responsible for event handling and animation 
- The project was created in the [Gitpod](https://www.gitpod.io/ )
- And stored in the [GitHub](https://github.com) 
- [Heroku](https://www.heroku.com/) was used for database 

#### Languages 
- [HTML](https://www.w3schools.com/html/)
- [CSS](https://www.w3schools.com/css/)
- [JavaScript](https://www.javascript.com/)
- [Python](https://www.python.org/)




