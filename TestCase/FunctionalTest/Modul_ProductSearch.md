# Test Case Pada Modul Product Search
Pengujian fitur pada modul product search yang bertujuan untuk memastikan fitur yang mencakup proses product search dapat berjalan dengan baik dan lancar sesuai dengan requirement

## TK-T36
**Skenario**: Mencari produk di search bar  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman yang memiliki fitur pencarian  
**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk
3. Tekan enter

**Data Uji**:  
Nama Produk: Lemari Pakaian  
**Hasil yang Diharapkan**: Sistem dapat menemukan dan menampilkan produk yang dicari  
**Hasil Sebenarnya**: Sistem dapat menemukan dan menampilkan produk yang dicari

## TK-T37
**Skenario**: Pencarian nama produk salah ketik (typo)  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman yang memiliki fitur pencarian  
**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk typo
3. Tekan enter

**Data Uji**:  
Nama Produk: Lemri Pakqian  
**Hasil yang Diharapkan**: Sistem menampilkan pesan "Tidak dapat menemukan hasil untuk lemri pakqian. Menampilkan hasil untuk lemari pakaian", sistem menampilkan hasil pencarian yang dimaksud "Lemari Pakaian"  
**Hasil Sebenarnya**: Sistem menampilkan pesan "Tidak dapat menemukan hasil untuk lemri pakqian. Menampilkan hasil untuk lemari pakaian", sistem menampilkan hasil pencarian yang dimaksud "Lemari Pakaian"

## TK-T38
**Skenario**: Mencari nama produk tanpa spasi  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman yang memiliki fitur pencarian  
**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk tanpa menggunakan spasi
3. Tekan enter

**Data Uji**:  
Nama Produk: Lemaripakaian  
**Hasil yang Diharapkan**: Sistem menampilkan pesan "Tidak dapat menemukan hasil untuk lemaripakaian. Menampilkan hasil untuk lemari pakaian", sistem menampilkan hasil pencarian "Lemari Pakaian"  
**Hasil Sebenarnya**: Sistem menampilkan pesan "Tidak dapat menemukan hasil untuk lemaripakaian. Menampilkan hasil untuk lemari pakaian", sistem menampilkan hasil pencarian "Lemari Pakaian"

## TK-T39
**Skenario**: Mencari produk dengan nama asal  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman yang memiliki fitur pencarian  
**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk secara asal
3. Tekan enter

**Data Uji**:  
Nama Produk: vrqwert  
**Hasil yang Diharapkan**: Sistem menampilkan hasil pencarian berdasarkan kata kunci "VR" yang terdapat pada penulisan "vrqwert"  
**Hasil Sebenarnya**: Sistem menampilkan hasil pencarian berdasarkan kata kunci "VR" yang terdapat pada penulisan "vrqwert"

## TK-T40
**Skenario**: Menampilkan saran pencarian produk pada search bar  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada di halaman yang memiliki fitur pencarian  
**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk
3. Klik saran produk di bawah search bar

**Data Uji**:  
Nama Produk: Lemari Pakaian  
**Hasil yang Diharapkan**: Sistem dapat memberikan saran pencarian produk yang terkait dengan nama produk yang diketik pada search bar  
**Hasil Sebenarnya**: Sistem dapat memberikan saran pencarian produk yang terkait dengan nama produk yang diketik pada search bar

## TK-T41
**Skenario**: Jumlah produk yang ditampilkan bertambah ketika halaman discroll ke bawah  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada​​​​​ di halaman hasil pencarian produk  
**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk
3. Tekan enter
4. Scroll halaman sampai akhir halaman

**Data Uji**:  
Nama Produk: Lemari Pakaian  
**Hasil yang Diharapkan**: Sistem dapat menampilkan hasil pencarian produk lainnya yang serupa ketika discroll ke bawah  
**Hasil Sebenarnya**: Sistem dapat menampilkan hasil pencarian produk lainnya yang serupa ketika discroll ke bawah

## TK-T42
**Skenario**: Memuat total produk lebih banyak  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berada​​​​​ di halaman hasil pencarian produk  
**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk
3. Tekan enter
4. Scroll halaman sampai akhir halaman
5. Klik "Muat lebih banyak"

**Data Uji**:  
Nama Produk: Lemari Pakaian  
**Hasil yang Diharapkan**: Sistem dapat memuat lebih banyak produk yang dicari  
**Hasil Sebenarnya**: Sistem dapat memuat lebih banyak produk yang dicari

## TK-T43
**Skenario**: Mencari nama toko  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berad​​​​​a pada halaman yang memiliki fitur pencarian  
**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama toko
3. Tekan enter
4. Klik "Toko"

**Data Uji**:  
Nama Toko: Lenovo Official  
**Hasil yang Diharapkan**: Sistem dapat menampilkan nama toko yang dicari  
**Hasil Sebenarnya**: Sistem dapat menampilkan nama toko yang dicari

## TK-T44
**Skenario**: Mengurutkan produk yang ditampilkan  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Jenis Tes**: Functional Test  
**Prasyarat**: Berad​​​​​a pada halaman yang memiliki fitur pencarian  
**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk "Lemari Pakaian"
3. Tekan enter
4. Pilih opsi urutkan (Paling Sesuai, Ulasan, Terbaru, Harga Tertinggi, Harga Terendah)
5. Pilih urutan yang diinginkan

**Data Uji**:  
Nama Produk: Lemari Pakaian  
**Hasil yang Diharapkan**: Sistem dapat mengurutkan produk berdasarkan pilihan user  
**Hasil Sebenarnya**: Sistem dapat mengurutkan produk berdasarkan pilihan user

## TK-T45
**Skenario**: Back to top button  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Jenis Tes**: Functional Test  
**Prasyarat**: B​​​​​erada di halaman hasil pencarian  
**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk
3. Tekan enter
4. Scroll halaman sampai akhir halaman
5. Klik ikon back to top

**Data Uji**:  
Nama Produk: Lemari Pakaian  
**Hasil yang Diharapkan**: Tampilan otomatis kembali ke bagian paling atas hasil pencarian  
**Hasil Sebenarnya**: Tampilan otomatis kembali ke bagian paling atas hasil pencarian
