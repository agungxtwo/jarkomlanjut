Langkah Pengerjaan:
1. Semua IP telah di konfigurasi
2. konfigurasi router borobudur menjadi transparent firewall. dibutuhkan fungsi bridge.
3. Gunakan network 192.168.13.0 /24 untuk router prambanan dan Terminal dalam subnet yang sama.
4. Pastikan router prambanan dapat mengakses router Terminal dengan using TELNET or HTTP, semua trafik di drop.
5. pastikan router prambanan dan Terminal tidak dapat berkomunikasi dengan IPV6.

Tools: GNS3
IOS : C3725