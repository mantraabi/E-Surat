# ✉️ E-Surat - Aplikasi Manajemen Arsip Surat

**E-Surat** adalah aplikasi desktop modern berbasis Electron untuk pengelolaan surat masuk, surat keluar, dan pengarsipan digital. Dirancang untuk instansi atau perkantoran yang membutuhkan manajemen surat yang cepat, *offline-first*, namun tetap memiliki kemampuan sinkronisasi cloud.

## ✨ Fitur Unggulan

### 📝 Manajemen Surat
- **Surat Masuk & Keluar:** Pencatatan detail nomor, tanggal, perihal, pengirim/penerima.
- **Status Tracking:** Pantau status surat (Aktif, Dibalas, Selesai).
- **Lampiran File:** Simpan file surat langsung di aplikasi.
- **Referensi Silang:** Tautkan surat balasan (keluar) dengan surat masuk terkait.

### 🗂️ Klasifikasi Arsip
- **Standar Kode Klasifikasi:** Manajemen kode klasifikasi arsip berjenjang.
- **Import/Export JSON:** Mudah memindahkan struktur klasifikasi antar komputer.

### 🔒 Keamanan & User
- **Multi-Role User:** Administrator, Petugas Surat Masuk, Petugas Surat Keluar.
- **Offline Auth:** Login tanpa internet.
- **Database Lokal:** Data tersimpan aman di komputer (SQLite).

### ☁️ Sinkronisasi & Backup
- **Cloud Sync:** Sinkronisasi data opsional ke **Supabase** untuk backup realtime.
- **Backup/Restore:** Backup database (`.db`) lokal dengan satu klik.
- **Auto Update:** Aplikasi melakukan update otomatis saat versi baru tersedia.

### 🎨 UI/UX Modern
- **Dark Mode Support:** Nyaman di mata dengan mode gelap otomatis/manual.
- **Responsive Design:** Tampilan rapi dan mudah digunakan.

---

## 🛠️ Teknologi yang Digunakan

Aplikasi ini dibangun menggunakan teknologi web modern yang dibungkus menjadi aplikasi desktop native:

*   **Core:** [Electron](https://www.electronjs.org/)
*   **Frontend:** [Vue 3](https://vuejs.org/) + [TypeScript](https://www.typescriptlang.org/)
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/)
*   **State Management:** [Pinia](https://pinia.vuejs.org/)
*   **Database:** [Better-SQLite3](https://github.com/WiseLibs/better-sqlite3)
*   **Icons:** [Phosphor Icons](https://phosphoricons.com/)
*   **Build Tool:** [Vite](https://vitejs.dev/) & [Electron-Builder](https://www.electron.build/)

---

## 📥 Download & Instalasi

Untuk pengguna Windows, silakan unduh installer versi terbaru di menu **Releases**:

👉 **[Download E-Surat Terbaru](https://github.com/mantraabi/E-Surat/releases/latest)**

1.  Download file `.exe`.
2.  Jalankan installer.
3.  Aplikasi siap digunakan!

---

## 📸 Screenshots

| Dashboard | Surat Masuk |
|:---:|:---:|
| ![Dashboard](https://placehold.co/600x400/EEE/31343C?text=Dashboard+Preview) | ![Surat Masuk](https://placehold.co/600x400/EEE/31343C?text=Surat+Masuk+Preview) |

| Surat Keluar | Arsip Surat |
|:---:|:---:|
| ![Dark Mode](https://placehold.co/600x400/1e293b/FFF?text=Dark+Mode+Preview) | ![Pengaturan](https://placehold.co/600x400/EEE/31343C?text=Pengaturan+Preview) |

---
