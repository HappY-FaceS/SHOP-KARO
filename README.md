<h1 align="center">  🛒 &nbsp; Shopping App 🛒 </h1>

[SHOP-KARO BY RISHAV](https://afternoon-atoll-93127.herokuapp.com/)

## 🚩 &nbsp; Main Features

> This App was made to track the order state since the customer place it
> once it's shipped the seller mark it as shipped, and then the shipper mark it as delivered.

#### Project Functionalities

- **Register and signin system**

  - Everyone is registered as a customer.
  - Customers can apply to be sellers.
    <img src="Snapshots\apply seller.png"/>

- **Product life cycle**

  - A seller add a product.
  - A customer order some products, number in stock decreases.
  - The customer tracks the order's state since it's placed.
    <img src="Snapshots\order status.jpeg"/>
  - The shipper pick the product, the seller mark it as shipped.
  - The shipper deliver the order, and mark it as delivered.
  - The customer may want to turn it back (to be done).

- **Other facilities**

  - Users can edit their account info.
    <img src="Snapshots\account info.jpeg"/>
  - Users can add, delete or edit addresses.
    <img src="Snapshots\add delete address.jpeg"/>
  - Users can have a wishlist with any amount of products.
    <img src="Snapshots\wish list.jpeg"/>

- **Customer**

  - Sign up & login.
  - Purchase order of any amount of products.
  - Return order (To do).

- **Seller** -> all above plus.

  - Add and edit his own products.
  - Receive notifications of the new orders the customer make (only his products).
  - Mark the orders the customers make as shipped when the Shipper takes it.

- **Admin** -> all above plus
  - Add, Edit and Delete categories.
  - Add, Edit and Delete any products.
  - Create other Admins.
  - Create Shippers and add Shipper area he will be responsible for.
  - Restrict any user from all the permissions.

## 💹 &nbsp; Technologies

#### Backend

- Express
- Mongoose
- Json Web Token (For authentication)

#### Frontend

- React JS
- Redux (Manage app state)
- Bootstarp
- React-router (To handle routing)
- HTML ,CSS
- Sass

## 💻 &nbsp; Setup

To run this project, install it locally using npm:

```
$ cd inventory-application
$ npm install (install backend dependencies)
$ cd views
$ npm install (install frontend dependencies)
$ cd ..
$ npm run server (for Node server side development)
$ npm run client (for React client side development)
$ npm run dev (for both client and server side)
```
