# Common-Deal
Online platform to associate vendors with a group of customers. Vendor agrees that if sufficient amount of potential customers will gather, he's going to sell the product for a wholesale price. The purpose of this project was to practice MVC pattern, separating back and frontend, managing database resources through ORM and to finally deploy it on the Microsoft Azure cloud service.

You can find it here:
http://commondeal.azurewebsites.net/

We decided to separate the back and frontend servers. Backend is running on Django REST Framework while front is made in Vue.js. 

There are currently two developers who's been working on this project. We've divided work equally so that we could both work on every aspect of this application.

# Tech Stack
- Python
- Django / Django REST Framework
- Vue.js
- Vuetify
- PostgreSQL
- Microsoft Azure

# Goals
The purpose of this project was to practice following topics:
- handling HTTP requests with Django REST Framework for different HTTP methods,
- user authentication, authorization and permissions using JWT Token,
- managing database records and relationships through Django ORM,
- how to use JSON field in a model class to store object's attributes,
- how to handle files upload,
- data serialization,
- API endpoints testing,
- setting up of Sendgrid Email API to send user registration confirmation and password reset emails, 
- integration of the separate presentation and data access layer,
- how to use views and components in Vue.js,
- route/ view mapping using Vue Router,
- how to pass data between components,
- how to emit signals in Vue.js,
- asynchronous request handling,
- how to use instance lifecycle hooks,
- events handling,
- differentiate styles and components for mobile and desktop devices,
- user input validation on front and back end,
- how to build applications using Vuetify - material design component framework for Vue.js,
- deployment on Microsoft Azure.

# Implemented Features
- user registration, login, logout and password recovery,
- product list view,
- sorting items by price,
- filtering products by category,
- product detail view.

# Development plans
We're still working on this project and we want to add the following features:
- adding new products/offers,
- limiting customer access to offers only if he meets certain requirements,
- calculate current number of subscribtions left to finalize the offer,
- integration with Inpost API to choose a pick up parcel locker,
- integration with PayPal as a payment method,
- searchbar,
- filtering products by their attributes.
