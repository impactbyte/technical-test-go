# Golang Technical Test

Buatlah sebuah web service menggunakan framework Go yaitu Gin dan juga akses database menggunakan Gorm. Gunakan driver MySQL.

Web Service API yang dibuat adalah berupa data order suatu produk.
Setiap order dapat melakukan order lebih dari 1 item.

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

Buat juga sebuah Middleware berupa authentication (boleh menggunakan auth basic atau jwt token) untuk dapat mencegah user mengakses endpoint berikut:

- Create Order
- Update Order
- Delete Order

Terakhir dokumentasikan Web Service API yang sudah kamu buat menggunakan Swaggo
