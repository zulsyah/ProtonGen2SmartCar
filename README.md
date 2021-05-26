# Proton Gen2 SmartCar v1.0
oleh AZ Putra

Anda boleh melihat projek saya yang lain di halaman Digital CV saya : http://cv.zulsyah.com

# Bahasa Melayu #

Assalamualaikum, syukur ke hadrat ilahi kerana dengan kurniaNya saya dapat menghasilkan projek ini. Projek ini masih tidak siap sepenuhnya tapi saya berpuas hati dengan apa yang saya dapat capai.

Laman Github ini mengandungi kod sumber (source code) untuk projek ini. Antaranya ialah :- 

- **Pelayan :** Python 3.7
- **Nod :** Arduino C++
- **Aplikasi mudah alih :** MIT App Inventor

Untuk memuat turun kod Arduino, sila muat turun fail yang bernama `ESP8266_SmartCar.ino` manakala untuk memuat turun fail (.aia), sila muat turun fail yang bernama `HondaCRV_RD1_smartcar.aia`.

### Litar skematik dan cara pasang

Anda boleh melihat litar skematik yang lengkap pada laman Instructable saya di https://www.instructables.com/Honda-CRV-RD1-SmartCar-V10/.

### Cara penggunaan sistem ini

1. Buka fail `ESP8266_SmartCar.ino` menggunakan Arduino IDE
2. Muat turun aplikasi Blynk dari Google Play Store pada telefon anda
3. Daftarkan NodeMCU ESP8266 anda dan dapatkan token Blynk anda menggunakan aplikasi tersebut
4. Ubah nama dan katalaluan WiFi anda serta token Blynk yang anda perolehi tadi

```java
//Token Blynk anda
char auth[] = "Your Blynk Auth";

//Nama dan kataluan WiFi anda
char ssid[] = "Your SSID";
char pass[] = "Your WiFi password";
```
5. Simpan dan muat naik kod tersebut ke ESP8266
6. Buka fail `HondaCRV_RD1_smartcar.aia` dengan mengimport ke MIT App Inventor
7. Cari `global token` dan ubah kepada token Blynk anda seperti dibawah
<p align="centre"> <img src="https://i.imgur.com/xWP7rzB.jpg"> </p>

### Antara muka pengguna aplikasi ini

Aplikasi ini hanya mempunyai satu antara muka sahaja.
<p align="centre"> <img src="https://i.imgur.com/OzQiomU.jpg" width="25%" height="25%"> </p>
10 | MB102 830 Holes Large Solderless Breadboard | 

BlynkSimpleEsp8266 | ESP8266WiFi | dht11 | SoftwareSerial
----- | ----- | ----- | ----- |
**TinyGPS++** | **Arduino** | **PCF8574** | **Adafruit_ADS1015**

__________________________________________________________________________________________________________________
