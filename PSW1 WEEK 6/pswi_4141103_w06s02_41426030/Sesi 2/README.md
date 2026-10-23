1. Starter Mobile
Ketika saya mengganti ukurannya mengikuti tampilan mobile, yaitu menjadi 320px, tampilannya mengecil, mengikuti bagaimana di mobile akan terlihat, yaitu lebih kecil. Namun yang menjadi sorotan adalah konten yang disajikan tidak terpotong melainkan lengkap walafiat.

2. Breakpoint Konten
Pada viewport terjadi perubahan ukuran untuk tampilan web. Breakpointnya terletak di 768px yang mana tampilan kotak yang ada di web menjadi berbaris dua kolom, beda dengan 767px yang mana kotaknya satu baris saja. Ini menyesuakan ukuran ponsel ke tablet.

3. Uji Label Panjang
Ketika saya membuat teks panjang pada bagian h2, p, an h3 dengan overflow. Teks yang berada dalam card tidak sampai keluar dari kotak. Bukti tersedia dalam bentuk png di folder bukti sebelum dan sesudah.

4. Uji Matriks Viewport
Pengujian dilakukan pada viewport 320px, 768px, dan 1200px serta zoom browser 200%. Simulasi overflow dicoba dengan menambahkan min-width: 900px pada elemen .card. Namun, efek overflow tidak tampak secara signifikan karena tata letak katalog telah menggunakan CSS Grid yang membantu menjaga elemen tetap tersusun rapi. Setelah properti dikembalikan menjadi min-width: 0, halaman tetap responsif dan tidak ditemukan scroll horizontal pada seluruh pengujian

5. Laporan Mahasiswa
Kasus Normal
Tindakan: Membuka halaman pada viewport 1200px.
Hasil aktual: Seluruh konten tampil dengan baik dan tata letak tetap rapi.
Status/Bukti: Berhasil, halaman dapat diakses tanpa masalah.
Kasus Batas
Tindakan: Menguji viewport 320px dan zoom browser 200%.
Hasil aktual: Konten tetap terlihat lengkap, teks tidak terpotong, dan fokus keyboard masih terlihat.
Status/Bukti: Berhasil, tampilan tetap responsif pada ukuran layar kecil.
Kasus Gagal
Tindakan: Menambahkan min-width: 900px pada elemen .card untuk memicu overflow.
Hasil aktual: Overflow horizontal tidak muncul secara signifikan karena elemen berada dalam layout .catalog yang menggunakan CSS Grid sehingga susunan kartu tetap menyesuaikan ruang yang tersedia.
Status/Bukti: Simulasi gagal direproduksi, tidak ditemukan scroll horizontal meskipun ukuran minimum kartu diperbesar.