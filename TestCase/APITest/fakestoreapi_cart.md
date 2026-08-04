# DISCLAIMER  
Dikarenakan saya tidak memiliki hak akses untuk API internal Tokopedia, maka di sini saya akan melakukan API Testing menggunakan dummy API website. Pada tahap ini, saya ingin menunjukkan proses pengujian API Testing pada website fakestoreapi dan membuktikan saya dapat memahami proses API Testing.

## AT-12
**API Name**: Get List cart  
**Fitur**: Menampilkan seluruh data item di cart  
**Method**: GET  
**Endpoint**: https://fakestoreapi.com/carts/  
**Tool**: Postman  
**Objective**: Memastikan API dapat mengembalikan response seluruh data item di cart  
**Test Status**: Pass  
**Hasil yang diharapkan**:
- API mengembalikan response seluruh data item di cart
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: Data item di cart berhasil dikembalikan, status code 200 OK, body berupa json, response time berhasil < 1000ms

## AT-13
**API Name**: Get item in cart by ID  
**Fitur**: Menampilkan data item di cart berdasarkan ID  
**Method**: GET  
**Endpoint**: https://fakestoreapi.com/carts/:id  
**Path Variables**:  
Key: id  
Value: 3

**Tool**: Postman  
**Objective**: Memastikan API dapat mencari dan mengembalikan data item di cart berdasarkan ID  
**Test Status**: Pass  
**Hasil yang diharapkan**:
- API mengembalikan response data product sesuai ID
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: API berhasil mengembalikan data item, status code 200 OK, body berupa json, response time berhasil < 1000ms

## AT-14  
**API Name**: Add new item to cart  
**Fitur**: Menambahkan item baru ke cart  
**Method**: POST  
**Endpoint**: https://fakestoreapi.com/carts/  
**Tool**: Postman  
**Objective**: Memastikan API dapat menambahkan data item baru ke cart  
**Test Status**: Pass

**Request**  
Body:
```json
{
  "userId": 2,
  "products": [
    {
      "id": 7,
      "title": "Celana pendek",
      "price": 0.5,
      "description": "Celana pendek adem",
      "category": "Men's clothing",
      "image": "http://example.com"
    }
  ]
}
```

**Hasil yang diharapkan**:
- API akan menambahkan data item baru ke cart
- Status code 201
- Response body berupa json
- API mengembalikan response data item baru
- Response time < 1000ms

**Hasil sebenarnya**: API berhasil menambahkan item baru, status code 201 Created, body berupa json, API berhasil mengembalikan data item, response time berhasil < 1000ms

## AT-15
**API Name**: Update item in cart  
**Fitur**: Mengupdate data existing item di cart  
**Method**: PUT  
**Endpoint**: https://fakestoreapi.com/carts/:id  
**Path Variables**:  
Key: id  
Value: 3

**Tool**: Postman  
**Objective**: Memastikan API mengupdate data existing item dan mengembalikan data item di cart  
**Test Status**: Pass  

**Request**  
Body
```json
{
  "id": 0,
  "userId": 0,
  "products": [
    {
      "id": 0,
      "title": "string",
      "price": 0.1,
      "description": "string",
      "category": "string",
      "image": "http://example.com",
      "quantity": 2
    }
  ]
}
```

**Hasil yang diharapkan**:
- API mengupdate data existing product
- API mengembalikan response data user yang telah diupdate
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: API berhasil mengupdate data user, API berhasil mengembalikan data user, status code 200 OK, body berupa json, response time berhasil < 1000ms

## AT-16
**API Name**: Delete item in cart  
**Fitur**: Menghapus data item di cart berdasarkan ID  
**Method**: DELETE  
**Endpoint**: https://fakestoreapi.com/carts/:id  
**Path Variables**:  
Key: id  
Value: 3

**Tool**: Postman  
**Objective**: Memastikan data item di cart dengan ID tertentu dapat dihapus  
**Test Status**: Pass  
**Hasil yang diharapkan**:
- Data item di cart dapat dihapus
- API mengembalikan response data item yang dihapus
- Status code 200
- Response body berupa json
- Response time < 1000ms

**Hasil sebenarnya**: Data item berhasil dihapus, API berhasil mengembalikan response data item, status code 200 OK, body berupa json, response time berhasil < 1000ms
