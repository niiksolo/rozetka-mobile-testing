# Test Case: Search Functionality - Jim Beam

**ID:** TC-API-003  
**Type:** Functional / API + UI  
**Priority:** Medium  
**Status:** Pass  

## Preconditions
1. Fiddler Classic is installed and configured.  
2. Phone is connected to Wi-Fi with manual proxy:  
   - Host: `<your IP>`  
   - Port: `8888`  
3. Mobile site [Rozetka.com.ua](https://rozetka.com.ua) is open on the phone.  

## Steps
### UI
1. In the search bar on the main page, enter `Jim Beam` and press Enter.  

### API
2. In Fiddler, locate the corresponding search request.  
3. Verify that the API request contains correct search parameters.  
4. Check that the response JSON returns products relevant to `Jim Beam`.  

## Expected Result
- **UI:** Search results page displays products related to `Jim Beam`.  
- **API:** Search request parameters are correct; JSON response contains relevant products.  

## Screenshots
1. **UI Search Results** – Phone shows products for `Jim Beam`.  
   <img src="../screenshots/3.jpg" width="300"/>  
2.**API Search Response** – Fiddler shows JSON response with relevant products.  
   <img src="../screenshots/4.png" width="300"/>  
