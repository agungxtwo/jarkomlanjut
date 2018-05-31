# Firewall Basic Zone

* Semua konfigurasi sesuai dengan topologi, setiap router memiliki loopback interface
    Router LAN: L0: 1.1.1.1 /24
    Router FIREWALL:L0:  2.2.2.2 /24
    Router INTERNET: L0: 3.3.3.3 /24 dan L1: 33.33.33.33 /24
   
* Static routes telah dikonfigurasi, dan terhubung ke semua router.
* Router INTERNET memiliki: SSH, TELNET, DNS, HTTP and HTTPS.
* Router FIREWALL memiliki: SSH and TELNET.

    Username: akakom
    Password: akakom
    
* Buat 2 security zones dengan nama “LAN” dan “INTERNET” di router FIREWALL.
* Tempatkan interface pada zona yang sesuai.
* Membuat class-map, policy-map dan zone-pair sehingga traffic LAN ke INTERNET diijinkan.
* Traffic dari INTERNET ke LAN di block.
* Meningkatkan keamanan dengan hanya mengizinkan hanya HTTP, ICMP dan HTTPS traffic dari LAN ke INTERNET.
* Lakukan tes dengan menggunakan telnet router LAN ke router INTERNET, seharusnya akses ini di block.

# IOS Image
c3725-adventerprisek9-mz.124-15.T7.bin
