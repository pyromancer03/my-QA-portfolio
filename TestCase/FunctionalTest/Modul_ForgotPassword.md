# Test Case Pada Modul Forgot Password
Pengujian fitur pada modul forgot password yang bertujuan untuk memastikan fitur yang mencakup proses forgot password dapat berjalan dengan baik dan lancar sesuai dengan requirement

## TK-T27
**Test Case**: Ubah kata sandi baru  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- No hp/email sudah terdaftar
- No hp atau email aktif

**Langkah Pengujian**:

1. Buka website
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
**Hasil yang Diharapkan**:
- User berhasil ubah kata sandi baru
- Kata sandi lama sudah tidak valid
- User bisa login menggunakan kata sandi baru

**Hasil Sebenarnya**: Kata sandi baru berhasil diubah, kata sandi lama tidak valid, user berhasil login kembali

## TK-T28
**Skenario**: No HP kurang dari 8 karakter  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. Klik "Masuk"
3. Klik ​"Lupa kata sandi?"
4. Masukkan no hp kurang dari 8 karakter
5. Klik "Lanjut"

**Data Uji**:  
No HP: 081350  
**Hasil yang Diharapkan**:
- Website dapat memvalidasi minimum no hp dari hasil input user
- Menampilkan pesan error "Nomor ponsel terlalu pendek, minimum 8 angka" di bawah kolom input no hp
- User tidak bisa lanjut proses ubah kata sandi

**Hasil Sebenarnya**: Validasi sistem berhasil, website berhasil menampilkan pesan error, user tidak bisa lanjut ubah kata sandi

## TK-T29
**Test Case**: No HP lebih dari 15 karakter  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. Klik "Masuk"
3. Klik ​"Lupa kata sandi?"
4. Masukkan no hp lebih dari 15 karakter
5. Klik "Lanjut"

**Data Uji**:  
No HP: 0813800546584848485415  
**Hasil yang Diharapkan**:
- Website dapat memvalidasi maksimum no hp dari hasil input user
- Menampilkan pesan error "Nomor ponsel terlalu panjang, maksimum 15 angka" di bawah kolom input no hp
- User tidak bisa lanjut proses ubah kata sandi

**Hasil Sebenarnya**: Validasi sistem berhasil, website berhasil menampilkan pesan error, user tidak bisa lanjut ubah kata sandi

## TK-T30
**Test Case**: Memasukkan format email yang tidak sesuai  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. Klik "Masuk"
3. Klik "Lupa kata sandi"
4. Masukkan email dengan format yang tidak sesuai
5. Klik "Lanjut"

**Data Uji**:  
Email: rizky@com  
**Hasil yang Diharapkan**:
- Website dapat memvalidasi format email dari hasil input user
- Menampilkan pesan error "Format email salah" di bawah kolom input email
- User tidak bisa lanjut proses ubah kata sandi

**Hasil Sebenarnya**: Validasi sistem berhasil, website berhasil menampilkan pesan error, user tidak bisa lanjut ubah kata sandi

## TK-T31
**Test Case**: Memasukkan No HP atau email yang belum terdaftar  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. Klik "Masuk"
3. Klik "Lupa kata sandi?"
4. Masukkan no hp atau email yang tidak terdaftar
5. Klik ​"Lanjut"

**Data Uji**:  
No HP: 081380054545
Email: rizkyf@gmail.com  
**Hasil yang Diharapkan**:
- Website dapat memvalidasi no hp atau email dari hasil input user
- Menampilkan pesan error "Email atau nomor telepon tidak terdaftar" di bawah kolom input no hp atau email
- User tidak bisa lanjut proses ubah kata sandi  

**Hasil Sebenarnya**: Validasi sistem berhasil, website berhasil menampilkan pesan error, user tidak bisa lanjut ubah kata sandi

## TK-T32
**Test Case**: Show/hide kata sandi  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Low  
**Test Status**: Pass
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Memiliki akun terdaftar

**Langkah Pengujian**:

1. Buka website
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
**Hasil yang Diharapkan**:
- Kata sandi dapat dishow/hide
- Proses ubah kata sandi dapat dilanjut

**Hasil Sebenarnya**: Kata sandi berhasil dishow/hide, user bisa lanjut ubah kata sandi

## TK-T33
**Test Case**: Memasukkan kata sandi baru dengan kata sandi lama  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Memiliki kata sandi lama
- Memiliki akun terdaftar

**Langkah Pengujian**:

1. Buka website
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
**Hasil yang Diharapkan**:
- Menampilkan pesan error "Kata sandi baru harus berbeda dengan kata sandi lama"
- Kata sandi baru gagal diubah

**Hasil Sebenarnya**: Sistem berhasil menampilkan pesan error, ubah kata sandi gagal

## TK-T34
**Test Case**: Akun otomatis keluar di semua perangkat ketika ubah kata sandi baru  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Akun yang sama telah login di beberapa perangkat

**Langkah Pengujian**:

1. Buka website
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
**Hasil yang Diharapkan**:
- Sistem berhasil melakukan perubahan kata sandi baru pada akun user
- Sistem akan melakukan logout otomatis pada akun di perangkat lain yang tertaut

**Hasil Sebenarnya**: Kata sandi berhasil diubah, akun berhasil logout di semua perangkat yang tertaut

## TK-T35
**Test Case**: "Kata Sandi Baru" dan "Ketik Ulang Kata Sandi Baru" tidak sama  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Memiliki akun terdaftar
  
**Langkah Pengujian**:

1. Buka website
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
**Hasil yang Diharapkan**:
- Sistem akan menampilkan pesan error "Kata sandi baru tidak cocok"
- User tidak bisa lanjut proses ubah kata sandi
**Hasil Sebenarnya**: Sistem berhasil menampilkan pesan error, proses ubah kata sandi tidak bisa dilanjut
