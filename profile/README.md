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

<img src="https://github.com/TemanDifa/.github/blob/main/profile/arsitektur-temandifa.png" alt="Arsitektur TemanDifa"  />

**Alur Kerja Singkat:**

1.  **Aplikasi Klien** berinteraksi dengan **API Gateway** sebagai satu-satunya titik masuk.
2.  **API Gateway** mengarahkan permintaan ke layanan yang sesuai: mengelola data di **MongoDB**, menangani sesi panggilan di **Redis**, atau meneruskan tugas AI ke **Microservices Python**.
3.  Untuk panggilan video, **Agora** menangani streaming media secara langsung antar pengguna, sementara **Firebase/GCM** mengirimkan notifikasi panggilan masuk.

-----

## 🛠️ Tumpukan Teknologi

Berikut adalah teknologi utama yang kami gunakan di seluruh ekosistem TemanDifa:

| Kategori | Teknologi |
| --- | --- |
| **Frontend** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="40" alt="express logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" height="40" alt="flask logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/socketio/socketio-original.svg" height="40" alt="socketio logo"  /> |
| **Backend** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original-wordmark.svg" height="40" alt="nodejs logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="40" alt="express logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" height="40" alt="flask logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/socketio/socketio-original.svg" height="40" alt="socketio logo"  /> |
| **AI / Machine Learning** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" height="40" alt="grafana logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" height="40" alt="grafana logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" height="40" alt="grafana logo"  /> |
| **Database & Cache** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original-wordmark.svg" height="40" alt="mongodb logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" height="40" alt="redis logo"  /> |
| **Panggilan Video** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" height="40" alt="grafana logo"  /> |
| **DevOps & Infrastruktur** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" alt="docker logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="github logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prometheus/prometheus-original.svg" height="40" alt="prometheus logo"  /> <img width="12" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" height="40" alt="grafana logo"  /> |
| **Pemantauan** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" height="40" alt="grafana logo"  /> |

-----

## 👨‍💻 Tim Pengembang

  - UI/UX Designer - <a href="https://github.com/iamTsani" title="Github Muhamad Ishlakhudin Tsani" target="_blank">Muhamad Ishlakhudin Tsani</a>
  - Machine Learning Engineer - <a href="https://github.com/UmiHidayah12" title="GitHub Umi Inayatul Hidayah" target="_blank">Umi Inayatul Hidayah</a>
  - Front End Developer - <a href="https://github.com/analativach" title="Github Ana Lativach" target="_blank">Ana Lativach</a>
  - Back End Developer - <a href="https://github.com/muftiardani" title="Github Muhammad Mufti Ardani" target="_blank">Muhammad Mufti Ardani</a>

-----

## 📄 Lisensi

Proyek ini dilisensikan di bawah **Lisensi MIT**.
