Allergy Scanner App - Android Studio Project
============================================

Project Description:
--------------------
This Android app scans food barcodes using the device's camera, then sends the scanned barcode to a local PHP server to check for allergens. The app helps users with food allergies to avoid harmful ingredients.

Key Features:
-------------
- Barcode scanning using JourneyApps ZXing library.
- Sends HTTP request to a PHP backend with a local XAMPP server.
- Displays allergy information based on barcode.
- Uses a simple background thread (no async/ThreadPool complexity).
- Designed for clarity and academic understanding.

Backend:
--------
- PHP script receives the barcode via GET request.
- PHP queries a MySQL database hosted on localhost via XAMPP.
- Returns allergy information (or error message) as plain text.

How To Run:
-----------
1. Open project in Android Studio.
2. Ensure your phone and XAMPP server are on the same Wi-Fi network.
3. Use a real Android device (camera needed).
4. Start XAMPP → Make sure Apache and MySQL are running.
5. Place 'food_checker.php' inside 'htdocs'.
6. Create and populate your MySQL 'food' database.
7. Run the app, scan a barcode, view allergy info.


--------
Omar Dalle
CSI 370 Project - Spring 2025
