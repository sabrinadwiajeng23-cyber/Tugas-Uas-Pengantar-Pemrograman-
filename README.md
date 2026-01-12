# Tugas-Uas-Pengantar-Pemrograman-
# Nama : Sabrina Dwi Ajeng <br>
# Nim  : 312510308
# Kelas: TI.25 C5

# ============================================
# CLASS DATA - Menyimpan data mahasiswa
# ============================================

#di bagian ini menyimpan data satu mahasiswa dengan atribut:

#nim: nomor identitas mahasiswa
#nama: nama mahasiswa
#jurusan: program studi
#ipk: indeks prestasi kumulatif

#Metode __str__() digunakan untuk menampilkan data dalam format string yang terformat.

# ============================================
# CLASS PROCESS - Logika bisnis/proses data
# ============================================

# bagian ini menangani logika bisnis dan penyimpanan data. Berisi:
#Validasi Data:

#validasi_nim(): Memastikan NIM berupa angka 8 digit dan tidak duplikat
#validasi_nama(): Memastikan nama minimal 3 karakter dan hanya huruf/spasi
#validasi_jurusan(): Memastikan jurusan sesuai daftar yang tersedia
#validasi_ipk(): Memastikan IPK berupa angka antara 0.0-4.0

#Operasi Data (CRUD):

#tambah_mahasiswa(): Menambah mahasiswa baru dengan validasi
#hapus_mahasiswa(): Menghapus mahasiswa berdasarkan NIM
#cari_mahasiswa(): Mencari data mahasiswa
#get_semua_mahasiswa(): Mengambil semua data mahasiswa

# ============================================
# CLASS VIEW - Menampilkan data ke user
# ============================================

#bagian ini menampilkan antarmuka kepada user:

#tampilkan_header(): Menampilkan judul aplikasi
#tampilkan_menu(): Menampilkan pilihan menu
#input_mahasiswa_baru(): Form input data mahasiswa baru
#tampilkan_tabel_mahasiswa(): Menampilkan semua data dalam bentuk tabel
#cari_dan_tampilkan(): Interface untuk mencari mahasiswa
#hapus_mahasiswa_view(): Interface untuk menghapus data

# ============================================
# MAIN - Program Utama
# ============================================

# Loop utama yang:

#Menampilkan menu pilihan
#Menjalankan fungsi sesuai pilihan user (1-5)
#Program berhenti saat user memilih opsi 5 (Keluar)

#Fitur Utama Aplikasi

# ✅ Tambah data mahasiswa dengan validasi otomatis
# ✅ Tampilkan semua data dalam format tabel
# ✅ Cari mahasiswa berdasarkan NIM
# ✅ Hapus data mahasiswa
# ✅ Pesan error yang informatif
