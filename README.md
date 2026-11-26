# CI untuk Repo Compose

![Compose Check](https://github.com/melaniayuanjani/compose-ci-minggu11/actions/workflows/compose-check.yml/badge.svg)

## File Repository

- `.gitignore` : Mengabaikan file `.env`.
- `.env.example` : Contoh konfigurasi variabel database.
- `docker-compose.yml` : Konfigurasi layanan MariaDB dan WordPress.
- `.github/workflows/compose-check.yml` : Workflow untuk memvalidasi konfigurasi Docker Compose.

## Menjalankan Aplikasi

1. Salin file `.env.example` menjadi `.env`.
2. Sesuaikan nilai konfigurasi di file `.env`.
3. Jalankan perintah:

   ```bash
   docker compose up -d
