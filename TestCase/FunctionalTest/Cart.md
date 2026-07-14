# Test Case Pada Modul Cart
Pengujian fitur pada modul cart yang bertujuan untuk memastikan fitur yang mencakup proses cart dapat berjalan dengan baik dan lancar sesuai dengan requirement

## TK-T46
**Skenario**: Menambahkan produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: User sudah login  
**Langkah Pengujian**:

1. Cari produk
2. K​​​​​lik thumbnail produk
3. Tentukan spesifikasi produk (jika tersedia)
4. Masukkan quantity produk
5. Klik "Keranjang"

**Data Uji**:  
Produk: Asus Vivobook Go 14  
**Hasil yang Diharapkan**: Muncul pop up "Berhasil ditambahkan", produk berhasil ditambahkan ke cart  
**Hasil Sebenarnya**: Muncul pop up "Berhasil ditambahkan", produk berhasil ditambahkan ke cart

## TK-T47
**Skenario**: Menambahkan produk yang sama di toko yang sama  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki produk yang sama di cart dan berada pada halaman produk di toko yang sama  
**Langkah Pengujian**:

1. Isi spesifikasi produk yang sama
3. Masukkan quantity produk
4. Klik "Keranjang"
  
**Hasil yang Diharapkan**: Muncul pop up "Berhasil ditambahkan", produk berhasil ditambahkan ke cart, quantity produk yang sama bertambah, tidak membuat list produk baru jika di toko yang sama  
**Hasil Sebenarnya**: Muncul pop up "Berhasil ditambahkan", produk berhasil ditambahkan ke cart, quantity produk yang sama bertambah, tidak membuat list produk baru jika di toko yang sama

## TK-T48
**Skenario**: Menambahkan produk yang sama namun dengan spesifikasi produk berbeda  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki produk yang sama di cart dan berada pada halaman produk di toko yang sama  
**Langkah Pengujian**:

1. Isi spesifikasi produk yang berbeda
3. Masukkan quantity produk
4. Klik "Keranjang"
  
**Hasil yang Diharapkan**: Muncul pop up "Berhasil ditambahkan", produk berhasil ditambahkan ke cart, produk yang sama tetap berada pada grup toko yang sama  
**Hasil Sebenarnya**: Muncul pop up "Berhasil ditambahkan", produk berhasil ditambahkan ke cart, produk yang sama tetap berada pada grup toko yang sama

## TK-T49
**Skenario**: Menambahkan quantity produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki produk di cart  
**Langkah Pengujian**:

1. Buka menu cart
2. Klik "+" pada produk
  
**Hasil yang Diharapkan**: Quantity produk bertambah +1  
**Hasil Sebenarnya**: Quantity produk bertambah +1

## TK-T50
**Skenario**: Mengurangi quantity produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki quantity produk >1 di cart  
**Langkah Pengujian**:

1. Buka menu cart
2. Klik "-" pada produk
  
**Hasil yang Diharapkan**: Quantity produk berhasil dikurangi -1  
**Hasil Sebenarnya**: Quantity produk berhasil dikurangi -1

## TK-T51
**Skenario**: Menghapus produk dari cart  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki produk di cart  
**Langkah Pengujian**:

1. Buka menu cart
2. Klik ikon hapus pada produk
  
**Hasil yang Diharapkan**: Produk berhasil terhapus dari cart  
**Hasil Sebenarnya**: Produk berhasil terhapus dari cart

## TK-T52
**Skenario**: Mengubah quantity produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki produk di cart  
**Langkah Pengujian**:

1. Buka menu cart
2. Isi manual quantity pada produk
  
**Hasil yang Diharapkan**: Quantity produk berhasil diubah sesuai dengan angka yang dimasukkan  
**Hasil Sebenarnya**: Quantity produk berhasil diubah sesuai dengan angka yang dimasukkan

## TK-T53
**Skenario**: Menambahkan quantity produk melebihi stok  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki produk di cart  
**Langkah Pengujian**:

1. Buka menu cart
2. Isi quantity melebihi stok toko
  
**Hasil yang Diharapkan**: Sistem otomatis mengisi quantity produk ke jumlah maksimal produk yang sedang tersedia  
**Hasil Sebenarnya**: Sistem otomatis mengisi quantity produk ke jumlah maksimal produk yang sedang tersedia

## TK-T54
**Skenario**: Isi 0 pada quantity produk  
**Jenis Pendekatan**: Negative Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki produk di cart  
**Langkah Pengujian**:

1. Buka menu cart
2. Isi quantity produk menjadi 0
  
**Hasil yang Diharapkan**: Sistem menampilkan pesan error "Min. beli 1", quantity produk otomatis terisi 1  
**Hasil Sebenarnya**: Sistem menampilkan pesan error "Min. beli 1", quantity produk otomatis terisi 1

## TK-T55
**Skenario**: Memilih beberapa produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki beberapa produk di cart  
**Langkah Pengujian**:

1. Buka menu cart
2. Klik checkbox pada beberapa produk
  
**Hasil yang Diharapkan**: Beberapa produk dapat diselect/dipilih  
**Hasil Sebenarnya**: Beberapa produk dapat diselect/dipilih

## TK-T56
**Skenario**: Menghapus beberapa produk sekaligus  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki beberapa produk di cart  
**Langkah Pengujian**:

1. Buka menu cart
2. Centang pada beberapa produk
3. Klik "Hapus"
4. Klik "Hapus" pada pop up
  
**Hasil yang Diharapkan**: Produk yang dipilih berhasil terhapus dari cart  
**Hasil Sebenarnya**: Produk yang dipilih berhasil terhapus dari cart

## TK-T57
**Skenario**: Menampilkan total harga produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Memiliki beberapa produk di cart  
**Langkah Pengujian**:

1. Buka menu cart
2. Centang pada beberapa produk
  
**Hasil yang Diharapkan**: Menampilkan total harga produk yang dicentang  
**Hasil Sebenarnya**: Menampilkan total harga produk yang dicentang
