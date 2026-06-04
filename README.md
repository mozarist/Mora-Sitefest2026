# Mora

Mora adalah platform web berbasis Character Improvement System yang dirancang untuk membantu sekolah dalam pengelolaan data siswa dan pembinaan karakter di lingkungan sekolah. Proyek ini mengangkat tema Education & Digital Literacy dengan pendekatan sistem poin untuk mendukung budaya sekolah yang lebih positif dan terstruktur.

## Tentang Mora

Mora membantu admin dan guru memantau perkembangan perilaku siswa, mencatat perolehan poin positif maupun pembinaan, serta menampilkan peringkat kelas melalui sistem leaderboard. Proyek ini berfokus pada penyediaan antarmuka yang modern, responsif, dan mudah digunakan untuk mendukung proses monitoring karakter siswa.

## Fitur Utama

- Landing Page Interaktif: tampilan landing yang menjelaskan tujuan platform, ringkasan statistik, bagian "Perolehan Poin", "Agenda Sekolah", dan "Rewards".
- Input Poin: halaman `input-poin.html` menyediakan formulir untuk memasukkan penambahan atau pengurangan poin karakter siswa.
- Leaderboard: halaman `Leaderboard.html` menampilkan peringkat kelas per angkatan, podium global, serta tabel histori perolehan/pengurangan poin dengan fitur pencarian, filter, sortir, dan paginasi yang dijalankan di browser.
- Dashboard (UI Admin/Guru): `Dashboard.html` berisi tata letak admin dengan sidebar, kartu statistik, tabel aktivitas, panel guru, dan modal

## Struktur Halaman

- `index.html` — Halaman utama/landing yang menjelaskan tujuan Mora dan menautkan ke fitur lain.
- `Dashboard.html` — Antarmuka admin/guru: statistik, tabel aktivitas, panel guru, dan modul UI untuk interaksi internal (prototipe tanpa penyimpanan server).
- `input-poin.html` — Form input poin siswa: pilihan siswa, jenis penambahan/pengurangan, preview poin, dan riwayat perubahan (semua berjalan di sisi-klien).
- `Leaderboard.html` — Menampilkan peringkat kelas, podium, dan tabel histori poin dengan kontrol filter/urut/paginasi.
- `style.css` — File stylesheet utama.
- `Assets/` — Folder berisi ilustrasi, logo, dan foto wali-kelas yang digunakan di halaman.

## Teknologi yang Digunakan

- HTML5
- CSS3 (file `style.css` dan utilitas Tailwind via CDN untuk helper)
- JavaScript (vanilla) untuk interaksi halaman, manipulasi DOM, dan fungsi UI client-side
- Library ringan via CDN: TailwindCSS (styling classes), AOS (Animate on Scroll), Boxicons/font (ikon)

Catatan: Proyek ini adalah aplikasi front-end statis. Tidak ada mekanisme autentikasi yang terhubung ke server, dan data tidak dipersisten ke backend.

## Tim Pengembang

- Hadi Fawwaz Sudewo (github.com/HadiFawwaz)
- Ahmad Azzam Mozarist (github.com/mozarist)
- Aoddi Reskeh Pechokov (github.com/oodikxeonz)

---
File README ini dibuat berdasarkan isi aktual proyek; tidak menambahkan fitur yang tidak ada dalam berkas sumber.