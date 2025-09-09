# NTP Time Information Indonesia

<div align="center">

![NTP Logo](https://img.shields.io/badge/NTP-Time%20Sync-blue?style=for-the-badge&logo=clock&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

## Deskripsi

Aplikasi web sederhana yang menampilkan informasi waktu real-time dengan menggunakan Network Time Protocol (NTP). Proyek ini dibuat menggunakan teknologi web fundamental (HTML, CSS, dan JavaScript) untuk memberikan informasi satuan waktu yang akurat dari server NTP tertentu.

##  Fitur Utama

- **Sinkronisasi Waktu Real-time** - Menampilkan waktu yang disinkronkan dengan server NTP
- **Interface Responsif** - Desain yang dapat menyesuaikan berbagai ukuran layar
- **Informasi Detail** - Menampilkan berbagai format waktu dan informasi terkait
- **Ringan & Cepat** - Dibuat dengan teknologi web murni tanpa framework tambahan

##  Teknologi yang Digunakan

| Teknologi | Fungsi |
|-----------|--------|
| **(https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)** | Struktur dan markup aplikasi |
| **(https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)** | Styling dan layout responsif |
| **(https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)** | Logika aplikasi dan komunikasi NTP |

##  Cara Menjalankan

### Prasyarat
- Web browser modern (Chrome, Firefox, Safari, Edge)
- Koneksi internet untuk akses NTP server

### Langkah Instalasi

1. **Clone repository ini**
   ```bash
   git clone https://github.com/raihanrama/NTP.git
   cd NTP
   ```

2. **Buka file HTML**
   - Buka file `index.html` di web browser Anda
   - Atau gunakan live server untuk development

3. **Akses aplikasi**
   ```
   http://localhost:3000
   ```
   *atau sesuai dengan port yang Anda gunakan*

## Struktur Proyek

```
NTP/
├── index.html          # File HTML utama
├── Style.css          # Stylesheet aplikasi
├── images/            # Folder untuk aset gambar
└── README.md          # Dokumentasi proyek
```

## Konfigurasi

Aplikasi ini menggunakan server NTP default untuk sinkronisasi waktu. Untuk mengubah server NTP:

1. Buka file JavaScript utama
2. Temukan konfigurasi NTP server
3. Ganti dengan server NTP pilihan Anda

```javascript
// Contoh konfigurasi
const ntpServer = 'time.google.com';
const ntpPort = 123;
```

## Fitur yang Ditampilkan

- **Waktu Lokal** - Waktu berdasarkan timezone browser
- **Waktu UTC** - Waktu universal terkoordinasi
- **Timestamp Unix** - Format timestamp dalam detik
- **Format Kustom** - Berbagai format tampilan waktu
- **Status Sinkronisasi** - Indikator koneksi dengan NTP server

## Kontribusi

Kontribusi sangat diterima! Untuk berkontribusi:

1. Fork repositori ini
2. Buat branch fitur baru (`git checkout -b fitur/AmazingFeature`)
3. Commit perubahan Anda (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin fitur/AmazingFeature`)
5. Buat Pull Request

## 📋 TODO List

- [ ] Menambahkan pilihan multiple NTP server
- [ ] Implementasi dark/light theme
- [ ] Menambahkan timezone converter
- [ ] Integrasi dengan API timezone
- [ ] Menambahkan notifikasi untuk perubahan waktu

## Laporan Bug

Jika Anda menemukan bug atau memiliki saran, silakan buat [issue baru](https://github.com/raihanrama/NTP/issues/new).

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE) - lihat file LICENSE untuk detail lebih lanjut.

## Pengembang

**Raihan Rama**
- GitHub: [@raihanrama](https://github.com/raihanrama)

---

<div align="center">

**Dibuat dengan** ❤️ **menggunakan HTML, CSS & JavaScript**

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=raihanrama.NTP)

</div>
