# ✅ Network Testing Checklist — Rozetka Mobile

**Goal:**  
Verify Rozetka mobile website behavior under different network conditions and ensure proper loading, responsiveness, and error handling.

---

## 1️⃣ Preparation
- [ ] Open Rozetka mobile site in **Chrome DevTools** or a mobile emulator.  
- [ ] Enable **Device Toolbar** and select a mobile device (e.g., Pixel 3).  
- [ ] Ensure DevTools network throttling options are available (Offline, 3G, Slow 4G, Fast 4G).  

---

## 2️⃣ Network Conditions
### Slow 4G
- [ ] Set network throttling to Slow 4G.  
- [ ] Open homepage and observe loading behavior.  
- [ ] Ensure progressive rendering of key UI elements (header, search, banners).  
- [ ] Verify no broken resources, missing images, or layout shifts.  
- [ ] Check approximate page load time (~3–5 seconds).  

### 3G
- [ ] Set network throttling to 3G.  
- [ ] Open homepage and observe loading behavior.  
- [ ] Ensure key elements appear progressively.  
- [ ] Check layout stability and correct rendering of images/content.  
- [ ] Verify page load time (~6–10 seconds).  

### Offline
- [ ] Set network throttling to Offline.  
- [ ] Open homepage and observe behavior.  
- [ ] Ensure page does not crash or freeze.  
- [ ] Check for proper offline message or error notification.  
- [ ] Verify previously loaded content (if any) is displayed correctly.  

---

## 3️⃣ Functional Checks
- [ ] Test search and navigation under each network condition.  
- [ ] Test adding items to cart and checking cart behavior (if possible).  
- [ ] Verify error messages and notifications appear correctly when network fails.  

---

## 4️⃣ Reporting
- [ ] Take screenshots of page loading under each network condition.  
- [ ] Note load times and any visual/layout issues.  
- [ ] Record environment: device, network type, browser, orientation.  
- [ ] Summarize results: pass/fail for each condition.  

---

**Expected Result:**  
Rozetka mobile site loads and functions correctly across all tested network conditions. Layout remains stable, UI elements render properly, and offline handling is graceful.