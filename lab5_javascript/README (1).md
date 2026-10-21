<img width="960" height="504" alt="latihan1-output" src="https://github.com/user-attachments/assets/ed046239-46f7-40ea-b236-e77f205e9f19" />
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

![Latihan 1 - Menampilkan Output](<img width="960" height="504" alt="latihan1-output" src="https://github.com/user-attachments/assets/88b543af-5e36-4c5b-bc96-c61a7dd4937a" />
)

## Latihan 2 — Alert dan Prompt
**Tujuan:** Meminta nama pengguna, menampilkan sapaan, dan memperbarui teks halaman.

**Hasil yang diharapkan:** Jika nama diisi, tampil sapaan dan pesan selamat datang. Jika input dibatalkan atau kosong, tampil pesan bahwa nama belum diisi.

![Latihan 2 - Alert dan Prompt](<img width="960" height="504" alt="latihan2-prompt" src="https://github.com/user-attachments/assets/0ed2cc3e-0535-429f-8fac-f3bc932b782c" />
)

## Latihan 3 — Function dan Operasi Aritmetika
**Tujuan:** Menghitung penjumlahan, pengurangan, perkalian, pembagian, dan modulus dari `operasiDasar(9, 4)`.

**Hasil yang diharapkan di Console:**
- Penjumlahan: `13`
- Pengurangan: `5`
- Perkalian: `36`
- Pembagian: `2.25`
- Modulus: `1`

![Latihan 3 - Operasi Aritmetika](<img width="960" height="504" alt="latihan3-aritmetika" src="https://github.com/user-attachments/assets/3af969d8-9800-42af-a7d6-9fc595f5faca" />
)

## Latihan 4 — Seleksi Kondisi If-Else
**Tujuan:** Memeriksa nilai mahasiswa.

**Hasil yang diharapkan:** Nilai 60–100 dinyatakan lulus; nilai di bawah 60 dinyatakan belum lulus; input kosong, tidak valid, atau di luar rentang 0–100 menampilkan pesan input tidak valid.

![Latihan 4 - If Else](<img width="960" height="504" alt="latihan4-if-else" src="https://github.com/user-attachments/assets/75682282-754a-435c-a985-9f6990b949e9" />
)

## Latihan 5 — Seleksi Kondisi Switch
**Tujuan:** Meminta angka 1–5 dan menampilkan nama bilangan menggunakan `switch`.

**Hasil yang diharapkan:** Angka 1–5 menampilkan nama bilangan yang sesuai; input lainnya menampilkan pesan pilihan tidak tersedia.

![Latihan 5 - Switch](<img width="960" height="504" alt="latihan5-switch" src="https://github.com/user-attachments/assets/1ea4c29a-bcd3-4e0c-917b-cc2ac93d2fd4" />
)

## Latihan 6 — Form Bilangan Genap atau Ganjil
**Tujuan:** Memeriksa bilangan bulat yang dimasukkan melalui form HTML.

**Hasil yang diharapkan:** Bilangan genap menampilkan `Bilangan genap`, bilangan ganjil menampilkan `Bilangan ganjil`, dan input kosong atau desimal menampilkan pesan validasi.

![Latihan 6 - Genap atau Ganjil](<img width="960" height="504" alt="latihan6-genap-ganjil png" src="https://github.com/user-attachments/assets/fa152468-fbe4-4091-b4d0-18a71dd2eda5" />
)

## Latihan 7 — Mengubah Warna Halaman
**Tujuan:** Mengubah warna latar menggunakan satu function dengan parameter.

**Hasil yang diharapkan:** Tombol Latar Hijau, Latar Putih, dan Latar Kuning mengubah warna latar halaman.

![Latihan 7 - Mengubah Warna](<img width="960" height="504" alt="latihan7-warna" src="https://github.com/user-attachments/assets/dcac7f94-fa9d-4103-bf49-fae374a7441b" />
)

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

![Mini Project - Kalkulator Nilai Mahasiswa](<img width="960" height="504" alt="miniproject-kalkulator" src="https://github.com/user-attachments/assets/b7aebe72-f505-43ed-81d9-fd005e79e3c4" />
)

## Kesimpulan
Praktikum ini melatih penggunaan output JavaScript, dialog input, operasi aritmetika, seleksi kondisi, function, manipulasi DOM, dan perhitungan nilai mahasiswa. Hasil diuji melalui tampilan browser dan Console.

## Catatan Screenshot
**Penting:** gambar tidak akan muncul sampai screenshot asli dimasukkan ke folder `screenshots` di repository GitHub. Pastikan nama file sama persis dengan nama pada tautan gambar di atas. Gunakan screenshot dari hasil praktikum kamu sendiri; jangan mengunggah file teks atau gambar yang bukan screenshot.
