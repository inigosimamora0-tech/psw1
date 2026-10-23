1. Container
Hasil:
Setelah CSS Grid diterapkan, seluruh elemen .card di dalam container .catalog secara otomatis menjadi grid item.
Layout yang awalnya tersusun dalam satu kolom berubah menjadi dua kolom dengan lebar yang sama. Jarak antar card juga tetap rapi karena menggunakan properti gap.

2. Grid Adaptif
Hasil Pengujian:
Viewport 320px
Layout menampilkan satu kolom sehingga setiap card tersusun ke bawah secara vertikal. Hal ini terjadi karena ruang yang tersedia tidak cukup untuk membentuk lebih dari satu kolom.

Viewport 768px
Layout secara otomatis menyesuaikan jumlah kolom sesuai ruang yang tersedia. Card dapat ditampilkan dalam beberapa kolom tanpa perlu mengubah kode CSS.

Viewport 1200px
Jumlah kolom bertambah secara otomatis sehingga area kosong dapat dimanfaatkan dengan lebih efisien dan tampilan menjadi lebih rapi.

3. Card & Internal Gap
Hasil:
Setelah Flexbox diterapkan pada .card, isi card tersusun secara vertikal mulai dari judul, deskripsi, hingga tautan detail. Jarak antar elemen menjadi lebih teratur dan konsisten karena menggunakan properti gap.
Penghapusan margin bawaan membuat tampilan lebih rapi dan menghindari jarak yang berlebihan antar elemen. Link juga tampil sesuai ukuran teks sehingga lebih proporsional. 

Tindakan Nyata:
Mengubah .card menjadi flex container menggunakan display: flex.
Mengatur arah susunan elemen secara vertikal dengan flex-direction: column.
Menambahkan gap: .5rem untuk memberi jarak antar elemen di dalam card.
Menghilangkan margin bawaan pada elemen heading dan paragraf.
Menambahkan pengaturan untuk elemen link (.card a) agar tidak melebar apabila nantinya ditambahkan tautan di dalam card.

4. Review Layout 
Pengujian Card
0 card= Katalog tetap rapi ketika tidak ada card.

1 card= Card tampil dengan ukuran dan jarak yang sesuai.

5 card= Card tersusun dengan baik dan menyesuaikan lebar layar.
Bukti ada di folder bukti berisi screenshot

Alasan Pemilihan Layout:
Pada CSS, Grid saya pilih untuk katalog karena memudahkan pengaturan baris dan kolom secara responsif. Flexbox saya gunakan pada setiap card agar judul, deskripsi, dan tautan tersusun secara vertikal.

Validasi CSS di HTML checker
Tidak terdapat adanya error ataupun peringatan, dan bukti foto tersedia di folder bukti.

5. Laporan yang diisi mahasiswa
Kasus Normal
Kondisi: Halaman dibuka menggunakan browser.
Tindakan: Memeriksa tampilan lima card kegiatan mahasiswa.
Hasil aktual: Lima card memiliki judul dan deskripsi sesuai dengan HTML.
Status: Lulus.

Lebar Layar 320px
Kondisi: Lebar viewport browser diatur menjadi 320px.
Tindakan: Memeriksa apakah card tetap berada di dalam container.
Hasil aktual: CSS Grid menggunakan minmax() dan .card memiliki min-width: 0 untuk membantu mencegah overflow.
Status: Lulus dengan bukti screenshot.

Pengujian Satu Card
Kondisi: Hanya satu elemen .card yang ditampilkan.
Tindakan: Menyisakan satu card di dalam elemen .catalog.
Hasil aktual: Grid dirancang untuk menyesuaikan kolom dengan ruang yang tersedia.
Status: Lulus.

Pengujian Lima Card
Kondisi: Lima card ditampilkan sesuai HTML awal.
Tindakan: Memeriksa penataan card menggunakan CSS Grid.
Hasil aktual: Properti auto-fit dan minmax() digunakan untuk menyesuaikan jumlah kolom dengan lebar container.
Status: Lulus.

Pengujian Urutan Tab
Kondisi: Navigasi halaman menggunakan keyboard.
Tindakan: Menekan tombol Tab untuk berpindah ke elemen interaktif.
Hasil aktual: Tombol dan tautan dapat menerima fokus sesuai urutan DOM. Card yang tidak memiliki elemen interaktif dilewati.
Status: Lulus.
