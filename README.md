a. ampq adalah protokol standar terbuka di tingkat aplikasi yang digunakan oleh perangkat lunak middleware untuk mengirim dan menerima pesan antar sistem atau aplikasi.
b. guest:guest@localhost:5672, guest yang pertama adalah username yang digunakan untuk masuk ke server ampq, guest yang kedua adalah password untuk pengguna tersebut, localhost:5672 adalah alamat dari server ampq yang sedang berjalan.

Pada percobaan saya, total queue yang terlihat adalah 4. Jumlah queue tersebut terjadi karena publisher mengirim message lebih cepat daripada subscriber memprosesnya. Dalam program ini, setiap kali publisher dijalankan, publisher mengirim 5 event ke queue `user_created`.
<img width="1918" height="962" alt="image" src="https://github.com/user-attachments/assets/f0e5cef8-80bc-4151-bc9f-a827598504c2" />

