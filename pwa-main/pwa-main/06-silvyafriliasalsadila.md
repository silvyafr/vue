Berdasarkan foto papan tulis yang Anda unggah mengenai **Teknologi Mobile Web & Aplikasi**, berikut adalah rangkuman komprehensif menggunakan pola **PREP** (**Point**, **Reason**, **Example**, **Point**).

---

## Perbandingan Teknologi Pengembangan Aplikasi Mobile

### **1. Point (Titik Utama)**
Terdapat tiga pendekatan utama dalam membangun aplikasi mobile: **Native**, **Hybrid**, dan **PWA (Progressive Web Apps)**. Masing-masing memiliki karakteristik yang berbeda dalam hal akses perangkat keras, performa, biaya, dan metode distribusi.

### **2. Reason (Alasan/Penjelasan)**
Perbedaan ini terjadi karena cara aplikasi berinteraksi dengan sistem operasi (OS) dan perangkat keras ponsel tidaklah sama:

* **Akses Hardware:** * **Native** memiliki akses langsung ke sensor (Cam, GPS, NFC). 
    * **Hybrid** menggunakan *Plugin* untuk menjembatani kode web ke hardware.
    * **PWA** sangat bergantung pada kemampuan *Web Browser API*.
* **Performa & Biaya:**
    * **Native** menawarkan performa tertinggi (*High*) namun dengan biaya pengembangan paling mahal (3x lipat) karena harus dibuat spesifik per platform (iOS/Android).
    * **Hybrid** berada di tengah-tengah (*Medium* performa dan 2x biaya).
    * **PWA** memiliki biaya paling rendah (1x) karena berbasis web, namun performanya terbatas pada kemampuan browser.
* **Distribusi:**
    * **Native/Hybrid** harus melalui toko aplikasi (Play Store, App Store).
    * **PWA** cukup diakses melalui URL/Link.


### **3. Example (Contoh Penggunaan yang Tepat)**
Berdasarkan catatan "Pemilihan Tepat" di papan tulis:

* **Native:** Sangat cocok untuk aplikasi yang membutuhkan grafis berat dan latensi rendah seperti **AR (Augmented Reality), VR (Virtual Reality), dan Games**.
* **Hybrid:** Pilihan ideal untuk **Aplikasi Bisnis, ERP, atau POS (Point of Sale)** yang membutuhkan fungsionalitas lintas platform dengan anggaran menengah.
* **PWA:** Paling efektif untuk **Web Apps, LMS (Learning Management System), CMS**, atau layanan informasi yang ingin mudah diakses tanpa harus menginstal aplikasi dari store.

### **4. Point (Kesimpulan)**
Tidak ada teknologi yang "terbaik" secara mutlak; pemilihan antara Native, Hybrid, atau PWA harus didasarkan pada **kebutuhan spesifik proyek**. Jika Anda mengutamakan pengalaman pengguna dan performa maksimal untuk game, pilihlah **Native**. Namun, jika Anda membutuhkan jangkauan luas dengan biaya efisien untuk aplikasi konten, **PWA** adalah solusinya.

---
**Data Tabel Singkat (Rangkuman Gambar):**

| Aspek | Native | Hybrid | PWA |
| :--- | :--- | :--- | :--- |
| **Akses Hardware** | Langsung (Cam, GPS, NFC) | Lewat Plugin/Framework | Web Browser API |
| **Performa** | Tinggi (High) | Menengah (Medium) | Menengah (High-WB) |
| **Biaya** | Tinggi (3x) | Menengah (2x) | Rendah (1x) |
| **Distribusi** | Play Store, App Store | Play Store, App Store | URL / Link |

Apakah ada bagian dari tabel tersebut yang ingin Anda gali lebih dalam, misalnya mengenai plugin khusus pada Hybrid?
