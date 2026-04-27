# cara penggunaan github

1. Langkah-Langkah Push Repository
Push berfungsi untuk mengirimkan perubahan kode dari komputer lokal ke server pusat (seperti GitHub atau GitLab).
Langkah-langkah:
- Inisialisasi (Jika folder baru): git init
- Menambahkan file ke staging area: git add . (untuk semua file) atau git add nama_file.ext
- Menyimpan perubahan dengan pesan:
- Menghubungkan ke remote (Jika pertama kali):
- Mengirim kode
<img src="/asset/git-push.png">

2. Langkah-Langkah Clone Repository
Clone berfungsi untuk menyalin (mendownload) seluruh isi repository yang ada di server ke komputer lokal Anda.
Langkah-langkah:
- Buka terminal dan masuk ke folder tujuan.
- Gunakan perintah:
git clone https://github.com/username/nama-repo.git
- Git akan membuat folder baru sesuai nama repository dan mendownload semua file serta riwayat perubahannya.
    <img src="/asset/git-clone.jpg">
3. Langkah-Langkah Pull dan Push (Alur Kerja Kolaborasi)
Fungsi Pull: Mengambil dan menggabungkan (merge) perubahan terbaru dari server ke komputer lokal Anda.
Alur Kerja Standar:
- Pull terlebih dahulu:
git pull origin main
Ini dilakukan untuk menghindari konflik (conflict) jika rekan tim sudah mengubah file yang sama.
- Lakukan perubahan kode pada file Anda.
- Add dan Commit:
git add
git commit -m "Menambahkan fitur login"
- Push kembali ke server:
git push origin main
<img src="/asset/git-push-pull.jpg">
4. Pentingnya Penggunaan Command Line (CLI)
Meskipun banyak aplikasi GUI (seperti GitHub Desktop atau GitKraken), Command Line tetap menjadi pilihan utama profesional karena:
Kecepatan dan Efisiensi: Mengetik perintah seringkali lebih cepat daripada menavigasi menu klik-kanan.
Kontrol Penuh: CLI memberikan akses ke fitur-fitur tingkat lanjut yang mungkin tidak tersedia atau tersembunyi di versi GUI.
Otomatisasi: Perintah CLI dapat dimasukkan ke dalam script untuk otomatisasi tugas (CI/CD).
Universal: Perintah Git di terminal Linux, macOS, dan Windows tetap sama, memudahkan kolaborasi antar platform.