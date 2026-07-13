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
**Hasil yang Diharapkan**: Muncul pesan error di bawah form no hp "Nomor ponsel terlalu pendek, minimum 8 angka"  
**Hasil Sebenarnya**: Muncul pesan error di bawah form no hp "Nomor ponsel terlalu pendek, minimum 8 angka"

## TK-T29
**Skenario**: No HP lebih dari 15 karakter  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Masuk"
3. Klik ​"Lupa kata sandi?"
4. Masukkan no hp lebih dari 15 karakter
5. Klik "Lanjut"

**Data Uji**:  
No HP: 0813800546584848485415  
**Hasil yang Diharapkan**: Muncul pesan error di bawah form no hp "Nomor ponsel terlalu panjang, maksimum 15 angka"  
**Hasil Sebenarnya**: Muncul pesan error di bawah form no hp "Nomor ponsel terlalu panjang, maksimum 15 angka"

## TK-T30
**Skenario**: Memasukkan format email yang tidak sesuai  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Masuk"
3. Klik "Lupa kata sandi"
4. Masukkan email dengan format yang tidak sesuai
5. Klik "Lanjut"

**Data Uji**:  
Email: rizky@com  
**Hasil yang Diharapkan**: Sistem dapat memvalidasi format email yang salah, muncul pesan error di bawah form email "Format email salah"  
**Hasil Sebenarnya**: Sistem dapat memvalidasi format email yang salah, muncul pesan error di bawah form email "Format email salah"

## TK-T31
**Skenario**: Memasukkan No HP atau email yang belum terdaftar  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Masuk"
3. Klik "Lupa kata sandi?"
4. Masukkan no hp atau email yang tidak terdaftar
5. Klik ​"Lanjut"

**Data Uji**:  
No HP: 081380054545
Email: rizkyf@gmail.com  
**Hasil yang Diharapkan**: Sistem dapat memvalidasi no hp atau email yang belum terdaftar, muncul pesan error di bawah form no hp atau email "Email atau Nomor Telepon tidak terdaftar"  
**Hasil Sebenarnya**: Sistem dapat memvalidasi no hp atau email yang belum terdaftar, muncul pesan error di bawah form no hp atau email "Email atau Nomor Telepon tidak terdaftar"

## TK-T32
**Skenario**: Show/hide kata sandi  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki akun terdaftar  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Masuk"
3. Klik "Lupa kata sandi?"
4. Masukkan no hp atau email terdaftar
5. Klik "Lanjut"
6. Masukkan kode verifikasi
7. Masukkan kata sandi baru dan ketik ulang kata sandi baru
8. Klik ikon mata

**Data Uji**:  
No HP: 081380065633
Email: rizky03@gmail.com  
Kata Sandi: Rizky123  
**Hasil yang Diharapkan**: Kata sandi dapat di show/hide  
**Hasil Sebenarnya**: Kata sandi dapat di show/hide

## TK-T33
**Skenario**: Memasukkan kata sandi baru dengan kata sandi lama  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Kata sandi lama "rizkyf03"  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Masuk"
3. Klik "Lupa kata sandi?"
4. Masukkan no hp atau email terdaftar
5. Klik "Lanjut"
6. Masukkan kode verifikasi
7. Masukkan kata sandi baru dan ketik ulang kata sandi baru dengan kata sandi lama
8. Klik "Lanjut"

**Data Uji**:  
No HP: 081380065633
Email: rizky03@gmail.com  
Kata Sandi: rizkyf03  
**Hasil yang Diharapkan**: Sistem berhasil menampilkan pesan error "Kata sandi baru harus berbeda dengan kata sandi lama", ubah password gagal  
**Hasil Sebenarnya**: Sistem berhasil menampilkan pesan error "Kata sandi baru harus berbeda dengan kata sandi lama", ubah password gagal

## TK-T34
**Skenario**: Akun otomatis keluar di semua perangkat ketika ubah kata sandi baru  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Sud​​​​​ah login dengan akun yang sama di beberapa perangkat  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Masuk"
3. Klik "Lupa kata sandi?"
4. Masukkan no hp atau email terdaftar
5. Klik "Lanjut"
6. Masukkan kode verifikasi
7. Masukkan kata sandi baru dan ketik ulang kata sandi baru
8. Klik "Lanjut"

**Data Uji**:  
No HP: 081380065633
Email: rizky03@gmail.com  
Kata Sandi: Rizky123  
**Hasil yang Diharapkan**: Akun yang tertaut pada perangkat lain berhasil logout setelah ubah kata sandi, ubah kata sandi berhasil  
**Hasil Sebenarnya**: Akun yang tertaut pada perangkat lain berhasil logout setelah ubah kata sandi, ubah kata sandi berhasil

## TK-T35
**Skenario**: "Kata Sandi Baru" dan "Ketik Ulang Kata Sandi Baru" tidak sama  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki akun terdaftar    
**Langkah Pengujian**:

1. Buka Website
2. Klik "Masuk"
3. Klik "Lupa kata sandi?"
4. Masukkan no hp atau email terdaftar
5. Klik "Lanjut"
6. Masukkan kode verifikasi
7. Masukkan kata sandi baru dan ketik ulang kata sandi baru dengan isian yang tidak sama

**Data Uji**:  
No HP: 081380065633
Email: rizky03@gmail.com  
Kata Sandi Baru: RizkyF03  
Ketik Ulang Kata Sandi: rizkyf
**Hasil yang Diharapkan**: Sistem berhasil menampilkan pesan error "Kata sandi baru tidak cocok", proses ubah kata sandi tidak bisa dilanjut  
**Hasil Sebenarnya**: Sistem berhasil menampilkan pesan error "Kata sandi baru tidak cocok", proses ubah kata sandi tidak bisa dilanjut
