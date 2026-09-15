# Cara pasang FairGuard di laptop CS (Windows)

Sekali saja per laptop. Tidak perlu hak admin.

1. Unduh **`pasang-fairguard.reg`** dari halaman ini.
2. Klik dua kali berkasnya. Windows bertanya "apakah Anda yakin" — pilih **Yes**,
   lalu **OK**.
3. **Tutup semua jendela Chrome**, lalu buka Chrome lagi. Menutup tab saja tidak
   cukup — Chrome baru membaca pendaftaran ini saat dijalankan ulang.
4. Buka `chrome://extensions`. FairGuard harus sudah ada di sana.
5. Buka WhatsApp Web. Badge muncul di pojok kanan atas.

Chrome akan menampilkan tulisan **"Dikelola oleh organisasi Anda"** di menunya.
Itu wajar dan memang efek dari cara pasang ini. Chrome tidak jadi bisa dipantau
dari jauh: satu-satunya aturan yang terdaftar adalah "pasang FairGuard".

## Kalau tidak muncul

1. Buka `chrome://policy`, klik **Reload policies**.
2. Cari baris `ExtensionInstallForcelist`. Kalau tidak ada, berkas `.reg` belum
   terpasang — ulangi langkah 2 di atas.
3. Kalau ada tapi ekstensinya tetap tidak muncul, tunggu beberapa menit: Chrome
   mengunduhnya di latar belakang.

## Memperbarui

Tidak ada yang perlu dilakukan. Chrome memeriksa versi baru sendiri setiap
beberapa jam, dan saat dijalankan ulang.

## Mencopot

Klik dua kali **`copot-fairguard.reg`**, lalu jalankan ulang Chrome. Ekstensinya
terhapus sendiri.

## Yang dibaca FairGuard

Arah pesan (masuk atau keluar), nama lawan chat, dan jam. **Isi pesan tidak
pernah dibaca.** Tidak ada satu byte pun yang dikirim ke luar laptop — tidak ada
server, tidak ada laporan. Nomor HP customer tidak disimpan; yang dicatat hanya
hash bersalt, dan saltnya dibuat sendiri di tiap laptop, jadi catatan di satu
laptop tidak bisa dicocokkan dengan laptop lain.
