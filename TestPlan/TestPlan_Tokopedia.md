# 1. Informasi Dokumen

## Versi dokumen: 1.0  
Disusun oleh: Muhammad Rizky Fiqryansyah  
Tanggal: 14 Juli 2026  
Direview oleh: -  
Status Persetujuan: Draft

# 2. Pendahuluan
Dokumen ini menjelaskan strategi, pendekatan, ruang lingkup, dan kriteria keberhasilan untuk pengujian fitur modul login, register, forgot password, product detail, product search, dan cart pada website Tokopedia

# 3. Tujuan
- Memastikan pengguna dapat masuk ke aplikasi menggunakan kredensial yang valid, sistem menolak kredensial yang tidak valid, serta seluruh proses autentikasi berjalan dengan aman, benar, dan sesuai kebutuhan bisnis
- Memastikan proses pendaftaran akun baru berjalan sesuai spesifikasi, seluruh validasi input diterapkan dengan benar, dan akun berhasil dibuat apabila seluruh data yang dimasukkan valid
- Memastikan pengguna dapat melakukan reset kata sandi melalui mekanisme yang tersedia, seperti email atau OTP, serta memastikan hanya pengguna yang berhak yang dapat mengubah kata sandinya
- Memastikan halaman detail produk menampilkan informasi produk secara lengkap, akurat, dan konsisten, serta fungsi-fungsi yang tersedia pada halaman tersebut
- Memastikan fitur pencarian dapat menemukan produk yang sesuai berdasarkan kata kunci yang dimasukkan pengguna, menampilkan hasil yang relevan, serta menangani berbagai kondisi pencarian seperti typo, kata kunci, maupun produk yang tidak ditemukan
- Memastikan pengguna dapat menambahkan, mengubah jumlah, menghapus produk dari keranjang, menghitung total harga dengan benar, serta mempertahankan data keranjang sesuai dengan proses bisnis aplikasi

# 4. Ruang Lingkup
## In Scope  
- Login functionality
- Register functionality
- Forgot Password Functionality
- Product Search Functionality
- Product Detail Functionality
- Cart Functionality
- Field validation
- Error message validation
- Basic session behavior (redirect ke halaman selanjutnya setelah login)
- Boundary value testing untuk input field

## Out of Scope
- Database validation
- Performance testing
- Security penetration testing

# 5. Strategi Pengujian  
Pengujian akan dilaksanakan secara **manual testing** dengan menerapkan metode **black-box testing** untuk memverifikasi fungsionalitas sistem berdasarkan kebutuhan yang telah ditentukan. Proses pengujian mencakup skenario **positif** dan **negatif** guna memastikan sistem mampu menangani berbagai kondisi input secara tepat. Selain itu, teknik **Boundary Value Analysis (BVA)** akan digunakan untuk menguji batas minimum dan maksimum nilai input sehingga validasi data dapat dipastikan berjalan sesuai spesifikasi

## 6. Lingkungan Pengujian
- OS: Windows 11
- Browser: Google Chrome versi **150**
- Environment: Production

## 7. Kriteria Keberhasilan
- Minimal 95% test case berhasil (Pass).
- Tidak ditemukan defect dengan severity Critical maupun High.
- Semua fungsi utama (Login, Register, Forgot Password, Product Search, Product Detail, dan Cart) berjalan sesuai expected result.
