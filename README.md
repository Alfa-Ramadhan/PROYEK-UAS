MovieStore – Sistem Pemesanan Tiket Bioskop Online

MovieStore adalah platform pemesanan tiket bioskop berbasis web yang memungkinkan pengguna untuk memilih film, lokasi bioskop, jadwal tayang, kursi, hingga menerima tiket dalam bentuk QR Code secara digital.

Fitur Utama

- Login & Registrasi pengguna
- Melihat daftar film dan detailnya
- Memilih bioskop dan jadwal tayang
- Memilih kursi secara visual
- Menghitung total harga tiket
- Generate tiket digital dengan QR Code
- Mengirim undangan ke teman via email
- Download tiket dalam format PDF

Teknologi yang Digunakan

Frontend:
- React.js
- Redux
- Material-UI
- jsPDF

Backend:
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Nodemailer
- QRCode

Struktur Folder:
MovieStore/
├── client/    #React frontend
│ └── src/
├── server/    #Express backend
│ ├── routes/
│ ├── models/
│ ├── controllers/
│ ├── seed.js
│ └── src/db/mongoose.js
├── .env
├── README.md
└── package.json


Cara Menjalankan:

# 1. Clone Repository
git clone https://github.com/Alfa-Ramadhan/PROYEK-UAS.git
cd moviestore


# 2. Buat file .env di folder /server
MONGODB_URI="mongodb+srv://fuadalfajri92:y2IMxI7LIAjYUdLL@movie.jhepvky.mongodb.net/?retryWrites=true&w=majority&appName=Movie"


# 3. Install dependencies
Root folder
npm install


Frontend
cd client
npm install


# 4. Jalankan Project
Backend
cd server
npm run dev

Frontend
cd ../client
npm start


# Anggota Kelompok:
1. Alfa Ramadhan
2. Farrel Adrian Laksana
3. Fuad Al Fajri
4. Rayhan Juliansyah
