# weblar-shopify-assignment

Name: Sai Keerthi Lella  
Email: saikeerthilella13@gmail.com  
Store URL: https://skl-liquid-dev.myshopify.com  
GitHub Repo: https://github.com/keerthi1366/weblar-shopify-assignment

# Task Overview

# Task 1: Product Badges  
File: `snippets/card-product.liquid`  
- Shows a “Budget Pick” badge if product price < ₹500  
- Shows a “Limited Stock” badge if inventory quantity < 5  
- Custom CSS was added in `base.css` to style badges

# Task 2: Collection Page Tag Filter  
File: `sections/main-collection-product-grid.liquid`  
- Added a dropdown to filter products based on tags:  
  - Best Seller  
  - New Arrival  
  - Discounted  
- Dynamically filters products using selected tag

# Task 3: Personalized Time-Based Greeting  
File:`sections/image-banner.liquid`  
- Displays a greeting based on current time (UTC):  
  - Good Morning (before 12 PM UTC)  
  - Good Afternoon (12 PM – 6 PM UTC)  
  - Good Evening (after 6 PM UTC)  
- Implemented using Liquid's `now` and `date` filters  
- Time is shown based on Shopify's default UTC output (not adjusted to IST)

# Task 4: Cart Upsell Logic  
File:`sections/main-cart-items.liquid`  
- If cart total is < ₹1000 → recommends a product from ‘accesories’ collection  
- If cart total is ≥ ₹1000 → recommends from ‘premium’ collection  
- Includes product image, name, price, and link  
- Responsive layout with CSS styling

# Bonus Task: Free Shipping Message  
File: `sections/main-cart-items.liquid`  
- If cart total < ₹500 → shows:  
  “Spend ₹X more to get free shipping!”  
- If cart total ≥ ₹500 → shows:  
  “You’ve unlocked free shipping!”  
- Dynamically updates as cart value changes

# Notes

- All features tested in **Dawn theme** on Shopify dev store
- Code is modular, clean, and responsive
- Screenshots of functionality available if required


**Thank you for reviewing my submission!**
