# Test Case Pada Modul Product Search
Pengujian fitur pada modul product search yang bertujuan untuk memastikan fitur yang mencakup proses product search dapat berjalan dengan baik dan lancar sesuai dengan requirement

## TK-T36
**Test Case**: Melakukan pencarian produk  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada di halaman yang menampilkan search bar

**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk
3. Tekan enter

**Data Uji**:  
Nama Produk: Laptop Asus Vivobook Go 14  
**Hasil yang Diharapkan**:
- Menampilkan daftar produk berdasarkan kata kunci yang dimasukkan
- Informasi produk ditampilkan dengan benar (nama, harga, gambar, nama toko, dan rating produk)

**Hasil Sebenarnya**: Sistem berhasil menampilkan daftar produk, informasi produk berhasil ditampilkan

## TK-T37
**Test Case**: Pencarian nama produk salah ketik (typo)  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada di halaman yang menampilkan search bar

**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk typo
3. Tekan enter

**Data Uji**:  
Nama Produk: Lemri Pakqian  
**Hasil yang Diharapkan**:
- Menampilkan pesan "Tidak dapat menemukan hasil untuk lemri pakqian. Menampilkan hasil untuk lemari pakaian"
- Sistem memperbaiki penulisan yang typo
- Sistem menampilkan hasil pencarian yang sudah dikoreksi
- Informasi produk ditampilkan dengan benar (nama, harga, gambar, nama toko, dan rating produk)

**Hasil Sebenarnya**: Sistem berhasil menampilkan pesan, sistem berhasil memperbaiki penulisan, sistem berhasil menampilkan hasil pencarian, informasi produk sesuai

## TK-T38
**Test Case**: Mencari nama produk tanpa spasi  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada di halaman yang menampilkan search bar

**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk tanpa menggunakan spasi
3. Tekan enter

**Data Uji**:  
Nama Produk: Lemaripakaian  
**Hasil yang Diharapkan**:
- Menampilkan pesan "Tidak dapat menemukan hasil untuk lemaripakaian. Menampilkan hasil untuk lemari pakaian"
- Sistem memperbaiki penulisan yang kurang spasi
- Sistem menampilkan hasil pencarian yang sudah dikoreksi
- Informasi produk ditampilkan dengan benar (nama, harga, gambar, nama toko, dan rating produk)

**Hasil Sebenarnya**: Sistem berhasil menampilkan pesan, sistem berhasil memperbaiki penulisan, sistem berhasil menampilkan hasil pencarian, informasi produk sesuai 

## TK-T39
**Test Case**: Mencari produk dengan nama asal  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada di halaman yang menampilkan search bar

**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk secara asal
3. Tekan enter

**Data Uji**:  
Nama Produk: vrqwert  
**Hasil yang Diharapkan**:
- Sistem mencari berdasarkan kata kunci yang ada pada penulisan
- Menampilkan hasil pencarian berdasarkan kata kunci "VR" yang terdapat pada penulisan "vrqwert"
- Informasi produk ditampilkan dengan benar (nama, harga, gambar, nama toko, dan rating produk)

**Hasil Sebenarnya**: Sistem berhasil mencari produk dari kata kunci, sistem berhasil menampilkan produk, informasi produk sesuai

## TK-T40
**Test Case**: Menampilkan saran pencarian produk pada search bar  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada di halaman yang menampilkan search bar

**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk
3. Klik saran produk di bawah search bar

**Data Uji**:  
Nama Produk: Lemari Pakaian  
**Hasil yang Diharapkan**:
- Memberikan saran pencarian produk yang terkait dengan nama produk yang diketik pada search bar
- Menampilkan hasil pencarian dari saran produk yang diklik
- Informasi produk ditampilkan dengan benar (nama, harga, gambar, nama toko, dan rating produk)

**Hasil Sebenarnya**: Sistem memberikan saran pencarian produk, sistem berhasil menampilkan hasil pencarian, informasi produk sesuai

## TK-T41
**Test Case**: Jumlah produk yang ditampilkan bertambah ketika halaman discroll ke bawah  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada di halaman yang menampilkan search bar

**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk
3. Tekan enter
4. Scroll halaman sampai akhir halaman

**Data Uji**:  
Nama Produk: Lemari Pakaian  
**Hasil yang Diharapkan**:
- Load hasil pencarian produk lainnya yang serupa ketika discroll ke bawah
- Informasi produk ditampilkan dengan benar (nama, harga, gambar, nama toko, dan rating produk)

**Hasil Sebenarnya**: Sistem berhasil load produk lainnya, informasi produk sesuai

## TK-T42
**Test Case**: Memuat total produk lebih banyak  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada di halaman yang menampilkan search bar

**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk
3. Tekan enter
4. Scroll halaman sampai akhir halaman
5. Klik "Muat lebih banyak"

**Data Uji**:  
Nama Produk: Lemari Pakaian  
**Hasil yang Diharapkan**:
- Sistem memuat lebih banyak produk
- Informasi produk ditampilkan dengan benar (nama, harga, gambar, nama toko, dan rating produk)

**Hasil Sebenarnya**: Sistem dapat memuat lebih banyak produk yang dicari

## TK-T43
**Test Case**: Mencari nama toko  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada di halaman yang menampilkan search bar

**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama toko
3. Tekan enter
4. Klik "Toko"

**Data Uji**:  
Nama Toko: Lenovo Official  
**Hasil yang Diharapkan**:
- Menampilkan nama toko yang dicari
- Memuat data nama toko lainnya yang memiliki kata kunci serupa

**Hasil Sebenarnya**: Sistem berhasil menampilkan nama toko, sistem berhasil memuat nama toko lainnya

## TK-T44
**Test Case**: Mengurutkan produk yang ditampilkan  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: High  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada di halaman yang menampilkan search bar

**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk
3. Tekan enter
4. Pilih opsi urutkan (Paling Sesuai, Ulasan, Terbaru, Harga Tertinggi, Harga Terendah)
5. Pilih urutan yang diinginkan

**Data Uji**:  
Nama Produk: Lemari Pakaian  
**Hasil yang Diharapkan**:
- Produk diurutkan berdasarkan pilihan user
- Informasi produk ditampilkan dengan benar (nama, harga, gambar, nama toko, dan rating produk)

**Hasil Sebenarnya**: Sistem berhasil mengurutkan produk, informasi produk sesuai

## TK-T45
**Test Case**: Back to top button  
**Jenis Pendekatan**: Positive Test  
**Prioritas**: Normal  
**Test Status**: Pass  
**Jenis Tes**: Functional Test  
**Prasyarat**:
- Berada di halaman hasil pencarian

**Langkah Pengujian**:

1. K​​​​​lik pada search bar
2. Ketik nama produk
3. Tekan enter
4. Scroll halaman sampai akhir halaman
5. Klik ikon back to top

**Data Uji**:  
Nama Produk: Lemari Pakaian  
**Hasil yang Diharapkan**:
- Tampilan otomatis kembali ke hasil pencarian paling atas
- Halaman tetap menampilkan hasil pencarian saat ini

**Hasil Sebenarnya**: Tampilan kembali ke hasil pencarian paling atas, tetap menampilkan hasil pencarian produk saat ini
