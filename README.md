# 🖼️ Supabase Image Repository

Repositori ini digunakan sebagai tempat penyimpanan (storage) berbagai **gambar atau aset visual** yang terhubung dengan **database Supabase** pada project utama.

## 📦 Tujuan
Repository ini berfungsi untuk:
- Menyimpan file gambar yang digunakan oleh aplikasi berbasis Supabase (misalnya untuk tampilan antarmuka, data destinasi, profil, dsb).
- Menyediakan URL publik dari GitHub agar dapat diintegrasikan langsung ke Supabase Storage atau API.
- Mempermudah dokumentasi dan versioning aset gambar agar tidak tercampur dengan source code utama.

## 🧩 Struktur Isi
Setiap direktori di repo ini mewakili kategori atau wilayah tertentu, misalnya:
- `/banten` → Gambar destinasi wisata di Provinsi Banten  
- `/jawatimur` → Gambar wisata di Jawa Timur  
- `/sumut` → Gambar wisata di Sumatera Utara  
- `/ntt` → Gambar wisata di Nusa Tenggara Timur  
- dan seterusnya.

## 🔗 Cara Menggunakan
1. Buka gambar yang ingin digunakan dari folder ini.  
2. Klik kanan → “Copy image address” atau salin URL GitHub-nya.  
3. Gunakan URL tersebut di dalam aplikasi atau database Supabase, misalnya:

   ```sql
   INSERT INTO destinations (name, image_url)
   VALUES ('Danau Toba', 'https://github.com/username/repo-name/assets/.../gambar.jpg');
