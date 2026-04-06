# Product Detail View Enhancement TODO

## Steps:
- [ ] 1. Update src/data/products.js: Add realistic "description" field to all 46 products (product-specific, 1-2 sentences matching examples like "Fresh, crispy red apples sourced from Chennai hub").
- [ ] 2. Update src/pages/ProductsPage.js: 
  - Make quantity options dynamic based on category/unit (fruits/veg: 250g/500g/1kg; dairy: 500ml/1L/2L etc.).
  - Modify handleAddToCart to pass selectedQuantity/product.
  - Update description fallback removal.
- [ ] 3. Test changes: Run `npm run dev`, navigate /products, click products, verify details/add/go back.
- [ ] 4. Complete task.

Current: Starting step 1.

