# FairGuard — saluran distribusi

Repo ini **bukan** kode sumber. Isinya cuma paket terpasang dan berkas
pembaruan, supaya Chrome bisa mengunduhnya tanpa login:

| Berkas | Gunanya |
|---|---|
| `fairguard.crx` | Paket ekstensi yang sudah ditandatangani |
| `update.xml` | Berkas yang dicek Chrome untuk tahu ada versi baru |
| `pasang-fairguard.reg` | Sekali klik di laptop CS — mendaftarkan ekstensi ke Chrome |
| `copot-fairguard.reg` | Kebalikannya: mencabut pendaftaran, ekstensi terhapus sendiri |

## Apa itu FairGuard

Penunjuk kecepatan chat di WhatsApp Web untuk tim CS. Ia **membaca layar dan
menghitung**, tidak pernah mengetik, mengirim, atau membaca isi pesan, dan tidak
mengirim apa pun ke luar laptop. Semua angka disimpan di laptop masing-masing.

Nomor HP customer tidak pernah disimpan — yang dicatat hanya hash bersalt, dan
saltnya dibuat sendiri di tiap laptop.

## Cara pasang

Lihat `PASANG.md`.
