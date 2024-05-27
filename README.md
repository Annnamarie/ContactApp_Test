# 🌟 ContactApp_Test: CS 320 Software Testing - JUnit Testing 🌟

 **ContactApp_Test** JUnit Testing: CS 320 Software Testing 

## 📜 JUnit Testing Overview

Implemented both the **Contact** and **ContactService** classes, along with their respective JUnit tests. Here’s what each class does and how we tested them:

### 📇 Contact Class

**Features:**
- **Contact ID:** Must be unique, non-null, and no longer than 10 characters.
- **First Name:** Must be non-null and no longer than 10 characters.
- **Last Name:** Must be non-null and no longer than 10 characters.
- **Phone Number:** Must be a string of digits, non-null, and no longer than 10 digits.
- **Address:** Must be non-null and no longer than 30 characters.

### 🛠️ ContactService Class

**Functionalities:**
- **Add Contact:** Adds a contact with a unique ID.
- **Delete Contact:** Deletes a contact using the contact ID.
- **Update Contact:** Updates contact fields (first name, last name, phone number, address) using the contact ID.

## 🧪 JUnit Tests

### 🧪 ContactTest

We rigorously tested for both valid and invalid scenarios:

- **Contact ID:** Tested for uniqueness, non-null value, and length (<= 10 characters).
- **First Name:** Tested for non-null value and length (<= 10 characters).
- **Last Name:** Tested for non-null value and length (<= 10 characters).
- **Phone Number:** Tested for non-null value, digit-only string, and length (<= 10 digits).
- **Address:** Tested for non-null value and length (<= 30 characters).

### 🧪 ContactServiceTest

We ensured that the service methods perform correctly under various conditions:

- **Add Contact:** Tested adding contacts, handling duplicate IDs.
- **Delete Contact:** Tested deleting contacts, handling non-existent IDs.
- **Update Contact:** Tested updating contact details, handling invalid values.
