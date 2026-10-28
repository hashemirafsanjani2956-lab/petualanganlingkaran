# Misi Rahasia Kerajaan Lingkaran

Presentasi matematika interaktif tentang **lingkaran** dengan tema petualangan. Seluruhnya berupa satu file HTML (HTML, CSS, dan JavaScript), tanpa pustaka luar, dan bisa berjalan tanpa internet.

**Demo:** `https://USERNAME.github.io/petualangan-lingkaran/` (ganti `USERNAME` dengan nama pengguna GitHub Anda setelah GitHub Pages aktif)

## Isi materi (19 slide)

Pengertian lingkaran, asal-usul lingkaran, rahasia π, sejarah π, asal-usul 22/7 dan 3,14, eksperimen π, jari-jari, diameter, luas lingkaran (juring disusun ulang), keliling lingkaran, perbedaan luas dan keliling, kuis 5 soal, Boss Battle, ringkasan, dan penutup beserta referensi.

## Fitur interaktif

- Navigasi tombol Sebelumnya/Berikutnya dan tombol panah keyboard; tombol `F` untuk layar penuh.
- Peta Misi yang menyala bertahap sesuai materi yang diselesaikan.
- Simulasi: eksperimen π, jari-jari dan diameter, juring disusun ulang, pita keliling.
- Soal latihan acak, kuis dengan skor, dan soal Boss Battle.

## Cara menjalankan di komputer

Klik dua kali `index.html`. Browser seperti Chrome, Edge, atau Firefox akan membukanya.

## Cara mengunggah ke GitHub

### Lewat situs web (tanpa Git)

1. Buka <https://github.com/new>, beri nama repositori `petualangan-lingkaran`, pilih **Public**, lalu **Create repository**.
2. Klik **uploading an existing file**, seret semua isi folder ini (termasuk `.nojekyll` jika terlihat), lalu **Commit changes**.

### Lewat Git

```bash
cd petualangan-lingkaran
git init
git add .
git commit -m "Versi pertama presentasi lingkaran"
git branch -M main
git remote add origin https://github.com/USERNAME/petualangan-lingkaran.git
git push -u origin main
```

## Mengaktifkan GitHub Pages (agar bisa dibuka lewat tautan)

1. Di repositori, buka **Settings → Pages**.
2. Pada **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch `main` dan folder `/ (root)`, lalu **Save**.
4. Tunggu beberapa menit. Tautan situs akan muncul di halaman yang sama.

## Mengedit

Buka `index.html` di editor teks (misalnya VS Code). Warna tema ada di bagian `:root` pada CSS, dan setiap slide ditandai komentar `/* ===== nomor. Judul ===== */`. Penyempurnaan tampilan ada di bagian `PENYEMPURNAAN TAMPILAN`.

## Referensi

- Beckmann, P. *A History of Pi*.
- Berggren, L., Borwein, J., & Borwein, P. (eds.). *Pi: A Source Book*. Springer.
- Heath, T. L. *The Works of Archimedes*.
- Eves, H. *An Introduction to the History of Mathematics*.
- Boyer, C. B., & Merzbach, U. C. *A History of Mathematics*.
- Blatner, D. *The Joy of π*.
- Arndt, J., & Haenel, C. *Pi Unleashed*.
- MacTutor History of Mathematics (University of St Andrews), artikel "A history of Pi".
- Buku teks Matematika SMP kelas VIII (Kemendikbud), bab Lingkaran.

## Lisensi

Belum ditentukan. Tambahkan file `LICENSE` (misalnya MIT) jika ingin orang lain boleh memakai ulang.
