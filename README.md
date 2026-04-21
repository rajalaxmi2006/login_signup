# 🔐 Login & Signup Web App

A simple and responsive **Login & Signup interface** built using **HTML, CSS, and Vanilla JavaScript**, with client-side authentication using `localStorage`.

---

## 🚀 Features

- 🔁 Toggle between **Login** and **Signup** forms  
- ✅ Form validation (email, password, required fields)  
- 🔒 Password confirmation check  
- 📧 Email format validation using regex  
- 💾 Stores user data in **localStorage**  
- ⚡ Instant success/error feedback messages  
- 🎨 Clean and responsive UI with modern styling  

---

## 🛠️ Tech Stack

- **HTML5** – Structure  
- **CSS3** – Styling (Flexbox, gradients, shadows)  
- **JavaScript (ES6)** – Logic & validation  
- **Web Storage API** – Data persistence (localStorage)  

---

## 📂 Project Structure
```
project-folder/
│── index.html # Main application file
```


---

## 📸 Preview

Simple card-based UI with login & signup tabs and form validation.

---

## ⚙️ How It Works

### Signup Flow

1. User enters name, email, password, confirm password  
2. Validations:
   - All fields required  
   - Valid email format  
   - Password ≥ 6 characters  
   - Password match check  
3. Stores user in `localStorage`  

---

### Login Flow

1. User enters email & password  
2. Checks against stored users  
3. Displays success or error message  

---

## 🧠 Core Logic

Users are stored as:

```js
[
  {
    name: "John Doe",
    email: "john@example.com",
    password: "123456"
  }
]
```
## 🧠 Key Functions

- `getUsers()`  
  Retrieves the list of users from `localStorage`.

- `saveUsers(users)`  
  Stores the updated user array into `localStorage`.

- `isValidEmail(email)`  
  Validates email format using a regular expression.

- Signup Logic  
  - Checks required fields  
  - Validates email format  
  - Ensures password length ≥ 6  
  - Confirms password match  
  - Prevents duplicate email registration  

- Login Logic  
  - Matches entered credentials with stored users  
  - Displays success or error message
 
## ⚠️ Limitations

- ❌ No backend (pure frontend application)  
- ❌ Passwords stored in plain text (security risk)  
- ❌ No encryption or hashing implemented  
- ❌ No session handling or authentication tokens  
- ❌ Data can be cleared if browser storage is reset

## 🔮 Future Improvements

- 🔐 Integrate backend (Node.js / Express / Firebase)  
- 🔑 Implement password hashing (bcrypt)  
- 🗄️ Replace localStorage with a database (MongoDB / SQL)  
- 🔐 Add JWT-based authentication  
- 🌐 Enable API-based login/signup  
- 🎨 Improve UI/UX with animations and transitions  
- 📱 Make fully mobile-optimized enhancements

## 🙏 Acknowledgements

- Inspired by modern authentication UI patterns  
- Thanks to open-source community resources and documentation  
- Built as a learning project for frontend development  

## 📞 Support & Contact

If you have any questions, suggestions, or issues:

- 📧 Email: biswalrajalaxmi901@gmail.com  
- 💼 LinkedIn: https://linkedin.com/in/your-profile  
- 🐙 GitHub: https://github.com/rajalaxmi2006/ 

Feel free to open an issue or contribute to the project!
