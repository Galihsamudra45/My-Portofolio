# 🌟 Portofolio Personal Branding & Magang (Internship Ready)

Portofolio personal branding interaktif, modern, dan responsif yang dirancang khusus untuk memikat tim HRD dan recruiter saat melamar posisi magang (*internship*) maupun *fresh graduate*.

---

## 📁 Struktur Berkas Projek

```text
Porto magang coba coba/
├── index.html                   # Berkas utama website portofolio
├── assets/
│   ├── css/
│   │   └── style.css            # Custom styling, animasi, glassmorphism, scrollbar
│   ├── js/
│   │   └── main.js              # Interaktivitas (Dark/Light mode, Filter, Modal popup, WhatsApp Form)
│   └── images/
│       ├── profile-avatar.svg   # Foto/Avatar profil utama
│       ├── projects/            # Gambar thumbnail projek (project-1 s/d project-4)
│       ├── certificates/        # Gambar sertifikat (cert-1 s/d cert-4)
│       └── gallery/             # Foto dokumentasi kegiatan (gallery-1 s/d gallery-4)
└── README.md                    # Panduan kustomisasi & petunjuk deployment
```

---

## 🚀 Cara Menjalankan Portofolio

Website ini dibuat dengan **Pure HTML5, Modern Tailwind CSS, dan JavaScript murni**. Anda **tidak perlu menginstal Node.js atau paket tambahan apa pun**:

1. Cukup buka folder ini di File Explorer Windows Anda.
2. **Klik dua kali pada file `index.html`**, atau klik kanan lalu pilih **Open with Google Chrome / Microsoft Edge**.
3. Website portofolio interaktif Anda langsung berjalan sempurna!

---

## 🎨 Bagian-Bagian Lengkap yang Tersedia

1. **Perkenalan Diri (Hero & Value Proposition)**:
   - Nama lengkap, headline profesional, status kesiapan magang (*Open to Internship*).
   - Bio ringkas yang menjual keunggulan diri.
   - Tombol Unduh CV, Hubungi Saya, dan link sosial media (LinkedIn, GitHub, Email, WhatsApp).
   - Indikator metrik ringkas: 8+ Projek Selesai, 4+ Organisasi, 10+ Sertifikat, IPK 3.85 / 4.00.

2. **Riwayat Pendidikan (Education History)**:
   - Timeline interaktif pendidikan universitas dan jenjang sebelumnya.
   - Sorotan akademik, capaian beasiswa, asisten laboratorium, dan komitmen waktu magang penuh (*Full-Time / Remote / On-site*).

3. **Minat & Skill yang Didukung Tools**:
   - **4 Pilar Minat**: *Web Development*, *UI/UX Design*, *Data Analytics*, dan *Project Delivery*.
   - **Hard Skills & Tools**: HTML5, CSS3, Tailwind, JavaScript, React, Python, Git, Figma, Canva, Excel Pivot, Tableau, Notion, Jira, dll.
   - **Karakter & Soft Skills**: *Critical Thinking*, *Team Leadership*, *Time Management*, *Communication*, dan *Fast Learner*.

4. **Pengalaman Organisasi (Organizational Leadership)**:
   - Pengalaman kepemimpinan terstruktur dengan metode STAR (Situation, Task, Action, Result).
   - Lengkap dengan metrik dampak (misal: memimpin tim 12 staf, menaikkan engagement 45%, mengelola anggaran acara nasional, dan relawan UMKM).

5. **Projek Pendukung (Project Showcase)**:
   - Filter projek berdasarkan kategori (*Semua*, *Web Application*, *UI/UX Design*, *Data & Analytics*).
   - Tombol **"Detail Kasus & Solusi"** yang memunculkan pop-up modal interaktif berisi latar belakang masalah, peran, fitur utama, dan tautan live demo / GitHub.

6. **Sertifikat Pelatihan & Lisensi**:
   - Kartu sertifikasi kredibel (Dicoding, Google Career Certificates, Binar Academy, PMI Authorized).
   - Tombol **"Lihat Detail Sertifikat"** yang menampilkan pratinjau sertifikat, ID kredensial resmi, dan kompetensi yang tervalidasi.

