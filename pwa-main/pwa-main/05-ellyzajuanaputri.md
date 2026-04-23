Rangkuman Materi Mobile Computing & OS
1. Manajemen Memori dan Proses (Memory Management)
Point: Sistem operasi mobile membagi prioritas proses untuk menjaga performa dan efisiensi baterai.
Reason: Karena keterbatasan sumber daya (RAM dan baterai) pada perangkat mobile, OS harus secara agresif mengatur mana aplikasi yang aktif dan mana yang bisa dihentikan.
Example: Foreground: Aplikasi yang sedang berinteraksi langsung dengan user (tampak di layar).
Background: Aplikasi yang berjalan di balik layar (misalnya sinkronisasi data atau GPS).
Cache: Data yang disimpan sementara untuk mempercepat akses kembali.
Low Memory: Kondisi di mana OS akan mematikan proses tertentu untuk membebaskan ruang bagi sistem.
Point: Manajemen memori yang ketat sangat krusial untuk mencegah lag dan memastikan stabilitas sistem operasi mobile.

2. Komunikasi Antar Proses (Inter-Process Communication / IPC)
Point: Komunikasi data antar aplikasii dilakukan melalui mekanisme terstruktur seperti Intent dan Content Provider.
Reason: Keamanan mobile (sandboxing) mencegah satu aplikasi mengakses data aplikasi lain secara langsung tanpa izin.
Example: Intent (IPC): Digunakan untuk memicu aksi atau mengirim pesan antar komponen (misal: membuka aplikasi peta dari aplikasi pesan).
Content Provider: Digunakan untuk berbagi dataset besar antar aplikasi (misal: aplikasi WhatsApp mengakses daftar kontak dari sistem Android).
Point: IPC memungkinkan ekosistem aplikasi yang saling terhubung namun tetap aman dalam batasannya masing-masing.

3. Penjadwalan Tugas (WorkManager)
Point: Penggunaan WorkManager diperlukan untuk menangani tugas-tugas yang berjalan di latar belakang secara efisien.
Reason: WorkManager memastikan tugas tetap berjalan meskipun aplikasi ditutup atau perangkat di-restart, dengan memperhatikan kondisi baterai dan jaringan.
Example: Penjadwalan sinkronisasi GPS atau pengiriman data ke server secara berkala yang tidak harus dilakukan saat itu juga (deferred tasks).
Point: Dengan WorkManager, sistem dapat mengoptimalkan penggunaan daya perangkat tanpa mengorbankan tugas fungsional aplikasi.

4. Keamanan Data (Data Security)
Point: Keamanan data pada perangkat mobile berfokus pada enkripsi tingkat tinggi, khususnya menggunakan metode FBE (File-Based Encryption).
Reason: Melindungi data sensitif pengguna jika perangkat hilang atau dicuri, sehingga file tidak dapat dibaca tanpa kunci dekripsi yang sah.
Example: Implementasi File-Based Encryption (FBE) yang memungkinkan file yang berbeda dienkripsi dengan kunci yang berbeda pula.
Point: Standar keamanan seperti FBE dan integrasi dengan EDA (Event-Driven Architecture) memastikan data tetap aman dan sistem responsif terhadap perubahan status keamanan.
