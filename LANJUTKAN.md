# Lanjutkan deploy dari komputer

Status saat zip ini dibuat:
- DNS `pecs.yametpalembang.io` (A) sudah mengarah ke VPS Hostinger 72.62.124.82.
- Repo git lokal ini (2 commit, cabang `main`) berisi build siap pakai: `index.html`, `data/`, `media/`, `docker-compose.yml`.
- Belum: repo GitHub `kampala08-dev/kartu-bicara`, project Docker `kartu-bicara` di VPS (id 2014501).

Langkah:
1. Buat repo publik kosong `kampala08-dev/kartu-bicara` di GitHub (tanpa README).
2. Di folder ini: `git remote add origin https://github.com/kampala08-dev/kartu-bicara.git` lalu `git push -u origin main`.
3. Hostinger hPanel, VPS, Docker Manager, Compose: buat project `kartu-bicara` dari URL `https://github.com/kampala08-dev/kartu-bicara`, lalu Deploy.
4. Tunggu 1-2 menit (sertifikat HTTPS), buka https://pecs.yametpalembang.io.
