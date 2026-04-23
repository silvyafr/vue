Rangkuman Teknologi Mobile Web & Aplikasi
1. Akses Hardware (Hardware Access)
* **Point:** Aplikasi **Native** memiliki akses paling dalam dan stabil terhadap fitur perangkat keras dibandingkan Hybrid atau PWA.
* **Reason:** Aplikasi Native dibangun menggunakan bahasa pemrograman spesifik OS yang memberikan izin langsung ke API sistem, sementara Hybrid memerlukan jembatan (plugin) dan PWA terbatas pada API browser.
* **Example:** Aplikasi Native dapat mengakses **Camera, GPS, dan NFC** secara instan dan responsif. Hybrid memerlukan **Plugin**, sedangkan PWA bergantung pada **Web Browser API**.
* **Point:** Untuk performa fitur perangkat keras yang kompleks, teknologi Native tetap menjadi pilihan unggulan.

 2. Performa dan Biaya (Performance & Cost)
* **Point:** Terdapat hubungan berbanding terbalik antara kualitas performa dengan efisiensi biaya pengembangan.
* **Reason:** Performa tinggi membutuhkan optimasi spesifik platform (Native), yang berarti membutuhkan tim berbeda untuk iOS dan Android, sehingga biaya (*cost*) menjadi sangat tinggi.
* **Example:** * **Native:** Performa paling tinggi (*High*), namun biaya juga paling tinggi.
    * **Hybrid:** Performa menengah (*Medium*), biaya pengembangan lebih murah karena satu basis kode untuk dua platform.
    * **PWA:** Performa cukup baik (berbasis web), namun biaya paling rendah (*Low*) karena hanya perlu membangun satu situs web.
* **Point:** Pemilihan teknologi harus didasarkan pada keseimbangan antara anggaran perusahaan dan kebutuhan kecepatan aplikasi.


3. Jalur Distribusi (Distribution)
* **Point:** Kemudahan pengguna menemukan aplikasi bergantung pada platform distribusi yang digunakan.
* **Reason:** Aplikasi Native dan Hybrid harus melewati proses moderasi toko aplikasi yang ketat, sedangkan PWA bersifat terbuka dan langsung.
* **Example:** Aplikasi Native/Hybrid didistribusikan melalui **Play Store (PS), App Store (AS), atau Microsoft Store (MS)**. Sebaliknya, PWA didistribusikan cukup melalui **URL/Link** yang bisa diakses langsung lewat browser.
* **Point:** PWA menawarkan aksesibilitas tercepat tanpa hambatan instalasi dari toko aplikasi.

4. Kesesuaian Penggunaan (Use Case)
* **Point:** Setiap teknologi memiliki "spesialisasi" tersendiri berdasarkan jenis konten aplikasi yang dibuat.
* **Reason:** Karakteristik teknis masing-masing platform membuatnya lebih cocok untuk tugas-tugas tertentu.
* **Example:** * **Native:** Pilihan tepat untuk **AR/VR dan Game** yang haus daya komputasi.
    * **Hybrid:** Ideal untuk **Aplikasi Bisnis, ERP, atau POS** yang membutuhkan fungsionalitas lintas platform dengan cepat.
    * **PWA:** Sangat efektif untuk **Web Apps, CMS, dan POS** berbasis cloud yang mengutamakan kemudahan akses di berbagai perangkat.
* **Point:** Memilih teknologi yang tepat di awal pengembangan sangat menentukan keberhasilan produk di pasar sasaran.

---

Tabel Perbandingan (Ringkasan Visual)

| Aspek | Native | Hybrid | PWA |
| :--- | :--- | :--- | :--- |
| **Akses Hardware** | Langsung (Cam, GPS, NFC) | Lewat Plugin | Browser API |
| **Performa** | Tinggi (Height) | Menengah (Medium) | Menengah/Tinggi (Web) |
| **Biaya (Cost)** | Tinggi | Menengah | Rendah |
| **Distribusi** | App Store (PS, AS, MS) | App Store | URL / Link |
| **Pilihan Tepat** | Game, AR/VR | Aplikasi Bisnis, ERP | CMS, POS, Web Apps |
