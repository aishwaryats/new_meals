# Meal Matters

**Meal Matters** is a platform designed to reduce food waste by facilitating the collection and distribution of leftover food. The platform connects restaurants (donors), charity organisations, and volunteers, creating a seamless process for donating and distributing food to those in need.

---

## Features

### Donor (Restaurant) Features:
- **Request Submission**: Submit requests for leftover food with details such as:
  - Food quantity.
  - Preparation date and time.
- **Profile Management**: Update and manage donor profiles.

### Charity Organisation Features:
- **View Requests**: Access and review available food donation requests.
- **Accept/Decline Requests**: Accept or decline requests based on food requirements.
- **Order Management**: Manage orders once requests are accepted.

### Volunteer Features:
- **View Orders**: Access the list of food orders awaiting delivery.
- **Accept/Decline Orders**: Choose orders based on availability.
- **Delivery Status Updates**: Update the status of delivery (e.g., "In Transit," "Delivered"), visible to both donors and charity organisations.

### Additional Features:
- **Transparency**: Delivery status updates ensure accountability.
- **User Profiles**: Allow users (donors, charities, and volunteers) to manage and update their personal information.

---

## Technical Workflow

1. **Request Creation**:
   - Restaurants log in and submit food donation requests.
   - Requests include food quantity, preparation date, and additional details.

2. **Request Acceptance**:
   - Charity organisations view and accept requests, converting them into orders.
   - Declined requests remain available for other organizations.

3. **Order Assignment**:
   - Orders become available to volunteers for collection and delivery.
   - Volunteers can accept or decline orders based on their availability.

4. **Delivery Status**:
   - Volunteers update the status of the order during delivery.
   - Status changes are visible to both donors and charity organizations.

---

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Firebase, JavaScript
- **Database**: Firebase Firestore

---
