# DISCLAIMER  
Dikarenakan saya tidak memiliki hak akses untuk API internal Tokopedia, maka di sini saya akan melakukan API Testing menggunakan dummy API website. Pada tahap ini, saya ingin menunjukkan proses pengujian API Testing pada website fakestoreapi dan membuktikan saya dapat memahami proses API Testing.

## AT-06
**API Name**: Get List product  
**Fitur**: Menampilkan seluruh data product  
**Method**: GET  
**Endpoint**: https://fakestoreapi.com/products  
**Tool**: Postman  
**Objective**: Memastikan API dapat mengembalikan response seluruh data product  
**Test Status**: Pass  
**Hasil yang diharapkan**:
- API mengembalikan response seluruh data product
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: Data product berhasil dikembalikan, status code 200 OK, body berupa json, response time berhasil < 1000ms
