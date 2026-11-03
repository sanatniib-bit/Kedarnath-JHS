KEDARNATH JUNIOR HIGH SCHOOL — INSTALLABLE WEB APP

Package contents:
- index.html: your school ERP application
- manifest.webmanifest: install metadata and app icons
- service-worker.js: app-shell caching for repeat loads
- icons/: home-screen icons

HOW TO INSTALL ON ANDROID
1. Upload the contents of this folder to a static web host that provides HTTPS (for example, your existing website/hosting).
2. Open the hosted index.html address in Chrome on Android.
3. Tap Chrome menu (⋮) > Install app / Add to Home screen.
4. Confirm Install.

IMPORTANT
- This package is a PWA, not an APK file.
- A secure HTTPS website is required for installation and service workers. Opening index.html directly from Files will not enable PWA installation.
- The current school app saves records in browser localStorage on that device/browser. It does not sync between multiple phones or computers.
- Some external libraries are loaded from CDNs, so an internet connection may be needed for all charts/icons/styles to load.
- Make regular JSON backups from the app's Backup & Settings section.
