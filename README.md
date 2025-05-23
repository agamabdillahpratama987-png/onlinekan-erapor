# Onlinekan Aplikasi Erapor Dapodik

**Onlinekan Aplikasi Erapor Dapodik** adalah solusi digital untuk memudahkan pengelolaan dan pelaporan hasil belajar siswa secara online, terintegrasi dengan sistem Dapodik.

## Fitur Unggulan

- **Akses Online**  
    Guru, siswa, dan orang tua dapat mengakses rapor kapan saja dan di mana saja.

- **Mudah Digunakan**  
    Antarmuka sederhana dan ramah pengguna.

## Panduan Instalasi

1. **Download Release atau Source Code**
   - Unduh file release atau source code aplikasi dari repository ini.
2. **Download Cloudflared Release untuk Windows 64bit**
   - Download file `cloudflared-windows-amd64.exe` (Windows 64bit) dari link berikut:
     [Download Cloudflared Terbaru (Windows 64bit)](https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-windows-amd64.exe)
3. **Extract isi ZIP file ke dalam folder instalasi erapor**
    - Ekstrak semua file ke folder instalasi erapor. Secara default, folder instalasi berada di `C:\newappraporsmp2025`.
4. **Membuat shortcut file `online-erapor.cmd` ke folder Startup**
   - Klik kanan file `online-erapor.cmd` → Create Shortcut.
   - Tekan `Win+R`, ketik `shell:startup`, lalu tekan Enter untuk membuka folder Startup.
   - Pindahkan shortcut yang sudah dibuat ke folder Startup tersebut.
5. **Jalankan shortcut untuk memulai script**
   - Klik dua kali shortcut di folder Startup untuk menjalankan aplikasi.
6. **Akses aplikasi melalui browser**
   - Jika berhasil, browser akan terbuka otomatis dengan link aplikasi yang sudah online dan siap digunakan.

## Panduan Uninstall

1. Hapus shortcut aplikasi dari folder Startup:
   - Tekan `Win+R`, ketik `shell:startup`, lalu tekan Enter untuk membuka folder Startup.
   - Hapus shortcut `online-erapor.cmd` dari folder tersebut.
2. Hapus seluruh file aplikasi dari folder instalasi:
   - Buka File Explorer dan masuk ke folder instalasi, misal `C:\newappraporsmp2025`.
   - Hapus semua file dan folder yang ada di dalam folder instalasi erapor.

## Kontribusi

Kontribusi sangat terbuka! Silakan buat issue atau pull request untuk perbaikan dan pengembangan fitur.

## Lisensi

Proyek ini menggunakan lisensi [MIT](LICENSE).

---

**Onlinekan Aplikasi Erapor Dapodik** — Digitalisasi pelaporan pendidikan yang mudah, cepat, dan aman.