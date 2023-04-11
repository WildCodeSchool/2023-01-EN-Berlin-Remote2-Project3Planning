# Project 3 Planning

## Scope

An order/table management system for a restaurant that is intended to enhance and increase the efficiency of restuaurant operations (and hence perceived service at the intended level of service of the retaurant type).

The real-life quantity that the app will try to help minimize is the "sit-to-serve time".

This is the time it takes for a customer to have their food served, from the moment they sit at a table in a restaurant.

### Core Mission

The core mission of the application is to manage the lifecycle of the order.

An order is "placed" when the customer orders food, it is "ready" when the food had been prepared, and it is "served" when it is at the table.
### Side Mission

An important side mission of the application is to manage the lifecycle of the table.

A table is "opened" when someone or a group of people make one or more orders from the table, and "closed" when the people leave the table and the bill is paid.

## Background

The "sit-to-serve time" is composed of:
1. The time it takes for the customer to have access to a waiter/waitress for ordering
2. The time it takes the waiter/waitress to let the kitchen/bar know of the order
3. The time it takes for the kitchen/bar to make the food/drink
4. The time it takes after the food/drink is made until it is picked up and delivered to the right table/place

## Approach

We agreed to try to solve problems in the domain, and understand that some discussions in the team will target restaurant operations, rather not just coding and fullstack development.

### Service variations

1. How are the tables indicated in the restaurants (for example, do the restaurant use table numbers? do they change? do they become irrelevant when moving tables)
2. How orders are placed, do the customer wait for the waiter/waitress to attend to them at the table vs. the customer approaching
3. How is the food/drink delivered to the table, is it served by runners/waiters or is the customer called to pick up the food (e.g. using a special device)

### Implementation strategy

In the first phase we aim solely for an MVP (_Minimum Viable Product_) meaning that anything that does not fit the core mission statement above will be dropped initially until a fully functional, but a minimal, application is achieved.

## Design

### User roles

_TODO: who will use this application_

> Suggestion:
> 1. Waiter/waitress/self-service/cashier (anyone ordering food, usually they also serve the food)
> 2. Barista/barman/waiter (anyone serving drinks)
> 3. Cheff (anyone making food)
> 4. Runners (anyone picking up the food and taking it to the table)

### Order States

_TODO: using a state diagram in markdown and later using an XSTATE library visualizer_

### Table States

_TODO: using a state diagram in markdown and later using an XSTATE library visualizer_
### Signup Sequences

_TODO: a sequence diagram showing the steps needed to make an account_