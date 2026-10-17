NEET UG Pro - fixed starter files

Files:
- index.html: mobile-friendly working starter with MCQ A/B/C/D, answer feedback, local question manager, JSON import/export, dark mode.
- manifest.json: PWA metadata.
- service-worker.js: basic offline caching for same-origin app files.

IMPORTANT LIMITATIONS:
1. Questions created in Question Manager are stored only in the current browser/device. They are not shared with other students.
2. Admin page is not protected. Do not use it to store confidential/paid content or deploy as a production admin system.
3. Login, Firebase sync, secure admin roles, payments and real payment verification are not configured in this starter. Payment page intentionally does not show a fake QR code.
4. GitHub Pages requires HTTPS for service workers/PWA. Upload all three main files to the repository root and enable Pages in repository Settings > Pages.
5. Offline mode can cache the app shell, but first visit requires internet. External fonts/icons are not used in this fixed version.
