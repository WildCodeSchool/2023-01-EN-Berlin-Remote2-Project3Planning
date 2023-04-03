# Project 3 Planning

## Mission Statement

This is an internal website for a restaurant that manages the lifecycle of an order.

The key performance metric that the app will try to minimize is the sit-to-serve time.

## Background

The sit to serve time is composed of:
1. The time it takes for the customer to have access to a waiter/waitress for ordering
2. The time it takes the waiter/waitress to let the kitchen/bar know of the order
3. The time it takes for the kitchen/bar to make the food/drink
4. The time it takes after the food/drink is made until it is picked up and delivered to the right table/place

## Spirit

We agreed to try to solve problems in the domain, and understand that some discussions in the team will target restaurant operations, rather not just programming.

## Variations in Restaurants

1. How are the tables or the places indicated in the restaurants (for example, do the restaurant use table numbers? do they change? do they become irrelevant when moving tables)
2. Do the restaurant use the customer for picking up the order (for example with the call out devices)
3. Do the restaurant use some kind of indoor positioning gadgets

## Strategy

In the first phase we aim solely for an MVP (_Minimum Viable Product_) meaning that anything that does not fit the mission statement above will be dropped initially until a fully functional, but a minimal, application is achieved.

## Design

### User roles

TODO: who will use this application

Suggestion:
1. Waiter/waitress/self-service/cashier (anyone ordering food, usually they also serve the food)
2. Barista/barman/waiter (anyone serving drinks)
3. Cheff (anyone making food)
4. Runners (anyone picking up the food and taking it to the table)

### Order States

TODO: using a state diagram in markdown and later using an XSTATE library visualizer

### Signup Sequence

TODO: a sequence diagram showing the steps needed to make an account