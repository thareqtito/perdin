# Generator SPPD — KPU Kabupaten Pacitan

Aplikasi web satu file untuk membuat dokumen perjalanan dinas dalam format Word (.docx, A4):

- **SPT** — Surat Perintah Tugas (Komisioner)
- **SPT2** — Surat Perintah Tugas (Sekretariat)
- **SPD** — Surat Perjalanan Dinas per nama
- **SPD-B** — halaman belakang SPD
- **LPD** — Laporan Perjalanan Dinas, termasuk dokumentasi foto

Semua dokumen dibuat langsung di browser, tanpa server dan tanpa database. Isian form, data pegawai, pengaturan, dan foto tersimpan di browser masing-masing pengguna.

## Cara pakai

1. Buka aplikasinya, lalu isi tab **Form SPPD**.
2. Klik tombol **Cetak** sesuai dokumen yang dibutuhkan. File .docx akan terunduh.
3. Data pegawai (NIP, pangkat, jabatan) bisa diubah di tab **Data Pegawai**.
4. Kop surat, dasar tetap, tembusan, dan teks baku lain bisa diubah di tab **Pengaturan**.

## Hosting di GitHub Pages

1. Unggah `index.html` (dan README ini) ke repository.
2. Buka **Settings → Pages**.
3. Pada **Source**, pilih **Deploy from a branch**, lalu pilih branch `main` dan folder `/ (root)`, kemudian **Save**.
4. Tunggu 1–2 menit. Aplikasi bisa diakses di `https://<username>.github.io/<nama-repo>/`.

## Catatan

- Untuk memperbarui aplikasi, cukup ganti `index.html` dengan versi baru.
- Data yang tersimpan di browser pengguna tidak hilang saat file diperbarui.
- Huruf tampilan (Plus Jakarta Sans) dimuat dari Google Fonts. Saat offline, aplikasi tetap berjalan dengan huruf bawaan.
