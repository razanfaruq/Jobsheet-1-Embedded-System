# Jobsheet-1-Embedded-System

### DASAR PEMROGRAMAN ESP32 UNTUK PEMROSESAN DATA INPUT/OUTPUT ANALOG DAN DIGITAL

##### I. Teori Dasar
 

ESP-32 adalah mikrokontroler yang dikenalkan oleh Espressif System merupakan penerus dari mikrokontroler ESP8266. Pada mikrokontroler ini sudah tersedia modul WiFi     dalam chip sehingga sangat mendukung untuk membuat sistem aplikasi Internet of Things. Perbedaan antara ESP32 dengan ESP8266 adalah pada bagian prosesornya. ESP32 sudah  Dual-Core 32 bit, jelas lebih cepat ESP32 secara kinerja. Selain itu modul ini juga mempunyai bluetooth, satu fitur yang tidak ada di ESP8266.

##### II. Alat dan Bahan yang Digunakan
1) ESP32
2) Breadboard
3) Kabel jumper
4) Potensiometer 10k Ohm (1)
5) Sensor Capacitive Soil Moisture
6) LED (5) dan Push Button (3)
7) Multimeter
8) Resistor 330,1K, 10K Ohm (@ 3)

##### III. Percobaan
A. Instalasi Board ESP32 pada Arduino IDE
   1. Buka Arduino IDE
   2. Kemudian klik Menu File > Preferences
   3. Pada kolom Additional ... yang ada dibawah, tambahkan link berikut https://dl.espressif.com/dl/package_esp32_index.json
   4. Klik menu Tools > Board: > Pilih Boards Manager ...
   5. Pada kolom pencarian tulis ESP32 kemudian install dan tunggu sampai selesai.

B. Mengakses GPIO dan PWM ESP32
a) GPIO
1. Buatlah rangkaian seperti pada Gambar di bawah ini.

![Capture](https://user-images.githubusercontent.com/118172386/210171226-b675b914-9494-4b29-8bde-1a4eab5dae88.JPG)

2. Buka program example blink, kemudian modifikasi dan buat agar LED dapat melakukan blink dengan interval 100ms, 1 detik, 2 detik dan 3 detik sekali. Setelah itu, buatlah program agar LED dapat blink 1 detik sekali menggunakan timer milis(). Dokumentasikan hasilnya.
3. Buatlah program seperti pada script GPIO1.ino untuk mengendalikan led menggunakan push button. Kemudian upload program tersebut pada ESP32 dan dokumentasikan hasilnya.


https://user-images.githubusercontent.com/118172386/210171784-6ddea236-f50f-4674-bf9f-d0429c2e9351.mp4


b) PWM

C. ADC dan DAC


