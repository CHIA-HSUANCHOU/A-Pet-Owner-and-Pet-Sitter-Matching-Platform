# Database-Management-System-project
---
Project: Funny Paw: A Pet Owner and Pet Sitter Matching Platform

Author: Group 2

Date: 2024-06-10

---

## 1. Code Structure

**Frontend**：HTML、CSS

**Backend**：Python Flask

**Database**：MySQL

## 2. Functions
![Function Image](/Petservice/static/img/functiondiagram.jpg)

## 3. Contributors

| Teammates | Department | Contribution |
|-----------|------------|--------------|
| **周佳萱 (ME)** | **Department of Statistics** | **Backend: Role selection, Pet sitter and owner registration/login, Filter sitters, Filter results, Book sitters, Frontend HTML structure** |
| 黃育心 | Department of Statistics | Backend: Owner and sitter review, Owner order result, Sitter order information, Filter sitters, Filter results, Frontend HTML structure |
| 朱耀宇 | Department of Business Management | Backend: Edit profile, Owner and sitter comments, Frontend HTML structure |
| 李亞駿 | Department of Advertising | Backend: Order history, Frontend HTML structure |
| 陳姿妤 | Department of Accounting  | Overall website design |

In more detailed of my job：

Role Selection: Allows users to choose between being a pet sitter or an owner seeking pet sitting services.

Pet Sitter and Owner Registration/Login: Enables users to register and log in username and password. Stores owner or pet sitter information securely in the database, utilizing hashing techniques for authentication security.

Filter Sitters: Allows sitters to choose sitter based on service type, average sitter rating, accepted pet type, and veterinary experience using the SQLAlchemy package.

Filter Results: Displays filtered search results of pet sitters, and allows owners to select their preferred sitter.

Book Sitters: Enables owners to input reservation details for a sitter. Stores this information in the Reservation database.

## 4. ERD
<img src="/Petservice/static/img/ERD.jpg" alt="ERD Image" style="width: 100%">




