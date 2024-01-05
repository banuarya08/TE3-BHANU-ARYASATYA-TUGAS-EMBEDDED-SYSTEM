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

## Hasil A


https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/c47d1b87-6d8e-4f77-be26-12abb405f08e



## Kesimpulan
ESP akan menampilkan kumpulan SSID WiFi yang tersedia di sekitarnya. Setelah itu, Anda diminta untuk memasukkan IP Address yang muncul di serial monitor ke dalam browser dan mengisi formulir yang disediakan dengan SSID dan Password yang sesuai. Setelah melakukan langkah-langkah tersebut, ESP akan berhasil terhubung ke jaringan WiFi yang telah dipilih, dalam hal ini, jaringan WiFi dengan SSID "alfingay". Hasil akhirnya adalah ESP akan menampilkan pesan "Connected to alingay successfully" untuk menunjukkan bahwa koneksi ke jaringan WiFi "alfingay" telah berhasil dilakukan.



## B. Transmisi Data Menggunakian Protokol HTTP
# 1. Metode Get
# a. Ranngkaian
![flowchart 4 b](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/cb7ee371-6a34-45ae-9929-c93e8996e200)

# b. Hasil dan Pembahasan
Pada percobaan ini, langkah pertama yang dilakukan adalah membuat database banjir_db dan diisi dengan tabel smartwater. Struktur dalam tabel mengikuti panduan jobsheet. Install terlebih dahulu node-red-dashboard pada bagian manage pallette kemudian import kode JSON Multi-Protocol IoT Server ke Node-Red untuk menampilkan flow rangkaian. Kemudian, install libraru JSON5 pada Arduino dan upload program protokol HTTP dengan metode GET. Setelah berhasil diupload, klik Deploy pada Node-Red. Hasil percobaan dapat dilihat pada Serial Monitor Arduino, Debug Node-Red, dan juga Dashboard Node-Red. Hasil akan terlihat seperti berikut.

- Serial Monitor
  
![serialmonitor](https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/58c6b8f1-3fc2-4f0c-b061-f17cb725802f)

- Debug
  
![debug node-red](https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/28bfe678-435c-41fd-a329-66d2bca0a6de)

- Dashboard

![node-red dashboard](https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/78d847b8-80c3-4ffe-ba19-b9b6ad9df883)


- ![flowchart d](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/7e767273-a97c-44d1-8198-27db56256c75)



  ## 2. Metode Post
  # a. rangkaian
  Rangkaian pada percobaan ini adalah sebagai berikut
![flowchart 4 b](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/2dc3916d-8435-442a-a02a-c90bd417ea80)

# b. Hasil Pembahasan
- serial monitor

  ![serialmonitor 2](https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/8b4ea9d9-cd76-484e-84fc-10f1ad164b0c)


- debug

![debug node-red 2](https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/d77da297-a901-40bd-8365-98a46e4ca2f8)


- dashboard

![node-red dashboard 2](https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/e512a82b-1579-425b-b18d-c5f46aacb052)

- flowchart
  
![flowchart d](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/728d8307-173c-48c0-bad3-76d948d867d7)

## 3. Transmisi Data Menggunakan Protokol MQTT
# Hasil Percobaan

- serial monitor
  
![serialmonitor](https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/d977f02e-5833-4842-a1b3-efdd0bb445d1)

- debug
  
![debug](https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/4815b0f9-2dd7-4735-a1ec-669d65b53a91)

- dashboard

  ![dashboard](https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/410be49d-5efa-4870-a6d5-8ebc7816dc03)


 ## 4.Akuisi Data Kendali Perangkat IoT Menggunakan Protokol MQTT
 # Hasil Percobaan

 - serial monitor
   
![serialmonitor](https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/5463607c-a747-400b-b305-881dfbdf3b68)

 - debug
   
![debug](https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/6271674e-27fe-4c53-9c6a-be667a34c2b2)

 - dashboard
   
![dashboard](https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/3f16bb04-d3ea-426e-8d33-15f3ee598f78)

