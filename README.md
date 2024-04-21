# Pengaruh Gamma Correction Terhadap Kinerja Waktu Dengan Menerapkan Sequential dan Parallel Programming

Gamma correction, juga dikenal sebagai gamma encoding atau gamma companding, adalah
proses menyesuaikan luminansi (kecerahan) sinyal gambar atau video untuk mengkompensasi
respon yang tidak linear pada perangkat tampilan. Gamma correction biasanya dilakukan untuk
meningkatkan kualitas visual gambar atau video pada tampilan karena mata manusia lebih
sensitif terhadap beberapa tingkat luminasi dari pada yang lain. Untuk menerapkan gamma
correction secara efisien kita bisa menggunakan teknik pemrograman parallel dan sequential.
Pemrograman tersebut melibatkan eksekusi beberapa instruksi secara bersamaan menggunakan
beberapa unit pemrosesan (misal inti GPU). Eksekusi ini dapat meningkatkan kecepatan dan
efisiensi gamma correction karena mengizinkan tiap bagian kecil dari GPU berperan untuk
pemrosesan secara parallel.
