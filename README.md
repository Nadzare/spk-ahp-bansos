
# 🎯 Laravel SPK AHP

**Laravel SPK AHP** adalah aplikasi berbasis web yang menyediakan sistem pendukung keputusan menggunakan metode **AHP (Analytic Hierarchy Process)**. Aplikasi ini membantu pengguna dalam menganalisis berbagai alternatif keputusan berdasarkan kriteria tertentu secara **sistematis**, **transparan**, dan **akurat**.  

Dengan antarmuka yang ramah pengguna, pengguna dapat dengan mudah memasukkan data dan memperoleh hasil analisis mendalam untuk menunjang pengambilan keputusan yang lebih tepat.


Pada kasus perkenalkan team kami
 1. Nadzare Kafah Alfatiha (H1D023014)
 2. Mukhammad Alfaen Fadillah (H1D023032)
 3. M. Edwi Tsanystya Raihan (H1D023087)

 Pada sistem ini terlebih kamu gunakan untuk sebagai "Sistem Pendukung Keputusan Penentuan Prioritas Penerima Bantuan Sosial Menggunakan Metode **AHP (Analytic Hierarchy Process)**"

---

## 🚀 Tech Stack

| Teknologi           | Keterangan                                 |
|---------------------|---------------------------------------------|
| Laravel             | Framework PHP (Versi 12)                    |
| Laravel Breeze      | Autentikasi sederhana                       |
| MySQL               | Database management system                  |
| TailwindCSS         | CSS utility-first untuk styling             |
| daisyUI             | Komponen UI berbasis TailwindCSS            |
| Laravel Excel       | [maatwebsite/excel](https://laravel-excel.com/) untuk impor data |
| DOMPDF              | [barryvdh/laravel-dompdf](https://github.com/barryvdh/laravel-dompdf) untuk cetak PDF |

---

## 🔑 Demo Login

Untuk mencoba aplikasi, gunakan kredensial berikut:

- **Email**: `minahp@gmail.com`  
- **Password**: `12345678`

---

## ✨ Fitur Utama

- 🧮 Implementasi metode **AHP (Analytic Hierarchy Process)**
- 📥 Fitur **import data**
- 📊 Visualisasi hasil perbandingan
- 📄 Ekspor laporan ke **PDF** atau **Excel**
- 👤 Sistem login dan manajemen pengguna

---

## 🛠️ Instalasi

Ikuti langkah-langkah di bawah untuk menjalankan proyek ini di lokal Anda:

1. **Clone repository:**

   ```bash
   git clone https://github.com/Akbarwp/Laravel-SPK-AHP.git
   cd Laravel-SPK-AHP
   ```

2. **Install dependencies via Composer & NPM:**

   ```bash
   composer install
   npm install
   ```

3. **Copy file `.env` dan atur konfigurasi:**

   ```bash
   cp .env.example .env
   ```

4. **Generate application key:**

   ```bash
   php artisan key:generate
   ```

5. **Atur koneksi database di file `.env`:**

   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=laravel_ahp
   DB_USERNAME=root
   DB_PASSWORD=
   ```

6. **Jalankan migrasi database:**

   ```bash
   php artisan migrate
   ```

7. **Jalankan seeder untuk mengisi data awal:**

   ```bash
   php artisan db:seed
   ```

8. **Jalankan server dan frontend:**

   ```bash
   npm run dev
   php artisan serve
   ```

---

## 📄 Lisensi

Proyek ini menggunakan lisensi [MIT](https://choosealicense.com/licenses/mit/).

---

Jika Anda butuh bantuan atau ingin berkontribusi, silakan buat *issue* atau *pull request*.  
Happy coding! 💻✨
