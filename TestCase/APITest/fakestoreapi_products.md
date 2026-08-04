# DISCLAIMER  
Dikarenakan saya tidak memiliki hak akses untuk API internal Tokopedia, maka di sini saya akan melakukan API Testing menggunakan dummy API website. Pada tahap ini, saya ingin menunjukkan proses pengujian API Testing pada website fakestoreapi dan membuktikan saya dapat memahami proses API Testing.

## AT-07
**API Name**: Get List product  
**Fitur**: Menampilkan seluruh data product  
**Method**: GET  
**Endpoint**: https://fakestoreapi.com/products/  
**Tool**: Postman  
**Objective**: Memastikan API dapat mengembalikan response seluruh data product  
**Test Status**: Pass  
**Hasil yang diharapkan**:
- API mengembalikan response seluruh data product
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: Data product berhasil dikembalikan, status code 200 OK, body berupa json, response time berhasil < 1000ms

## AT-08
**API Name**: Get product by ID  
**Fitur**: Menampilkan data product berdasarkan ID  
**Method**: GET  
**Endpoint**: https://fakestoreapi.com/products/:id  
**Path Variables**:  
Key: id  
Value: 4

**Tool**: Postman  
**Objective**: Memastikan API dapat mencari dan mengembalikan data product berdasarkan ID  
**Test Status**: Pass  
**Hasil yang diharapkan**:
- API mengembalikan response data product sesuai ID
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: API berhasil mengembalikan data product, status code 200 OK, body berupa json, response time berhasil < 1000ms

## AT-09  
**API Name**: Add new product  
**Fitur**: Menambahkan product baru  
**Method**: POST  
**Endpoint**: https://fakestoreapi.com/products/  
**Tool**: Postman  
**Objective**: Memastikan API dapat menambahkan data product baru  
**Test Status**: Pass

**Request**  
Body:
```json
{
    "title": "Celana pendek",
    "price": 3,
    "description": "Celana pendek adem",
    "category": "Men's Clothing",
    "image": "http://example.com"
}
```

**Hasil yang diharapkan**:
- API akan menambahkan data product baru
- Status code 201
- Response body berupa json
- API mengembalikan response data product baru
- Response time < 1000ms

**Hasil sebenarnya**: API berhasil menambahkan product baru, status code 201 Created, body berupa json, API berhasil mengembalikan data product, response time berhasil < 1000ms

## AT-10
**API Name**: Update product  
**Fitur**: Mengupdate data existing product  
**Method**: PUT  
**Endpoint**: https://fakestoreapi.com/products/:id  
**Path Variables**:  
Key: id  
Value: 3

**Tool**: Postman  
**Objective**: Memastikan API mengupdate data existing product dan mengembalikan data product  
**Test Status**: Pass  

**Request**  
Body
```json
{
    "title": "Baju panjang",
    "price": 3,
    "description": "Baju panjang adem",
    "category": "Men's Clothing",
    "image": "http://example.com"
}
```

**Hasil yang diharapkan**:
- API mengupdate data existing product
- API mengembalikan response data user yang telah diupdate
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: API berhasil mengupdate data user, API berhasil mengembalikan data user, status code 200 OK, body berupa json, response time berhasil < 1000ms

## AT-11
**API Name**: Delete product  
**Fitur**: Menghapus data product berdasarkan ID  
**Method**: DELETE  
**Endpoint**: https://fakestoreapi.com/products/:id  
**Path Variables**:  
Key: id  
Value: 3

**Tool**: Postman  
**Objective**: Memastikan data product dengan ID tertentu dapat dihapus  
**Test Status**: Pass  
**Hasil yang diharapkan**:
- Data product dapat dihapus
- API mengembalikan response data product yang dihapus
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: Data product berhasil dihapus, API berhasil mengembalikan response data, status code 200 OK, body berupa json, response time berhasil < 1000ms
