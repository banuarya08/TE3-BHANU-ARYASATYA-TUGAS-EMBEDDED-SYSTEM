# JOBSHEET 7 - TRANSMISI DATA MENGGUNAKAN HYPER TEXT TRANSFER PROTOCOL (HTTP)

## Abstrak
Protokol Hypertext Transfer Protocol (HTTP) adalah sebuah protokol jaringan lapisan aplikasi yang digunakan dalam sistem informasi terdistribusi, kolaboratif, dan berbasis hipermedia. HTTP pertama kali diperkenalkan pada tahun 1990 oleh Tim Berners-Lee sebagai bagian integral dari pembentukan World Wide Web. Terdapat dua versi mayor dari HTTP, yakni HTTP/1.0 dan HTTP/1.1. Pada HTTP/1.0, setiap dokumen memerlukan koneksi terpisah, sementara pada HTTP/1.1, efisiensi ditingkatkan dengan memungkinkan penggunaan koneksi yang sama untuk transaksi berulang.

Proses pengembangan standar HTTP melibatkan Konsorsium World Wide Web (W3C) dan Internet Engineering Task Force (IETF). Pada Juni 1999, RFC 2616 diterbitkan untuk mendefinisikan spesifikasi HTTP/1.1. Fungsinya adalah sebagai protokol permintaan dan jawaban antara klien, seperti web browser, dan server, dengan klien yang dikenal sebagai user agent.

Jobsheet ini memiliki tujuan utama untuk memahami alur kerja, kegunaan, dan manfaat protokol HTTP. Lebih lanjut, jobsheet ini juga bertujuan untuk memberikan pemahaman serta implementasi protokol HTTP dalam konteks sistem Internet of Things (IoT), khususnya untuk tujuan monitoring dan kendali. Dengan demikian, peserta diharapkan dapat menggambarkan secara komprehensif bagaimana HTTP berperan dalam menjembatani interaksi antara klien dan server pada lingkungan IoT.

Sub-job pada jobsheet ini, antara lain :
1. Instalasi SQL
2. Basic Flow Transmisi HTTP
3. Mengirim Data JSON ke Server dan Menyimpannya ke Database

## Alat dan Bahan
Alat dan Bahan yang digunakan dalam praktikum ini :
1. Komputer terpasang Node Red
2. Postman

## Hasil Percobaan 
## A. Instalasi SQL Server (MySQL)

![JB 7 A](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/252aeef0-5825-4bfd-8131-321f6a5e8bf3)

## B. Basic Flow Transmisi Data Menggunakan Protokol HTTP

- database
  
  ![JB 7 DATABASE](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/a3c5e38c-8d08-4085-9768-eab6384a1c6a)

- body
  
  ![7B body](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/b857ec4f-6326-4495-9bcf-c0aa54a3ec14)

- body status ok
  
  ![7B body status ok](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/c093a95a-8fd5-4ab3-9374-792b7088cd79)

- body error
  
  ![7b body error](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/7175cf0a-0191-45a0-b904-2612376454d6)

- hasil error
  
  ![7b hasil error](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/56e51dce-111b-441d-bbae-d6459a5fcc4d)

- hasil ok
  
  ![hasil 7b ok](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/e17bb031-9b42-4910-a4a2-d9e52697a8ba)

## Analisa
Transmisi Data Menggunakan Hypertext Transfer Protocol (HTTP) dirancang untuk memberikan peserta pemahaman mendalam tentang penggunaan HTTP dalam mentransmisikan data. Penjelasan sejarah HTTP oleh Tim Berners-Lee pada tahun 1990 memberikan konteks penting tentang evolusi protokol ini. Fokus pada versi HTTP/1.0 dan HTTP/1.1 membuka wawasan mengenai peningkatan efisiensi dengan penggunaan koneksi yang sama pada versi terakhir.

Pentingnya pengembangan standar HTTP melalui keterlibatan Konsorsium World Wide Web (W3C) dan Internet Engineering Task Force (IETF), dengan penerbitan RFC 2616 pada tahun 1999, menekankan pentingnya protokol ini dalam struktur internet. Implementasi HTTP dalam konteks sistem Internet of Things (IoT) untuk monitoring dan kendali menambah dimensi praktis, mengaitkan teori dengan aplikasi nyata. Praktikum ini menjadi kesempatan bagi peserta untuk merancang dan mengimplementasikan solusi berbasis HTTP, meningkatkan pemahaman mereka tentang bagaimana protokol ini berperan dalam transmisi data efektif antara klien dan server. Dengan demikian, praktikum ini tidak hanya mengajarkan dasar-dasar HTTP, tetapi juga mendorong penerapan praktis dalam konteks teknologi terkini.

## Kesimpulan
Praktikum ini secara efektif membahas penggunaan Hypertext Transfer Protocol (HTTP) dalam transmisi data, dengan menyoroti evolusi versi HTTP/1.0 ke HTTP/1.1 untuk meningkatkan efisiensi. Keterlibatan Konsorsium World Wide Web (W3C) dan Internet Engineering Task Force (IETF) dalam pengembangan standar, terutama RFC 2616, menekankan pentingnya protokol ini dalam struktur internet. Implementasi HTTP pada sistem Internet of Things (IoT) dalam konteks monitoring dan kendali menambah nilai praktis. Kesimpulannya, praktikum ini berhasil menggabungkan teori dan aplikasi nyata, memberikan pemahaman menyeluruh tentang peran HTTP dalam transmisi data yang efektif.
