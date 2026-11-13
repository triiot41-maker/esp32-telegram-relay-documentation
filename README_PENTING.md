BHP ESP32 TELEGRAM + USB FLASH DOCUMENTATION

Isi:
- Panduan_ESP32_Telegram_1Admin_5Users_dan_USB_Flash.docx
- Panduan_ESP32_Telegram_1Admin_5Users_dan_USB_Flash.pdf

Catatan penting:
1. Source yang diberikan mengandung token Telegram dan password Wi-Fi dalam teks biasa.
   Revoke token lama melalui BotFather dan ganti password Wi-Fi sebelum distribusi.
2. Source tersebut tidak memuat ElegantOTA/ESPAsyncWebServer/AsyncTCP.
   Panduan ini mencakup Telegram + relay + user management dan USB flashing.
3. Layout alamat flash yang ditulis adalah layout umum ESP32 klasik; verifikasi build/partition
   scheme dan gunakan boot_app0.bin dari ESP32 Arduino Core yang sesuai.
4. Pengguna menyatakan chip telah di-erase; jangan erase lagi sebelum flash.
