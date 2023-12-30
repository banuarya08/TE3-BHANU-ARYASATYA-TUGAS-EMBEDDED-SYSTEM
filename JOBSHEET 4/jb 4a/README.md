# JOBSHEET 4 - TRANSMISI DATA MENGGUNAKAN PROTOKOL HTTP DAN MQTT
![GAMBAR PENDAHULUAN](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/da114f33-7190-4331-aef1-096c8ef7a43e)
## Abstrak
Jobsheet ini fokus pada pemahaman dan implementasi protokol HTTP dan MQTT untuk transmisi data pada Platform IoT Node-Red. HTTP, atau Hypertext Transfer Protocol, berfungsi sebagai protokol jaringan lapisan aplikasi yang digunakan dalam sistem informasi terdistribusi dan kolaboratif dengan menggunakan hypermedia. Umumnya diimplementasikan untuk melayani permintaan data dari pengguna dan manajemen situs web. Di sisi lain, MQTT atau Message Queuing Telemetry Transport merupakan protokol komunikasi yang beroperasi di atas stack TCP/IP dan dirancang khusus untuk komunikasi Machine-to-Machine (M2M). MQTT bersifat open source, lightweight, memiliki overhead protokol yang rendah, konsumsi daya yang kecil, dan mampu bekerja pada latency tinggi serta bandwidth yang kecil. Jobsheet ini memiliki tujuan ganda, yakni memberikan pemahaman mendalam tentang cara kerja kedua protokol tersebut dan memfasilitasi praktik merancang serta melakukan konfigurasi pada perangkat Internet of Things (IoT). Penerapan protokol HTTP dan MQTT pada Node-Red IoT Platform diarahkan untuk keperluan monitoring dan kendali, memungkinkan transmisi efisien data seperti akuisisi data dan pengendalian perangkat IoT.
Sub - job pada jobsheet ini, antara lain :
1. Setting SSID dan Pasword Wi-Fi ESP32 melalui Web Server
2. Transmisi Data Menggunakan Protokol HTTP
3. Transmisi Data Menggunakan Protokol MQTT
4. Akuisi Data dan Kendali Perangkat IoT Menggunakan Protokol MQTT
5. Pertanyaan dan Tugas

Flowchart 
![flow](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/ed0f1630-b665-4bcd-ad23-b8bcaf3bc930)

## ALat dan Bahan
Alat dan Bahan yang digunakan dalam Praktikum ini, antara lain :
1. ESP32 dan Server Node-Red
2. Breadboard
3. Kabel jumper
4. Sensor DHT 11
5. LED (5)
6. Resistor 330, 1K, 10K Ohm (3)

## Hasil 
Hasil 1.1

https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/36093f13-e594-4fc6-985e-247022a05586

ESP Daftar SSID
![esp daftar ssid](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/c4787d7c-f7b6-4003-abf4-b3596f4a8b42)

Hasil 1-2

![hasil-1-2](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/740f839d-0e4e-46fd-9f2d-fc2449e83043)

Hasil 1.3

https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/a1ca9780-09f7-4cb7-9781-028393f7e1b1

## Kesimpulan
ESP akan menampilkan kumpulan SSID WiFi yang tersedia di sekitarnya. Setelah itu, Anda diminta untuk memasukkan IP Address yang muncul di serial monitor ke dalam browser dan mengisi formulir yang disediakan dengan SSID dan Password yang sesuai. Setelah melakukan langkah-langkah tersebut, ESP akan berhasil terhubung ke jaringan WiFi yang telah dipilih, dalam hal ini, jaringan WiFi dengan SSID "alfingay". Hasil akhirnya adalah ESP akan menampilkan pesan "Connected to alingay successfully" untuk menunjukkan bahwa koneksi ke jaringan WiFi "alfingay" telah berhasil dilakukan.



## B. Transmisi Data Menggunakian Protokol HTTP
# 1. Metode Get
# a. Ranngkaian
![flowchart 4 b](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/cb7ee371-6a34-45ae-9929-c93e8996e200)

# b. Hasil dan Pembahasan
Pada percobaan ini, langkah pertama yang dilakukan adalah membuat database banjir_db dan diisi dengan tabel smartwater. Struktur dalam tabel mengikuti panduan jobsheet. Install terlebih dahulu node-red-dashboard pada bagian manage pallette kemudian import kode JSON Multi-Protocol IoT Server ke Node-Red untuk menampilkan flow rangkaian. Kemudian, install libraru JSON5 pada Arduino dan upload program protokol HTTP dengan metode GET. Setelah berhasil diupload, klik Deploy pada Node-Red. Hasil percobaan dapat dilihat pada Serial Monitor Arduino, Debug Node-Red, dan juga Dashboard Node-Red. Hasil akan terlihat seperti berikut.
- Serial Monitor
![serial monitor 1](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/b4c50e06-8500-43f1-b6c7-124d8048a880)

- Debug
![debug stlh 1](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/1b815d00-bd25-4edc-8ac5-6609aa9b9a9b)

- Dashboard
![dashboard 1](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/715d098b-aaa6-4d90-81ae-8805f9851b96)

- flowchart
- ![flowchart d](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/7e767273-a97c-44d1-8198-27db56256c75)

  ## 2. Metode Post
  # a. rangkaian
  Rangkaian pada percobaan ini adalah sebagai berikut
![flowchart 4 b](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/2dc3916d-8435-442a-a02a-c90bd417ea80)

# b. Hasil Pembahasan
- serial monitor
  
  ![serial monitor 2](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/02f0bbd7-b2de-4559-b923-8276aa8b0375)

- debug

![debug 2](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/2441c26d-bb5e-4fd3-86d1-abfeee0230b4)

- dashboard


![dashboard 2](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/dfcc69ec-6c95-41cf-b6a8-87f329e4b920)

- flowchart
  
![flowchart d](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/728d8307-173c-48c0-bad3-76d948d867d7)
