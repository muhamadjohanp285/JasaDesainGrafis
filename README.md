# Situs Web Jasa Desain Grafis

Situs web statis (HTML, CSS, dan sedikit JavaScript) untuk Tugas 1 mata kuliah Pemrograman Web, Universitas Islam Balitar. Tidak perlu server atau instalasi apa pun; cukup dibuka lewat peramban (browser).

## Cara Membuka Situs

1. Jika file masih berbentuk `.zip`, ekstrak dulu ke satu folder. Jangan membuka file langsung dari dalam zip, karena gambar dan gaya tampilan tidak akan muncul.
2. Pastikan susunan folder seperti ini dan jangan dipisah:

   ```
   situs/
   ├── login.html
   ├── index.html
   ├── pengertian.html
   ├── layanan.html
   ├── daftarjasa.html
   ├── alur.html
   ├── biodata.html
   ├── style.css
   ├── README.md
   └── img/
       ├── logo.svg
       ├── poster.svg
       ├── kemasan.svg
       └── sosmed.svg
   ```

3. **Buka `login.html` terlebih dahulu** dengan cara klik dua kali, atau klik kanan lalu pilih *Open with* dan pilih peramban (Chrome, Edge, Firefox, dan sebagainya).
4. Masukkan akun pada bagian berikut, lalu klik **Masuk**.
5. Jika berhasil, Anda otomatis diarahkan ke halaman Beranda (`index.html`) dan dapat menjelajahi halaman lain lewat menu di bagian atas.

## Akun Login

| Isian          | Nilai   |
|----------------|---------|
| Nama Pengguna  | `admin` |
| Kata Sandi     | `12345` |

Akun ini hanya contoh untuk latihan dan tertulis di dalam kode (`login.html`). Jangan dipakai untuk situs sungguhan.

Pesan yang mungkin muncul:
- *"Nama pengguna dan kata sandi wajib diisi."* berarti salah satu kolom masih kosong.
- *"Nama pengguna atau kata sandi salah."* berarti akun yang dimasukkan tidak cocok. Perhatikan huruf besar/kecil.

## Daftar Halaman

| File               | Isi                                                                 |
|--------------------|---------------------------------------------------------------------|
| `login.html`       | Pop up login (halaman pertama yang dibuka)                          |
| `index.html`       | Beranda dan pengantar situs                                         |
| `pengertian.html`  | Pengertian dan manfaat jasa desain grafis                           |
| `layanan.html`     | Jenis-jenis layanan beserta contoh gambar                           |
| `daftarjasa.html`  | Tabel daftar jasa dan harga (dibuat dengan array dan perulangan JS) |
| `alur.html`        | Alur kerja dan tips memilih jasa desain                             |
| `biodata.html`     | Biodata anggota kelompok dan catatan pengerjaan                     |

## Catatan

- Menu `Login` tidak ada di menu bar karena login hanya dipakai di awal. Untuk keluar atau masuk ulang, buka kembali `login.html`.
- Halaman selain login saat ini masih bisa dibuka langsung tanpa login, karena situs ini statis dan belum memakai pemeriksaan sesi.
- Harga dan estimasi di halaman Daftar Jasa hanya contoh.
- Gunakan peramban versi terbaru. Koneksi internet tidak diperlukan.

## Jika Ada Masalah

- **Gambar tidak muncul:** pastikan folder `img/` berada satu tingkat dengan file `.html`, dan nama file gambar tidak diubah.
- **Tampilan polos tanpa warna:** pastikan `style.css` berada satu folder dengan file `.html`.
- **Tabel di Daftar Jasa kosong:** pastikan JavaScript di peramban tidak dinonaktifkan.
- **Setelah login tidak berpindah halaman:** tunggu sekitar satu detik; jika tetap tidak berpindah, pastikan `index.html` ada di folder yang sama.

## Dibuat Oleh

Kelompok Pemrograman Web, Universitas Islam Balitar (lihat `biodata.html` untuk daftar anggota).
