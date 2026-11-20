CATATAN KEUANGAN (PWA)

Isi: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png
Semua file harus ada dalam satu folder yang sama.

CARA PASANG DI ANDROID
1. Unggah seluruh isi folder ke hosting HTTPS, misalnya:
   - Netlify Drop (app.netlify.com/drop): seret folder ini, selesai.
   - GitHub Pages: unggah file ke repository lalu aktifkan Pages.
   - Cloudflare Pages atau Vercel.
2. Buka alamat situs di Chrome Android.
3. Ketuk menu (tiga titik) lalu Instal aplikasi.
4. Ikon muncul di layar utama dan berjalan layar penuh, juga bisa dipakai offline.

CATATAN
- PWA wajib lewat HTTPS (localhost dikecualikan untuk uji coba).
- Data tersimpan di browser perangkat (localStorage), tidak ikut pindah ke HP lain.
- Jika mengubah file, naikkan nilai V di sw.js (misalnya keuangan-v2) agar pembaruan terpasang.
