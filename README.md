# Product Table
## Date: 7/7/2025
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
<!DOCTYPE html>
<html>

<head>
    <title>Product Table</title>
</head>

<body>

    <h1>Product Catalog</h1>

    <table border="1">
        <caption>List of Available Products</caption>
        <thead>
            <tr>
                <th>Product Name</th>
                <th>Product Price</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Laptop</td>
                <td>₹45,000</td>
                <td>High-speed performance</td>
            </tr>
            <tr>
                <td>Smartphone</td>
                <td>₹25,000</td>
                <td>Budget-friendly and powerful</td>
            </tr>
            <tr>
                <td>Wireless Earbuds</td>
                <td>₹2,999</td>
                <td>Long battery life and noise cancellation</td>
            </tr>
            <tr>
                <td>Smartwatch</td>
                <td>₹5,499</td>
                <td>Fitness tracking with call alerts</td>
            </tr>
        </tbody>
    </table>

</body>

</html>

## Output:
![image](https://github.com/user-attachments/assets/37a57b64-dcb4-41a1-9514-135bdf1c38c6)

## CSS Code:
/* Body Styling */
body {
    background-color: #f9f9f9;
    font-family: Arial, sans-serif;
}

/* Page Title */
.page-title {
    text-align: center;
}

/* Table Styling */
table {
    border-collapse: collapse;
    margin: auto;
    width: 80%;
}

/* Caption Styling */
caption {
    font-weight: bold;
    font-size: 1.5em;
    margin: 20px 0;
}

/* Table Header */
thead th {
    background-color: #4CAF50;
    color: white;
    padding: 12px;
    text-align: left;
}

/* Table Cells */
tbody td {
    border: 1px solid #ddd;
    padding: 10px;
}

/* Alternating Rows */
tbody tr:nth-child(even) {
    background-color: #f2f2f2;
}

/* Hover Row Effect */
tbody tr:hover {
    background-color: #e6f7ff;
}

## Output:
![image](https://github.com/user-attachments/assets/255eff64-f8db-422b-afa1-e75b9faa62e4)



## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
