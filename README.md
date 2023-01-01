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

4. Tambahkan 1 LED dan 1 push button pada rangkaian, kemudian kembangkan program agar ketika push button ke-2 ditekan, LED akan melakukan blink setiap 500 ms sekali. Kemudian dokumentasikan hasilnya.

https://user-images.githubusercontent.com/118172386/210172246-ca2301a3-39a1-4bc1-a2c7-60396f990e8c.mp4

5. Tambahkan 3 LED dan 1 push button pada rangkaian, kemudian kembangkan program agar ketuka push button ke-3 ditekan, LED akan menyala menjadi running led (menyala bergantian dari kiri ke kanan). Setelah itu dokumentasikan hasilnya.

https://user-images.githubusercontent.com/118172386/210172259-cad10e4b-bb9e-40e2-8eff-e0dacccc24dd.mp4

b) PWM

1. Buatlah rangkaian seperti pada gambar di bawah ini.

![Capture](https://user-images.githubusercontent.com/118172386/210172286-de54c8f4-7a38-4fc0-a6a6-682a34644060.JPG)

2. Buatlah script program seperti berikut.
3. Upload program tersebut, kemudian amati dan analisis apa yang terjadi serta dokumentasikan hasilnya

https://user-images.githubusercontent.com/118172386/210172327-d4263dbf-5d91-453e-8382-f7f40eb24e50.mp4

4. Buatlah program lanjutan seperti pada script berikut ini.
5. Upload program tersebut, kemudian amati dan analisis apa yang terjadi serta dokumentasikan hasilnya.

https://user-images.githubusercontent.com/118172386/210172352-3ef1fd2f-fc34-4bcb-b895-902764eb0b27.mp4

C. ADC dan DAC
1. Buatlah rangkaian seperti pada gambar di bawah ini.

![Capture1](https://user-images.githubusercontent.com/118172386/210172373-b737083a-5ebb-402a-878a-245a3b3dfc52.JPG)

2. Buatlah program seperti pada script berikut ini
3. Putar potensiometer secara perlahan agar mendapatkan nilai 0 hingga 4095 pada tampilan serial monitor. Analisis apa yang terjadi dan dokumentasikan hasilnya.


https://user-images.githubusercontent.com/118172386/210172404-85a9d5fd-c17c-4f91-8297-3c26153d8067.mp4

4. Buatlah program seperti pada script berikut ini.Tambahkan LED pada GPIO5.
5. Upload program, kemudian putar potensiometer dari nilai terendah hingga nilai tertinggi. Amati yang terjadi, analisis dan dokumentasikan hasilnya.


https://user-images.githubusercontent.com/118172386/210172437-70ff65f5-ca19-4424-a879-51388817cd34.mp4


