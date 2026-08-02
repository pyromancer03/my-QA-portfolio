# Test Case Pada Modul Login
Pengujian fitur pada modul login yang bertujuan untuk memastikan fitur yang mencakup proses login dapat berjalan dengan baik dan lancar sesuai dengan requirement

## TK-T1
**Test Case**: Login dengan no HP terdaftar  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Memiliki akun terdaftar
- No hp aktif

**Langkah Pengujian**:

1. Buka website
2. Klik "Login"
2. Masukkan nomor hp
3. Klik "Selanjutnya"
4. Masukkan kode verifikasi (6 digit pin tokopedia)

**Data Uji**:  
No HP: 081380065633  
**Hasil yang Diharapkan**:
- Akun user tervalidasi sudah terdaftar
- User diarahkan ke halaman utama tokopedia

**Hasil Sebenarnya**: Akun berhasil divalidasi, user berhasil login ke halaman utama

## TK-T2
**Test Case**: Login dengan akun yang belum terdaftar  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Test Case**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Memiliki no hp atau email yang belum terdaftar

**Langkah Pengujian**:

1. Buka website
2. Klik "Login"
2. Masukkan nomor hp atau email yang belum terdaftar
3. Klik "Selanjutnya"

**Data Uji**:  
No HP: 081380065233  
Email: rizky@gmail.com  
**Hasil yang Diharapkan**:
- Sistem menampilkan pesan error "Nomor HP/Email belum terdaftar" di bawah kolom input no hp/email
- Sistem menampilkan opsi ubah informasi login atau daftar akun
- User tidak bisa melanjutkan proses login dengan no hp/email yang belum terdaftar

**Hasil Sebenarnya**: Sistem berhasil menampilkan pesan error, sistem berhasil memberikan opsi, user tidak bisa lanjut proses login

## TK-T3
**Test Case**: Checklist ingat saya  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Email sudah didaftarkan

**Langkah Pengujian**:

1. Buka website
2. Masukkan email yang terdaftar
3. Klik "Selanjutnya"
4. Masukkan kata sandi
5. Centang "Ingat saya"
6. Klik "Masuk"

**Data Uji**:  
Email: rizky03@gmail.com  
**Hasil yang Diharapkan**:
- Token akun akan tersimpan
- User berhasil login

**Hasil Sebenarnya**: Sistem berhasil menyimpan token akun, user berhasil login

## TK-T4
**Test Case**: Login dengan QR Code  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Akun yang sama sudah login di handphone
- Perangkat handphone tersedia

**Langkah Pengujian**:

1. Buka website
2. Klik "Masuk"
3. Klik "Scan QR code"
4. Lakukan scan pada QR code yang muncul
6. Klik "Ya, lanjut masuk" pada tampilan handphone

**Hasil yang Diharapkan**:
- User login dengan akun yang sama di handphone
- User diarahkan ke halaman utama website

**Hasil Sebenarnya**: User berhasil login dengan akun yang sama di handphone, user berhasil masuk ke halaman utama

## TK-T5
**Test Case**: Login dengan akun Google  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Memiliki akun google yang masih aktif

**Langkah Pengujian**:

1. Buka website
2. Klik ​"Masuk"
3. Klik "Metode lain"
4. Klik ​"Google"
5. Pilih akun google dari tampilan pop up
6. Masukkan kode verifikasi yang dikirim ke alamat email

**Hasil yang Diharapkan**:
- User bisa login menggunakan akun google
- User akan diarahkan ke halaman utama website

**Hasil Sebenarnya**: User berhasil login, user berhasil masuk ke halaman utama

## TK-T7
**Test Case**: Login dengan email terdaftar  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Memiliki akun terdaftar

**Langkah Pengujian**:

1. Buka website
2. Klik "Masuk"
3. Masukkan email terdaftar
4. Klik "Selanjutnya"
5. Masukkan kata sandi
6. Klik "Masuk"

**Data Uji**:  
Email: rizky03@gmail.com  
Kata Sandi: rizkyf03  
**Hasil yang Diharapkan**:
- Akun user tervalidasi sudah terdaftar
- User diarahkan ke halaman utama tokopedia

**Hasil Sebenarnya**: Akun berhasil divalidasi, user berhasil login ke halaman utama

## TK-T8
**Test Case**: Format No HP atau Email tidak sesuai  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. Klik "Masuk"
3. Masukkan format no hp atau email yang tidak sesuai

**Data Uji**:  
No HP: 0813800  
Email: rizky03@gmail    
**Hasil yang Diharapkan**:
- Tombol "Selanjutnya" akan disabled
- User tidak bisa lanjut proses login

**Hasil Sebenarnya**: Tombol berhasil disabled, user tidak bisa login

## TK-T9
**Test Case**: No HP atau email kosong   
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Low  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. Klik "Masuk"
3. Kosongkan kolom input no hp atau email

**Hasil yang Diharapkan**:
- Tombol "Selanjutnya" akan disabled
- User tidak bisa lanjut proses login

