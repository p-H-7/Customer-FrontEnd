# Customer Front End
* This is an Client side FrontEnd Application for an E-Commerce and is integrated with an Admin Dashboard [Website](https://github.com/p-H-7/E-Commerce-Admin/edit/main/README.md) . This is built using
[Next.js](https://nextjs.org/) framewrok, and [styled-components](https://styled-components.com/) is used for styling. [MongoDB](https://www.mongodb.com/) is used for database and Node.js is used backend.

## Getting Started
Kickstart by using  the 
```bash
 `npm install`
```
command to install dependencies.

Start the application on terminal by these two commands
 ```bash
 `yarn build` `yarn start`
```
Landing page has a a feature product area where a display of product is shown in the Layout.
Navbar has a list of pages of **Home**, **Products** and **Cart**.

New Arrivals where all the new arrivals are displayed.
Each product has a single page dedicated where all the details are shown.

All the product information is retrieved from the MongoDB database, which can be updated from [E-commerce-Admin](https://github.com/p-H-7/E-Commerce-Admin/edit/main/README.md).
*  ***Order Item***page where we can **Add to Cart** it is an array of `OrderItem_id`, `qauntity`, `price`, `field`
* ***Cart*** is an array of `cart_id`, `quantity`
* ***Customer Details***. On the final checkout, we request information of customer in a `string` format in an array of `Name`, `E-mail`, `City`, `Postal code`, `Street Address`, `Country`.

Below ae the working images of the website.
![image](https://github.com/p-H-7/Customer-FrontEnd/assets/82563863/1a4f016b-1d71-47c0-9ead-d09bf732eb0c)

![image](https://github.com/p-H-7/Customer-FrontEnd/assets/82563863/8ab4d619-3cd6-43ed-967d-3af82b989e46)

![image](https://github.com/p-H-7/Customer-FrontEnd/assets/82563863/25346205-b16b-42c1-b8cb-e70220826c8b)

![image](https://github.com/p-H-7/Customer-FrontEnd/assets/82563863/85294214-6236-4921-a458-fd631a93adb3)