# Hasil Video

- Adafruit

https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/a08ec421-eae3-47df-aab1-e529c04c2722

- Dashboard
  

https://github.com/banuarya08/TE3-BHANU-ARYASATYA-TUGAS-EMBEDDED-SYSTEM/assets/146574933/cd2a31e6-a8b6-4568-a325-9d8fcea335dd

## Analisa
Pada percobaan pertama dilakukan  proses setting SSID dan Password Wi-Fi ESP32 melalui Web Server dan penggunaan Serial Monitor Arduino IDE, sehingga serial Monitor pada Arduino IDE digunakan untuk memantau status dan informasi dari ESP32. Jika ESP32 belum terhubung ke jaringan Wi-Fi, Serial Monitor akan menampilkan daftar SSID Wi-Fi yang tersedia di sekitar. Daftar SSID Wi-Fi yang ditampilkan pada Serial Monitor memberikan interaktivitas kepada pengguna. Mereka dapat memilih jaringan Wi-Fi yang diinginkan dari daftar tersebut. Serial Monitor Arduino IDE tetap memberikan visibilitas terhadap status koneksi dan proses konfigurasi. Hal ini memudahkan pemantauan dan pemecahan masalah jika terjadi kendala selama proses konfigurasi. Pendekatan ini memberikan fleksibilitas bagi pengguna untuk mengonfigurasi perangkat tanpa perlu pengetahuan mendalam tentang konsep pemrograman. Dengan menggunakan formulir web dan Serial Monitor, proses ini menjadi lebih user-friendly.
Dengan demikian, kombinasi pengaturan melalui web server dan pemantauan melalui Serial Monitor memberikan pengguna pengalaman konfigurasi yang lebih interaktif, mudah, dan efisien pada perangkat ESP32. Pada percobaan kedua yaitu Transmisi Data Menggunakan Protokol HTTP yang mana data yang ditransmisikan menggunakan HTTP umumnya bersifat teks (plain text).Meskipun ini mempermudah pemahaman dan debugging, namun dapat menimbulkan masalah keamanan jika tidak dienkripsi. Sehingga Meskipun HTTP memiliki keunggulan dalam kejelasan dan kemudahan penggunaan, ia memiliki keterbatasan dalam kinerja dan efisiensi bila dibandingkan dengan protokol komunikasi yang dioptimalkan untuk transmisi data besar atau real-time, seperti WebSocket.Dengan keunggulan universalitas, fleksibilitas metode komunikasi. Pada percobaan ke tiga adalah Transmisi Data Menggunakan Protokol MQTT MQTT (Message Queuing Telemetry Transport) didesain untuk transmisi data yang efisien, membuatnya cocok untuk perangkat terbatas daya dan jaringan yang tidak stabil. Protokol ini menggunakan overhead yang rendah dan memiliki ukuran pesan yang kecil. Namun MQTT dirancang untuk bekerja di atas protokol TCP/IP dan dapat mengatasi keterbatasan jaringan seperti koneksi yang tidak stabil atau bandwidth yang terbatas.Pada percobaan ke empat melakukan Akuisi Data dan Kendali Perangkat IoT Menggunakan Protokol MQTT. MQTT menyediakan mekanisme yang efisien untuk mengakuisisi data dari berbagai perangkat IoT. Dengan model publikasi/berlangganan, perangkat dapat mengirim data saat terjadi perubahan, mengoptimalkan penggunaan bandwidth. Melalui MQTT, perangkat IoT dapat dipantau dan dikelola dari jarak jauh. Pengguna dapat mengirimkan perintah konfigurasi atau memonitor status perangkat secara efisien.

## Kesimpulan
Dari percobaan yang sudah dilakukan, dapat disimpulkan bahwa:
- Konfigurasi melalui Web Server & Serial Monitor ESP32 mudah digunakan.
- HTTP sederhana namun rentan, sementara MQTT efisien & cocok untuk IoT.
- MQTT memungkinkan pengawasan & kendali perangkat IoT dari jarak jauh dengan efisiensi.


