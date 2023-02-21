# P.-Keamanan-Informasi-1_-Analyzing-HTTP-and-HTTPS

**PEMBAHASAN**

Pada praktikum ini dilakukan perekaman aktivitas HTTP dan HTTPS dan juga menganalisisnya. Menggunakan command tcpdump, dapat dibuat file pcap yang bisa dibuka menggunakan Wireshark. Untuk file hasil rekam HTTP yaitu httpdump.pcap, dapat dilihat pada POST bahwa UID dan password yang digunakan untuk login pada website HTTP tidak terenkripsi atau terproteksi. 
Pada file hasil rekam HTTPS yaitu httpsdump.pcap, terdapat beberapa application data dalam port tcp 443, namun di dalamnya tidak terdapat informasi tentang UID dan password, dan hanya terdapat encrypted application data.
Melihat hasil praktikum di atas, terlihat jelas perbedaan antara HTTP dan HTTPS. HTTPS mengamankan koneksi dengan protokol keamanan digital menggunakan kunci kriptografik untuk mengenkripsi dan memvalidasi data. Untuk menggunakan HTTPS dan mengamankan domain, diperlukan sertifikat SSL/TLS. Oleh karena itu, pada website yang memiliki credentials akun-akun pengguna, HTTPS merupakan pilihan yang wajib untuk digunakan.
