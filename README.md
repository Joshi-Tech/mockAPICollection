# Mock API Collection

A Bruno API Collection created for learning, testing, and demonstrating REST API operations using mock endpoints.

## Overview

This collection contains sample API requests for common CRUD operations:

* Create Customer (POST)
* Get Customer(s) (GET)
* Update Customer (PUT)
* Partial Update Customer (PATCH)
* Delete Customer (DELETE)

The collection is maintained using Bruno and version controlled through GitHub.

---

## Project Structure

```text
mockAPICollection/
│
├── DEV/
│   ├── CreateCustomer.yml
│   ├── GET Customers.yml
│   ├── GETSingleCustomer.yml
│   ├── PATCHRequest.yml
│   ├── Update a resource.yml
│   └── Untitled.yml
│
├── environments/
│   ├── DEV.yml
│   └── QA.yml
│
├── opencollection.yml
└── README.md
```

---

## Tools Used

* Bruno
* Git
* GitHub
* REST APIs

---

## Environment Configuration

The collection includes:

### DEV Environment

Used for development and local testing.

### QA Environment

Used for validation and testing activities.

Environment variables can be updated from the Bruno Environment settings.

---

## How to Use

### Clone Repository

```bash
git clone https://github.com/Joshi-Tech/mockAPICollection.git
```

### Open in Bruno

1. Launch Bruno.
2. Select **Open Collection**.
3. Browse to the cloned repository.
4. Open the collection.

### Execute Requests

1. Select the required environment.
2. Open the desired request.
3. Click **Send**.

---

## Version Control

Changes are tracked using Git.

### Commit Changes

```bash
git add .
git commit -m "Updated API collection"
```

### Push Changes

```bash
git push origin main
```

---

## Learning Objectives

This repository is intended for:

* API testing practice
* Bruno learning exercises
* CRUD operation validation
* Environment management
* Git and GitHub integration

---

## Author

Laxmi Kant Joshi

Quality Engineer | API Testing | Automation Testing

GitHub: https://github.com/Joshi-Tech
