# Mobile Testing of Rozetka Website

## Project Goal
This portfolio demonstrates manual testing of the Rozetka mobile website, showcasing skills in:  
- API testing and verifying UI matches server responses  
- UI testing and interface elements  
- Responsive design and cross-browser compatibility  
- Website loading under different network conditions  

## Project Structure
- `api_tests/` — check API requests and ensure UI data matches server responses. Used Fiddler and a real phone.  
- `ui_tests/` — test interface elements (menu, search, filters, checkout) on Android Studio emulator (Pixel 3, Android 13).  
- `cross-browser_viewport/` — check responsiveness and compatibility across devices and browsers via BrowserStack.  
- `network_tests/` — test website loading under different network conditions (Offline, 3G, Slow 4G) using Chrome DevTools Device Toolbar.  

## Tools
- Android Studio (Pixel 3 emulator, Android 13)  
- Fiddler Classic for traffic interception  
- BrowserStack for cross-browser and responsive testing  
- Chrome DevTools Device Toolbar for network tests  
- Real device: Redmi Note 12 Pro 5G  

## Results
- Website displays correctly on all tested devices and browsers  
- Core functionality works; UI elements are clickable and correct  
- Responsive design is maintained; no cross-browser issues  
- Site loads correctly under different network conditions