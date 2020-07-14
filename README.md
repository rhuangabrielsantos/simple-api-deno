# Simple API DENO

![](https://imgr.co/cache/img/90feda064b7bd52f4b604cc4587b1a18.jpg)

A simple API using deno!

## How to Run?

1. Install [deno](https://deno.land/#installation)
2. Clone this project
3. Run this command `deno run --allow-net  server.ts`
4. Go to [go to localhost: 8000](localhost: 8000) and be happy

## Routes

| METHODS | URI | Description |
| ----- | ---- | ---- |
| GET | /products | Get all products |
| GET | /products/:id | Get specific product |
| POST | /products | Add Product |
| PUT | /products/:id | Update product |
| DELETE | /products/:id | Delete product


```
{
  "id": "4",
  "name": "New Product",
  "description": "A nice product",
  "price": 66.00
}
```
