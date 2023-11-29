# 1. ADC dan DAC | membaca nilai analog yang dihasilkan oleh potensiometer 

## 1. Keterangan Singkat (Abstrak)

Dalam percobaan ini program dibuat untuk dapat membaca nilai analog yang dihasilkan oleh potensiometer yang terhubung ke GPIO34 dan menampilkan nilai tersebut melalui komunikasi serial.

## 2. Alat dan Bahan
1. ESP32                     ==> 1 buah
2. Potensiometer 10k ohm     ==> 1 buah
3. Breadboard                ==> 1 buah
4. Kabel Jumper

### Rangkaian

![rangkaian 1](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/4b134fa2-8d30-490b-b9da-bdbc0fa9fd33)


## 3. Hasil dan Pembahasan

### Hasil Percobaan
## jobsheet 1.a

https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/4e673f96-e0cd-423f-813f-25920b0bca78

## jobsheet 1 gpio 4


https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/17cdc549-aff4-4504-ade6-e044684d9196


## jobsheet 1 gpio 5


https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/bd504045-df4c-494d-bcdb-77112360c397



### Flowchart

![283651896-fb0bebfc-f73a-4bbc-886b-bc8e87bf75fc](https://github.com/brianrahma/brian-system-embedded/assets/82065700/1da6ca03-86a3-4d92-9556-40f6d6c60286)

Pada percobaan ini program dirancang untuk membaca nilai analog dari sebuah potensiometer yang terhubung ke pin GPIO34 pada ESP32. Setiap kali program dijalankan, nilai yang dibaca dari potensiometer ditampilkan di Serial Monitor melalui komunikasi serial dengan baudrate 115200.

Pada fungsi setup(), program menginisialisasi komunikasi serial dengan Serial.begin(115200) dan memberikan jeda waktu 1 detik menggunakan delay(1000). Pada fungsi loop(), terdapat beberapa langkah utama. Pertama, program membaca nilai analog dari potensiometer menggunakan fungsi analogRead(potPin) dan menyimpannya dalam variabel potValue. Selanjutnya, nilai potensiometer tersebut ditampilkan di Serial Monitor menggunakan Serial.println(potValue). Serta terdapat delay sebesar 500 ms menggunakan delay(500) agar nilai potensiometer tidak terlalu cepat berganti dan lebih mudah diamati di Serial Monitor.

Percobaan ini bertujuan memonitor nilai potensiometer secara real-time melalui Serial Monitor. Potensiometer, dapat diubah nilai analognya dengan cara memutarnya. Hasilnya adalah nilai potensiometer tersebut akan terus ditampilkan di Serial Monitor, nilainya dengan rentang 0 hingga 4095.

<br></br>
# 2. ADC dan DAC | Mengatur Cahaya LED dengan Potensiometer menggunakan ADC dan PWM

## 1. Keterangan Singkat (Abstrak)

Dalam percobaan ini program dibuat untuk mengendalikan kecerahan LED menggunakan potensiometer sebagai input analog untuk mengatur kecerahan sebuah LED menggunakan modul PWM. Dengan membaca nilai dari potensiometer, program kemudian mengonversinya ke nilai PWM yang dapat mengendalikan kecerahan LED. 

## 2. Alat dan Bahan
1. ESP32                     ==> 1 buah
2. Potensiometer 10k ohm     ==> 1 buah
3. Breadboard                ==> 1 buah
4. LED                       ==> 1 buah
5. Resistor 220 Ohm          ==> 1 buah
6. Kabel Jumper

### Rangkaian

![rangkaian ADC 2](https://github.com/brianrahma/brian-system-embedded/assets/82065700/e308d705-1c89-4040-af1f-294cd4b59c91)

## 3. Hasil dan Pembahasan


### Hasil Percobaan

## Langkah 1


https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/922079a6-7c61-4222-b5c6-abe713783432


## PWM 2


https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/5ec75f3e-b769-425d-ae6c-c7048b466edd


## PWM 4


https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/bd6e22c2-a1db-4343-b24a-fed80e30916f



## Percobaan menggunakan tanah


## way tanah kering
![way meter tanah kering](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/f0e16bdd-a7ac-4c07-a764-23d4b6ca6016)
![nilai adc 805 kering](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/fbd202fd-137a-4db9-a65c-de56b2a8721f)

## way tanah basah
![way meter tanah basah](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/6a2d7e9d-cbe5-44b9-8631-9714f7d8e849)

![nilai adc 558 basah](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/2dcc429c-2012-488d-9bc1-2b17ca8be41a)

## way tanah lembab
![way meter tanah lembab](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/f5d38b30-a8e8-4ae8-b918-fbb1a13b4084)

![nilai adc 608 lembab](https://github.com/Baiqjulita/TE3A-BAIQ-JULITA-TUGAS-EMBEDDED-SYSTEM/assets/144913808/8c8aa9a4-c371-47dc-81cb-9daac04e2098)


### Flowchart

![FLOWCHART ADC 2](https://github.com/brianrahma/brian-system-embedded/assets/82065700/8daa59f4-5fa7-4009-be3e-2b65d1c099ac)


## 4. Kesimpulan

Percobaan dasar pemrograman ESP32 untuk pemrosesan data input/output analog dan digital memungkinkan kontrol fleksibel terhadap perangkat dengan hasil simpulan bahwa ESP32 dapat mengelola data analog dan digital dengan baik, memberikan dasar pemahaman tentang bahasa pemrograman, dan menunjukkan keterhubungan yang baik dengan berbagai perangkat input/output.
