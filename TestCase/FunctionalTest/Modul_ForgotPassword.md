# Test Case Pada Modul Forgot Password
Pengujian fitur pada modul forgot password yang bertujuan untuk memastikan fitur yang mencakup proses forgot password dapat berjalan dengan baik dan lancar sesuai dengan requirement

## TK-T27
**Skenario**: Ubah kata sandi baru  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki akun terdaftar  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Masuk"
3. Klik "Lupa kata sandi?"
4. Masukkan no hp atau email
5. Klik "Lanjut"
6. Masukkan kode verifikasi
7. Masukkan kata sandi baru dan ketik ulang kata sandi
8. Klik "Lanjut"

**Data Uji**:  
No HP: 081380065633  
Email: rizky03@gmail.com  
Kata Sandi: Rizky123  
**Hasil yang Diharapkan**: Sistem dapat menyimpan informasi kata sandi baru yang telah diubah, user berhasil mengubah password  
**Hasil Sebenarnya**: Sistem dapat menyimpan informasi kata sandi baru yang telah diubah, user berhasil mengubah password

## TK-T28
**Skenario**: No HP kurang dari 8 karakter  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Masuk"
3. Klik ​"Lupa kata sandi?"
4. Masukkan no hp kurang dari 8 karakter
5. Klik "Lanjut"

**Data Uji**:  
No HP: 081350  
**Hasil yang Diharapkan**: Sistem dapat menyimpan informasi kata sandi baru yang telah diubah, user berhasil mengubah password  
**Hasil Sebenarnya**: Sistem dapat menyimpan informasi kata sandi baru yang telah diubah, user berhasil mengubah password
