# UASPertemuan-16
# Putri Melati Ramadhaniati (312410194)
# TI.24.A2

Buatlah program sederhana dengan ketentuan:

• Program harus dibuat dengan konsep modular dan OOP (pisahkan
class data, class view, dan class process)

• Program harus meminta input dari pengguna

• Tambahkan validasi input (dapat menggunakan konsep eksepsi)

• Program menapilkan hasil (dapat berupa table view)


# Class Data:

•	Bertanggung jawab untuk menyimpan dan mengelola data pengguna.

•	Memiliki metode add_record untuk menambahkan catatan pengguna ke dalam daftar.

![WhatsApp Image 2025-01-06 at 21 50 14_3e94da5a](https://github.com/user-attachments/assets/338e2460-f24e-47d7-ba20-584ee2eac611)

**Penjelasan Kode**

•	__init__: Konstruktor yang menginisialisasi atribut records sebagai list kosong untuk menyimpan catatan pengguna.

•	add_record: Menerima name dan nim sebagai parameter dan menambahkan catatan baru ke dalam list records dalam bentuk dictionary.

# Class View: 

•	Bertanggung jawab untuk menampilkan data pengguna.

•	Memiliki metode display_records yang mencetak daftar pengguna dalam format tabel.

![WhatsApp Image 2025-01-06 at 21 50 54_01aa8347](https://github.com/user-attachments/assets/ca494f4b-2b2f-4d5a-ba32-75be76e14be6)

**Penjelasan Kode**

display_records: Mencetak daftar pengguna dalam format tabel. Menggunakan format untuk memastikan kolom nama dan NIM terformat dengan baik.

    • Menggunakan format untuk memastikan kolom nama dan NIM terformat dengan baik.
    
    • Menampilkan header tabel dan garis pemisah untuk kejelasan.

# Class Process:

• Mengelola alur program, termasuk pengambilan input dari pengguna dan interaksi antara kelas Data dan View.
    
• Memiliki metode get_input untuk meminta input dari pengguna dan memvalidasi input tersebut.  
    
• Memiliki metode run yang menjalankan keseluruhan proses.

![WhatsApp Image 2025-01-06 at 21 51 54_31ace8a5](https://github.com/user-attachments/assets/a7211286-5a12-4b7a-b21c-07ab9510a21d)

**Penjelasan Kode**

•	__init__: Konstruktor yang menginisialisasi objek Data dan View.

•	get_input: Metode ini meminta input dari pengguna untuk nama dan NIM.

    •	Menggunakan try-except untuk menangani kesalahan input. Jika NIM tidak dapat diubah menjadi integer atau jika NIM negatif, program akan menampilkan pesan kesalahan dan meminta input ulang.

![WhatsApp Image 2025-01-06 at 21 53 16_8a793eb1](https://github.com/user-attachments/assets/bce99a0d-e479-4233-9961-343c0bea4f19)

**Penjelasan Kode**

•	run: Metode ini menjalankan alur program dengan memanggil get_input untuk mendapatkan data dan kemudian menampilkan data menggunakan display_records.

•	Fungsi utama:

    •	Memastikan bahwa program akan berjalan hanya jika file ini dijalankan sebagai program utama.

    •	Membuat instance dari kelas Process dan memanggil metode run untuk memulai program.
    
# Output:

![WhatsApp Image 2025-01-06 at 22 14 13_5e459e83](https://github.com/user-attachments/assets/792f72b4-9bf0-4ada-a3ce-bad664f961fa)




