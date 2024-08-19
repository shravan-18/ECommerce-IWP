# E-commerce Website

This is a dynamic e-commerce platform where customers can browse products, search for items, register, add products to their cart, and complete purchases using the Stripe payment system. The site includes an admin panel where I can manage posts, site content, and users, with options to add, delete, or update them. Additionally, I offer a repair service where users can check offers based on their purchase history.

## Project Information

This project was developed as part of the Internet and Web Programming Course at Vellore Institute of Technology.

## Database Setup

To configure the database on your localhost, follow these steps:

1. Locate the provided `.sql` file in the `database` folder.
2. Go to `localhost/phpmyadmin` and create a new database named `electric-shop`.
3. Select the newly created database, go to the `Import` section, and upload the `electric-shop.sql` file.
4. Click the "Go" button to complete the import.

Congratulations, your database is now set up!

## Stripe Configuration

I've provided a Stripe configuration file, but you'll need to replace the publishable and secret keys with your own Stripe account credentials.

Please note: You may encounter a Stripe-related error. This is because the Stripe files were not uploaded to GitHub due to certain issues. However, I have included a `stripe.zip` file containing the necessary `stripe` and `vendor` folders. 

To resolve the issue:

1. Unzip the `stripe.zip` file.
2. Place the `stripe` and `vendor` folders into the root directory of your project.

Once done, the Stripe payment gateway should work seamlessly.
