# App

Stock Management System

## Entities

- Product
  - sku
  - name
  - stock
  - size
  - color
  - weight
  - costPrice
  - salePrice
- Sale
  - id
  - createdAt
  - cart
- Cart
  - id
  - creatredAt
  - updatedAt
  - products ProductsOnCart[]
- ProductsOnCart
  - productSKU
  - quantity

## Use-cases

- LocateAnyProduct(sku: ProductSKU)
- DefineMinimunStock(value: any)
- FetchProductsStock
- GetProductStock
- AlertLowStockInEmail
- AlertLowStockInSystem
- FetchProductSalesByPeriod
- FetchProfitsPerProduct
- FetchBestSalesByPeriod
- FetchTrendingProducts

## Repositories

- ProductRepositories
  - LocalProductRepository
