# Latihan-OPP
#### Julius Hutabarat
#### 312410429
#### TI.24.A3

# Deskripsi
Program ini merupakan program manajemen data mahasiswa yang dibangun menggunakan Python. Program ini memungkinkan pengguna untuk menambah, mengubah, menghapus, dan mencari data mahasiswa.

# Fitur
1. Tambah data mahasiswa
2. Ubah data mahasiswa
3. Hapus data mahasiswa
4. Cari data mahasiswa berdasarkan NIM
5. Tampilkan semua data mahasiswa

# Deskripsi Kode
###### data/mahasiswa.py
File ini berisi definisi kelas Mahasiswa yang memiliki atribut nama, nim, dan nilai. Selain itu, terdapat beberapa fungsi untuk mengelola data mahasiswa:
tambah_mahasiswa(data_mahasiswa, mahasiswa): Menambahkan objek mahasiswa ke dalam daftar.
ubah_mahasiswa(data_mahasiswa, nim, nilai_baru): Mengubah nilai mahasiswa berdasarkan NIM.
hapus_mahasiswa(data_mahasiswa, nim): Menghapus mahasiswa dari daftar berdasarkan NIM.
cari_mahasiswa(data_mahasiswa, nim): Mencari mahasiswa berdasarkan NIM.
tampilkan_semua_mahasiswa(data_mahasiswa): Menampilkan semua data mahasiswa

###### view/input_form.py
File ini berisi fungsi input_data_mahasiswa() yang digunakan untuk mengambil input dari pengguna untuk menambah data mahasiswa.

###### view/mahasiswa.py
File ini berisi fungsi tampilkan_data_mahasiswa(mahasiswa) yang digunakan untuk menampilkan informasi mahasiswa.

###### main.py
File ini adalah file utama yang menjalankan aplikasi. Di dalamnya terdapat fungsi load_data() untuk memuat data dari file JSON dan save_data(data) untuk menyimpan data ke file JSON. Fungsi main() mengatur menu interaksi dengan pengguna.


# Data Mahasiswa
![WhatsApp Image 2024-12-10 at 10 19 34_619b2530](https://github.com/user-attachments/assets/9f466403-34c8-443b-9363-9d54f4dddb8e)

# File Data Mahasiswa
![WhatsApp Image 2024-12-10 at 10 20 54_ccb33ffe](https://github.com/user-attachments/assets/4ef5984f-736c-4619-83c9-453a87f36b34)

# File View/Input Data Mahasiswa
![WhatsApp Image 2024-12-10 at 10 20 14_177f52c9](https://github.com/user-attachments/assets/a3cdf628-ad98-4caa-8e96-8ea9e237f9dc)

# File Main
![WhatsApp Image 2024-12-10 at 10 20 55_bd292052](https://github.com/user-attachments/assets/5cb4c098-088b-4f1d-acf2-aa7842daa0c8)
