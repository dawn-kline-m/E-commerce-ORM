# Object-Relational Mapping (ORM): E-Commerce Back End

## Table of Contents
- [Description](#description)
- [User Specifications](#user-specifications)
- [Functionality](#functionality)
- [Mock-Up](#mock-up)
- [Deliverables](#deliverables)

## Description

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

This challenge is to build the back end for an e-commerce site by modifying starter code. The challenge will configure a working Express.js API to use Sequelize to interact with a MySQL database.

## User Specification

A manager at an internet retail company wants a back end for my e-commerce website that uses the latest technologies so that the company can compete with other e-commerce companies

## Functionality

Given a functional Express.js API, when the user connects connects to a database using Sequelize and 
enters schema and seed commands, a development database is created and is seeded with test data.

When the user enters the command to invoke the application, the server is started and the Sequelize models are synced to the MySQL database.

WHEN the user opens API GET routes in Insomnia for categories, products, or tags, the data for each of these routes is displayed in a formatted JSON

When the user tests API POST, PUT, and DELETE routes in Insomnia, the user is able to successfully create, update, and delete data in my database

## Mock-Up

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/13-orm-homework-demo-03.gif)

The walkthrough video shows the POST, PUT, and DELETE routes for products and tags being tested in Insomnia.

## Deliverables: 10%

* A walkthrough video demonstrating the functionality of the application and all of the acceptance criteria being met:  https://watch.screencastify.com/v/h0f6aFLYAVsJfqMf3O2o

* The URL of the GitHub repository:  https://github.com/dawn-kline-m/E-commerce-ORM

