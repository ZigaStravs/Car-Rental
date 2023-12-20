BookCars is an open source car rental platform, supplier-oriented, with a backend for managing car fleets and bookings, as well as a frontend and a mobile app for renting cars.

BookCars is designed to work with multiple suppliers. Each supplier can manage his car fleet and bookings from the backend. BookCars can also work with only one supplier as well.

From the backend, admins can create and manage suppliers, cars, locations, customers and bookings.

When new suppliers are created, they will receive an email prompting them to create an account in order to access the backend and manage their car fleet and bookings.

Customers can sign up from the frontend or the mobile app, search for available cars based on pickup and drop-off points and time, choose a car and complete the checkout process.

A key design decision was made to use TypeScript instead of JavaScript due to its numerous advantages. TypeScript offers strong typing, tooling, and integration, resulting in high-quality, scalable, more readable and maintainable code that is easy to debug and test.

## Features

* Supplier management
* Ready for one or multiple suppliers
* Car fleet management
* Booking management
* Customer management
* Multiple payment methods (Credit Card, Pay Later)
* Multiple language support (English, French)
* Multiple pagination options (Classic pagination with next and previous buttons, infinite scroll)
* Responsive backend and frontend
* Native Mobile app for Android and iOS with single codebase
* Push notifications
* Secure against XSS, XST, CSRF and MITM
