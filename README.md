# FlyMe Documentation: Flight Booking System with Tracking

## Project Structure
```
/src
  /components
    AddShipment.js
    Home.js
    Login.js
    MyFlight.js
    Loader.js
  /styles
    AddShipment.css
    Home.css
    Login.css
    MyFlight.css
    Loader.css
  /utils
    generateTrackingNumber.js
  firebase.js
  App.js
  index.js
```

## Technologies Used
* React: JS Library and Framework for interface.
* Firebase: 
    * Firebase Authentication: Used for user authentication.
    * Firestore: A NoSQL database to store ticket details.
* React Router: A library for routing in React applications.
* CSS: For styling the application components.
* HTML2Canvas and JSpdf: A Package to handle saving the receipt to PDF.

## Aims and Objectives

### Aims
The primary aim of this project is to create a simple and efficient flight booking system with tracking capabilities. The system allows users to add new shipments and track them using a unique tracking number.

### Objectives
* User Authentication: Ensure that only authenticated users can add new shipments.
* Shipment Tracking: Allow users to track their shipments using a unique tracking number.
* Data Storage: Store shipment details securely in Firestore.
* User-Friendly Interface: Provide an intuitive and easy-to-use interface for users to interact with the system.

## Future Upgrades
* Enhanced Security: Implement more granular Firestore security rules to enhance data security.
* User Profiles: Add user profiles to manage user-specific shipment data.
* Payment Integration: Integrate a payment gateway for handling payments related to shipments.
* Email Notifications: Send email notifications to users when their shipment status changes.
* Shipment Status Updates: Implement a feature to update and track the status of shipments (e.g., In Transit, Delivered).
* Multi-Language Support: Add support for multiple languages to cater to a global audience.
* Advanced Search: Implement advanced search and filtering options for tracking shipments.
