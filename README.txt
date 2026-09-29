SAMIA'S CLOSET — PROFESSIONAL FIREBASE BUILD

This version separates the public customer website (index.html) from the private admin panel (admin.html).

CUSTOMER
- No admin button/link is shown anywhere.
- Products, settings and orders are online through Firebase.
- Mobile-first premium fashion design.
- Product photo selection uses a normal image/file picker and does NOT request camera capture.

ADMIN
- Separate admin.html URL.
- Google/Gmail sign-in through Firebase Authentication.
- Only the configured ADMIN_EMAIL is allowed in the UI.
- Products: add/edit/delete, price, category, description, Gallery photo upload.
- Orders: view and update status.
- Website: edit hero/title/about/contact/social settings.

IMPORTANT SETUP
1. Create a Firebase project and register a Web App.
2. Enable Google in Authentication > Sign-in method.
3. Create Firestore Database and Storage.
4. Copy the Web App config into firebase-config.js.
5. Replace YOUR_ADMIN_GMAIL@gmail.com in firebase-config.js, firestore.rules and storage.rules with the exact Google account that will manage the store.
6. Deploy the folder to your chosen static host/Firebase Hosting.
7. Add the deployed domain to Firebase Authentication > Authorized domains.

The project intentionally does not contain real Firebase credentials. It becomes live after your Firebase project config and security rules are added.
