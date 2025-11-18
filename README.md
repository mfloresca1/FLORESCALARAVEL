# 🧾 CRUD Inventory Transaction Processing System

## 📘 Description / Overview
The **CRUD Inventory Transaction Processing System** is a simple web-based application designed to manage and monitor product inventory.  
It allows users to **Create, Read, Update, and Delete (CRUD)** inventory items, ensuring that transactions are properly tracked and recorded.  
The system aims to help small to medium-sized businesses maintain accurate stock records and reduce human error in manual inventory management.

---

## 🎯 Objectives
- To develop a **functional CRUD system** for managing inventory records.  
- To automate the **inventory transaction process** (adding, updating, and removing items).  
- To improve **accuracy and efficiency** in monitoring product availability.  
- To enhance understanding of **database operations** and **backend-frontend integration**.  
- To demonstrate knowledge in **PHP, MySQL, HTML, CSS, and JavaScript**.

---

## ⚙️ Features / Functionality
- ➕ **Add New Item** – Input item details such as name, category, quantity, and price.  
- 👁️ **View Inventory List** – Display all stored items with sorting and searching capability.  
- ⚙️ **Edit / Update Item** – Modify product information when restocked or corrected.  
- ✖️ **Delete Item** – Remove outdated or discontinued products.  
- ⏺️ **Transaction Records** – Track all inventory changes and movements.  
- 🦋 **Responsive Design** – Accessible from both desktop and mobile devices.  

---

## 💻 Installation Instructions
1. **Clone or Download the Repository**
   ```bash
   git clone https://github.com/mfloresca/FLORESCA-TPS.git



      ## 🧩 Usage
Follow these steps to use the **Inventory CRUD Transaction Processing System**:

1. **Login** using your administrator account.  
2. **Record Inventory Transactions** Tracks the quantity of each product in real-time to prevent shortages or overstocking
3. **Update Inventory Data** Reflects any changes immediately in the database whenever an item is added, edited, or deleted.
4. **Improve Business Operations** Streamlines the process of managing inventory, allowing faster service and organized record-keeping. 
5. **Increase Efficiency** Saves time and effort by performing CRUD (Create, Read, Update, Delete) operations quickly and easily.
6. **Data Security and Accuracy** Stores data in a secured database to ensure information consistency and reliability.

Example of starting the project (if using PHP local server):
```bash
php -S localhost:8000/product 

## 🧩 Sample Code Snippet

// Update existing product
if(isset($_POST['update'])){
    $id = $_POST['id'];
    $name = $_POST['name'];
    $quantity = $_POST['quantity'];
    $price = $_POST['price'];

    $sql = "UPDATE products SET name='$name', quantity='$quantity', price='$price' WHERE id=$id";
    mysqli_query($conn, $sql);
}


## Contributors
* Marivic Floresca - Developer/ IT Student
* Year and Section - 4C

## License
This project  is licensed under the MIT License.

