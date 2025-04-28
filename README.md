# HTML FORM SURVEY
Proyek ini bertujuan untuk membuat sebuah form survei perokok menggunakan HTML murni tanpa CSS tambahan. Fokus utama proyek ini adalah memahami struktur dasar form dalam HTML dan berbagai jenis input yang bisa digunakan.

## Fitur 
- Membuat struktur form HTML dari awal.
- Menggunakan berbagai elemen form seperti text input, radio button, number field, dan checkbox.
- Menjalankan file HTML secara live di browser menggunakan live-server.

## Persyaratan
Node.js sudah terinstal di komputer.

## Cara memulai
1. Inisialisasi proyek Node.JS
```
npm init -y
```

2. Install live-server sebagai dependensi:
```
npm install live-server --save-dev
```

3. Buka file package.json, lalu tambahkan script berikut:
```
"scripts": {
  "dev": "live-server"
}
```

4. Buat File HTML
- Buat file index.html.

- Tulis struktur dasar HTML, mulai dari ```<html>```, ```<head>```, hingga ```<body>```.

- Buat form menggunakan elemen: ```<form>```, ```<label>```, ```<input>``` dengan berbagai tipe seperti ```text```, ```number```. ```radio```, dan ```checkbox```.

5. Jalankan perintah berikut untuk menampilkan form di browser:
```
npm run dev
```