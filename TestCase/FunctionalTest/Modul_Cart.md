# Test Case Pada Modul Cart
Pengujian fitur pada modul cart yang bertujuan untuk memastikan fitur yang mencakup proses cart dapat berjalan dengan baik dan lancar sesuai dengan requirement

## TK-T46
**Test Case**: Menambahkan produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:  
- User sudah login
- User berada di halaman detail produk
- Stok produk tersedia

**Langkah Pengujian**:

1. Pilih varian/spesifikasi produk (jika tersedia)
2. Masukkan quantity produk
3. Klik "Keranjang"
4. Buka halaman keranjang

**Hasil yang Diharapkan**:  
- Sistem menampilkan pesan pop up "Berhasil ditambahkan"
- Badge ikon keranjang bertambah
- Produk berhasil masuk dan ditampilkan di keranjang dengan nama, varian, harga, quantity produk yang sesuai

**Hasil Sebenarnya**: Website berhasil menampilkan pesan pop up, badge berhasil bertambah, produk berhasil ditambahkan ke keranjang, informasi produk sudah sesuai

## TK-T47
**Test Case**: Menambahkan produk yang sama dari toko yang sama  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- User sudah login
- User telah menambahkan produk yang sama ke keranjang sebelumnya
- User kembali membuka halaman detail produk yang sama dari toko yang sama
- Stok produk tersedia

**Langkah Pengujian**:

1. Buka kembali halaman detail produk yang sama
2. Pilih varian/spesifikasi produk yang sama
3. Masukkan quantity produk
4. Klik "Keranjang"
5. Buka halaman keranjang
  
**Hasil yang Diharapkan**:
- Sistem menampilkan pesan pop up "Berhasil ditambahkan"
- Badge ikon keranjang bertambah
- Produk berhasil masuk dan ditampilkan di keranjang dengan nama, varian, harga, quantity produk yang sesuai
- Quantity produk dengan varian/spesifikasi yang sama akan bertambah
- Produk yang sama dari toko yang sama ditampilkan dalam satu grup pada halaman keranjang tanpa membuat entri produk baru

**Hasil Sebenarnya**: Website berhasil menampilkan pesan pop up, badge berhasil bertambah, produk berhasil ditambahkan ke keranjang, informasi produk sudah sesuai, quantity produk bertambah, produk yang sama dari toko yang sama tidak membuat list baru

## TK-T48
**Test Case**: Menambahkan produk yang sama dengan varian yang berbeda  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**: 
- User sudah login
- User telah menambahkan produk yang sama ke keranjang sebelumnya
- User kembali membuka halaman detail produk yang sama dari toko yang sama
- Stok produk tersedia
  
**Langkah Pengujian**:

1. Buka kembali halaman detail produk yang sama
2. Pilih varian/spesifikasi produk yang berbeda
3. Masukkan quantity produk
4. Klik "Keranjang"
5. Buka halaman keranjang
  
**Hasil yang Diharapkan**:
- Sistem menampilkan pesan pop up "Berhasil ditambahkan"
- Badge ikon keranjang bertambah
- Produk berhasil masuk dan ditampilkan di keranjang dengan nama, varian, harga, quantity produk yang sesuai
- Produk yang sama dari toko yang sama ditampilkan dalam satu grup pada halaman keranjang dengan membuat entri produk baru

**Hasil Sebenarnya**: Website berhasil menampilkan pesan pop up, badge berhasil bertambah, produk berhasil ditambahkan ke keranjang, informasi produk sudah sesuai, produk yang sama tetap berada pada grup toko yang sama

## TK-T49
**Test Case**: Menambahkan quantity produk di keranjang
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- User sudah login
- User minimal memiliki 1 produk di keranjang
- Stok produk masih tersedia untuk penambahan quantity (lebih dari quantity yang ada di keranjang)

**Langkah Pengujian**:

1. Buka halaman keranjang
3. Klik "+" pada produk
  
**Hasil yang Diharapkan**:
- Quantity produk +1
- Harga produk satuan tetap

**Hasil Sebenarnya**: Quantity produk berhasil bertambah, harga satuan produk tidak berubah

## TK-T50
**Test Case**: Mengurangi quantity produk di keranjang 
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- User sudah login
- User minimal memiliki 1 produk di keranjang
- Quantity produk yang diuji harus > 1

**Langkah Pengujian**:

1. Buka halaman keranjang
2. Klik "-" pada produk
  
**Hasil yang Diharapkan**:
- Quantity produk -1
- Harga produk satuan tetap

**Hasil Sebenarnya**: Quantity produk berhasil berkurang, harga satuan produk tidak berubah

