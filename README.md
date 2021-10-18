# JavaScript-Cart-Ecommerce
Creating Ecommerce cart using JavaScript


![WhatsApp Image 2021-10-18 at 22 05 23](https://designmodo.com/wp-content/uploads/2016/08/shop-bag.jpg)


Session Storage:
We use sessions to store data and share such data across several pages. Usually, a user would pick a product, and we’d save the product’s name along with the chosen quantity and price.

Then, the user would fill out a form with their personal information, and we’d save it in the current session before the end of the process, which is typically the checkout page and the subsequent redirection to the payment gateway (for example, PayPal).

Works:
The user may add and remove products from their shopping cart, update the cart, change the quantity of each product, and empty the cart. They have to fill a form with their contact information, specifying whether their billing address is the same as their shipping address.

HTML Structure #
Our project is made up of the following sections:

index.html This contains the list from which users may add products to their shopping cart, specifying the quantity for each product.
cart.html This is the shopping cart page where users may update or empty their cart. Alternatively, they can go back to the main page to continue shopping or proceed to the checkout page.
checkout.html On this page, users fill out a form with their personal information — specifically, their billing and shipping addresses.
order.html This page contains a brief summary of the user’s order plus the PayPal form. Once a user submits the form, they will be redirected to PayPal’s landing page.
