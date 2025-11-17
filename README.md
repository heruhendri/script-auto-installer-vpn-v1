# `INSTAL SCRIPT`

<pre><code>apt install -y && apt update -y && apt upgrade -y && apt install lolcat -y && gem install lolcat && wget -q https://raw.githubusercontent.com/Anggajrxxx/vip/main/setup.sh && chmod +x setup.sh && screen -S install ./setup.sh</pre></code>
### TESTED ON OS
- UBUNTU 20.04
- DEBIAN 10

# Script Auto Installer VPN v1

[![GitHub stars](https://img.shields.io/github/stars/heruhendri/script-auto-installer-vpn-v1?style=flat-square)](https://github.com/heruhendri/script-auto-installer-vpn-v1/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/heruhendri/script-auto-installer-vpn-v1?style=flat-square)](https://github.com/heruhendri/script-auto-installer-vpn-v1/network)
[![Views](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fheruhendri%2Fscript-auto-installer-vpn-v1&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23FFCC00)](https://hits.seeyoufarm.com)

Deskripsi singkat: Script-shell ini mempermudah pemasangan dan konfigurasi layanan VPN pada server (centOS/Ubuntu/Debian — cek file script untuk detail). Cocok untuk pengaturan cepat VPS.

Fitur utama
- Instal otomatis komponen VPN (lihat script untuk daftar paket & konfigurasi).
- Minim konfigurasi manual — cocok untuk deploy cepat.
- Shell-only: mudah dibaca dan dimodifikasi.

Persyaratan
- VPS dengan akses root atau user dengan sudo.
- Sistem operasi yang didukung: Debian / Ubuntu / CentOS (cek script untuk versi yang didukung).
- Koneksi internet saat instalasi.

Instalasi (contoh)
1. Unduh repository atau salin script:
   git clone https://github.com/heruhendri/script-auto-installer-vpn-v1.git
2. Masuk ke direktori:
   cd script-auto-installer-vpn-v1
3. Beri izin eksekusi dan jalankan:
   chmod +x install.sh
   sudo ./install.sh
4. Ikuti petunjuk di layar.

Contoh penggunaan
- Jalankan installer seperti di atas, atau lihat file README di direktori script (jika ada) untuk opsi tambahan.
- Untuk kustomisasi, edit variabel dalam script sebelum menjalankan.

Troubleshooting singkat
- Jika skrip gagal karena paket yang tidak ditemukan, perbarui indeks paket:
  sudo apt update   (Debian/Ubuntu)
  sudo yum update   (CentOS)
- Periksa log output skrip dan jalankan kembali dengan hak akses root.
- Pastikan port yang dibutuhkan tidak diblokir oleh firewall provider.

Contact / Dukungan
- Email: heruu2004@gmail.com
- Telegram: https://t.me/GbtTapiPngnSndiri

Cara kontribusi
- Fork repo → buat branch fitur → buat PR dengan deskripsi perubahan.
- Untuk perbaikan sederhana, Anda dapat membuka issue atau mengirimkan PR langsung.

Catatan keamanan
- Gunakan script ini hanya pada server yang Anda percayai.
- Periksa isi script sebelum menjalankan untuk memastikan tidak ada perintah berbahaya.
- Backup konfigurasi penting sebelum instalasi.

Lisensi
- Tidak ada lisensi khusus tercantum (default: semua hak dilindungi). Jika Anda ingin memakai/menyebarkan secara publik, pertimbangkan menambahkan file LICENSE (mis. MIT).

Mengedit README ini
- Anda dapat langsung mengedit melalui: https://github.com/heruhendri/script-auto-installer-vpn-v1/edit/main/README.md
- Atau paste konten ini ke editor lalu commit.

Jika mau saya commit README.md langsung ke branch main, balas "commit" dan saya akan melakukan push (minta konfirmasi lagi sebelum push).
