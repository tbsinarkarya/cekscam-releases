# CekScam

**Pantau otomatis akun palsu yang memakai nama toko Anda.**

CekScam adalah aplikasi gratis untuk Windows 10 dan 11, untuk pemilik toko dan UMKM mana pun.

- Mencari nama toko Anda di Google secara terjadwal (web, Google Maps, Google Gambar, Instagram, Facebook, TikTok).
- Mengambil nomor WhatsApp di hasil pencarian dan membandingkannya dengan nomor resmi toko.
- Menandai nomor yang bukan milik Anda sebagai **PALSU** atau **PERLU DICEK**.
- Mengenali foto asli toko Anda yang diedit penipu.
- Menyiapkan panduan dan teks laporan untuk Instagram, Facebook, TikTok, Google, Google Maps, aduannomor.id, dan cekrekening.id. Laporan tetap Anda kirim sendiri.

Semua data tersimpan di komputer Anda. CekScam tidak punya server. Pencarian memakai API key Serper.dev milik Anda sendiri.

## Unduh

Unduh installer terbaru (`CekScam_<versi>_x64-setup.exe`) di:

**https://github.com/tbsinarkarya/cekscam-releases/releases/latest**

Setelah terpasang, CekScam memeriksa versi baru sendiri dan memberi tahu di Dasbor. Pembaruan dipasang hanya setelah Anda setujui di Pengaturan → Pembaruan aplikasi.

## Peringatan Windows SmartScreen

Windows mungkin menampilkan ‘Windows melindungi PC Anda’. Klik **Info selengkapnya → Tetap jalankan**. Peringatan ini muncul karena CekScam belum memakai sertifikat berbayar. File pembaruan sudah diperiksa keasliannya oleh CekScam.

Peringatan ini bisa muncul saat memasang pertama kali dan juga saat memasang pembaruan dari dalam aplikasi (Pengaturan → Pembaruan aplikasi → Mulai Ulang & Pasang). Bila Anda terlanjur menekan **Jangan jalankan**, buka CekScam lagi: versi lama tetap berjalan seperti biasa dan pembaruan bisa dipasang ulang dari Pengaturan.

## Mencocokkan SHA-256

Kode SHA-256 installer tertulis di halaman rilisnya. Untuk mencocokkan, buka PowerShell di folder unduhan lalu jalankan:

```powershell
Get-FileHash .\CekScam_0.2.0_x64-setup.exe -Algorithm SHA256
```

Ganti `0.2.0` dengan versi yang Anda unduh. Kode yang tampil harus sama persis dengan kode di halaman rilis. Bila berbeda, jangan jalankan installer itu.

## Kode sumber dan kontak

Repo ini hanya berisi installer dan file pembaruan. Kode sumber CekScam tidak dipublikasikan.

Dikembangkan oleh Sinar Karya — [tbsinarkarya.com](https://tbsinarkarya.com)
