# 📦 SmartStock-Manager

Welcome to **SmartStock-Manager**!  
This Python-based application is a handy tool for managing stock, tracking sales, and keeping inventory up to date! 🎉

---

## 🌟 Features

✨ **Interactive Menu**: View all products with their details (ID, name, price, and quantity).  
✨ **Real-Time Updates**: Adjust inventory automatically after every sale.  
✨ **Billing System**: Generate accurate bills instantly.  
✨ **Sales Log**: Keep a record of all transactions in a separate file.  
✨ **Low Stock Alerts**: Notify users if requested stock is insufficient.  

---

## 🛠️ Requirements

- **Python 3.x** 🐍
- A JSON file (`Record.json`) to store inventory data.  
- A text file (`Sales.txt`) to log transaction details (optional).

---

## 🚀 How to Run

1. Clone this repository:  
   ```bash
   git clone https://github.com/Bhuteshkumarmeher07/SmartStock-Manager.git
   cd smartstock-manager
   ```

2. Make sure you have Python 3 installed.  
   To check, run:
   ```bash
   python --version
   ```

3. Prepare the `Record.json` file in the same directory:  
   Example structure:  
   ```json
   {
       "1001": {"Name": "5 Star", "Price": 10, "Qn": 188},
       "1002": {"Name": "Bar-One", "Price": 20, "Qn": 0},
       "1003": {"Name": "Candy", "Price": 2, "Qn": 500},
       "1004": {"Name": "Chocolate Cake", "Price": 550, "Qn": 1},
       "1005": {"Name": "Blueberry Cake", "Price": 650, "Qn": 3}
   }
   ```

4. Create an empty `Sales.txt` file for transaction logs.

5. Run the program:  
   ```bash
   python smartstock_manager.py
   ```

---

## 📋 Example Workflow

### 🛍️ Menu
```
-----------------------------------------
                  MENU                   
1005 Blueberry Cake 650 3
1004 Chocolate Cake 550 1
1003 Candy 2 500
1002 Bar-One 20 0
1001 5 Star 10 188
---------------------------------------------
```

### ✏️ User Input
```plaintext
Enter your name    : BK
Enter Mail ID      : Bk2@gmail.com
Enter Phone No     : 12345789
Enter product ID   : 1004
Enter Quantity     : 5
```

### 🔔 Low Stock Alert
```plaintext
Sorry, We're not having enough quantity of product in our Inventory.
We're only having 1 quantity.
---------------------------------------------
Press Y to purchase: y
```

### 🧾 Bill
```plaintext
---------------------------------------------
Name      :  Chocolate Cake
Price (Rs):  550
Quantity  :  1
---------------------------------------------
Billing   :  550 Rs
---------------------------------------------
```

### ✅ Inventory Updated
```plaintext
---------------------------------------------
  Thanks for your order, Inventory Updated!  
---------------------------------------------
```

---

## 📂 File Structure

```plaintext
📦 SmartStock-Manager
├── smartstock_manager.py  # Main program
├── Record.json            # Inventory data
├── Sales.txt              # Transaction log
```

---

## 🌈 Future Enhancements

💡 Add user authentication for admin and customer roles.  
💡 Generate detailed PDF invoices.  
💡 Implement a graphical user interface (GUI).  
💡 Add advanced search and filtering options.  

---

## 🤝 Contributing

Contributions are welcome! 🤗  
Feel free to fork this repository, create a branch, and submit a pull request. Let's make **SmartStock-Manager** even better! 🚀

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

🎉 **Enjoy using SmartStock-Manager!**  
For questions or feedback, feel free to contact me at [bhuteshkumarmeher125@gmail.com](mailto:bhuteshkumarmeher125@gmail.com).  

---

Let me know if there’s anything else you’d like to tweak or enhance! 😊
