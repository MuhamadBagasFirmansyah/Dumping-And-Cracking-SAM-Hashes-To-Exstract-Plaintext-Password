# CEHv10 Module 06: System Hacking

## Pendahuluan
Modul ini membahas langkah-langkah dan teknik yang digunakan dalam system hacking, serta memberikan pengetahuan tentang bagaimana ethical hacker melindungi sistem dari berbagai serangan. **System hacking** melibatkan beberapa tahapan yang bertujuan untuk mendapatkan akses dan kontrol ke sistem target, serta menyembunyikan jejak setelahnya.

## Tujuan Pembelajaran
1. Memahami proses hacking sistem.
2. Mengenal tahapan dari pencarian celah hingga kontrol penuh sistem.
3. Menguasai penggunaan tools hacking populer.
4. Mengidentifikasi langkah-langkah perlindungan terhadap serangan.

## Tahapan Hacking Sistem
Hacking sistem dilakukan dalam beberapa langkah utama, yaitu:

### 1. Reconnaissance (Pencarian Celah)
Mengumpulkan informasi target sebelum melakukan serangan. Ini termasuk mengetahui alamat IP, sistem operasi, dan aplikasi yang digunakan oleh target.

### 2. Gaining Access (Penetrasi)
Melakukan exploitasi pada celah yang ditemukan untuk mendapatkan akses ke sistem target.

### 3. Privilege Escalation (Meningkatkan Hak Akses)
Setelah mendapatkan akses awal, attacker berusaha untuk meningkatkan hak akses dari pengguna biasa menjadi administrator untuk mendapatkan kontrol penuh atas sistem.

### 4. Maintaining Access (Menjaga Akses)
Menanamkan backdoor atau metode lain yang memungkinkan attacker untuk tetap memiliki akses ke sistem secara berkelanjutan tanpa terdeteksi.

### 5. Covering Tracks (Menghapus Jejak)
Langkah terakhir adalah menghapus jejak untuk mencegah deteksi. Ini termasuk menghapus log dan menyembunyikan proses atau file yang mencurigakan.

## Tools yang Digunakan
Beberapa tools penting yang dijelaskan dalam modul ini:
- **Metasploit**: Framework untuk pengembangan dan peluncuran exploit.
- **Cain & Abel**: Tool untuk password cracking dan network sniffing.
- **John the Ripper**: Tool untuk melakukan cracking hash.
- **Hydra**: Tool brute-force untuk berbagai protokol seperti FTP dan SSH.

## Teknik Pengujian Keamanan
- **Password Cracking**: Menggunakan brute-force, dictionary attack, dan rainbow tables untuk menebak password.
- **Keylogging**: Menangkap input dari keyboard korban untuk mendapatkan informasi sensitif.
- **Privilege Escalation**: Teknik untuk mendapatkan akses admin dengan mengeksploitasi kelemahan sistem.
- **Rootkits**: Digunakan untuk menyembunyikan jejak di sistem agar tidak terdeteksi oleh administrator.

## Perlindungan Terhadap System Hacking
Untuk melindungi sistem dari serangan, langkah-langkah berikut sangat dianjurkan:
1. **Penggunaan Password Kuat dan MFA**: Hindari password yang mudah ditebak dan gunakan autentikasi multi-faktor.
2. **Pemantauan Aktivitas Sistem**: Selalu memonitor log sistem untuk mendeteksi aktivitas yang mencurigakan.
3. **Patching Berkala**: Pastikan sistem selalu diperbarui untuk menutup celah keamanan.
4. **Firewall dan Anti-malware**: Pastikan sistem dilindungi oleh perangkat lunak keamanan yang mutakhir.

## Kesimpulan
Modul ini memberikan pemahaman menyeluruh mengenai teknik system hacking dan tools yang digunakan, serta langkah-langkah preventif untuk melindungi sistem dari serangan serupa. Ethical hacker menggunakan pengetahuan ini untuk mengidentifikasi dan mengatasi potensi ancaman.

