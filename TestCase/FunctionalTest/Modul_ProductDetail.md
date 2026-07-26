# Test Case Pada Modul Product Detail
Pengujian fitur pada modul product detail yang bertujuan untuk memastikan fitur yang mencakup proses product detail dapat berjalan dengan baik dan lancar sesuai dengan requirement

## TK-T60
**Test Case**: Menampilkan detail produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada pada halaman hasil pencarian produk "Laptop Asus Vivobook Go 14"
- Stok produk masih tersedia

**Langkah Pengujian**:

1. Klik pada salah satu thumbnail produk yang tersedia

**Hasil yang Diharapkan**:
- Sistem menampilkan halaman detail produk (nama produk, varian yang tersedia, harga produk, stok produk, deskripsi, spesifikasi, ulasan)

**Hasil Sebenarnya**: Sistem berhasil menampilkan halaman detail produk

## TK-T61
**Test Case**: Ulasan produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada pada halaman detail produk "Laptop Asus Vivobook Go 14"

**Langkah Pengujian**:

1. Klik menu ulasan pada detail produk atau scroll ke bawah

**Hasil yang Diharapkan**:
- User dapat melihat ulasan dari pembeli terkait produk

**Hasil Sebenarnya**: Sistem berhasil menampilkan ulasan produk pembeli

## TK-T62
**Test Case**: Memilih variant/spesifikasi produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada pada halaman detail produk "Laptop Asus Vivobook Go 14"
- Stok produk masih tersedia

**Langkah Pengujian**:

1. Tentukan varian/spesifikasi produk

**Hasil yang Diharapkan**:
- Varian produk dapat ditampilkan (jika tersedia)
- Varian produk dapat dipilih oleh user

**Hasil Sebenarnya**: Varian produk berhasil tampil dan dapat dipilih

## TK-T63
**Test Case**: Menampilkan harga produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada pada halaman detail produk "Laptop Asus Vivobook Go 14"
- Stok produk masih tersedia 

**Langkah Pengujian**:

1. Tentukan varian/spesifikasi produk
2. Masukkan quantity produk (Misalnya 5 item)

**Hasil yang Diharapkan**:
- Varian produk dapat ditampilkan (jika tersedia)
- Varian produk dapat dipilih oleh user
- Quantity produk dapat diisi sesuai stok yang tersedia
- Harga produk ditampilkan berdasarkan hasil pilihan varian dan quantity produk

**Hasil Sebenarnya**: Varian produk berhasil tampil dan dapat dipilih, quantity produk dapat diisi, harga produk berhasil dikalkulasikan dan ditampilkan

## TK-T64
**Test Case**: Memilih variant/spesifikasi produk yang stoknya sudah habis  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada pada halaman detail produk "Laptop Asus Vivobook Go 14"
- Stok beberapa varian produk sudah habis

**Langkah Pengujian**:

1. Pilih varian/spesifikasi produk yang stoknya sudah habis

**Hasil yang Diharapkan**:
- Menampilkan pesan error "Stok varian ini habis"
- Menampilkan jumlah stok produk 0
- Sistem memberikan pilihan "Ingatkan saya" jika stok kembali tersedia
- Produk tidak bisa ditambahkan ke keranjang

**Hasil Sebenarnya**: Sistem berhasil menampilkan pesan error, menampilkan stok produk 0, sistem memberikan pengingat saat produk tersedia, produk tidak bisa ditambahkan ke keranjang

## TK-T65
**Test Case**: Isi quantity produk 0  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada pada halaman detail produk "Laptop Asus Vivobook Go 14"
- Stok produk masih tersedia

**Langkah Pengujian**:

1. Masukkan quantity produk ke 0

**Hasil yang Diharapkan**:
- Menampilkan pesan error "Minimal pembelian produk ini adalah 1 barang"
- Quantity otomatis akan berubah ke 1 (Tergantung minimal jumlah pembelian produk) jika cursor diklik di area kosong pada website

**Hasil Sebenarnya**: Sistem berhasil menampilkan pesan error, quantity akan terisi minimal jumlah pembelian produk

## TK-T66
**Test Case**: Bagikan link produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada pada halaman detail produk "Laptop Asus Vivobook Go 14"

**Langkah Pengujian**:

1. Klik "Share"
2. Klik "Salin link" atau platform lainnya

**Hasil yang Diharapkan**:
- Muncul pesan pop up "Link tersalin"
- Link produk akan tersalin di clipboard perangkat

**Hasil Sebenarnya**: Sistem berhasil menampilkan pesan pop up, link produk berhasil disalin

## TK-T67
**Test Case**: Isi quantity produk melebihi stok  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada pada halaman detail produk "Laptop Asus Vivobook Go 14"
- Stok produk masih tersedia min 1

**Langkah Pengujian**:

1. Masukkan quantity produk melebihi stok yang tersedia

**Hasil yang Diharapkan**:
- Menampilkan pesan error "Maks. pembelian barang ini '...' item, kurangi pembelianmu, ya!" (Tergantung maksimum stok yang tersedia)
- Quantity otomatis akan berubah ke maksimal stok yang tersedia jika cursor diklik di area kosong pada website

**Hasil Sebenarnya**: Sistem berhasil menampilkan pesan error, quantity berhasil berubah otomatis

## TK-T68
**Test Case**: Tanya produk ke penjual  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada pada halaman detail produk "Laptop Asus Vivobook Go 14"

**Langkah Pengujian**:

1. Tentukan varian/spesifikasi produk
2. Kli​k "Chat"

**Hasil yang Diharapkan**:
- User dapat membuka room chat kepada penjual
- Jenis produk yang pilih sebelumnya otomatis akan terkirim ke penjual ketika obrolan dimulai

**Hasil Sebenarnya**: Chat room kepada penjual berhasil terbuka, jenis produk yang dipilih berhasil terkirim ke penjual sebagai topik pertanyaan
