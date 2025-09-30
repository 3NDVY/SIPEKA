# 📡 Tugas Akhir – Sistem Monitoring Suhu dan Kelembapan Berbasis ESP32 & Google Sheets

Proyek ini merupakan implementasi sistem **Internet of Things (IoT)** untuk **monitoring suhu dan kelembapan** secara real-time menggunakan **ESP32**, **sensor DHT22**, dan integrasi dengan **Google Sheets** serta **Dashboard berbasis Web**.

---

## 📊 Realtime Dashboard Monitoring

Dashboard ini menampilkan grafik suhu dan kelembapan dari dua node (Node 1 dan Node 2) secara real-time:

🔗 **[Klik untuk membuka Dashboard](https://script.google.com/macros/s/AKfycbwr8vpJcWJCbbE6ODexby1gcIbAs1n7bWXPa730mxGJYbJ3WtMxH6r9JVc9o6nsGyaONQ/exec)**

![Tampilan Dashboard](assets/dashboard.png)

---

## 📋 Spreadsheet Google Sheets

Data yang dikirimkan dari ke 2 Node akan otomatis tersimpan pada Google Sheets berikut:

🔗 **[Lihat Spreadsheet Data](https://docs.google.com/spreadsheets/d/1eFOSuYBjNJ0WZvjqI1QSj9x_vhyQNP2CYTDQAU9VUgI/edit#gid=1782827535)**

---

## ⚙️ Fitur Sistem

- ✅ Pembacaan suhu dan kelembapan dari dua node menggunakan sensor DHT22
- ✅ Komunikasi antar ESP32 menggunakan ESP-NOW
- ✅ Pengiriman data ke Google Sheets melalui HTTP Request
- ✅ Visualisasi data real-time pada Web Dashboard (Chart.js)
- ✅ Tampilan lokal via LCD I2C
- ✅ Indikator LED untuk peringatan suhu/kelembapan melebihi batas

---

## 🧰 Teknologi yang Digunakan

- **ESP32**
- **Sensor DHT22**
- **ESP-NOW**
- **LCD I2C 20x4**
- **Google Apps Script**
- **Google Sheets**
- **HTML + CSS + JavaScript (Chart.js)**

---

## 📁 Struktur Direktori

```bash
├── /Draft
├── /src/              # Source code 
├── /assets/           
├── README.md
