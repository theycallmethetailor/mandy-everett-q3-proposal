# mandy-everett-q3-proposal

## Project Description

I'm proposing to recreate a local Chinese food restaurant's website using React. http://www.asiancafeexpress.com/about-us. I intend to recreate the home/menu/Location & Hours/About Us pages, but with the menu page having a mock ordering functionality. 

I also hope to try to make the design more modern-looking.

## Who uses it?

Users would be potential and current customers for the restaurant. 

## What outputs do they need?

Users would need to be able to see the menu, which will be provided by the database, and will be able to 

### Menu

| ID            |  Name           | Description  | Price | Options | Image_url
| ------------- |:-------------:| ---------:| --------| -------|---|
| 1             | Mongolian Chicken | Declicious chicken with stuff.     | $5.00 | [array] | www.url.com
| 1             | Mongolian Chicken | Declicious chicken with stuff.     | $5.00 | [array] | www.url.com
| 1             | Mongolian Chicken | Declicious chicken with stuff.     | $5.00 | [array] | www.url.com

### Orders

|ID | Customer_id |Customer Name | Ordered_at | Scheduled_for| Total
|---|-------------|----------|------------|--------------|------|
|1  | 3  |Mandy   | TIMESTAMP  | TIMESTAMP    |$25.00 |




## What inputs are needed to generate those outputs?

The customer would need to select items and quantity of items to place in their cart, and provide their name/when they want the order. 

### Order Info 

| Name      | Schedule For | Items
|----------|--------------|---------|
|Mandy     | TIMESTAMP    | [Array]

The items array would be generated by the cart that's updated as a user interacts with the page. 

## A list of technologies that you plan to use

* Backend: 
  * Node.js
  * Express
  * PostgreSQL
* Frontend
  * React.js/Vue.js
  * Moment.js
  * Schedulure.js

## A well-defined and written-out feature list

#### User Stories

##### Landing Page
 
 1. When a user goes to "/", they'll arrive at the landing page
 2. On the landing page, the user will see a NavBar with a Menu, Location & Hours, About Us, and Home page links. 
 3. On the landing page, the user will see a blurb about the restaurant
 4. STRETCH: the user will also see a "Dish of the Week" component that will display a list of dishes of the week ordered by most recent. 
 5. On the landing page, the user will see a Press section component

 ##### Location & Hours Page

 1. When a user goes to "/contacts", they'll see the store's contanct/location info view. 
 2. STRETCH On the Location & Hours page, the user will see a contact form that will send an email to the owner
 3. STRETCH On the Location & Hours page, the user will see a map view of the location. 

 ##### About Us

 1. When a user goes to "/about", they'll see the store's about view
 2. The about view will simply contain a blurb about the owners and their business, as well as a picture. 

 ##### Menu

 1. When a user vitis "/menu", they'll see the menu view
 2. In the menu view, the user will see the menu items displayed by category (i.e. Appetizers, Hong Kong)
 3. The categories can be toggled as visible/hidden
 3. The menu items should have a picture/name/and price. 
 4. Users can toggle the description for the menu item. 
 5. In the menu page, there will be an "Order Online" button, when clicked, the button will prompt users to login/register to make an order
 6. The login form works as one would expect
 7. The registration form works as one would expect. 
 8. If the user is logged in, a cart icon with a number bage for items in cart, as well as a sidebar with the car items will be rendered
 9. If a user clicks the "order" button on a menu item, a dialogue will pop up, requiring them to specify the quantity. 
 10. If a user clicks "Submit" on the order dialogue, the item with a specified quantity will be added to the cart. 
 11. If a user clicks the "checkout" button in the cart sidebar, or the cart icon, they are taken to a checkout page ("/checkout"), which displays the cart items/total. 
 12. Clicking "submit" in the checkout page sends adds the order to the orders table.
 13. If a user clicks the trashcan icon on a cart item, the item is removed from the cart. 
 14. If a user clicks the edit icon on a cart item, they can change the quantity. 

 ##### Stretch

 1. When a user clicks the "order" button, the dialogue also displays certain options (i.e. spiciness, white or brown rice, etc.)
 2. The user can reorder past orders. 





