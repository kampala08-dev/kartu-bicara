# Kartu Bicara

Aplikasi komunikasi gambar (AAC) untuk anak, klinik Yamet Palembang. Isinya build statis: `index.html`, `data/`, `media/`.

- Live: https://pecs.yametpalembang.io. Situs ini berjalan di VPS Hostinger sebagai project Docker `kartu-bicara` (lihat `docker-compose.yml`).
- Di hosting ini aplikasi berjalan dalam **mode lokal**: data tiap anak tersimpan di browser tablet masing-masing. Pakai menu Data & cadangan untuk menyimpan dan memulihkan file cadangan.
- Simbol: ARASAAC (arasaac.org), lisensi CC BY-NC-SA, karya Sergio Palao untuk Pemerintah Aragon. Suara dibuat dengan AI.
- Tidak berafiliasi dengan Pyramid Educational Consultants. PECS® adalah merek dagang Pyramid.

Cara memperbarui: ganti isi repo dengan build baru, lalu Restart project `kartu-bicara` di Docker Manager.
