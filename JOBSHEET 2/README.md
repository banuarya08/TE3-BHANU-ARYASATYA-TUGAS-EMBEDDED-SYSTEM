# 1. Jobshet 2 Protokol Komuniaksi dan Sensor
## Keterangan singkat (Abstrak)
ESP32 adalah nama dari mikrokontroler yang dirancang oleh perusahaan yang berbasis di Shanghai, China yakni Espressif Systems. ESP32 menawarkan solusi jaringan WiFi dan BLE. ESP32 menggunakan prosesor dual core yang berjalan di instruksi Xtensa LX16. Selain itu, ESP32 telah mendukung protokol komunikasi seperti I2C, UART dan SPI.

## 2.Alat dan Bahan
1. ESP32                     ==> 1 buah
2. Potensiometer 10k ohm     ==> 1 buah
3. Breadboard                ==> 1 buah
4. Kabel Jumper
5. Led (5 buah ) dan Push Button (3 buah)
6. Sensor DHT 11 RFID
7. Resistor 330, 1K, 10K Ohm (3 buah)

## Rangkaian 

![jobsheet 2](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/d0aa80c9-96bf-4f48-b176-f4f759127e05)

## 3. Hasil 


https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/477b6e95-9fd1-4b59-97f7-d7276c099055

![komponen 2a](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/1f32cff7-a6b5-4741-95b0-07c8d52677bd)

## Flowchart


ESP32 dengan capacitive touch sensor melibatkan penggunaan sensor sentuh kapasitif pada mikrokontroler ESP32. mempelajari konfigurasi pin, pembacaan nilai sentuh, dan implementasi aplikasi praktis seperti tombol sentuh atau kontrol interaktif.

# Jobsheet 2.1 JARINGAN SENSOR NIRKABEL MENGGUNAKAN ESP-NOW
## keterangan singkat (Abstrak)
ESP-NOW adalah protokol yang dikembangkan oleh Espressif, yang memungkinkan banyak perangkat untuk berkomunikasi satu sama lain tanpa menggunakan Wi-Fi. Protokol ini mirip dengan konektivitas nirkabel 2.4GHz berdaya rendah. Pendifinisian alamat (MAC Address) pada masing-masing ESP32 diperlukan pada awal konfigurasi. Setelah konfigurasi Alamat selesai dilakukan, jaringan peer-to-peer akan terbentuk dan perangkat tidak perlu melakukan handshaking kembali ketika akan berkomunikasi. Hal ini memunjukkan bahwa setelah perangkat ESP32 saling terpasang satu sama lain, koneksi akan tetap ada. Dengan kata lain, jika tiba-tiba salah satu ESP32 kehilangan daya atau diatur ulang, ketika restart, secara otomatis akan terhubung ke pasangan ESP32 yang telah terdefinisi alamatnya untuk melanjutkan komunikasi.

## 2. Alat dan Bahan
1. ESP32                     ==> 1 buah
2. Potensiometer 10k ohm     ==> 1 buah
3. Breadboard                ==> 1 buah
4. Kabel Jumper
5. Resistor 10K Ohm

## Rangkaian

![jobsheet 2 1](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/7f7b1866-f08f-410c-afc5-23a521b7c434)

## Hasil 
many to one receiver
![hasil many to one receiver](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/abe061c3-0c7d-4856-a212-c7764ce90833)

hasil mengirim pesan
![hasil mengirim pesan](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/407eecb8-8ee0-4945-97c4-550e41115379)

hasil one way two communication
![hasil one way two comunication](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/e990b269-7fe6-4b3d-a80d-e5a29791fdb2)


https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/59efd8bb-8e7a-49e3-b5c6-8a5d7379aeac

## Penjelasan Singlat
Pada praktikum ke 2 adalah protocol komunikasi dan sensor pada ESP32 yang menggunakan beberapa protocol yaitu protocol I2C adalah protokol komunikasi yang digunakan untuk menghubungkan mikrokontroler dengan berbagai perangkat seperti sensor, EEPROM, dan display.lalu ada SPI (Serial Peripheral Interface) SPI adalah protokol komunikasi seriel yang memungkinkan komunikasi cepat antara mikrokontroler dan perangkat lain. Lalu ada UART (Universal Asynchronous Receiver-Transmitter) UART adalah protokol komunikasi asinkron yang umum digunakan untuk mentransfer data antara perangkat. Lalu ada MQTT (Message Queuing Telemetry Transport) MQTT adalah protokol ringan dan berbasis publish-subscribe yang digunakan untuk komunikasi pada jaringan IoT. Selanjutnya ada HTTP/HTTPS Protokol HTTP/HTTPS digunakan untuk komunikasi web, memungkinkan ESP32 untuk berinteraksi dengan server atau layanan web.Pada praktikum 2.1 yang telah dilakukan dapat dijelaskan bahwa One-Way Communication Point to Point pada ESP32 sebagai pengirim (sender) mengirimkan data ke ESP32 lainnya sebagai penerima (receiver). Pengiriman data ini dapat dilakukan, misalnya, menggunakan protokol WiFi untuk mengirimkan data tanpa perlu tanggapan langsung. Setelah itu One-to-Many Communication pada ESP32 berarti satu ESP32 mengirimkan data kepada beberapa ESP32 sekaligus melalui koneksi nirkabel. Many-to-One Communication pada ESP32 Dalam konteks ESP32, many-to-one communication berarti beberapa ESP32 mengirimkan data ke satu ESP32 penerima melalui koneksi nirkabel.  Cara kerja Two way communication yaitu membutuhkan  dua ESP32 saling bertukar informasi. Satu ESP32 dapat bertindak sebagai pengirim yang mengirimkan data, sementara ESP32 lainnya berfungsi sebagai penerima yang menerima data tersebut. Sebaliknya, keduanya dapat bertukar peran sehingga komunikasi menjadi dua arah.

## Kesimpulan
Kesimpulan dari penelitian ini menunjukkan beberapa hal penting terkait dengan penggunaan ESP32 dalam konteks komunikasi dan implementasi model komunikasi tertentu:

1.  ESP32 menonjol dalam penggunaan beragam protokol komunikasi seperti I2C, SPI, UART, MQTT, dan HTTP/HTTPS. Ketersediaan berbagai           protokol ini menandakan fleksibilitas ESP32 dalam berinteraksi dengan sensor dan perangkat eksternal yang memakai protokol yang           berbeda-beda.
2.  Praktikum 2.1 secara rinci menggambarkan penerapan model komunikasi yang berbeda, mulai dari komunikasi satu arah titik ke titik,         komunikasi satu arah ke banyak perangkat, hingga komunikasi banyak perangkat ke satu tujuan pada platform ESP32. Ini menunjukkan          kemampuan ESP32 dalam menyesuaikan diri dengan beragam skenario komunikasi dalam konteks jaringan nirkabel.
