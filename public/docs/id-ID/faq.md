# Bantuan & FAQ

Temukan jawaban yang sering ditanyakan dan panduan penelusuran masalah untuk AB Download Manager.
---

### Apakah aplikasi ini mendukung media dari website?
Ya! AB Download Manager bisa mengambil video, suara, dan stream HLS non-enkripsi dari website. Pastikan kamu menginstall extensi browser agar fitur ini bekerja.

---

### Apakah aplikasi ini mendukung pengunduhan dari YouTube?
Tidak. Karena ketentuan hukum dan lisensi, aplikasi ini tidak mendukung pengunduhan stream terenkripsi, termasuk video YouTube.

---

### Layar saya gelap atau berkedip — apa yang harus saya lakukan?
Kamu mungkin perlu untuk mengganti API render ke render perangkat lunak. Ikuti petunjuk di bawah:
1. Tambahkan baris ini ke environnment variablesmu
   ```env
   SKIKO_RENDER_API=SOFTWARE
   ```
2. Mulai ulang aplikasi.

Untuk informasi lebih lanjut, kamu bisa mengunjungi [tutorial rendering API resmi di Github](https://github.com/amir1376/ab-download-manager/wiki/Change-the-renderApi). 

---

### Extensi tidak terkoneksi ke aplikasi — apa yang harus saya lakukan?
Jika ekstensi browser tidak terkoneksi dengan aplikasi desktop:
1. Pastikan AB Download Manager desktop sedang berjalan.
2. Cek jika VPN, firewall, atau proxy tidak memblokir akses ke port lokal `15151`.
3. Coba buka [http://localhost:15151](http://localhost:15151) langsung di browsermu. Jika itu bekerja, kamu akan melihat respon koneksi dari aplikasi.