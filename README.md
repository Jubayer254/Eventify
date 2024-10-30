# Eventify (Event Management System)

## Overview

This Django-based Event Management System enables users to create, modify, delete, and reserve events. The system incorporates user authentication, allowing any user to view events, but only registered and logged-in users can manage or book events. The homepage displays booking statuses for logged-in users, highlighting events they have already reserved.

## Features and Requirements

### User Authentication
* **Registration:** Permits new users to establish an account.
* **Login:** Authenticates users to access additional functionalities.
* **Logout:** Allows users to securely log out of their account.
* **Profile Page:** Each user possesses a profile page to view and update personal details.

### Event Management
* **Create Event:** Logged-in users can create new events by providing details such as event name, date, location, and description.
* **Update Event:** Users can modify their own events.
* **Delete Event:** Users can remove events they have created.
* **View Events:** All users, even those not logged in, can view events on the homepage.
* **Event Permissions:** Users can only update or delete their own events. Admins have complete control over all events.

### Event Booking
* **Booking:** Only registered and logged-in users can reserve events.
* **Booked Events Page:** Displays all events reserved by the user, including details such as event name, date, and location.
* **Booking Status:** The homepage displays a "Booked" label next to events already reserved by the logged-in user.

### Homepage
* **Event Display:** Displays all events.
* **Booking Status for Logged-In Users:** Indicates if the logged-in user has already reserved an event.
* **Redirect for Non-Logged-In Users:** Non-logged-in users attempting to book are redirected to the login page.

### Booked Events Page
* **Access:** Available only to logged-in users.
* **Details:** Lists all events the user has reserved, with event details like name, date, and location.

### Navigation and User Experience
* **Navigation Bar:** Includes links to the homepage, login/logout, registration, profile, and booked events page.

### Additional Features
* **Search Functionality:** Users can search for events by name, date, or location on the homepage.
* **Event Categories:** Includes categories like conferences, concerts, and workshops, enabling users to filter events by category.
* **Booking Limits:** Shows "Fully Booked" when an event reaches its capacity limit.
