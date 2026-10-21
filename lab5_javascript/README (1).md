# Praktikum 5: JavaScript Dasar dan Manipulasi HTML

## Identitas Praktikum
- **Mata Kuliah:** Pemrograman Web
- **Praktikum:** Praktikum 5
- **Topik:** JavaScript Dasar dan Manipulasi HTML
- **Repository:** `Lab5Web`

## Tujuan Praktikum
1. Menampilkan output menggunakan JavaScript.
2. Menggunakan `alert()` dan `prompt()`.
3. Menggunakan function dan operator aritmetika.
4. Menerapkan seleksi kondisi `if-else` dan `switch`.
5. Memeriksa bilangan genap atau ganjil melalui form.
6. Mengubah warna latar halaman.
7. Membuat mini project kalkulator nilai mahasiswa.

## Struktur Folder
```text
Lab5Web/
├── index.html
├── script.js
├── README.md
└── screenshots/
    ├── latihan1-output.png
    ├── latihan2-alert-prompt.png
    ├── latihan3-operasi-aritmetika.png
    ├── latihan4-if-else.png
    ├── latihan5-switch.png
    ├── latihan6-genap-ganjil.png
    ├── latihan7-ubah-warna.png
    └── miniproject-kalkulator-nilai.png
```

## Cara Menjalankan
1. Simpan `index.html` dan `script.js` di folder proyek yang sama.
2. Pastikan HTML memanggil JavaScript menggunakan `<script src="script.js"></script>`.
3. Buka `index.html` di browser.
4. Tekan `F12` lalu buka tab **Console** untuk melihat hasil `console.log()`.
5. Ambil screenshot hasil tiap latihan dan simpan di folder `screenshots` dengan nama yang tercantum di bawah.

## Latihan 1 — Menampilkan Output
**Tujuan:** Menampilkan `Hello World` pada halaman dan Console.

**Hasil yang diharapkan:** Elemen dengan ID `pesan` menampilkan `Hello World`, dan teks yang sama tampil di Console.

![Latihan 1 - Menampilkan Output](screenshots/latihan1-output.png)

## Latihan 2 — Alert dan Prompt
**Tujuan:** Meminta nama pengguna, menampilkan sapaan, dan memperbarui teks halaman.

**Hasil yang diharapkan:** Jika nama diisi, tampil sapaan dan pesan selamat datang. Jika input dibatalkan atau kosong, tampil pesan bahwa nama belum diisi.

![Latihan 2 - Alert dan Prompt](screenshots/latihan2-alert-prompt.png)

## Latihan 3 — Function dan Operasi Aritmetika
**Tujuan:** Menghitung penjumlahan, pengurangan, perkalian, pembagian, dan modulus dari `operasiDasar(9, 4)`.

**Hasil yang diharapkan di Console:**
- Penjumlahan: `13`
- Pengurangan: `5`
- Perkalian: `36`
- Pembagian: `2.25`
- Modulus: `1`

![Latihan 3 - Operasi Aritmetika](screenshots/latihan3-operasi-aritmetika.png)

## Latihan 4 — Seleksi Kondisi If-Else
**Tujuan:** Memeriksa nilai mahasiswa.

**Hasil yang diharapkan:** Nilai 60–100 dinyatakan lulus; nilai di bawah 60 dinyatakan belum lulus; input kosong, tidak valid, atau di luar rentang 0–100 menampilkan pesan input tidak valid.

![Latihan 4 - If Else](screenshots/latihan4-if-else.png)

## Latihan 5 — Seleksi Kondisi Switch
**Tujuan:** Meminta angka 1–5 dan menampilkan nama bilangan menggunakan `switch`.

**Hasil yang diharapkan:** Angka 1–5 menampilkan nama bilangan yang sesuai; input lainnya menampilkan pesan pilihan tidak tersedia.

![Latihan 5 - Switch](screenshots/latihan5-switch.png)

## Latihan 6 — Form Bilangan Genap atau Ganjil
**Tujuan:** Memeriksa bilangan bulat yang dimasukkan melalui form HTML.

**Hasil yang diharapkan:** Bilangan genap menampilkan `Bilangan genap`, bilangan ganjil menampilkan `Bilangan ganjil`, dan input kosong atau desimal menampilkan pesan validasi.

![Latihan 6 - Genap atau Ganjil](screenshots/latihan6-genap-ganjil.png)

## Latihan 7 — Mengubah Warna Halaman
**Tujuan:** Mengubah warna latar menggunakan satu function dengan parameter.

**Hasil yang diharapkan:** Tombol Latar Hijau, Latar Putih, dan Latar Kuning mengubah warna latar halaman.

![Latihan 7 - Mengubah Warna](screenshots/latihan7-ubah-warna.png)

## Mini Project — Kalkulator Nilai Mahasiswa
**Tujuan:** Menghitung nilai akhir dari tugas, UTS, dan UAS serta menentukan predikat dan status kelulusan.

**Bobot:** Tugas 30%, UTS 30%, UAS 40%.

**Data contoh:** Tugas 85, UTS 78, UAS 88.

**Perhitungan:**
```text
Nilai akhir = (85 × 0,30) + (78 × 0,30) + (88 × 0,40)
            = 25,5 + 23,4 + 35,2
            = 84,10
```

**Hasil yang diharapkan di Console:**
- Nilai akhir: `84.10`
- Predikat: `B`
- Status: `Lulus`

![Mini Project - Kalkulator Nilai Mahasiswa](screenshots/miniproject-kalkulator-nilai.png)

## Kesimpulan
Praktikum ini melatih penggunaan output JavaScript, dialog input, operasi aritmetika, seleksi kondisi, function, manipulasi DOM, dan perhitungan nilai mahasiswa. Hasil diuji melalui tampilan browser dan Console.

## Catatan Screenshot
**Penting:** gambar tidak akan muncul sampai screenshot asli dimasukkan ke folder `screenshots` di repository GitHub. Pastikan nama file sama persis dengan nama pada tautan gambar di atas. Gunakan screenshot dari hasil praktikum kamu sendiri; jangan mengunggah file teks atau gambar yang bukan screenshot.