**Hasil Sebenarnya**: Tombol berhasil disabled, user tidak bisa login

## TK-T10
**Test Case**: No HP kurang dari 8 karakter  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. K​lik "Masuk"
3. Masukkan no hp kurang dari 8 karakter

**Data Uji**:  
No HP: 081350  
**Hasil yang Diharapkan**:
- Tombol "Selanjutnya" akan disabled
- User tidak bisa lanjut proses login

**Hasil Sebenarnya**: Tombol berhasil disabled, user tidak bisa login

## TK-T11
**Test Case**: No HP lebih dari 15 karakter  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka website
2. K​lik "Masuk"
3. Masukkan no hp lebih dari 15 karakter

**Data Uji**:  
No HP: 08138006580025466  
**Hasil yang Diharapkan**:
- Tombol "Selanjutnya" akan disabled
- User tidak bisa lanjut proses login

**Hasil Sebenarnya**: Tombol berhasil disabled, user tidak bisa login

## TK-T12
**Test Case**: Refresh halaman setelah login  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Memiliki akun terdaftar

**Langkah Pengujian**:

1. Login ke website
2. Lakukan refresh halaman setelah login

**Hasil yang Diharapkan**:
- Akun yang telah login tidak logout saat halaman direfresh
- Sistem dapat menyimpan informasi akun yang login

**Hasil Sebenarnya**: Akun tidak terlogout, informasi akun tersimpan

## TK-T13
**Test Case**: Login di 2 tab browser sekaligus dengan akun yang sama  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Memiliki akun terdaftar
- Membuka 2 tab browser

**Langkah Pengujian**:

1. La​kukan login di tab 1
2. Lakukan login di tab 2

**Hasil yang Diharapkan**:
- User tetap bisa login pada 2 tab browser dengan akun yang sama
- Tidak terjadi bentrok pada sistem
- Salah satu tab browser tidak terlogout

**Hasil Sebenarnya**: User bisa login di 2 tab browser, sistem tidak bentrok, akun tidak terlogout

## TK-T14
**Test Case**: Keluar akun  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Akun telah login
- Berada di halaman manapun yang menampilkan menu akun profil di bagian atas website

**Langkah Pengujian**:

1. Hover cursor ke ikon profile
2. Klik ​"Keluar"
3. Klik "Nanti Saja" pada pop up konfirmasi

**Hasil yang Diharapkan**:
- User bisa logout
- User akan diarahkan ke halaman login

**Hasil Sebenarnya**: User berhasil logout, user berhasil diarahkan ke menu login

## TK-T15
**Test Case**: Email case insensitive  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Memiliki akun terdaftar

**Langkah Pengujian**:

1. Bu​ka website
2. Klik "Masuk"
3. Masukkan email terdaftar dengan kombinasi huruf kecil dan huruf besar
4. Klik "Selanjutnya"
5. Masukkan kata sandi
6. Klik "Masuk"

**Data Uji**:  
Email: Rizky03@Gmail.com  
Kata Sandi: rizkyf03  
**Hasil yang Diharapkan**:
- Sistem dapat mengenali dan menerima karakter email kombinasi huruf kecil dan huruf besar
- User berhasil login ke website
- User diarahkan ke halaman utama website

**Hasil Sebenarnya**: Sistem menerima karakter kombinasi huruf kecil dan huruf besar, user berhasil login, user diarahkan ke halaman utama

## TK-T16
**Test Case**: Password case sensitive  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Test Case**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Memiliki akun terdaftar
- Kata sandi sebenarnya "rizkyf03"

**Langkah Pengujian**:

1. Bu​ka website
2. Klik "Masuk"
3. Masukkan email terdaftar
4. Klik "Selanjutnya"
5. Masukkan password dengan kombinasi huruf besar dan kecil
6. Klik "Masuk"

**Data Uji**:  
Email: rizky03@gmail.com  
Kata Sandi: RizKY03  
**Hasil yang Diharapkan**:
- Sistem dapat memvalidasi hasil input user
- Sistem menolak karakter yang tidak sesuai
- Sistem menampilkan pesan error "Email atau kata sandi salah"
- User tidak berhasil login

**Hasil Sebenarnya**: Sistem berhasil memvalidasi inputan user, sistem menolak format karakter yang tidak sesuai, sistem menampilkan pesan error, user tidak bisa lanjut login

## TK-T17
**Test Case**: Show/hide kata sandi  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Low  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Bu​ka Website
2. Klik "Masuk"
3. Masukkan email
4. Masukkan kata sandi
5. Klik ikon mata

**Data Uji**:  
Email: rizky03@gmail.com  
Kata Sandi: rizkyf03  
**Hasil yang Diharapkan**:
- Kata sandi dapat dishow/hide
- Proses login dapat dilanjut

**Hasil Sebenarnya**: Kata sandi berhasil dishow/hide, user bisa lanjut login
