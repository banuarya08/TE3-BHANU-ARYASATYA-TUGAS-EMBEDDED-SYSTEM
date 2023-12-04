### TRANSMISI DATA MENGGUNAKAN MESSAGE QEUING TELEMETRY TRANSPORT (MQTT) PROTOCOL
## 1. Keterangan singkat (Abstrak)
![abstrak 1](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/9c7eed81-d209-4e35-82b1-a06ce7bc033e)
![abstrak 2](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/27029c28-37a0-40c8-9d3a-c54511c49013)

MQTT (Message Queuing Telemetry Transport) adalah protokol ringan yang digunakan untuk mentransmisikan data dengan efisien melalui jaringan. Dengan model Pub/Sub, MQTT memisahkan pengirim dan penerima data. Protokol ini menonjol karena penggunaan bandwidth yang efisien, dukungan untuk koneksi dengan daya terbatas, dan kemampuan untuk menyimpan sementara pesan. Cocok untuk aplikasi IoT, MQTT menawarkan keandalan melalui tingkat Quality of Service (QoS) yang dapat disesuaikan. Dengan fitur seperti pesan yang tetap dan pesan terakhir dan wasiat, MQTT telah menjadi pilihan populer untuk transmisi data andal dalam berbagai lingkungan.


![3](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/19e563f3-cb6d-4265-990e-a96235a8f49e)

## 2. Alat dan Bahan
1. ESP32                     ==> 1 buah
2. Potensiometer             ==> 1 buah
3. Breadboard                ==> 1 buah
4. Kabel Jumper
5. Multimeter
6. Sensor DHT 11 
7. Resistor 1K

## 3. Hasil
## Jobsheet 6 a
![6a](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/f774c648-3e3e-4359-8768-a4ef238cc855)
![6a(2)](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/61eb2e14-9bf7-42b8-ae94-0267cd148ffb)

## Jobsheet 6 b
![6b](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/856d5b22-d86a-45d4-bb2f-753117348b74)
![6b(2)](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/2f6453d3-4b0c-48ec-9189-84ddac6c53e2)
## Hasil tugas dari 6 b
![jb 6 tugas B](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/0480788d-2cdc-4e5d-9fdd-5af6ade8dcbb)

![hasil 6 tugas b](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/3b127182-f0c8-428b-91e6-8f10eea52f9b)

## Penjelasan singkat
Dalam praktikum Node-RED, koneksi ke broker MQTT (Message Queuing Telemetry Transport) memungkinkan perangkat dan sistem berkomunikasi secara efisien melalui protokol MQTT. Node-RED menyediakan opsi keamanan, seperti penggunaan protokol TLS/SSL, untuk memastikan keamanan komunikasi antara Node-RED dan broker MQTT. Dalam praktikum menerima data JSON melalui protokol MQTT pada pemrograman Node-RED, akan mengonfigurasi Node-RED untuk berlangganan  ke topik MQTT yang mengirimkan data dalam format JSON. Praktikum ini memberikan pengalaman praktis dalam mengimplementasikan aliran kerja (workflow) yang menerima dan memproses data JSON melalui protokol MQTT menggunakan Node-RED. Dalam praktikum mengirim dummy data untuk simulasi I/O menggunakan hardware pada pemrograman Node-RED, Anda akan menggunakan node simulasi atau dummy untuk menghasilkan data yang seolah-olah berasal dari perangkat keras atau input/output (I/O) sebenarnya. Praktikum ini menjelaskan Ketika  dalam simulasi I/O menggunakan hardware pada Node-RED, memungkinkan pengguna untuk mengembangkan dan menguji logika pemrograman tanpa perlu mengakses perangkat keras sebenarnya.

## Kesimpulan
Dari praktikum ini, didapat pemahaman yang kokoh mengenai penerapan MQTT untuk mengirimkan data antar perangkat yang terhubung dalam jaringan. MQTT terbukti menjadi alat yang vital dalam pengembangan aplikasi IoT serta memfasilitasi pemantauan dari jarak jauh. Memiliki pemahaman yang kuat terhadap konsep MQTT sangatlah bernilai dalam konteks ini, karena menjadi fondasi yang penting dalam mengelola transmisi data yang efisien dan handal di lingkungan jaringan yang kompleks. Dengan pemahaman mendalam mengenai MQTT, praktikum ini memberikan dasar yang kokoh bagi pengembangan solusi-solusi aplikatif dalam domain IoT dan pemantauan jarak jauh.
