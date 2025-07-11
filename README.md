# 📚 Online Bookstore Management System (Spring Boot + Thymeleaf)

A full-featured **Bookstore Web Application** built using `Spring Boot`, `Thymeleaf`, and `Bootstrap`.  
This project demonstrates **CRUD operations**, **Add to Cart**, **Role-Based Access Control**, and **Session management**, making it perfect for real-world internship/project showcase.

---

## 🚀 Features

### 🧑‍💻 Public (USER)
- ✅ View list of all books
- ✅ Add books to cart
- ✅ View cart with total price
- 🔐 Cannot Add/Delete/Update books

### 🔐 Admin Panel (ADMIN)
- ✅ Add New Book (with image, price, stock, etc.)
- ✅ Update existing book by Title
- ✅ Delete book by Title
- ✅ Role-based protected routes
- ✅ Secure login/logout functionality

### 🧠 Backend Logic
- Built using MVC Architecture
- Cart stored in **HttpSession**
- Dynamic routing using Thymeleaf
- Session-based cart management
- Proper validations and fallback logic

---

## 🛠️ Tech Stack

| Layer        | Technology               |
|-------------|--------------------------|
| Backend     | Spring Boot, Java        |
| Frontend    | Thymeleaf + Bootstrap    |
| Build Tool  | Maven                    |
| View Engine | Thymeleaf                |
| Security    | Spring Security (RBAC)   |
| Database    | In-Memory (for now)      |
| Hosting     | (optional) Render/Railway |

---

## 👤 User Credentials

> For testing login system:

| Role   | Username | Password   |
|--------|----------|------------|
| ADMIN  | admin    | admin123   |
| USER   | user     | user123    |

---

## 📸 Screenshots

> Replace below image URLs with your own when hosted

- 🏠 Home Page  
  `![Home Page](screenshots/home.png)`

- 🔐 Login Page  
  `![Login Page](screenshots/login.png)`

- 🛒 Cart Page  
  `![Cart](screenshots/cart.png)`

- 📋 Add Book Form  
  `![Add Book](screenshots/addbook.png)`

---

## ⚙️ Setup Instructions


# 1. Clone the Repository
git clone https://github.com/yourusername/online-bookstore.git
cd online-bookstore

# 2. Open in IDE (Eclipse, IntelliJ, VS Code with Java Extension)


## 3. Build and Run

Use the following command to run the project:

```bash
./mvnw spring-boot:run
```

## Folder Structure

```
├── Controller/           # All controllers (routes)
├── Model/                # Book.java entity
├── Service/              # Service layer interfaces and implementations
├── Repository/           # BookRepository interface (JPA)
├── config/               # Spring Security configuration
├── templates/            # Thymeleaf HTML pages
├── static/               # CSS, JavaScript, and images
└── application.properties
```

## Future Improvements

- Store cart items in the database  
- User registration and profile management  
- Pagination and sorting on the homepage  
- RESTful APIs with Postman Collection  
- Payment Gateway Integration

## License

My License – Free for learning, educational use, and personal modifications.

## Contact

**Ankit Kumar Gurjar**  
📧 Email: ankdoi82@gmail.com  
🔗 LinkedIn: [https://www.linkedin.com/in/ankit-kumar-gurjar](https://www.linkedin.com/in/ankit-kumar-gurjar)  
📂 GitHub: [https://github.com/ankitdoi--coder](https://github.com/ankitdoi--coder)
