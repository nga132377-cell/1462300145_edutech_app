## Tugas EAS Pengembangan Aplikasi Bergerak (Kelas D)

Aplikasi EduTech untuk memenuhi ujian akhir semester gasal/genap. Aplikasi ini berisi materi pembelajaran mini, simulasi video, dan kuis interaktif yang bisa menyimpan skor secara lokal.

## Fitur Utama Aplikasi
1. **Login & Register:** Ada validasi form kalau inputnya kosong atau salah.
2. **Dashboard Modul:** Menampilkan daftar materi kursus yang diatur pakai Provider.
3. **Detail Materi:** Tempat baca materi teks dan ada simulasi pemutar videonya.
4. **Kuis Interaktif:** Bisa jawab soal pilihan ganda, hitung skor, dan simpan nilai tertinggi (High Score) pakai Shared Preferences agar tidak hilang pas aplikasi ditutup.

## Struktur Folder (Clean Architecture)
- `core/` : Untuk setup warna dan font aplikasi.
- `data/` : Untuk model data (MateriModel).
- `domain/` : Untuk entitas data murni (MateriEntity).
- `presentation/` : Untuk bagian UI (halaman login, register, dashboard, detail materi, kuis, dan file controller provider).

## Library yang Digunakan (pubspec.yaml)
- `provider` (untuk state management)
- `shared_preferences` (untuk simpan sesi login & skor kuis)
- `http` (untuk parsing data)
- `google_fonts` (untuk merapikan font)
