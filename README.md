# UAS-SENSOR
Repository ini berisikan project mata kuliah sensor dan tranduser - jurusan Mekatronika dan Kecerdasan Buatan - Universitas Pendidikan Indonesia Kampus Purwakarta. 

Anggota kelompok : Aisyah Aira Putri Maharani (2102727), Diana Eka Putri (2100041), Refrisca Lintang Pramesti (2103164), Muhamad Fajar Imannul Haq (2107617), Himmawan Saptha A (2100445). 
# i. Judul
ALAT PENDETEKSI HUJAN MENGGUNAKAN RAINDROP DAN DHT11 SENSOR

# ii. Problem 
Indonesia merupakan negara yang memiliki iklim tropis dengan dua musim yaitu musim hujan dan musim kemarau. Kedua musim ini di pengaruhi oleh Global Warming yang mengakibatkan kedua musim tersebut menjadi sulit diprediksi kedatangannya. Hal ini tentunya akan berpengaruh pada aktivitas manusia yang dalam kegiatannya membutuhkan cahaya matahari, misalnya kegiatan menjemur baju, makanan atau barang lainnya di luar ruangan. 

# iii. Solusi
Untuk mendeteksi hujan, selain intensitas curah hujan yang turun, kelembaban dan temperatur juga menjadi salah satu indikatornya. Data kelembaban dan temperatur sangat membantu pengamatan  diluar  ruangan karena  saat  kelembaban  udara  meningkat,  maka  curah  hujan  juga  akan  mengalami  kenaikan.    

oleh karena itu, dibuat sebuah alat pendeteksi hujan yang menggunakan sensor raindrop dan sensor DHT11 yang diharapkan dapat menjadi solusi dalam pendeteksian hujan.  

# iv. Analisis 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Deskripsi singkat

Alat pendeteksi hujan adalah sebuah alat yang digunakan untuk mendeteksi hujan berdasarkan intensitas air, suhu, dan kelembaban. Alat ini menggunakan sensor raindrop dan sensor DHT11 dimana data yang masuk akan di proses ke telepon genggam dan memunculkan nilai temperatur, nilai kelembaban dan nilai intensitas air.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Alat dan Bahan

  1). Esp8266
  
  2). raindrop sensor
   
  3). HL-01 modul
    
  4). DHT11

  5). Blynk Apps
  
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Cara kerja

Untuk pengujian nilai suhu dan nilai kelembaban, dilakukan pengujian dengan mendekatkan solder pada sensor DHT11 untuk memastikan apakah alat tersebut berjalan atau tidak. Untuk pengujian nilai intensitas air, dilakukan pengujian dengan meneteskan air pada sensor raindrop. nilai dari intensitas hujan kami setting ke nilai 100 untuk keadaan normal (tanpa air), sehingga ketika sensor raindrop diberi air, maka nilai intensitas air yang muncul pada telepon genggam akan semakin berkurang bergantung dari seberapa banyak air yang ada. 

selengkapnya pada : https://www.youtube.com/watch?v=wT8t1fPAsLU

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Pembahasan 

Sensor hujan atau disebut dengan Raindrop sensor merupakan sebuah alat yang mendeteksi hujan atau adanya cuaca hujan yang berada di sekitarnya. Sensor hujan bekerja berdasarkan perubahan nilai hambatan pada board sensor ketika mendeteksi air yang menyebabkan arus air sehingga dapat menandakan akan terjadi hujan. Semakin banyak air yang mengenai sensor, maka akan semakin cepat pula perubahan resistan pada sensor. Sensor ini juga dapat digunakan sebagai switch ketika ada tetesan air hujan yang jatuh mengenai raining board yang terdapat pada sensor. Selain itu raindrop sensor dapat digunakan untuk mengukur intensitas curah hujan. Output analog yang digunakan untuk melakukan pendeteksian hujan pada raindrop sensor yaitu pada saat tidak mendeteksi hujan maka nilai keluaran sensor tinggi, begitu pun sebaliknya pada saat sensor sedang mendeteksi hujan maka nilai keluarannya rendah. 

Selain raindrop sensor, sensor DHT11 juga digunakan untuk mendeteksi hujan berdasarkan dua parameter lingkungan sekaligus yaitu suhu dan kelembaban udara. Sensor DHT11 memiliki thermistor tipe NTC (Negative Temperature Coefficient) didalamnya. Sensor ini tergolong komponen yang memiliki tingkat stabilitas yang sangat baik. DHT11 memiliki fitur kalibrasi yang sangat akurat. Koefisien kalibrasi disimpan dalam one time programmable (OTP) program memori, sehingga ketika internal sensor mendeteksi sesuatu, maka module  ini  menyertakan  koefisien  tersebut  dalam  kalkulasinya  dengan  transimisi  sinyal  hingga  20  meter,  dengan  spesifikasi  Supply  Voltage :  +5  V,  Temperature  range :  0-50  °C error  of  ±  2  °C,  Humidity :  20-90% RH ± 5% RH error.  Sensor ini memiliki 4 kaki, yaitu pin VCC, Data, NC, dan GND. Prinsip kerjanya adalah memanfaatkan perubahan kapasitif, perubahan  posisi  bahan  dielektrik  diantara  kedua  keping, pergeseran  posisi  salah  satu  keping  dan luas keping yang berhadapan langsung.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Foto alat 

![sensor 1](https://user-images.githubusercontent.com/92429478/173230333-31d6d82c-4fc6-4d17-b0ea-44e08f2d378c.jpeg)

![sensor 2](https://user-images.githubusercontent.com/92429478/173230403-473f5198-f7be-4adf-84bd-93e137b81d32.jpeg)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Foto contoh hasil 

![Hasil Alat sensor](https://user-images.githubusercontent.com/92429478/173232164-7f0b7691-2471-4ada-8176-6ca2b5141870.jpeg)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Wiring diagram 

![wiring diagram](https://user-images.githubusercontent.com/92429478/173231557-9bdb16c2-1ca6-4373-9c28-051af7250c9d.png)



# v. Referensi
Referensi review paper 

- "Rancang Bangun Prototipe Detektor Hujan Sederhana Berbasis Raindrop Sensor Menggunakan Buzzer dan LED" oleh Naila Fauza, Dina Syaflita, Safina Salma Ramadini, dan Jumira Annisa. Diakses dari https://ejournal.unib.ac.id/index.php/kumparan_fisika/article/download/16911/9431.
- "Pengembangan Sistem Akuisisi Data Kelembaban Dan Suhu Dengan Menggunakan Sensor Dht11 Dan Arduino Berbasis IOT" oleh Kabul Setiya Budi dan Yudhiakto Pramudya. Diakses dari http://journal.unj.ac.id/unj/index.php/prosidingsnf/article/view/4114/3081

