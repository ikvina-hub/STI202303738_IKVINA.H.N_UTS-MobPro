# 🗓️ My Event Planner
**UTS Mobile Programming – Flutter Project**

## 👩‍💻 Identitas Mahasiswa
| Data | Keterangan |
|------|-------------|
| **Nama** | Ikvina Hidayatunnajah |
| **NIM** | STI202303738 |
| **Kelas** | C5.2 |
| **Dosen Pengampu** | NICOLAUS EUCLIDES WAHYU, S.KOM., M.CS. |
| **Tahun Ajaran** | 2025 |

---

## 📱 Deskripsi Aplikasi
**My Event Planner** adalah aplikasi Flutter yang digunakan untuk mencatat, menampilkan, dan mengelola daftar acara seperti seminar, ulang tahun, dan kegiatan kampus.  
Aplikasi ini memanfaatkan penyimpanan lokal serta integrasi media (foto & video) untuk membantu pengguna mengatur jadwal dengan lebih mudah.

---

## ⚙️ Fitur Utama
- 📋 Menampilkan daftar event dengan desain cerah dan responsif  
- ➕ Menambah event baru melalui form input (judul, deskripsi, tanggal, waktu, kategori)  
- 🗓️ Mengatur tanggal & waktu menggunakan `DatePicker` dan `TimePicker`  
- 🖼️ Mengambil foto menggunakan kamera dengan `image_picker`  
- 💾 Menyimpan data event ke file JSON lokal (`path_provider`)  
- 🎥 Menampilkan video promosi event menggunakan `video_player`  
- 🧭 Navigasi dengan `DefaultTabController` — **Daftar Event**, **Tambah Event**, dan **Media**

---

## 🧩 Struktur Folder
```
lib/
├── main.dart
├── models/
│   └── event.dart
├── services/
│   └── file_storage.dart
├── screens/
│   ├── event_list_screen.dart
│   ├── add_event_screen.dart
│   ├── event_detail_screen.dart
│   └── media_screen.dart
├── widgets/
│   └── event_card.dart
└── utils/
    └── constants.dart
```

---

## 🖼️ Tampilan Aplikasi

| Daftar Event | Form Tambah Event | Media Tab |
|:-------------:|:----------------:|:----------:|
| ![Tab 1](https://placehold.co/200x400/FFFFFF/007BFF?text=Daftar+Event) | ![Tab 2](https://placehold.co/200x400/FFFFFF/007BFF?text=Tambah+Event) | ![Tab 3](https://placehold.co/200x400/FFFFFF/007BFF?text=Media+Tab) |

> Tampilan menggunakan tema **cerah (biru muda & putih)** agar terlihat bersih dan modern.

---

## 🚀 Cara Menjalankan
1. Pastikan Flutter SDK sudah terinstal  
2. Jalankan perintah berikut di terminal:
   ```bash
   flutter pub get
   flutter run
   ```
3. Pilih emulator atau perangkat fisik  
4. Tambahkan event baru, dan lihat hasilnya langsung di tab daftar event atau media  

---

## 🧠 Pembelajaran yang Didapat
Mahasiswa mempelajari hal-hal berikut:
- Penerapan berbagai widget Flutter (`ListView`, `Column`, `Stack`, `TextField`)  
- Navigasi dengan `DefaultTabController`  
- Integrasi media (foto & video)  
- Penyimpanan lokal dengan `path_provider` dan `dart:io`  
- Desain UI yang rapi dan mudah digunakan  

---

## 🏁 Kesimpulan
Aplikasi *My Event Planner* membuktikan pemahaman konsep Flutter pada tingkat menengah: mulai dari penggunaan widget, navigasi multi-tab, penyimpanan data lokal, hingga pengelolaan media.  
Proyek ini menjadi representasi kemampuan mahasiswa dalam membangun aplikasi mobile fungsional dan interaktif.
