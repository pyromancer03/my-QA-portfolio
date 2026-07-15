# Test Case Pada Modul Product Detail
Pengujian fitur pada modul product detail yang bertujuan untuk memastikan fitur yang mencakup proses product detail dapat berjalan dengan baik dan lancar sesuai dengan requirement

## TK-T60
**Skenario**: Menampilkan detail produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman hasil pencarian "Asus Vivobook Go 14"  
**Langkah Pengujian**:

1. Klik thumbnail produk

**Hasil yang Diharapkan**: Sistem akan menampilkan detail produk  
**Hasil Sebenarnya**: Sistem akan menampilkan detail produk

## TK-T61
**Skenario**: Ulasan produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman hasil pencarian "Asus Vivobook Go 14"  
**Langkah Pengujian**:

1. Klik thumbnail produk
2. Klik tab "Ulasan"

**Hasil yang Diharapkan**: Sistem menampilkan ulasan produk dari pembeli  
**Hasil Sebenarnya**: Sistem menampilkan ulasan produk dari pembeli

## TK-T62
**Skenario**: Memilih variant/spesifikasi produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman hasil pencarian "Asus Vivobook Go 14"  
**Langkah Pengujian**:

1. Klik thumbnail produk
2. Pilih variant/spesifikasi produk

**Hasil yang Diharapkan**: Harga produk berubah sesuai variant/spesifikasi produk yang dipilih  
**Hasil Sebenarnya**: Harga produk berubah sesuai variant/spesifikasi produk yang dipilih

## TK-T63
**Skenario**: Menampilkan harga produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman hasil pencarian "Asus Vivobook Go 14"  
**Langkah Pengujian**:

1. Klik thumbnail produk

**Hasil yang Diharapkan**: Sistem menampilkan harga produk yang dipilih  
**Hasil Sebenarnya**: Sistem menampilkan harga produk yang dipilih

## TK-T64
**Skenario**: Memilih variant/spesifikasi produk yang stoknya sudah habis  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman hasil pencarian "Asus Vivobook Go 14"  
**Langkah Pengujian**:

1. Klik thumbnail produk
2. Pilih variant/spesifikasi produk yang stoknya sudah habis

**Hasil yang Diharapkan**: Menampilkan pesan "Stok varian ini habis", label quantity produk 0, produk tidak bisa ditambahkan ke keranjang  
**Hasil Sebenarnya**: Menampilkan pesan "Stok varian ini habis", label quantity produk 0, produk tidak bisa ditambahkan ke keranjang

## TK-T65
**Skenario**: Isi quantity produk 0  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman hasil pencarian "Asus Vivobook Go 14"  
**Langkah Pengujian**:

1. Klik thumbnail produk
2. Atur quantity produk ke 0

**Hasil yang Diharapkan**: Sistem menampilkan pesan error "Minimal pembelian produk ini adalah 1 barang"  
**Hasil Sebenarnya**: Sistem menampilkan pesan error "Minimal pembelian produk ini adalah 1 barang"

## TK-T66
**Skenario**: Bagikan link produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman hasil pencarian "Asus Vivobook Go 14"  
**Langkah Pengujian**:

1. Klik thumbnail produk
2. Klik "Share"
3. Klik "Salin link"

**Hasil yang Diharapkan**: Muncul pop up "Link tersalin", link produk berhasil tersalin  
**Hasil Sebenarnya**: Muncul pop up "Link tersalin", link produk berhasil tersalin

## TK-T67
**Skenario**: Isi quantity produk melebihi stok  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman hasil pencarian "Asus Vivobook Go 14"  
**Langkah Pengujian**:

1. Klik thumbnail produk
2. Masukkan quantity produk melebihi stok yang tersedia

**Hasil yang Diharapkan**: Muncul pesan error "Maks. pembelian barang ini '...' item, kurangi pembelianmu, ya!", quantity produk akan terisi ke maksimal jumlah stok yang tersedia secara otomatis jika cursor diklik di area kosong  
**Hasil Sebenarnya**: Muncul pesan error "Maks. pembelian barang ini '...' item, kurangi pembelianmu, ya!", quantity produk akan terisi ke maksimal jumlah stok yang tersedia secara otomatis jika cursor diklik di area kosong

## TK-T68
**Skenario**: Tanya produk ke penjual  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman hasil pencarian "Asus Vivobook Go 14"  
**Langkah Pengujian**:

1. Klik thumbnail produk
2. Kli​k "Chat"

**Hasil yang Diharapkan**: Chat room ke penjual akan dimulai, etalase produk akan terpilih di chat room  
**Hasil Sebenarnya**: Chat room ke penjual akan dimulai, etalase produk akan terpilih di chat room
