Berdasarkan catatan pada papan tulis tersebut, berikut adalah rangkuman komprehensif mengenai *Mobile Computing & Operating Systems (Lanjutan) dengan menggunakan pola PREP (Point, Reason, Example, Point)*.

---

## Rangkuman Mobile Computing & OS

 *1. Point (Titik Utama)*
Materi ini berfokus pada manajemen sumber daya dan mekanisme komunikasi internal pada sistem operasi mobile (khususnya Android) untuk menjaga performa, efisiensi baterai, dan keamanan data. Fokus utamanya adalah bagaimana OS mengelola proses di memori dan bagaimana antar aplikasi saling bertukar informasi.

*2. Reason (Alasan/Penjelasan)*
Sistem operasi mobile harus sangat ketat dalam mengelola memori karena keterbatasan hardware dibandingkan perangkat desktop. Oleh karena itu, OS membagi prioritas proses menjadi beberapa kategori agar aplikasi yang sedang digunakan pengguna tidak terganggu (lag/crash).

* *Manajemen Memori & Proses:*
    *Foreground:* Proses yang sedang aktif dilihat dan berinteraksi langsung dengan pengguna. Memiliki prioritas tertinggi.
    *Background:* Proses yang berjalan di belakang layar (seperti sinkronisasi atau musik).
     *Cache:* Proses yang disimpan sementara di memori untuk mempercepat pembukaan kembali aplikasi, namun akan dihapus pertama kali jika sistem kehabisan memori (**Low Memory Killer**).
* *Komunikasi & Data:*
    *Intent (IPC - Inter-Process Communication):* Mekanisme untuk berkirim pesan antar komponen aplikasi atau antar aplikasi berbeda.
    *Content Provider:* Komponen yang mengelola akses ke kumpulan data terpusat (seperti kontak atau galeri) sehingga bisa digunakan oleh aplikasi lain secara aman.
* *WorkManager:* Digunakan untuk menjadwalkan tugas di latar belakang yang harus tetap berjalan meskipun aplikasi ditutup atau perangkat dimulai ulang (seperti upload backup).
* *Keamanan Data:* Menggunakan metode **FBE (File-Based Encryption)** yang memungkinkan file berbeda dienkripsi dengan kunci yang berbeda, meningkatkan keamanan dibandingkan enkripsi seluruh disk.


---

 *3. Example (Contoh)*
Berikut adalah penerapan nyata dari poin-poin di atas:

* *Intent: Saat Anda menekan tombol "Share" di galeri foto, sistem mengirimkan Intent* ke aplikasi WhatsApp atau Instagram untuk menerima foto tersebut.
* *Content Provider:* Aplikasi WhatsApp meminta izin untuk mengakses daftar kontak Anda; daftar kontak tersebut disediakan melalui *Content Provider* milik sistem kontak telepon.
* *WorkManager:* Aplikasi Google Photos yang menjadwalkan pencadangan (backup) foto hanya saat ponsel sedang di-charge dan terhubung ke Wi-Fi.
* *FBE:* Saat ponsel baru dinyalakan dan masih di posisi *lock screen*, alarm atau telepon tetap bisa berdering karena file sistemnya sudah terdekripsi secara spesifik, sementara data pribadi lainnya masih terkunci rapat.

---

*4. Point (Kesimpulan)*
Secara garis besar, pemahaman tentang *WMT (Wireless Mobile Technology)* dalam konteks OS ini sangat krusial untuk memastikan aplikasi berjalan efisien. Dengan memahami hirarki memori (Foreground vs Background), mekanisme komunikasi (Intent & Content Provider), serta enkripsi data (FBE), pengembang dapat membuat aplikasi yang responsif namun tetap hemat baterai dan aman.

---

*Struktur Tambahan dari Gambar:*
* *Low Memory:* Strategi OS untuk mematikan proses cache guna memberikan ruang bagi proses foreground.
* *EDA:* Terlihat singkatan EDA (kemungkinan *Event-Driven Architecture*) yang berkaitan dengan bagaimana sistem merespon input atau perubahan status secara real-time.
