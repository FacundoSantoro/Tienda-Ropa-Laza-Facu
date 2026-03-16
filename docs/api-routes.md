GET /api/products
[
  {
    "id": 1,
    "nombre": "Remera Oversize",
    "precio": 15000,
    "talles": ["S", "M", "L"],
    "stock": 10,
    "imagen": "url"
  }
]
GET /api/products/:id
POST /api/products
{
  "nombre": "Buzo",
  "precio": 20000
}
PUT /api/products/:id
DELETE /api/products/:id
POST /api/cart
GET /api/cart
POST /api/payment
POST /api/users/register
POST /api/users/login
