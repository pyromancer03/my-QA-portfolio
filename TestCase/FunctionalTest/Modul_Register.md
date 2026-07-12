# Test Case Pada Modul Register
Pengujian fitur pada modul register yang bertujuan untuk memastikan fitur yang mencakup proses register dapat berjalan dengan baik dan lancar sesuai dengan requirement

## TK-T6
**Skenario**: Mendaftarkan akun baru  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Belum mendaftarkan akun  
**Langkah Pengujian**:

1. Buka Website
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
**Hasil yang Diharapkan**: Sistem berhasil menyimpan informasi akun baru yang didaftarkan, user berhasil mendaftarkan akun baru  
**Hasil Sebenarnya**: Sistem berhasil menyimpan informasi akun baru yang didaftarkan, user berhasil mendaftarkan akun baru

## TK-T18
**Skenario**: Mendaftarkan akun baru dengan google account  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Belum mendaftarkan akun  
**Langkah Pengujian**:

1. Buka Website
2. Klik ​"Daftar"
3. Klik ​"Google"
4. Pilih akun google
5. Masukkan kode verifikasi

**Hasil yang Diharapkan**: User berhasil mendaftarkan akun baru dengan google account, user diarahkan ke halaman utama  
**Hasil Sebenarnya**: User berhasil mendaftarkan akun baru dengan google account, user diarahkan ke halaman utama

## TK-T19
**Skenario**: Mendaftarkan akun baru dengan akun yang telah terdaftar  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki akun terdaftar  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Daftar"
3. Masukkan no hp atau email yang sudah terdaftar
4. Klik "Daftar"

**Data Uji**:  
No HP: 081380065633  
Email: rizky03@gmail.com  
**Hasil yang Diharapkan**: Sistem dapat mengenali no hp atau email yang telah terdaftar, muncul pop up "Email sudah terdaftar" dan user diberikan pilihan untuk ubah informasi no hp/email atau masuk dengan no hp/email tersebut  
**Hasil Sebenarnya**: Sistem dapat mengenali no hp atau email yang telah terdaftar, muncul pop up "Email sudah terdaftar" dan user diberikan pilihan untuk ubah informasi no hp/email atau masuk dengan no hp/email tersebut

## TK-T20
**Skenario**: No hp kurang dari 8 karakter  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Daftar"
3. Masukkan no hp kurang dari 8 karakter

**Data Uji**:  
No HP: 081350  
**Hasil yang Diharapkan**: Sistem dapat memvalidasi jumlah minimal karakter no hp, muncul pesan error di bawah form no hp "Nomor ponsel terlalu pendek, minimum 8 angka"  
**Hasil Sebenarnya**: Sistem dapat memvalidasi jumlah minimal karakter no hp, muncul pesan error di bawah form no hp "Nomor ponsel terlalu pendek, minimum 8 angka"

## TK-T21
**Skenario**: No hp lebih dari 15 karakter  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Daftar"
3. Masukkan no hp lebih dari 15 karakter

**Data Uji**:  
No HP: 081380065633326449  
**Hasil yang Diharapkan**: Sistem dapat memvalidasi jumlah maksimal karakter no hp, muncul pesan error di bawah form no hp "Nomor ponsel terlalu panjang, maksimum 15 angka"  
**Hasil Sebenarnya**: Sistem dapat memvalidasi jumlah maksimal karakter no hp, muncul pesan error di bawah form no hp "Nomor ponsel terlalu panjang, maksimum 15 angka"

## TK-T22
**Skenario**: Memasukkan format email yang tidak sesuai  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
2. K​lik "Daftar"
3. Masukkan format email yang salah

**Data Uji**:  
Email: rizky03@.com  
**Hasil yang Diharapkan**: Sistem dapat memvalidasi format email yang salah/tidak sesuai, muncul pesan error di bawah form email "Format email salah"  
**Hasil Sebenarnya**: Sistem dapat memvalidasi format email yang salah/tidak sesuai, muncul pesan error di bawah form email "Format email salah"

## TK-T23
**Skenario**: Mengosongkan field no hp atau email  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
2. K​lik "Daftar"
3. Kosongkan form no hp atau email

**Hasil yang Diharapkan**: Sistem dapat memvalidasi form input yang kosong, tombol daftar akan disabled  
**Hasil Sebenarnya**: Sistem dapat memvalidasi form input yang kosong, tombol daftar akan disabled

## TK-T24
**Skenario**: Email case insensitive  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
2. K​lik "Daftar"
3. Masukkan email dengan kombinasi lowercase dan uppercase
4. Klik "Daftar"

**Data Uji**:  
Email: Rizky03@Gmail.com  
**Hasil yang Diharapkan**: Sistem dapat mengenali dan menerima karakter email kombinasi huruf kecil dan huruf besar, user dapat melanjutkan proses register akun  
**Hasil Sebenarnya**: Sistem dapat mengenali dan menerima karakter email kombinasi huruf kecil dan huruf besar, user dapat melanjutkan proses register akun

## TK-T25
**Skenario**: Show/hide kata sandi  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Low  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
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
**Hasil yang Diharapkan**: Kata sandi dapat dishow/hide dan user dapat melanjutkan proses register  
**Hasil Sebenarnya**: Kata sandi dapat dishow/hide dan user dapat melanjutkan proses register

## TK-T26
**Skenario**: Nama lengkap diisi dengan karakter selain alfabet  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
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
**Hasil yang Diharapkan**: Sistem berhasil mevalidasi jenis karakter yang diinput, muncul pesan error di bawah form nama lengkap "Nama harus mengandung huruf alfabet saja"  
**Hasil Sebenarnya**: Sistem berhasil mevalidasi jenis karakter yang diinput, muncul pesan error di bawah form nama lengkap "Nama harus mengandung huruf alfabet saja"