## TK-T51
**Test Case**: Menghapus produk dari keranjang  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- User sudah login
- User minimal memiliki 1 produk di keranjang

**Langkah Pengujian**:

1. Buka halaman keranjang
2. Klik ikon hapus pada produk yang ingin dihapus
  
**Hasil yang Diharapkan**:
- Muncul pesan "Produk telah dihapus"
- Produk terhapus dari keranjang
- Badge ikon keranjang akan berkurang

**Hasil Sebenarnya**: Website berhasil menampilkan pesan yang sesuai, produk berhasil dihapus, badge keranjang berkurang

## TK-T52
**Test Case**: Mengubah quantity produk di keranjang  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- User sudah login
- User minimal memiliki 1 produk di keranjang

**Langkah Pengujian**:

1. Buka halaman keranjang
2. Klik kolom input quantity produk
3. Masukkan nilai secara manual (Misal dari 1 menjadi 7)
4. Klik cursor ke area kosong di website
  
**Hasil yang Diharapkan**:
- Quantity produk berubah mengikuti masukkan dari user
- Nilai quantity produk tidak melebihi stok yang tersedia

**Hasil Sebenarnya**: Quantity produk berhasil diubah sesuai dengan angka yang dimasukkan, nilai quantity tidak melebihi stok

## TK-T53
**Test Case**: Menambahkan quantity produk di keranjang melebihi stok  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- User sudah login
- User minimal memiliki 1 produk di keranjang

**Langkah Pengujian**:

1. Buka halaman keranjang
2. Klik kolom input quantity produk
3. Masukkan nilai melebihi stok yang tersedia
4. Klik cursor ke area kosong di website
  
**Hasil yang Diharapkan**:
- Nilai melebihi stok, otomatis berubah ke nilai maksimal stok yang tersedia
- Menampilkan teks peringatan di bawah kolom input quantity "Maks. beli "batas stok""

**Hasil Sebenarnya**: Quantity otomatis berubah ke maksimal stok tersedia, berhasil menampilkan teks peringatan

## TK-T54
**Test Case**: Isi 0 pada quantity produk di keranjang 
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- User sudah login
- User minimal memiliki 1 produk di keranjang

**Langkah Pengujian**:

1. Buka halaman keranjang
2. Klik kolom input quantity produk
3. Masukkan nilai quantity menjadi 0
4. Klik cursor ke area kosong di website
  
**Hasil yang Diharapkan**:
- Nilai quantity otomatis terisi 1 (Tergantung jumlah minimal pembelian)
- Menampilkan teks peringatan di bawah kolom input quantity "Min. beli 1" (Tergantung jumlah minimal pembelian)

**Hasil Sebenarnya**: Nilai quantity terisi 1, berhasil menampilkan teks peringatan

## TK-T55
**Test Case**: Memilih beberapa produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- User sudah login
- User memiliki >1 produk di keranjang
- Stok produk di keranjang masih tersedia

**Langkah Pengujian**:

1. Buka halaman keranjang
2. Centang beberapa produk yang ada di keranjang
  
**Hasil yang Diharapkan**:
- Produk yang masih tersedia stoknya bisa dicentang
- Produk yang sudah kosong stoknya tidak bisa dipilih
- Total harga produk yang dipilih ditampilkan

**Hasil Sebenarnya**: Produk berhasil dipilih, harga total produk berhasil dikalkulasikan dan ditampilkan

## TK-T56
**Test Case**: Menghapus beberapa produk sekaligus  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- User sudah login
- Memiliki produk >1 di keranjang
- Produk bisa dipilih (Stok produk masih tersedia)

**Langkah Pengujian**:

1. Buka halaman keranjang
2. Centang pada beberapa produk
3. Klik "Hapus"
4. Klik "Hapus" pada pop up konfirmasi
  
**Hasil yang Diharapkan**: 
- Produk yang dipilih terhapus
- Produk yang terhapus tidak tampil di keranjang

**Hasil Sebenarnya**: Produk berhasil terhapus, produk akan hilang dari keranjang

## TK-T57
**Test Case**: Menampilkan total harga produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- User sudah login
- Memiliki produk >1 di keranjang
- Stok produk masih tersedia

**Langkah Pengujian**:

1. Buka halaman keranjang
2. Centang pada beberapa produk
  
**Hasil yang Diharapkan**:
- Total harga produk yang dipilih akan dikalkulasikan dan ditampilkan
- Proses checkout dapat dilanjutkan

**Hasil Sebenarnya**: Total harga produk berhasil tampil, user dapat lanjut proses checkout
