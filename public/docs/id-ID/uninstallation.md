## Hapus Pemasangan

### Windows

- Pergi ke folder instalasi dan jalankan `uninstall.exe`
- Kamu juga bisa hapus pemasangan aplikasi di pengaturan windows (`Tambah atau Hapus program`)

### Linux

Jika kamu menggunakan script pemasangan untuk linux kamu bisa menggunakan perintah di bawah ini untuk menghapusnya

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/amir1376/ab-download-manager/master/scripts/uninstall.sh)
```

### Homebrew (macOS & Linux)

Jika kamu memasang aplikasi menggunakan Homebrew kamu bisa menggunakan perintah di bawah ini untuk menghapusnya

```bash
brew uninstall --cask --zap ab-download-manager && brew untap amir1376/tap
```

### Hapus pemasangan manual

Jika kamu memasang aplikasi secara manual (menggunakan `.zip` atau `tar.gz`) setelah kamu menghapus folder aplikasi, hapus file-file/folder-folder berikut juga.

- `~/.abdm` (konfigurasi aplikasi/folder cache)
- `~/.config/autostart/com.abdownloadmanager.desktop` (file yang dijalankan saat boot)
- `~/.local/share/applications/com.abdownloadmanager.desktop` (file entri desktop)
