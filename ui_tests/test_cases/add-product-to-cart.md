# Test Case: Add Product to Cart via Search

**ID:** TC-UI-03  
**Type:** Functional / UI  
**Priority:** Medium  
**Status:** Pass  

## Preconditions / Environment
- Android Studio is installed and configured.  
- Emulator device: **Pixel 3**, Android 13.  
- Emulator launched with command:  
C:\Users\jelez\AppData\Local\Android\Sdk\emulator\emulator.exe -avd Pixel_3 -dns-server 8.8.8.8  
- Rozetka mobile website is open on the emulator.  

## Steps
1. Enter `Asus Nitro V 15` in the search bar on the homepage and press Enter.

2. In the search results, select the first product and add it to the cart.

3. In the alert message confirming "Product added to cart", tap **Open**.  
   <img src="../screenshots/3.png" width="300"/>  

## Expected Result
- The cart page opens with the selected product displayed.  
- Correct quantity is shown in the cart.  
- All product details (title, price, image) are loaded correctly.  
- No visual defects or missing elements are present.  