# DISCLAIMER  
Dikarenakan saya tidak memiliki hak akses untuk API internal Tokopedia, maka di sini saya akan melakukan API Testing menggunakan dummy API website. Pada tahap ini, saya ingin menunjukkan proses pengujian API Testing pada website fakestoreapi dan membuktikan saya dapat memahami proses API Testing.

## AT-01
**API Name**: User Login  
**Fitur**: User Authentication  
**Method**: POST  
**Endpoint**: https://fakestoreapi.com/auth/login/  
**Tool**: Postman  
**Objective**: Memastikan user dapat login dengan username dan password yang valid  
**Test Status**: Pass

**Request**
Body:
```json
{
  "username": "johnd",
  "password": "m38rmF$"
}
```
**Hasil yang diharapkan**:
- User dapat login
- Status code 200
- Response body berupa json
- Response menampilkan token
- Response time < 1000ms

**Hasil sebenarnya**: User berhasil login, status code 200 OK, body berupa json, token berhasil diterima, response time berhasil < 1000ms
