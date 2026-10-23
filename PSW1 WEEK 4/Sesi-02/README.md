1. Persiapan Stylesheet
Ketika saya menambahkan { background: #f4f6fa; } di style.css sebagai bukti tidak ada perubahan perubahan sama sekali. Saya telah mengecek di DevTools network css dan statusnya bisa berjalan sementara itu saat ditambah { background: #f4f6fa; } muncul nama css baru bertuliskan "style.css?_cacheOverride=1791016198596".

2. Selector dan Class
Pada hal ini saya mencoba bereksperimen dimana nama class pada html saya ubah hal yang terjadi style css yang sudah dibuat tidak berfungsi tetapi ketika saya ulang dan perbaiki dalam html dan coba saya jalankan lagi style css sudah berfungsi dan berjalan seperti semula.

3. Konflik Specificity
.card menjadi yang terspesifik, serta menjadi yang paling diutamakan adalah karena card lah yang kita deklarasikan sehingga yang menjadi permasalahan bukan mana yang paling terdahulu antara card atau notice melainkan mana yang paling spesifik dari antara keduanya.

4. Ukuran Margin dan Kotak
Pada bagian ini bagian tabel pendaftaran diubah menjadi satu kotak yang semantik dan dibuat menjadi satu bagian, Dimana bagian tersebut sekarang sudah mempunyai latar kotak nya sendiri, tetapi ketika margin diubah tidak berpengaruh kepada halaman web.

5. FORMAT LAPORAN YANG DI ISI MAHASISWA

Kasus: style css tidak terbaca
tindakan: Saya menyadari bahwa style css berada dalam folder dan saya nge-linknya demikian: <link rel="stylesheet" href="style.css">. Maka saya memindahkan style.css keluar folder karena pada dasarnya href tidak href="(nama-folder)/style.css"


