ENGLISH INTERACTIVE QUIZ — GRADE XII

ISI FOLDER
- index.html: halaman pembuka
- question-01.html sampai question-30.html: satu soal per halaman (file terpisah)
- result.html: hasil nilai dan pembahasan
- assets/style.css: desain website
- assets/questions.js: data 30 soal dan kunci jawaban
- assets/app.js: navigasi, penilaian, penyimpanan jawaban, dan interaksi

CARA MEMASANG DI GITHUB PAGES
1. Ekstrak ZIP ini.
2. Upload seluruh isi folder (semua file HTML dan folder assets) ke root repository GitHub.
3. Pastikan index.html berada di root repository, bukan di dalam folder tambahan.
4. Buka Settings > Pages.
5. Pada Build and deployment, pilih Deploy from a branch.
6. Pilih branch main dan folder /(root), lalu Save.
7. Buka alamat GitHub Pages repository.

FITUR
- Satu soal pada satu halaman HTML yang terpisah.
- 30 soal pilihan ganda berdasarkan PDF tugas Bahasa Inggris.
- Pilihan jawaban langsung mendapat feedback dan pembahasan.
- Progress bar dan nomor soal.
- Tombol Previous, Next, dan Skip.
- Jawaban tersimpan di browser menggunakan localStorage.
- Halaman hasil menampilkan skor dan review semua jawaban.
- Tombol Try Again untuk mengulang kuis.

CATATAN
Kuis dibuat untuk tampilan desktop dan ponsel. Kunci jawaban diambil dari pilihan yang dicetak tebal pada PDF. Jawaban benar tidak ditampilkan sebelum siswa memilih opsi.
