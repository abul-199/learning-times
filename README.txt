Cara pakai:
1. Upload semua isi folder ini ke hosting statis seperti GitHub Pages, Netlify, atau Vercel.
2. Jangan ubah nama file: index.html, manifest.webmanifest, service-worker.js, dan folder icons.
3. Setelah online, buka website sekali lalu refresh 1 kali agar service worker aktif.
4. Jika browser mendukung, tombol install di banner akan aktif.

Fitur utama:
- Dark mode / light mode
- Tambah sesi belajar langsung dari web
- Popup pengingat dengan toleransi 10 menit
- Tombol tunda 5 menit
- Target harian
- Pomodoro 25 menit
- Canvas materi + kategori + rating
- Export data JSON
- Siap di-hosting sebagai PWA

Catatan:
- Notifikasi tanpa backend hanya bekerja saat browser/app masih punya konteks aktif.
- Untuk push notification saat aplikasi benar-benar tertutup, perlu backend push terpisah.
