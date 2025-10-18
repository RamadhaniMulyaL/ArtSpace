# 🎨 ArtSpace App

## 📌 Deskripsi Proyek

Proyek ini adalah pengembangan aplikasi **Galeri Seni Interaktif** yang dinamakan **ArtSpace**, dibangun menggunakan Android dengan **Jetpack Compose**. Aplikasi ini dirancang untuk menampilkan berbagai karya seni digital, khususnya lukisan burung-burung eksotis, dengan antarmuka yang bersih dan fokus pada tema alami (hijau).

Tujuan utama dari proyek ini adalah untuk melatih kemampuan dalam:
1.  Membangun antarmuka pengguna yang responsif (mendukung Portrait dan Landscape).
2.  Menerapkan navigasi stateful (maju dan mundur) menggunakan `remember` dan `mutableStateOf`.
3.  Menggunakan komponen Material 3 (Card, Button, Surface) dan animasi transisi (`AnimatedContent`).
4.  Mengimplementasikan skema warna yang kohesif (saat ini bertema hijau).

---

## ✨ Fitur Utama

* 🖼️ **Penampil Karya Seni:** Menampilkan gambar karya seni dalam bingkai kartu yang elegan.
* 📜 **Detail Karya:** Menampilkan judul, nama artis, dan tahun pembuatan di bagian deskripsi.
* ↔️ **Navigasi Interaktif:** Tombol "Previous" dan "Next" untuk beralih antara karya seni.
* 🔄 **Animasi Transisi:** Pengalaman pengguna yang mulus dengan animasi geser dan *fade* saat berpindah gambar.
* 📱 **Desain Responsif:** Layout otomatis beradaptasi antara mode **Portrait** (vertikal) dan **Landscape** (horizontal).
* 🟢 **Skema Warna Hijau:** Menggunakan palet hijau yang tenang (`Medium Sea Green` dan `Honeydew`) untuk nuansa alami dan menenangkan.

---

## 🖼️ Tampilan Aplikasi

Berikut adalah contoh tampilan aplikasi (mode Portrait):

<img width="356" height="804" alt="image" src="https://github.com/user-attachments/assets/2eee49c4-8895-4142-854e-dd6b789b15a5" /> 
<img width="362" height="804" alt="image" src="https://github.com/user-attachments/assets/99a55d85-27a4-4564-afe5-58141cf4482e" /> 
<img width="362" height="805" alt="image" src="https://github.com/user-attachments/assets/1345be69-e137-4508-abcf-637c5669dcd5" />
<img width="357" height="804" alt="image" src="https://github.com/user-attachments/assets/ef59f479-c03b-41fe-b664-38bc1dbd5e2a" />
<img width="357" height="805" alt="image" src="https://github.com/user-attachments/assets/9618f067-3b59-4b9c-b4b7-ef75e2bde72c" />

---

## ▶️ Cara Menjalankan

1.  Buka proyek ini di **Android Studio** (disarankan versi terbaru).
2.  Pastikan semua *resource* gambar (`gambar_1`, `gambar_2`, dst.) sudah dimasukkan ke dalam direktori `app/src/main/res/drawable/`.
3.  Pastikan Anda telah mengaktifkan eksperimental API untuk animasi di kode: `@OptIn(ExperimentalAnimationApi::class)`.
4.  Jalankan aplikasi di emulator atau perangkat fisik Android (target SDK 24+).

---

## 👤 Author

**Nama:** Ramadhani Mulya Liestiant
**NIM:** 243307110
**Kelas:** 3D

---

Terima kasih telah melihat proyek galeri digital ArtSpace ini! Feedback dan pengembangan lebih lanjut sangat disambut baik. 🎉
