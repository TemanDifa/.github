# Selamat Datang di TemanDifa\! 👋

Kami berfokus pada pengembangan teknologi inklusif berbasis AI untuk memberdayakan dan membantu teman-teman disabilitas dalam aktivitas sehari-hari. Misi kami adalah menciptakan solusi yang tidak hanya fungsional, tetapi juga andal, mudah diakses, dan memberikan dampak positif bagi kehidupan pengguna.

-----

## ✨ Tentang Proyek TemanDifa

**TemanDifa** adalah sebuah aplikasi seluler cerdas yang dirancang sebagai asisten digital bagi penyandang disabilitas, khususnya tunanetra. Dengan memanfaatkan kekuatan *Artificial Intelligence* (AI), aplikasi ini menyediakan serangkaian alat bantu canggih untuk meningkatkan kemandirian dan keamanan pengguna.

Proyek ini terdiri dari dua komponen utama: aplikasi *frontend* yang berjalan di perangkat pengguna dan serangkaian layanan *backend* yang mengelola logika bisnis serta pemrosesan AI.

### Fitur Utama

  - **👁️ Deteksi Objek Real-time**: Menggunakan kamera untuk mengidentifikasi objek di sekitar dan memberikan umpan balik suara secara langsung.
  - **📄 Pemindai Teks (OCR)**: Mengubah teks dari dokumen atau gambar menjadi suara, memungkinkan pengguna untuk "membaca" konten cetak.
  - **🗣️ Transkripsi Suara**: Merekam suara dan mengubahnya menjadi teks untuk pencatatan cepat atau komunikasi.
  - **📞 Panggilan Video Darurat**: Menghubungkan pengguna dengan kontak darurat secara cepat dan andal melalui panggilan video *real-time* yang didukung oleh Agora.

-----

## 📂 Repositori Kami

Proyek ini terbagi menjadi dua repositori utama:

1.  ### [Temandifa-Frontend](https://github.com/TemanDifa/TemanDifa-Frontend)

    Aplikasi seluler yang dibangun dengan **React Native** dan **Expo**. Repositori ini berisi semua kode yang berkaitan dengan antarmuka pengguna (UI), pengalaman pengguna (UX), dan logika sisi klien.

2.  ### [TemanDifa-Backend](https://github.com/TemanDifa/TemanDifa-Backend)

    Sistem *backend* dengan arsitektur *microservices* yang dikelola oleh **Docker**. Repositori ini berisi API Gateway, layanan-layanan AI, serta konfigurasi infrastruktur.

-----

## 🏗️ Arsitektur Keseluruhan

TemanDifa dibangun di atas arsitektur modern yang terdistribusi untuk memastikan skalabilitas, keandalan, dan kemudahan pemeliharaan.

**Alur Kerja Singkat:**

1.  **Aplikasi Klien** berinteraksi dengan **API Gateway** sebagai satu-satunya titik masuk.
2.  **API Gateway** mengarahkan permintaan ke layanan yang sesuai: mengelola data di **MongoDB**, menangani sesi panggilan di **Redis**, atau meneruskan tugas AI ke **Microservices Python**.
3.  Untuk panggilan video, **Agora** menangani streaming media secara langsung antar pengguna, sementara **Firebase/GCM** mengirimkan notifikasi panggilan masuk.

-----

## 🛠️ Tumpukan Teknologi

Berikut adalah teknologi utama yang kami gunakan di seluruh ekosistem TemanDifa:

| Kategori | Teknologi |
| --- | --- |
| **Frontend** | `React Native`, `Expo`, `TypeScript`, `React Navigation`, `Zustand` |
| **Backend** | `Node.js`, `Express.js`, `Python`, `Flask`, `Socket.IO` |
| **AI / Machine Learning** | `YOLOv8`, `OpenAI Whisper`, `Tesseract OCR` |
| **Database & Cache** | `MongoDB`, `Redis` |
| **Panggilan Video** | `Agora SDK` |
| **DevOps & Infrastruktur** | `Docker`, `Docker Compose`, `GitHub Actions`, `Prometheus`, `Grafana` |
| **Pemantauan** | `Sentry` |

-----

## 👨‍💻 Tim Pengembang

  - UI/UX Designer - <a href="https://github.com/iamTsani" title="Github Muhamad Ishlakhudin Tsani" target="_blank">Muhamad Ishlakhudin Tsani</a>
  - Machine Learning Engineer - <a href="https://github.com/UmiHidayah12" title="GitHub Umi Inayatul Hidayah" target="_blank">Umi Inayatul Hidayah</a>
  - Front End Developer - <a href="https://github.com/analativach" title="Github Ana Lativach" target="_blank">Ana Lativach</a>
  - Back End Developer - <a href="https://github.com/muftiardani" title="Github Muhammad Mufti Ardani" target="_blank">Muhammad Mufti Ardani</a>

-----

## 📄 Lisensi

Proyek ini dilisensikan di bawah **Lisensi MIT**.
