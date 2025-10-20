# ✅ Viewport + Cross-Browser Testing Checklist — Rozetka Mobile

**Goal:**  
Verify that the Rozetka mobile website displays and functions correctly across various screen sizes, resolutions, and mobile browsers.

---

## 1️⃣ Preparation
- [ ] Open BrowserStack or real mobile devices/emulators.  
- [ ] Select target devices covering different screen resolutions (small, medium, large).  
- [ ] Include at least one device per platform: Android / iOS / iPadOS.  
- [ ] Test on multiple browsers: Chrome, Safari, Edge, Mozilla, Samsung Internet.  
- [ ] Open Rozetka homepage: [https://rozetka.com.ua](https://rozetka.com.ua).  

---

## 2️⃣ Viewport Testing (Adaptive Layout)
**Purpose:** Verify how Rozetka adapts to different screen sizes and orientations.  

- [ ] Check homepage layout (banner, menu, product cards) on each device.  
- [ ] Verify that text and buttons fit within screen boundaries.  
- [ ] Switch between portrait and landscape orientation — layout should remain stable.  
- [ ] Check if navigation menu collapses correctly on smaller screens.  
- [ ] Ensure that the site uses responsive design (CSS media queries).  
- [ ] Verify correct scaling and padding of UI elements.  
- [ ] Check header and footer visibility on all devices.  
- [ ] Test scroll and touch responsiveness.  
- [ ] Take screenshots for each tested device.  

---

## 3️⃣ Cross-Browser Testing 
**Purpose:** Ensure UI and functional consistency across browsers.  

- [ ] Open Rozetka homepage in Chrome, Safari, Edge, Mozilla, Samsung Internet.  
- [ ] Check interactive elements (buttons, dropdowns, filters) work in each browser.  
- [ ] Verify animations and hover states (if applicable).  
- [ ] Ensure that fonts and colors are rendered consistently.  
- [ ] Check banner carousel functionality across browsers.  
- [ ] Confirm that links and redirects behave the same way everywhere.  
- [ ] Compare screenshots side-by-side for visual differences.  

---

## 4️⃣ Functional Smoke Checks
**Purpose:** Make sure main site actions are still working on all devices.  

- [ ] Perform a search — results should match across browsers.  
- [ ] Open a product page — verify image gallery and "Add to cart" button.  
- [ ] Add item to cart and check if the counter updates correctly.  
- [ ] Verify filters and sorting options on category pages.  
- [ ] Check page load time and responsiveness.  

---

## 5️⃣ Reporting
- [ ] Save screenshots per device and browser.  
- [ ] Attach short notes describing detected visual or layout issues.  
- [ ] Record environment: device, browser, OS version, orientation.  
- [ ] Add comparison screenshots if visual differences are found.   

---

**Expected Result:**  
Rozetka mobile website displays and functions consistently across all tested devices and browsers. Layout is responsive, no visual defects or broken elements are observed.