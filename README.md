# 🩺 Ranger HQ · OSCE Komprehensif Pra-Koas

Homepage belajar untuk **OSCE Komprehensif** (ujian pra-koas): materi dan ceklis semua sistem dalam satu tempat, lengkap dengan hitung mundur menuju hari ujian. Semua halaman berupa HTML yang bisa dibuka langsung di browser.

Dibuat untuk belajar sendiri, dibagikan kalau ada teman yang mau ikut pakai.

---

## ✨ Fitur

- **Hitung mundur realtime** menuju hari ujian (hari, jam, menit, detik).
- **12 sistem** dibagi sesuai kategori ujian: **8 sistem mayor** dan **4 sistem minor**.
- Tiap sistem punya dua akses: **Materi & Ceklis** (HTML) dan **Modul PDF** (Google Drive).
- **PPT Pengantar Sosialisasi** dan **Cheat Sheet Dasar OSCE** di bagian "Mulai dari sini".
- **Mode terang/gelap** dengan tombol di pojok kanan atas. Pilihan tersimpan di browser.
- Tampilan bersih dan responsif, nyaman dibuka dari HP.

---

## 📚 Daftar Sistem

| Kategori | Sistem | File HTML |
|---|---|---|
| Mayor | Respirasi | `OSCE-Kompre-Respirasi.html` |
| Mayor | Kardiovaskular | `OSCE-Kompre-Kardiovaskular.html` |
| Mayor | Gastrointestinal, Hepatobilier, dan Pankreas | `OSCE-Kompre-Gastrointestinal.html` |
| Mayor | Ginjal dan Saluran Kemih | `OSCE-Kompre-Ginjal-Saluran-Kemih.html` |
| Mayor | Endokrin, Metabolisme, dan Nutrisi | `OSCE-Kompre-Endokrin-Metabolik-Nutrisi.html` |
| Mayor | Hematologi dan Imunologi | `OSCE-Kompre-Hematologi-Imunologi-Infeksi.html` |
| Mayor | Muskuloskeletal | `OSCE-Kompre-Muskuloskeletal.html` |
| Mayor | Reproduksi | `OSCE-Kompre-Reproduksi-ObGyn.html` |
| Minor | Saraf | `OSCE-Kompre-Neurologi.html` |
| Minor | Psikiatri | `OSCE-Kompre-Psikiatri.html` |
| Minor | Indra (Mata/THT) | `OSCE-Kompre-Mata-THT.html` |
| Minor | Integumentum | `OSCE-Kompre-Kulit-Kelamin.html` |

---

## 📁 Struktur

```
osce-kompre/
├── index.html                    # Homepage (buka file ini)
├── OSCE-Kompre-<Sistem>.html     # 12 file materi + ceklis
├── README.md
├── LICENSE
└── .gitignore
```

Modul PDF **tidak disimpan di repositori**. PDF dibuka lewat link Google Drive di `index.html`. File HTML sistem harus **satu folder** dengan `index.html` karena tombolnya tertaut lewat nama file, jadi nama file jangan diubah tanpa mengubah link-nya.

---

## 🚀 Cara Pakai

Tidak perlu install apa pun:

1. Clone atau download repositori ini.
2. Buka `index.html` di browser.
3. Pilih sistem, lalu buka materi atau modul PDF-nya.

Kalau dipasang lewat **GitHub Pages**, `index.html` otomatis terbuka di alamat utamanya.

---

## 🛠️ Kustomisasi

- **Tanggal ujian:** ubah `EXAM_DATE` di bagian `<script>` pada `index.html`, misalnya `'2026-11-28T07:30:00+07:00'` (waktu WIB). Setelah jam diisi, ubah `EXAM_TIME_KNOWN` menjadi `true`.
- **Link Drive:** ubah `href` pada tombol yang bersangkutan di `index.html`.
- **Warna:** edit variabel di `:root` (mode terang) dan `html[data-theme="dark"]` (mode gelap).

---

## 🧱 Teknologi

HTML, CSS, dan JavaScript biasa. Tidak ada framework dan tidak ada proses build. Koneksi internet hanya dipakai untuk memuat Google Fonts dan membuka link Google Drive.

---

## 📄 Lisensi dan Catatan

Lisensi **CC BY-NC 4.0**, lihat [LICENSE](./LICENSE). Boleh dipakai dan disebarkan untuk belajar, tidak untuk keperluan komersial.

> ⚠️ Materi disusun dari checklist dan teks OSCE yang dimiliki penyusun, lalu dirapikan per sistem. Ini bukan sumber resmi. Ikuti versi checklist yang dipakai penguji dan cek ulang ke panduan dosen.

---

> *"Semangat, calon dokter muda! ✊🏻"*
