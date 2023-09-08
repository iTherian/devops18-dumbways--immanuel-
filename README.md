# devops18-dumbways--immanuel-
# Week 1
## Day 1
### 1. Definisi DevOps

Devops adalah kemampuan organisasi untuk membuat aplikasi dan layanan bergerak lebih efisien

### 2. Sebutkan lifecycle DevOps (Continuous ...) dan Jelaskan definisi-definisinya!
1. Pengembanagn:
   Perencanaan: Merencanakan fitur atau perubahan yang akan diterapkan dalam perangkat lunak.
   Kode: Menulis kode perangkat lunak dengan mempertimbangkan prinsip-prinsip pengembangan terbaik
   Pengujian unit: Memastikan bahwa bagian-bagian kecil dari kode berfungsi dengan baik
2. Pengujian
   Integrasi: Kode yang ditulis diintegrasikan ke dalam sistem utuh untuk memeriksa apakah berbagai komponen bekerja bersama dengan baik.
   Pengujian Fungsional: Pengujian fungsional dilakukan untuk emmeriksa apakah perangkat lunak berperilkau sesuai dengan spesifikasi.
   Pengujian kinerja: Dilakukan untuk memeriksa bagaimana perangkat lunak berfungsi dibawah beban kerja tertenu
   Pengujian Keamanan: Perangkat lunak diuji untuk mengidentifikasi dan memperbaiki potensi keretanannya.
3. Pengiriman
   Penggabungan Kode: Kode yang telah diuji dan disetujui digabungkan ke dalam cabang utama.
   Pengiriman Otomatis: Proses pengiriman otomatis memungkinkan perangkat lunak untuk diatur, dikemas, dan diterapkan ke lingkungan produksi secara otomatis.
   Penyediaan Lingkugnan: Lingkungan yang dibutuhkan untuk pengujian dan produksi disiapkan otomatis.
4. Operasi
   Pemantauan: Lingkungan produksi dipantau secara terus-menerus untuk mendeteksi masalah atau anomali
   Manajemen Log: Data log dari perangkat lunak dikumpulkan dan dianalisis untuk pemecahan masalah dan perbaikan.
   Pemantauan kinerja: Kinerja perangkat lunak dievaluasi secara terus-menerus untuk memastikan respon yang cepat.
5. Pemeliharaan:
   Pengelolaan konfigurasi:Manajemen konfigurasi dilakukan untuk memastikan konsistensi dan keandalan lingkungan produksi.
   Pembaruan Perangkat Lunak: Perangkat lunak diperberaui secara berkala untuk menghilangkan bug dan menambah fitur.
   Pemecahan Masalah: Tim operasi dan pengambangan bekerja sama untuk mengidentifikasi dan memecahkan masalah yang muncul.
6. Feedback
   Pengumpulan data pengguna: Data dari pengguna digunakan untuk megevaluasi penggunaan pernagkat lunak dan memahami kebutuhan mereka.
   Evaluasi Kinerja: Kinerja siklus hidup Devops dievaluasi secara berkala.

   ## Day 2
   ### 1. Perbedaan antara IP Private & Public, serta IP Dynamic & Static!
   IP Private :
   - IP private adalah alamat IP yang digunakan dalam jaringan lokal (LAN) pribadi.
   - IP private digunakan untuk mengidentifikasi dan mengarahkan perangkat di dalam jaringan lokal, tetapi tidak dapat diakses langsung dari internet.

   IP Public:
   - IP public adalah alamat IP yang dapat diakses secara langsung dari internet.
   - Setiap perangkat yang terhubung ke internet memiliki IP public yang unik.
   - IP public digunakan untuk mengidentifikasi perangkat di seluruh internet dan memungkinkan komunikasi antarperangkat di seluruh dunia.

   IP Dynamic
   - IP dynamic adalah alamat IP yang diberikan secara dinamis kepada perangkat oleh server DHCP (Dynamic Host Configuration Protocol) di jaringan.
   - Setiap kali perangkat terhubung ke jaringan, server DHCP akan menetapkan alamat IP yang tersedia secara dinamis kepada perangkat tersebut.
   - IP dynamic sering digunakan dalam jaringan rumahan dan bisnis kecil karena mereka lebih mudah dikelola.

   IP Static
   - IP static adalah alamat IP yang diberikan secara tetap kepada perangkat dan tidak berubah seiring waktu.
   - IP statis sering digunakan dalam bisnis besar, server, dan perangkat jaringan kritis yang memerlukan stabilitas alamat IP yang konsisten.

   ### 2. Buat rancangan sebuah jaringan dengan spesifikasi sebagai berikut!
      - CIDR Block : 192.168.1.xxx/24
      - Subnet : 255.255.255.0
      - Gateway : 192.168.1.1
