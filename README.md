*Dashboard Backend*
- This is the backend of the Dashboard project.

*Technology Used:*
- Node.js, Express.js

*Database Used:*
- Mongodb

***A system that fetches data from "https://s3.amazonaws.com/roxiler.com/product_transaction.json" and get the product details.***

**Functionality:**
- It match search text on product title/description/price and based on matching result it return the product transactions.
- If search parameter is empty then based on applied pagination it return all the records of that page number.
- API supports search and pagination on product transactions
- Default pagination values will be like page = 1, per page = 10

**The response should contain price range and the number of items in that range for the selected month regardless of the year:**
- 0- 100
- 101- 200
- 201-300
- 301-400
- 401-500
- 501- 600
- 601-700
- 701-800
- 801-900
- 901-above

*Backend link to test the apis: (https://dashboard-rox-backend.onrender.com)*
