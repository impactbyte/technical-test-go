# Golang Technical Test

Buatlah sebuah **Web Service API** menggunakan framework [Go](https://golang.org) yaitu [Gin](https://github.com/gin-gonic) dan juga akses database menggunakan [Gorm](https://gorm.io). Gunakan driver MySQL.

Web Service API yang dibuat adalah berupa **data order suatu produk**.
Setiap **order** dapat melakukan order **lebih dari 1 item**.

Order memiliki properti sebagai berikut

- OrderID
- CustomerName
- OrderedAt
- Items

Item memiliki properti sebagai berikut

- LineItemID
- ItemCode
- ItemName
- Quantity
- OrderID

Endpoint yang dibutuhkan adalah

- Create Order
- Get All Order
- Get Order by Id
- Update Order
- Delete Order

Buat juga sebuah **Middleware** berupa **authentication** (boleh menggunakan auth basic atau jwt token) untuk dapat mencegah user mengakses endpoint berikut:

- Create Order
- Update Order
- Delete Order

Terakhir dokumentasikan setiap endpoint Web Service API yang sudah kamu buat menggunakan [Swaggo](https://github.com/swaggo/swag)
