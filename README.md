# Product Table
## Date: 07-07-2025(html) and 08-07-2025 (css)
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
```
<!DOCTYPE html>
<html lang="en">
    <header>
        <title>Product Table</title>
        <link rel="stylesheet" href="styles.css">
    </header>

    <body>
      <table>
        <caption> List of Products with Prices and Descriptions </caption>
        <thead>
            <tr>
                <th>
                    Product Name
                </th>
                <th>
                    Product Price
                </th>
                <th>
                    Description
                </th>
            </tr>
        </thead>
        <tbody>

            <tr>
                <td>
                    Portable Power Bank
                </td>
                <td>
                    ₹1,299
                </td>
                <td>
                    10,000mAh fast-charging power bank with dual USB output.
                </td>
            </tr>

             <tr>
                <td>
                    Laptop
                </td>
                <td>
                    ₹65,000
                </td>
                <td>
                    Lightweight laptop with 15.6" display and 8GB RAM.
                </td>
            </tr>

             <tr>
                <td>
                    Noise Cancelling Headphones
                </td>
                <td>
                    ₹5,999
                </td>
                <td>
                    Over-ear Bluetooth headphones with active noise cancellation.
                </td>
            </tr>

            <tr>
                <td>
                    Smart LED Desk Lamp
                </td>
                <td>
                   ₹2,499
                </td>
                <td>
                    Dimmable LED lamp with touch controls, USB charging port, and adjustable arm.
                </td>
            </tr>

            


        </tbody>
      </table>

    </body>
</html>
```

## CSS Code:
```
body
{
    background-color:#FFF5EC;
}


table,th,td,tr
{
    border: 1px solid;
    align-content: center;
    text-align: center;
    padding: 10px 10px 10px 10px;
    
}

caption
{
    padding: 10px;
    margin-bottom: 10px;
    font-weight: bold;
    font-size: large;
    
}


table
{
    border-collapse: collapse;
    margin-left:auto;
    margin-right: auto;
    border-radius: 5px;
}

th
{
    background-color:#ED6A5A;
}

tr
{
    background-color:#F4F1BB;
}

tbody tr:nth-of-type(even)
{
    background-color:#E8EFCF;
}
tr:hover td
{
    background-color: #9BC1BC;
}
```
## Output:
![image](https://github.com/user-attachments/assets/587f5e2f-9f43-4b91-aaf5-c97ba8d84ebc)


![image](https://github.com/user-attachments/assets/ae72d0ff-f0bf-4413-a885-f67addd58bc1)



## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
