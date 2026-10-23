1. Gambar Fleksibel
Tindakan : mengubah maximal ukuran gambar menjadi 100% dan tinggi otomatis mengikuti. saya juga menambahkan gambar sendiri dan memakai path yang benar dan untuk alt tidak saya buat karena tujuan dari gambar yang saya buat hanya untuk hiasan. Gambar juga tiak mengalami eror 404.
Hasil : Gambar mengikuti ukuran wadah 
Bukti : Saya sematkan di bukti
Keterangan Foto: Sumber gambar adalah Pinterest. Saya memilih gambar-gambar tersebut karena saya sangat tertarik pada lukisan lukisan era renaisans juga sejarah serta makna spiritual lukisan yang bersifat religius.

2. Tindakan: Saya membuat dua versi gambar dengan ukuran berbeda, yaitu 320 piksel dan 640 piksel. Selanjutnya, saya menerapkan atribut srcset agar browser dapat memilih gambar yang paling sesuai berdasarkan ukuran layar pengguna.

Hasil: Browser dapat menentukan dan memuat gambar dengan resolusi yang dianggap paling tepat. Dalam beberapa kondisi, browser tetap memilih gambar berukuran 640 piksel untuk menjaga kualitas tampilan.

Bukti: Terlampir pada bagian bukti.

3. Kandidat Resolusi
Tindakan: Saya membuat dua versi gambar dengan ukuran berbeda, yaitu 320 piksel dan 640 piksel. Selanjutnya, saya menerapkan atribut srcset agar browser dapat memilih gambar yang paling sesuai berdasarkan ukuran layar pengguna.

Hasil: Browser dapat menentukan dan memuat gambar dengan resolusi yang dianggap paling tepat. Dalam beberapa kondisi, browser tetap memilih gambar berukuran 640 piksel untuk menjaga kualitas tampilan.

Bukti: Terlampir pada bagian bukti.

4. Fluid Font dan Container Query
Tindakan: Saya menerapkan fungsi clamp() pada ukuran font judul (h1) sehingga ukurannya dapat bertambah atau berkurang secara dinamis mengikuti perubahan ukuran viewport. Selain itu, saya membuat @container dengan .card-wrap sebagai acuan ukuran. Ketika ukuran .card-wrap bertambah, nilai padding pada kartu juga akan meningkat secara otomatis.

Hasil: Ukuran teks judul menjadi responsif terhadap perubahan ukuran layar. Padding pada card juga dapat menyesuaikan ukuran kontainernya sehingga tampilan menjadi lebih proporsional.

Bukti: Terlampir pada bagian bukti.

5. Reduce Motion dan Audit
Tindakan: Saya menambahkan media query prefers-reduced-motion: reduce untuk menonaktifkan efek transisi pada elemen card ketika pengguna memilih pengurangan animasi pada sistem operasi atau browser. Setelah itu, saya melakukan pengujian dengan mengaktifkan fitur reduced motion melalui browser, menguji navigasi menggunakan keyboard, mencoba pembesaran halaman (zoom), serta memastikan tidak ada informasi yang hanya muncul saat hover.

Hasil: Website tetap dapat digunakan dengan baik meskipun animasi dinonaktifkan. Seluruh informasi dan fitur utama tetap dapat diakses menggunakan keyboard maupun saat halaman diperbesar. Pengaturan preferensi reduced motion dari pengguna tidak menghilangkan fungsi atau konten yang tersedia pada website.