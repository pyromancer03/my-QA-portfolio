# Portfolio Software Quality Assurance (QA) - Manual Testing

## Project Overview  
Repository ini berisi dokumentasi Manual Software Quality Assurance untuk aplikasi e-commerce **(Tokopedia-Inspired)** yang terinspirasi dari alur bisnis marketplace. Proyek ini dibuat sebagai bagian dari portofolio untuk menunjukkan kemampuan dalam merancang, mengeksekusi, dan mendokumentasikan pengujian perangkat lunak menggunakan metode manual testing

## Ruang Lingkup Pengujian
### In Scope (Lingkup yang diuji)
- Login
- Register
- Forgot Password
- Product Search
- Product Detail
- Cart
- API website (Khusus untuk API menggunakan website Fakestoreapi)

### Out of Scope (Tidak termasuk)
- Database validation
- Performance testing
- Security penetration testing

## Pendekatan Pengujian
- Manual Testing
- Black-box Testing
- Skenario Positif & Negatif
- Boundary Value Analysis
- Equivalence Partitioning
- Exploratory Testing

## Tools dan Lingkungan Pengujian
- Sistem Operasi: Windows 11
- Browser: Google Chrome 150
- Test Management Tool: Jira Zephyr dan Postman
- Environment: Production
- Dokumentasi: Markdown

## Struktur Repository  
TestCase/  
├── APITest/  
│   ├── fakestoreapi_authentication.md  
|   ├── fakestoreapi_cart.md  
|   ├── fakestoreapi_products.md  
|   ├── fakestoreapi_users.md  
├── FunctionalTest/  
│   ├── Cart.md  
│   ├── Modul_ForgotPassword.md  
│   ├── Modul_Login.md  
│   ├── Modul_ProductDetail.md  
│   ├── Modul_ProductSearch.md  
│   └── Modul_Register.md  
├── TestPlan/  
│   └── TestPlan_TokopediaInspired.md  
└── README.md

## Testing Deliverables
Pada repository pengujian ini memiliki beberapa artefak pengujian:
- Test Plan
- Test Case
- API Testing
- Test Summary Report

## Test Result (Tokopedia-Inspired)                     
|      Metric      |     Result     |  
|------------------|----------------|  
| Total Test Cases |       66       |  
| Passed           |       66       |  
| Failed           |        0       |  
| Blocked          |        0       |  
| Not Executed     |        0       |  
| Defects Found    |        0       |

Dalam pengujian functional ini dapat diambil kesimpulan bahwa dari total 66 test case yang telah dieksekusi, tidak ditemukan adanya defect pada sistem dan seluruh test case lolos dalam pengujian. Presentasi keberhasilan pada test case adalah 100%, hasil tersebut sudah melebihi batas yang diharapkan

## Test Result (Fakestoreapi API Testing)
|      Metric      |     Result     |  
|------------------|----------------|  
| Total Test Cases |       16       |  
| Passed           |       16       |  
| Failed           |        0       |  
| Blocked          |        0       |  
| Not Executed     |        0       |  
| Defects Found    |        0       |


## Tentang Saya
Nama: Muhammad Rizky Fiqryansyah
Email: rizkyansyah7255@gmail.com
