# API Testing Checklist — Rozetka Mobile Web

## 1️⃣ Setup
- [ ] Connect your mobile device or emulator to Fiddler / proxy.  
- [ ] Enable filters to capture only Rozetka requests (`rozetka.com.ua`).  
- [ ] Do a clean site session (clear cookies / localStorage).  

---

## 2️⃣ Search API
**Goal:** Check that search results are correct.  
- [ ] Search for a product (e.g., "smartphone").  
- [ ] Make sure the Response JSON contains keys: `id`, `title`, `price`.  
- [ ] Compare the number of products in the UI and in JSON.  
- [ ] Check that multiple products appear in the list.  
- [ ] Take a screenshot of the request and response in Fiddler.  
- [ ] Check the response time (ms).  

---

## 3️⃣ Product API
**Goal:** Check product details.  
- [ ] Open the product page → find the product request.  
- [ ] Verify JSON fields: `id`, `title`, `price`, `availability`, `category_id`.  
- [ ] Compare price and title with UI.  
- [ ] Take a screenshot of the request and response.  

---

## 4️⃣ Cart API
**Goal:** Check adding and removing products from the cart.  
- [ ] Add a product → find the corresponding request in Fiddler.  
- [ ] Verify JSON: `cart_items`, `quantity`, `price`.  
- [ ] Add multiple products → make sure they appear in the requests.  
- [ ] Remove a product → check changes in request/response.  
- [ ] Take screenshots of all steps.  

---

## 5️⃣ Headers / Status
- [ ] Check HTTP status (200 for success).  
- [ ] Check headers: `Content-Type: application/json`, `Cache-Control`.  
- [ ] Take screenshots of Response Headers.  
