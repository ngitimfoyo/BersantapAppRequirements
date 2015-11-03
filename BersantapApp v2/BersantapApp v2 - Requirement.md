# BersantapApp version 2
#### see [Web prototype.jpg] for reference
#
Website ini menyediakan informasi beberapa tempat berdasarkan kategori yang tersedia. Saat location user terdeteksi lewat browser, sistem akan otomatis menampilkan beberapa tempat tujuan terdekat di dalam peta. Tempat tujuan dikelompokkan berdasarkan beberapa kategori:
  - Makan : informasi rumah makan, warteg, cafe
  - Nyalon : tempat cukur atau salon
  - Bengkel : bengkel kendaraan bermotor, tempat las
  - Gembok : tempat bikin kunci, service gembok
  - Ngekos : informasi kos2an, kontrakan
  - Nambal ban : tempat tambal ban, isi angin ban

### Fungsional
Secara umum semua kategori memiliki fungsionalitas yang sama, yaitu:
1. Bisa menampilkan tempat tujuan terdekat dengan lokasi user sesuai dengan kategori yang dipilih
2. Bisa search/mencari lokasi, lalu menampilkan tempat tujuan terdekat
3. Tempat2 tujuan yang terlacak akan ditampilkan di dalam peta dan ditandai oleh icon pin.
4. Saat user klik salah satu pin, informasi detail tentang tempat tujuan tersebut akan ditampilkan di panel kanan
5. Panel kanan juga bisa menampilkan review dari beberapa pelanggan yang pernah menggunakan jasa layanan
6. Pin lokasi di peta akan menampilkan nama tempat yang dituju sekaligus rating nya
7. Sistem rating sebuah lokasi akan dikalkulasikan dari kumpulan review para user

### Struktural
Secara garis besar ada 3 struktur utama dalam web ini:
1. **Area Kategori** : berupa list vertical menampilkan kategori2 tujuan
2. **Area Map** : berupa sebuah peta yang akan menampilkan lokasi2 yang ditandai dengan pin icon. Search textbox berupa autocomplete lokasi yang disediakan oleh provider Map.
3. **Area Detail** : berupa deskripsi dari lokasi yang dipilih melalui klik pin icon di peta. Detail bisa terdiri dari nama tempat, alamat lengkap, nomor kontak, deskripsi service. Bagian bawah akan terdapat kotak review berasal dari beberapa user yang telah terdaftar.

[//]: #
   [Web prototype.jpg]: <Web prototype.jpg>



