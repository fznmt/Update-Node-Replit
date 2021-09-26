<h1 align="center">Update Node Replit</h1>

> **Berikut adalah cara menaikkan / update versi NodeJS menjadi 16+ di [Repl.it](https://www.replit.com/)**
## 1️⃣ | Cara Pertama
> 1. Masuk ke project NodeJS yang ingin diupdate
> 2. Pergi ke shell (Disebelah Console) lalu ketik:
```shell
npm init -y && npm i --save-dev node@16 && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd)/node_modules/node/bin:$PATH 
```
> 3. Silahkan tunggu hingga selesai
> 4. Jika sudah selesai, buat file bernama ```.replit```
> 5. Jika sudah dibuat, silahkan masukkan:
```
run="npm start"
```
> 6. Masuk ke file ```package.json```
> 7. Cari bagian:
```json
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  }
```
> 8. Jika sudah ditemukan, tambahkan koma lalu klik ```enter``` dan masukkan:
```json
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node index.js" 
  },
```
**SELESAI**

> **Note:** ```index.js sesuaikan dengan main file kalian```

> **Note:** ```Untuk pengguna android, silahkan aktifkan situs dekstop untuk mengakses Shell pada replit```

## 2️⃣ | Cara Kedua
> 1. Masuk ke replit bagian My repls | [My Repls](https://replit.com/repls)
> 2. Klik tanda ```+``` di pojok kanan atas
> 3. Cari kata kunci ```NodeJS 16```
> 4. Lalu klik ```NodeJS 16```
> 5. Berikan nama project (Tidak Penting)
> 6. Klik tombol ```Create Repl```
> 7. Masuk kembali ke project

**SELESAI**
