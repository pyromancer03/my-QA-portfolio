# DISCLAIMER  
Dikarenakan saya tidak memiliki hak akses untuk API internal Tokopedia, maka di sini saya akan melakukan API Testing menggunakan dummy API website. Pada tahap ini, saya ingin menunjukkan proses pengujian API Testing pada website fakestoreapi dan membuktikan saya dapat memahami proses API Testing.

## AT-02
**API Name**: Get List user  
**Fitur**: Menampilkan seluruh data user  
**Method**: GET  
**Endpoint**: https://fakestoreapi.com/users  
**Tool**: Postman  
**Objective**: Memastikan semua data user tersedia dan ditampilkan  
**Test Status**: Pass  
**Hasil yang diharapkan**:
- API mengembalikan response seluruh data user
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: Data user berhasil dikembalikan, status code 200 OK, body berupa json, response time berhasil < 1000ms

## AT-03
**API Name**: Get Single user  
**Fitur**: Menampilkan data user berdasarkan ID    
**Method**: GET  
**Endpoint**: https://fakestoreapi.com/users/:id  
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
**Method**: POST  
**Endpoint**: https://fakestoreapi.com/users/  
**Tool**: Postman  
**Objective**: Memastikan sistem dapat mencari dan mengembalikan data user berdasarkan ID  
**Test Status**: Pass

**Request**
Body:
```
{
  "username": "Rizky",
  "email": "rizky@gmail.com",
  "password": "123456"
}
```

**Hasil yang diharapkan**:
- API akan menambahkan data user baru
- Status code 201
- Response body berupa json
- API mengembalikan response ID user baru
- Response time < 1000ms

**Hasil sebenarnya**: API berhasil menambahkan user baru, status code 201 Created, body berupa json, API mengembalikan ID user, response time berhasil < 1000ms

## AT-05
**API Name**: Update user  
**Fitur**: Mengupdate data existing user  
**Method**: PUT  
**Endpoint**: https://fakestoreapi.com/users/:id  
**Path Variables**:  
Key: id  
Value: 4

**Tool**: Postman  
**Objective**: Memastikan API mengupdate data existing user dan mengembalikan data user  
**Test Status**: Pass  

**Request**
Body
```
{
    "username": "Meka",
    "email": "meka@gmail.com",
    "password": "meka123"
}
```

**Hasil yang diharapkan**:
- API mengupdate data existing user
- API mengembalikan response data user yang telah diupdate
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: API berhasil mengupdate data user, API berhasil mengembalikan data user, status code 200 OK, body berupa json, response time berhasil < 1000ms

## AT-06
**API Name**: Delete user  
**Fitur**: Menghapus data user berdasarkan ID  
**Method**: DELETE  
**Endpoint**: https://fakestoreapi.com/users/:id  
**Path Variables**:  
Key: id  
Value: 4

**Tool**: Postman  
**Objective**: Memastikan data user dengan ID tertentu dapat dihapus  
**Test Status**: Pass  
**Hasil yang diharapkan**:
- Data user dapat dihapus
- API mengembalikan response data yang dihapus
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: Data user berhasil dihapus, API berhasil mengembalikan response data, status code 200 OK, body berupa json, response time berhasil < 1000ms
