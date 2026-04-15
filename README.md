#  Product API Project

Project ini adalah REST API untuk mengelola data produk, kategori, dan supplier.  
API ini dirancang menggunakan konsep RESTful dan mendukung operasi CRUD serta relasi antar entitas.

---

##  Fitur
- CRUD Product (Create, Read, Update, Delete)
- CRUD Category
- Relasi Product dengan Category
- Search Product berdasarkan Category
- API Testing menggunakan Insomnia
- Response API terstruktur (status, message, payload)

---

##  Teknologi
- Java / Spring Boot
- MySQL
- REST API (JSON)
- Insomnia (API Testing Tool)

---

##  Arsitektur & Konsep
Project ini menggunakan konsep:
- RESTful API design
- MVC (Model - View - Controller)
- Relasi Database (One-to-Many antara Category dan Product)
- Layered Architecture (Controller, Service, Repository)

---

##  Struktur Response API

Contoh response:

🔹 Create
<img width="1600" height="722" alt="image" src="https://github.com/user-attachments/assets/88fe25f0-922c-4d80-97c0-d6a0d6ad5107" />

🔹 Find All
<img width="1600" height="722" alt="image" src="https://github.com/user-attachments/assets/afa1f2f1-c916-48f6-bad2-09a0e8a08537" />

🔹 Update
<img width="1600" height="841" alt="image" src="https://github.com/user-attachments/assets/ed650716-5493-40b8-a4d9-7d3c582550d3" />

🔹 Search by Category
<img width="1600" height="774" alt="image" src="https://github.com/user-attachments/assets/4c81af94-b4bc-40d7-9576-ea578e3b4239" />

🔹 Get Categories

🔹 Delete Product
<img width="1600" height="724" alt="image" src="https://github.com/user-attachments/assets/011825c1-8050-49b6-89a4-80dccf0840b1" />

🔹 Find by Name
<img width="1600" height="770" alt="image" src="https://github.com/user-attachments/assets/1757bf29-d8d4-46ed-b46d-ccc993504323" />

🔹 Supplier FindAll
<img width="1600" height="722" alt="image" src="https://github.com/user-attachments/assets/38dadf09-ae65-400f-ab3b-36123afb2af2" />

🔹 Supplier Create
<img width="1600" height="727" alt="image" src="https://github.com/user-attachments/assets/344446fc-c515-4c43-8163-cddc9fec908c" />

## Setup database MySQL:
🔹Buka database MySQL

🔹Sesuaikan application.properties
<img width="1919" height="819" alt="image" src="https://github.com/user-attachments/assets/06017669-5dba-43d4-a861-78a4d8f1afa3" />
🔹Jalankan project

🔹Test API menggunakan Insomnia / Postman
<img width="1600" height="841" alt="image" src="https://github.com/user-attachments/assets/27c0d50c-7e80-47d3-8b7e-d92c6f121cba" />


## Tahap Pengembangan Selanjutnya

Authentication & Authorization (JWT)


Validasi input (Validation)


Pagination & Sorting


Dokumentasi API (Swagger/OpenAPI)
