# Exercise Requirements

Build a small pizza ordering and checkout application. A customer should be
able to customize a pizza, enter checkout details, place an order, and see the
result.

Use any language, frameworks, and AI tools you are comfortable with. Keep the
solution small enough to demonstrate during the interview. You may use starter
templates or generate a new project.

## Core requirements

### Pizza order and checkout

Create a browser-based experience that collects the following information.

Pizza details:

- one or more pizzas
- size and toppings for each pizza
- quantity for each item in the order
- special instructions for each pizza

Checkout details:

- customer name
- customer email
- card number
- card expiration date
- any other fields required by the payment flow

Choose a simple menu and pricing model. Show the customer what they selected
and the amount they will be charged.

### Order and payment flow

Add a backend that participates in the order flow and integrates with a payment
processor, such as Stripe, using a test account or sandbox environment. Do not
use real payment details. The customer should be able to submit the form and
receive a clear success or failure result.

The successful flow should produce enough information to identify the order
and its payment. Handle invalid input and payment failures in a way that can be
demonstrated.

## What a working solution demonstrates

By the end of the exercise, aim to show:

- a customer can customize a pizza and see its price;
- a payment can be attempted through a payment processor;
- the application clearly reports the outcome; and
- another developer can run the solution from its README.

Depth and judgment matter more than checking every box. If time is limited,
leave the application in a coherent state and explain what you would do next.

## Stretch goals

### Customer profiles

If the core flow is working, add reusable customer profiles with persistent
storage. A repeat customer should be identifiable on a later order.

Decide what belongs in the profile, how orders relate to it, and how you would
handle the profile lifecycle.

### Deployment

Deploy the application to a hosting provider. A production-quality deployment
is not required, but this is encouraged if time allows.
