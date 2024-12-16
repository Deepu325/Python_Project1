# Python_Project1
### **Title**
**Personal Expense Tracker Application**  

---

### **Abstract**
The Expense Tracker is a user-friendly desktop application designed to help users manage their personal finances effectively. Built using Python with the Tkinter library for the GUI, it enables users to record, view, and analyze their expenses. The application supports secure login and registration, storing user credentials and expenses in CSV files. Additionally, it provides graphical summaries of spending, helping users track their expenses by category.

---

### **Overview**
Managing personal finances is an essential skill, and the Expense Tracker simplifies this process with an interactive interface. Users can securely log in to their accounts, add daily expenses with details like date, category, and amount, and view their recorded expenses in a structured format. The application offers features such as password hashing for security, category-wise graphical summaries, and persistent storage of data through CSV files.

This project integrates key Python libraries:
- **Tkinter**: For GUI components.
- **tkcalendar**: To allow users to select dates easily.
- **csv**: For storing and retrieving user data and expenses.
- **matplotlib**: For graphical visualization of expense summaries.

---

### **Features**
1. **Secure Login and Registration**:
   - Passwords are securely hashed using SHA-256.
   - User credentials and email IDs are stored persistently in CSV files.

2. **Expense Management**:
   - Add expense entries with a specific date, category, and amount.
   - Persistent expense storage tied to the logged-in user.

3. **View and Analyze Expenses**:
   - View a detailed list of expenses in a tabular format.
   - Display total expenses and category-wise summaries.

4. **Graphical Summaries**:
   - Bar charts showing spending by category.
   - Easy visualization of financial habits.

5. **Responsive and Intuitive GUI**:
   - Navigation bar for easy switching between pages.
   - Organized interface with interactive buttons and forms.

6. **CSV Integration**:
   - Data for users and expenses is stored and retrieved from CSV files, ensuring persistence across sessions.

7. **Error Handling and Validation**:
   - Provides feedback for incomplete forms and invalid login attempts.
   - Ensures users cannot register duplicate usernames.

---

This project is a practical and simple implementation of personal finance management, ideal for individual users seeking better control over their spending habits.