7. **Galeri Pengalaman & Aktivitas**:
   - Dokumentasi foto kegiatan (Ketua pelaksana seminar, workshop coding, presentasi projek akhir, dan relawan pengabdian desa).
   - Fitur **Lightbox Modal Viewer**: klik foto mana saja untuk memperbesar dan membaca cerita di balik momen tersebut.

8. **Testimoni & Rekomendasi (Social Proof)**:
   - Ulasan positif dari Dosen Pembimbing, Ketua Organisasi, dan Mentor Industri.

9. **Kontak Langsung & Form WhatsApp**:
   - Formulir pesan interaktif: Saat pengunjung mengisi nama dan pesan, mengklik tombol akan **langsung membuka WhatsApp** dengan pesan yang telah tersusun rapi!

---

## ✏️ Panduan Kustomisasi Data Pribadi

Anda dapat membuka file `index.html` dan `assets/js/main.js` di teks editor (seperti Visual Studio Code atau Notepad):

### 1. Mengganti Nama & Headline
- Buka `index.html`.
- Cari kata `Galih Pratama` lalu ganti dengan nama lengkap Anda.
- Cari kata `Aspiring Software Engineer & Digital Solutions Specialist` dan sesuaikan dengan bidang yang Anda tuju (misal: *Frontend Developer Intern*, *UI/UX Designer Intern*, atau *Data Analyst Intern*).

### 2. Mengganti Foto Profil
- Masukkan foto formal Anda (format JPG/PNG/SVG) ke dalam folder `assets/images/`. Misal: `assets/images/foto-saya.jpg`.
- Pada `index.html`, cari baris:
  ```html
  <img src="assets/images/profile-avatar.svg" alt="Galih Pratama" ...>
  ```
- Ubah menjadi:
  ```html
  <img src="assets/images/foto-saya.jpg" alt="Nama Anda" ...>
  ```

### 3. Mengganti Nomor WhatsApp & Email
- Di `index.html`, cari nomor `+62 812-3456-7890` dan email `galih.pratama@example.com`, ganti dengan kontak aktif Anda.
- Di `assets/js/main.js`, cari baris:
  ```javascript
  const whatsappPhone = '6281234567890';
  ```
  Ganti dengan nomor WhatsApp Anda diawali kode negara tanpa tanda plus (misal: `628xxxxxxxxxx`).

### 4. Menghubungkan File CV / Resume (PDF)
- Simpan file CV Anda di dalam folder projek, misalnya `CV_NamaLengkap.pdf`.
- Di `index.html`, cari tombol unduh CV:
  ```html
  <a href="#kontak" onclick="showToast('Mengunduh CV...', 'info')" ...>
  ```
  Ubah `href` menjadi:
  ```html
  <a href="CV_NamaLengkap.pdf" download="CV_NamaLengkap.pdf" ...>
  ```

---

## 🌐 Cara Mengunggah (Deploy) ke Internet Secara Gratis

Agar portofolio ini memiliki link online (misal: `https://namakamu.github.io` atau `https://namakamu.vercel.app`) yang siap ditaruh di CV dan LinkedIn:

### Opsi 1: GitHub Pages (Paling Populer & Gratis Selamanya)
1. Buat akun di [GitHub.com](https://github.com).
2. Buat repository baru dengan nama `portofolio` (set ke *Public*).
3. Upload seluruh isi folder ini (`index.html`, folder `assets/`, dll.) ke repository tersebut.
4. Buka menu **Settings** > **Pages** di repository Anda.
5. Pada bagian **Branch**, pilih `main` dan folder `/ (root)`, lalu klik **Save**.
6. Dalam 1-2 menit, link portofolio Anda langsung aktif online!

### Opsi 2: Vercel / Netlify (Drag & Drop)
1. Buka [app.netlify.com/drop](https://app.netlify.com/drop) atau [vercel.com](https://vercel.com).
2. Cukup tarik (*drag & drop*) seluruh folder `Porto magang coba coba` ini ke halaman browser mereka.
3. Website Anda langsung tayang dalam hitungan detik dengan domain gratis berkecepatan tinggi!

---

Semoga portofolio ini sukses mendukung proses *branding* dan mengantarkan Anda meraih kesempatan magang terbaik! 🚀

