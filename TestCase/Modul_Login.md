# Test Case Pada Modul Login
Pengujian fitur pada modul login yang bertujuan untuk memastikan fitur yang mencakup proses login dapat berjalan dengan baik dan lancar sesuai dengan requirement

## TK-T1
**Skenario**: Login dengan no HP terdaftar  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki akun terdaftar  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Login"
2. Masukkan nomor hp
3. Klik "Selanjutnya"
4. Masukkan kode verifikasi (6 digit pin tokopedia)

**Data Uji**:  
No HP: 081380065633  
**Hasil yang Diharapkan**: User berhasil login, diarahkan ke halaman utama website, dan token tersimpan  
**Hasil Sebenarnya**: User berhasil login, diarahkan ke halaman utama website, dan token tersimpan

## TK-T2
**Skenario**: Login dengan akun yang belum terdaftar  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Belum mendaftarkan akun  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Login"
2. Masukkan nomor hp atau email yang belum terdaftar
3. Klik "Selanjutnya"

**Data Uji**:  
No HP: 081380065233  
Email: rizky@gmail.com  
**Hasil yang Diharapkan**: Muncul pop up "Nomor HP/Email belum terdaftar", sistem akan memberikan opsi ubah informasi login atau daftar akun, user tidak berhasil login  
**Hasil Sebenarnya**: Muncul pop up "Nomor HP/Email belum terdaftar", sistem akan memberikan opsi ubah informasi login atau daftar akun, user tidak berhasil login

## TK-T3
**Skenario**: Checklist ingat saya  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki akun terdaftar  
**Langkah Pengujian**:

1. Buka Website
2. Masukkan no hp atau email yang terdaftar
3. Klik "Selanjutnya"
4. Masukkan kata sandi
5. Klik "Masuk"

**Data Uji**:  
No HP: 081380065633  
Email: rizky03@gmail.com  
**Hasil yang Diharapkan**: Sistem dapat menyimpan token informasi login user, user berhasil login  
**Hasil Sebenarnya**: Sistem dapat menyimpan token informasi login user, user berhasil login

## TK-T4
**Skenario**: Login dengan QR Code  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Sudah login akun di versi handphone  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Masuk"
3. Klik "Scan QR code"
4. Klik "Ya, lanjut masuk" pada tampilan handphone

**Hasil yang Diharapkan**: User berhasil login dengan akun yang sama di handphone, user diarahkan ke halaman utama tokopedia  
**Hasil Sebenarnya**: User berhasil login dengan akun yang sama di handphone, user diarahkan ke halaman utama tokopedia

## TK-T5
**Skenario**: Login dengan akun Google  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki akun Google yang aktif  
**Langkah Pengujian**:

1. Buka Website
2. Klik ​"Masuk"
3. Klik "Metode lain"
4. Klik ​"Google"
5. Pilih akun google dari tampilan pop up
6. Masukkan kode verifikasi yang dikirim ke alamat email

**Hasil yang Diharapkan**: User berhasil masuk dengan akun google, user diarahkan ke halaman utama tokopedia  
**Hasil Sebenarnya**: User berhasil masuk dengan akun google, user diarahkan ke halaman utama tokopedia
