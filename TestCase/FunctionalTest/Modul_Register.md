# Test Case Pada Modul Register
Pengujian fitur pada modul register yang bertujuan untuk memastikan fitur yang mencakup proses register dapat berjalan dengan baik dan lancar sesuai dengan requirement

## TK-T6
**Test Case**: Mendaftarkan akun baru  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Belum memiliki akun terdaftar

**Langkah Pengujian**:

1. Buka website
2. Klik "Daftar"
3. Masukkan no hp atau email
4. Klik "Daftar"
5. Klik "Ya, benar"
6. Pilih metode verifikasi
7. Masukkan kode verifikasi
8. Masukkan nama lengkap dan kata sandi
9. Klik "Lanjut"

**Data Uji**:  
No HP: 081380065633  
Email: rizky03@gmail.com  
Nama Lengkap: Rizky F  
Kata Sandi: rizkyf03  
**Hasil yang Diharapkan**:
- User dapat mendaftarkan akun baru
- Informasi akun baru akan tersimpan di sistem
- User berhasil login ke website
- User diarahkan ke halaman utama website

**Hasil Sebenarnya**: User berhasil mendaftarkan akun, akun baru berhasil tersimpan, user berhasil login, user diarahkan ke halaman utama

## TK-T18
**Test Case**: Mendaftarkan akun baru dengan google account  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Belum memiliki akun terdaftar
- Memiliki akun google yang aktif

**Langkah Pengujian**:

1. Buka website
2. Klik ​"Daftar"
3. Klik ​"Google"
4. Pilih akun google
5. Masukkan kode verifikasi

**Hasil yang Diharapkan**:
- User dapat mendaftarkan akun baru dengan akun google
- Informasi akun baru akan tersimpan di sistem
- User berhasil login ke website
- User diarahkan ke halaman utama website

**Hasil Sebenarnya**: User berhasil mendaftarkan akun, akun baru berhasil tersimpan, user berhasil login, user diarahkan ke halaman utama

## TK-T19
**Test Case**: Mendaftarkan akun baru dengan akun yang telah terdaftar  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Memiliki akun yang sudah terdaftar

**Langkah Pengujian**:

1. Buka website
2. Klik "Daftar"
3. Masukkan no hp atau email yang sudah terdaftar
4. Klik "Daftar"

**Data Uji**:  
No HP: 081380065633  
Email: rizky03@gmail.com  
**Hasil yang Diharapkan**:
- Sistem dapat memvalidasi informasi akun yang sudah terdaftar
- Menampilkan pesan "Email sudah terdaftar"
- User diberikan opsi untuk ubah informasi no hp/email atau masuk ke halaman login

**Hasil Sebenarnya**: Sistem berhasil memvalidasi akun yang sudah terdaftar, sistem berhasil menampilkan pesan, user berhasil diberikan opsi untuk login

## TK-T20
**Test Case**: No hp kurang dari 8 karakter  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Test Status**:  Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. Klik "Daftar"
3. Masukkan no hp kurang dari 8 karakter

**Data Uji**:  
No HP: 081350  
**Hasil yang Diharapkan**:
- Sistem dapat memvalidasi jumlah minimal karakter no hp
- Sistem menampilkan pesan "Nomor ponsel terlalu pendek, minimum 8 angka"
- User tidak bisa melanjutkan proses pendaftaran

**Hasil Sebenarnya**: Sistem berhasil memvalidasi hasil input user, sistem berhasil menampilkan pesan, user tidak dapat lanjut pendaftaran

## TK-T21
**Test Case**: No hp lebih dari 15 karakter  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. Klik "Daftar"
3. Masukkan no hp lebih dari 15 karakter

**Data Uji**:  
No HP: 081380065633326449  
**Hasil yang Diharapkan**:
- Sistem dapat memvalidasi jumlah maksimum karakter no hp
- Sistem menampilkan pesan "Nomor ponsel terlalu panjang, maksimum 15 angka"
- User tidak bisa melanjutkan proses pendaftaran

**Hasil Sebenarnya**: Sistem berhasil memvalidasi hasil input user, sistem berhasil menampilkan pesan, user tidak dapat lanjut pendaftaran

## TK-T22
**Test Case**: Memasukkan format email yang tidak sesuai  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. K​lik "Daftar"
3. Masukkan format email yang tidak sesuai

**Data Uji**:  
Email: rizky03@.com  
**Hasil yang Diharapkan**:
- Sistem dapat memvalidasi format email yang tidak sesuai
- Menampilkan pesan "Format email salah"
- User tidak bisa melanjutkan proses pendaftaran

**Hasil Sebenarnya**: Sistem berhasil memvalidasi hasil input user, sistem berhasil menampilkan pesan, user tidak dapat lanjut pendaftaran

## TK-T23
**Test Case**: Mengosongkan field no hp atau email  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. K​lik "Daftar"
3. Kosongkan form no hp atau email

**Hasil yang Diharapkan**:
- Sistem dapat memvalidasi form input yang kosong
- Tombol daftar akan disabled

**Hasil Sebenarnya**: Sistem berhasil memvalidasi form input, tombol daftar disabled

## TK-T24
**Test Case**: Email case insensitive  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada
**Langkah Pengujian**:

1. Buka website
2. K​lik "Daftar"
3. Masukkan email dengan kombinasi huruf kecil dan huruf besar
4. Klik "Daftar"

**Data Uji**:  
Email: Rizky03@Gmail.com  
**Hasil yang Diharapkan**:
- Sistem dapat mengenali dan menerima karakter email kombinasi huruf kecil dan huruf besar
- User dapat melanjutkan proses pendaftaran akun

**Hasil Sebenarnya**: Sistem menerima karakter kombinasi huruf kecil dan huruf besar, user dapat melanjutkan pendaftaran

## TK-T25
**Test Case**: Show/hide kata sandi  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Low  
**Test Status**: Pass  
**Jenis Test**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. Klik "Daftar"
3. Masukkan no hp atau email
4. Klik "Daftar"
5. Klik "Ya, benar"
6. Pilih metode verifikasi
7. Masukkan kode verifikasi
8. Masukkan kata sandi
9. Klik ikon mata

**Data Uji**:  
No HP: 081380065633  
Email: rizky03@gmail.com  
Kata Sandi: rizkyf03  
**Hasil yang Diharapkan**:
- Kata sandi dapat dishow/hide
- User dapat melanjutkan proses pendaftaran akun

**Hasil Sebenarnya**: Kata sandi berhasil dishow/hide, user dapat lanjut pendaftaran

## TK-T26
**Test Case**: Nama lengkap diisi dengan karakter selain alfabet  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Test**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. Klik "Daftar"
3. Masukkan no hp atau email
4. Klik "Daftar"
5. Klik "Ya, benar"
6. Pilih metode verifikasi
7. Masukkan kode verifikasi
8. Masukkan nama lengkap dengan karakter selain alfabet

**Data Uji**:  
No HP: 081380065633  
Email: rizky03@gmail.com  
Nama Lengkap: RizkyF0313  
**Hasil yang Diharapkan**:
- Sistem memvalidasi jenis karakter yang diinput
- Menampilkan pesan "Nama harus mengandung huruf alfabet saja"
- User tidak dapat melanjutkan proses pendaftaran akun

**Hasil Sebenarnya**: Sistem berhasil memvalidasi jenis karakter yang diinput, sistem berhasil menampilkan pesan, user tidak dapat lanjut pendaftaran
