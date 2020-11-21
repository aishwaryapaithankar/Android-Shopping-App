# Android-Shopping-App
**Replace <YOUR_API_KEY> to your google api key in AndroidManifest file in order to run the project**


**AIM**

To design a general online shopping application which provides various facilities such as the information about the products, easy traversal between modules , cart, Generation of total bill and therefore is user friendly .




**INTRODUCTION**

 The project will launch with the home page of the application. And proceed through the modules like product display , Navigation menu ,locator and shopping cart.Also additional features like validation of use of back button has been done for the home page.


**MODULES**





LOGIN OR REGISTER

To access the contents of the shopping application, the user needs to login or register.





NAVIGATION MENU

After logging into the application , the user can traverse through the different categories and products with the help of the navigation bar.

The navigation bar includes three categories:

    Books

    Electronics

    Clothing

Clicking on any of the categories opens the page with the products related to the same.
Clicking on any category will open the related category page. Also logout option is available in the navigation bar.



PRODUCT PAGE

Clicking on a product will open a page with the information of that product.The page will contain image of the product for better understanding for the user.
Price and the product name will be displayed on the product page .
There will be a add to cart button at the bottom which will add the product info into the database after the confirmation of the user if he/she wants to buy it.





CART

The cart will open on clicking the add to cart button for a specific product.
The product will be added to cart after the user clicks on add to cart button again.Clicking on the show will show the total bill and the products added to the cart .





LOCATE US

The locate us module is a part of the navigation bar menu. It contains a map to physicallylocate the shop.
Clicking on the directions button will open google map application to guide the user to the shop.





**TECHNOLOGY USED**

Android studio is the IDE used to develop the online shopping application . It has features such as instant run, intelligent code editor, emulator etc.
Google maps is used to locate the shop and real time directions from the current location.Google map service has been added on Fragment.
SQLite is used to create and manage the database for login , register and the cart.
Intent has been used to traverse from one activity to another



**CONCLUSION** :

This Android Shopping application gives the user a display of available products and enables the user to add the selected products to cart and view the list of those items. 
The total price will be displayed. Hence , the flow of the application is successfully completed considering all the modules in the application.



**FUTURE SCOPE**

The project can be extended and made for administrator side.As of now , it is for customers only.Instead of using an inbuilt database like SQLite , we can use a centralized database server like MySQL

