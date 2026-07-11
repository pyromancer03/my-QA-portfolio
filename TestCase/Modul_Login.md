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
**Hasil Sebenarnya**: User berhasil masuk dengan akun google, user diarahkan ke halaman utama tokopedia4

## TK-T7
**Skenario**: Login dengan email terdaftar  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki akun terdaftar  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Masuk"
3. Masukkan email terdaftar
4. Klik "Selanjutnya"
5. Masukkan kata sandi
6. Klik "Masuk"

**Data Uji**:  
Email: rizky03@gmail.com
Kata Sandi: rizkyf03
**Hasil yang Diharapkan**: User berhasil login, user diarahkan ke halaman utama, token tersimpan  
**Hasil Sebenarnya**: User berhasil login, user diarahkan ke halaman utama, token tersimpan

## TK-T8
**Skenario**: Format No Hp atau Email tidak sesuai  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki akun terdaftar  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Masuk"
3. Masukkan email terdaftar
4. Klik "Selanjutnya"
5. Masukkan kata sandi
6. Klik "Masuk"

**Data Uji**:  
Email: rizky03@gmail.com
Kata Sandi: rizkyf03
**Hasil yang Diharapkan**: User berhasil login, user diarahkan ke halaman utama, token tersimpan  
**Hasil Sebenarnya**: User berhasil login, user diarahkan ke halaman utama, token tersimpan

## TK-T9
**Skenario**: No HP atau email kosong   
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Low  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
2. Klik "Masuk"
3. Kosongkan no hp atau email

**Hasil yang Diharapkan**: Tombol selanjutnya akan disabled jika form tidak diisi dan tidak bisa lanjut proses login  
**Hasil Sebenarnya**: Tombol selanjutnya akan disabled jika form tidak diisi dan tidak bisa lanjut proses login

## TK-T10
**Skenario**: No HP kurang dari 8 karakter  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
2. K​lik masuk
3. Masukkan no hp kurang dari 8 karakter

**Data Uji**:  
No HP: 081350
**Hasil yang Diharapkan**: Tombol selanjutnya akan disabled dan proses login tidak bisa dilanjut  
**Hasil Sebenarnya**: Tombol selanjutnya akan disabled dan proses login tidak bisa dilanjut

## TK-T11
**Skenario**: No HP lebih dari 15 karakter  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Tidak ada  
**Langkah Pengujian**:

1. Buka Website
2. K​lik masuk
3. Masukkan no hp lebih dari 15 karakter

**Data Uji**:  
No HP: 08138006580025466
**Hasil yang Diharapkan**: Tombol selanjutnya akan disabled dan proses login tidak bisa lanjut  
**Hasil Sebenarnya**: Tombol selanjutnya akan disabled dan proses login tidak bisa dilanjut

## TK-T12
**Skenario**: Refresh halaman setelah login  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki akun terdaftar  
**Langkah Pengujian**:

1. Login ke Website
2. Lakukan refresh halaman setelah login

**Hasil yang Diharapkan**: Akun yang telah login tidak keluar saat halaman direfresh, sistem dapat menyimpan informasi akun yang login pada saat halaman direfresh  
**Hasil Sebenarnya**: Akun yang telah login tidak keluar saat halaman direfresh, sistem dapat menyimpan informasi akun yang login pada saat halaman direfresh

## TK-T13
**Skenario**: Login di 2 tab browser sekaligus dengan akun yang sama  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki akun terdaftar  
**Langkah Pengujian**:

1. La​kukan login di tab 1
2. Lakukan login di tab 2

**Hasil yang Diharapkan**: User tetap bisa menggunakan 2 tab browser dengan akun yang sama, tidak terjadi bentrok antar akun yang sama pada sistem  
**Hasil Sebenarnya**: User tetap bisa menggunakan 2 tab browser dengan akun yang sama, tidak terjadi bentrok antar akun yang sama pada sistem

## TK-T14
**Skenario**: Keluar akun  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Sudah login  
**Langkah Pengujian**:

1. Login akun di Website
2. Hover cursor ke ikon profile
3. Klik ​"Keluar"

**Hasil yang Diharapkan**: Akun user berhasil keluar/logout  
**Hasil Sebenarnya**: Akun user berhasil keluar/logout

## TK-T15
**Skenario**: Email case insensitive  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki akun terdaftar  
**Langkah Pengujian**:

1. Bu​ka Website
2. Klik "Masuk"
3. Masukkan email terdaftar dengan kombinasi huruf kecil dan huruf besar
4. Klik "Selanjutnya"
5. Masukkan kata sandi
6. Klik "Masuk"

**Data Uji**:  
Email: Rizky03@Gmail.com
Kata Sandi: rizkyf03
**Hasil yang Diharapkan**: Sistem dapat mengenali dan menerima karakter email kombinasi huruf kecil dan huruf besar, user berhasil login dan diarahkan ke halaman utama website tokopedia  
**Hasil Sebenarnya**: Sistem dapat mengenali dan menerima karakter email kombinasi huruf kecil dan huruf besar, user berhasil login dan diarahkan ke halaman utama website tokopedia

## TK-T16
**Skenario**: Password case sensitive  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki akun terdaftar, password sebenarnya "rizkyf03"  
**Langkah Pengujian**:

1. Bu​ka Website
2. Klik "Masuk"
3. Masukkan email terdaftar
4. Klik "Selanjutnya"
5. Masukkan password dengan kombinasi huruf besar dan kecil
6. Klik "Masuk"

**Data Uji**:  
Email: rizky03@gmail.com
Kata Sandi: RizKY03
**Hasil yang Diharapkan**: Sistem dapat memvalidasi case sensitive pada password dan muncul pesan error "Email atau kata sandi salah", user gagal login  
**Hasil Sebenarnya**: Sistem dapat memvalidasi case sensitive pada password dan muncul pesan error "Email atau kata sandi salah", user gagal login
**Catatan**: Pesan error tidak spesifik dan masih bersifat umum. Pesan error mungkin bisa dibuat lebih spesifik lagi pada tahap UX

## TK-T17
**Skenario**: Show/hide kata sandi  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Low  
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
**Hasil yang Diharapkan**: Kata sandi dapat dishow/hide dan user dapat melanjutkan proses login  
**Hasil Sebenarnya**: Kata sandi dapat dishow/hide dan user dapat melanjutkan proses login
