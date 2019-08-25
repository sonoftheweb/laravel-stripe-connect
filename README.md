# Laravel Stripe Express Tutorial
This is a boilerplate repo showing how to use <a href='https://stripe.com/docs/connect/express-accounts'>Stripe Express Connect</a> with Laravel. 

## Introduction
### What Is Stripe Express?
Express accounts are a type of Stripe connect account and is generally used for two sided marketplaces where there is a seller selling services or a product and a buyer of those services/product. Examples include:
- Etsy
- Ebay
- Uber
- Lyft

Express essentially allows your platform to onboard and manage the flow of funds for your sellers. 

### What Does The Boilerplate Do?
In this boilerplate, we have two types of users. Sellers, who sell their product on the platform and customers, who purchase the products from the sellers. Sellers must create an Express account to ensure they can received payments, while customers must add a payment method to purchase a product. 

### Flow of funds with fees:
When a customer purchases a product from a seller, the charge will be collected by the platform. A separate transfer with your platform fees extracted will be sent to the connected account. Reference the image below to see the flow of funds during a purchase:

![Stripe Image](https://stripe.com/img/docs/connect/charges_transfers.png "Flow of Funds")

## Getting Started