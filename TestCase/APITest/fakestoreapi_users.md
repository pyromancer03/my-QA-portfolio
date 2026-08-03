# DISCLAIMER  
Dikarenakan saya tidak memiliki hak akses untuk API internal Tokopedia, maka di sini saya akan melakukan API Testing menggunakan dummy API website. Pada tahap ini, saya ingin menunjukkan proses pengujian API Testing pada website fakestoreapi dan membuktikan saya dapat memahami proses API Testing.

## AT-02 - Get List User
**API Name**: Get List user  
**Fitur**: Menampilkan seluruh data user  
**Method**: GET  
**Endpoint**: https://fakestoreapi.com/users  
**Tool**: Postman  
**Objective**: Memastikan semua data user tersedia dan ditampilkan  
**Test Status**: Pass
**Hasil yang diharapkan**:
- Seluruh data user dikembalikan
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: Data user berhasil dikembalikan, status code 200 OK, body berupa json, response time berhasil < 1000ms

## AT-03
**API Name**: Get Single user  
**Fitur**: Menampilkan data user berdasarkan ID    
**Method**: GET  
**Endpoint**: https://fakestoreapi.com/users/{id}  
**Path Variables**: 
Key: id  
Value: 4

**Tool**: Postman  
**Objective**: Memastikan sistem dapat mencari dan mengembalikan data user berdasarkan ID  
**Test Status**: Pass
**Hasil yang diharapkan**:
- API mengembalikan response data user sesuai ID
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: API berhasil mengembalikan data user dengan ID 4, status code 200 OK, body berupa json, response time berhasil < 1000ms

## AT-04  
**API Name**: Add new user  
**Fitur**: Menambahkan user baru  
**Method**: GET  
**Endpoint**: https://fakestoreapi.com/users/{id}  
**Path Variables**: 
Key: id  
Value: 4

**Tool**: Postman  
**Objective**: Memastikan sistem dapat mencari dan mengembalikan data user berdasarkan ID  
**Test Status**: Pass
**Hasil yang diharapkan**:
- API mengembalikan response data user sesuai ID
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: API berhasil mengembalikan data user dengan ID 4, status code 200 OK, body berupa json, response time berhasil < 1000ms
