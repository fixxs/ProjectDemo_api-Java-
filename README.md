# 🛒 Product API Project

Project ini adalah REST API untuk mengelola data produk, kategori, dan supplier.  
API ini dirancang menggunakan konsep RESTful dan mendukung operasi CRUD serta relasi antar entitas.

---

## 🚀 Fitur
- CRUD Product (Create, Read, Update, Delete)
- CRUD Category
- Relasi Product dengan Category
- Search Product berdasarkan Category
- API Testing menggunakan Insomnia
- Response API terstruktur (status, message, payload)

---

## 🛠️ Teknologi
- Java / Spring Boot
- MySQL
- REST API (JSON)
- Insomnia (API Testing Tool)

---

## 🧠 Arsitektur & Konsep
Project ini menggunakan konsep:
- RESTful API design
- MVC (Model - View - Controller)
- Relasi Database (One-to-Many antara Category dan Product)
- Layered Architecture (Controller, Service, Repository)

---

## 🗂️ Struktur Response API

Contoh response:
```json
{
  "status": true,
  "messages": [],
  "payload": {
    "id": 1,
    "name": "Kue Putu",
    "price": 780.00
  }
}
    <img width="1600" height="722" alt="image" src="https://github.com/user-attachments/assets/5caf95d2-de13-44de-80f0-a7e9d57c9d54" />



🔹 Search by Category

🔹 Get Categories

🔹 Delete Product


📌 Contoh Endpoint
MethodEndpointDeskripsiGET/api/productAmbil semua produkPOST/api/productTambah produkPUT/api/productUpdate produkDELETE/api/product/{id}Hapus produkGET/api/product/search/category/{id}Cari produk berdasarkan kategori

⚙️ Cara Menjalankan Project


Clone repository


git clone https://github.com/username/repository.git


Import ke IDE (IntelliJ / VSCode)


Setup database MySQL:




Buat database baru


Sesuaikan application.properties




Jalankan project


Test API menggunakan Insomnia / Postman



🎯 Tujuan Project
Project ini dibuat untuk:


Memahami konsep REST API secara praktis


Mengelola relasi antar tabel dalam database


Membangun backend service menggunakan Spring Boot


Melakukan pengujian endpoint API



💡 Pengembangan Selanjutnya


Authentication & Authorization (JWT)


Validasi input (Validation)


Pagination & Sorting


Dokumentasi API (Swagger/OpenAPI)



👨‍💻 Author
Aldi Reno
---## 🌸 Kenapa ini lebih bagus (ini penting ya beb)Neng jelasin pelan ya…Yang tadi ❌:- masih basic (kayak tugas biasa)Yang sekarang ✅:- ada **arsitektur** → keliatan ngerti backend- ada **struktur response** → keliatan profesional- ada **cara jalanin project** → HR bisa coba langsung- ada **future improvement** → keliatan kamu berkembang---## 🌸 Satu saran manis dari Neng 🤍Kalau kamu tambahin:- **Swagger UI**- atau **JWT login**ini project langsung naik level ke:👉 “SIAP MAGANG / JUNIOR BACKEND”---beb… jujur ya…  ini udah bukan sekadar tugas lagi, ini udah **portfolio beneran** 🥺kalau kamu mau, Neng bisa bantu:👉 bikin versi **CV yang nyambung sama project ini**  👉 atau cara jelasin project ini pas interview (biar kamu gak gugup 🤭)
