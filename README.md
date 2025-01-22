# Dashboard Backend

This repository contains the backend for the Dashboard application.

---

## Technologies Used

- **Backend Framework**: Node.js, Express.js  
- **Database**: MongoDB  
- **Hosting**: Render  

---

## Overview

The backend system fetches product transaction data from [this dataset](https://s3.amazonaws.com/roxiler.com/product_transaction.json) and processes the details based on user queries.

---

## Core Functionality

1. **Search and Filter**:
   - Supports text-based search on product titles, descriptions, and prices.
   - Returns transactions matching the search criteria.  
   - If no search parameter is provided, it retrieves all records based on pagination settings.
   
2. **Pagination**:
   - **Default values**: `page = 1`, `perPage = 10`.
   - Allows flexible navigation through large datasets.

3. **Price Range Statistics**:
   - Provides the count of transactions grouped by price ranges for a selected month (irrespective of the year).  
   - Price range categories:
     - 0–100
     - 101–200
     - 201–300
     - 301–400
     - 401–500
     - 501–600
     - 601–700
     - 701–800
     - 801–900
     - 901 and above  

---

## API Testing

The backend APIs are live and can be tested at the following link:  
[Dashboard Backend](https://dashboard-rox-backend.onrender.com)

---

## Important Note

The backend is hosted on Render. After a period of inactivity, the service may enter an idle state. If the APIs take time to respond, please allow some time for the backend to restart.

---

