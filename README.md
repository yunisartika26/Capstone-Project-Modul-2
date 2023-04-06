# Capstone-Project-Modul-2

## Latar Belakang
Tindak kejahatan atau kriminalitas merupakan suatu tindakan antisosial yang melanggar hukum, berkaitan dengan merampas hak milik orang lain dan dapat menimbulkan suatu kerugian, ketidaknyamanan, dan ketidakpatutan dalam bermasyarakat (Soerjono dalam Saraswati, 1999). Hal ini dapat menimbulkan berbagai macam kerugian bagi seseorang yang menjadi korban, baik dari segi materil (ekonomis) maupun dari segi immaterial seperti hilangnya rasa aman, nyaman, dan tentram dalam kehidupan bermasyarakat (Maslichah, 2012). Tindak kejahatan dapat muncul karena disebabkan oleh berbagai faktor, yaitu faktor personal, faktor sosial, dan faktor situasional yang mendorong pelaku untuk melakukan kejahatan (Separovic dalam Weda, 1996), dengan kata lain faktor lingkungan sangat berpengaruh (Davidson, 1981).

Kali ini saya akan mencoba mencari insight atau informasi dari laporan data kejahatan di kota Boston.Boston sendiri merupakan ibu kota dan kota terbesar di Massachusetts di Amerika Serikat. Kota ini salah satu kota tertua dan terkaya di A.S dengan luas wilayah sekitar 232,1 km² dan memiliki jumlah penduduk lebih dari 600 ribu jiwa.Data ini merupakan data resmi yang dicatat oleh Boston Police Department dari tahun 2015 sampai tahun 2018.

## Pernyataan Masalah
Tujuan utama pengumpulan data tindak kejahatan adalah untuk mengenali pola suatu tindakan kriminal agar dapat diantisipasi dan dicegah dimasa depan.

Sebagai seorang data analyst, untuk mengenali suatu pola tindakan kriminal dari laporan data kejahatan di kota Boston yang kita miliki, maka kita perlu menjawab beberapa pertanyaan berikut:

1. Kejahatan saja apa yang sering terjadi di kota boston?
2. Di distrik manakah yang paling banyak terjadi tindakan kejahatan? sehingga harus mendapatkan perhatian khusus dari Departemen Kepolisian di Boston.
3. Kapan biasanya tindak kejahatan sering terjadi? sehingga Departemen Kepolisian di Boston dapat melakukan patroli di jam-jam tersebut.

## Data Understanding and Cleaning
1. Menghapus Data Duplikat
2. Menangani Missing Values SHOOTING, UCR_PART, DISTRICT, REPORTING_AREA, STREET, Lat dan Long
3. Cek Outlier

## Data Yang Sudah Bersih
1. Menambah Kolom Baru
   *TIME : Morning (4:00-11:59), Afternoon (12:00-19:59), Night (20:00-3:59)
   *WEEK : Weekend (‘Saturday’, ’Sunday’), Weekday (‘Monday’ s.d. ‘Friday’)
   *DISTRIK: mengganti nomer distrik menjadi nama distrik agar mempermudah analisa

2. Analisa Data
   *Kejahatan saja apa yang sering terjadi di kota boston?
   *Di distrik manakah yang paling banyak terjadi tindakan kejahatan?
   *Kapan biasanya tindak kejahatan sering terjadi?


## **Kesimpulan**
*   Kejahatan saja apa yang sering terjadi di kota boston?
> * tindakan kejahatan yang paling sering terjadi adalah tindakan kejahatan yang membutuhkan tindakan investigasi dan diikuti kebutuhan bantuan medis yang dilakukan polisi terhadap korban/individu ditempat kejadian. dimana jumlah kasusnya sebanyak 17.885 atau sebesar 6.00% dari total kasus.
> * kemudian disusul oleh tindakan kejahatan dengan pengrusakan properti atau vandalisme sebanyak 14628 kasus, lalu disusul dengan pengrusakan harta benda akibat kecelakaan kendaraan bermotor sebanyak 14.569 kasus.
* Di distrik manakah yang paling banyak terjadi tindakan kejahatan?
> * Distrik Roxbury merupakan distrik dengan jumlah tindak kejahatan terbesar yaitu 15,49% dari total tindak kejahatan
>* Distrik Roxbury juga merupakan distrik dengan kasus yang membutuhkan bantuan medis paling banyak, yang kemudian disusul oleh distrik Dorchester
* Kapan biasanya tindak kejahatan sering terjadi?
> *  Jumlah kasus tertinggi terjadi pada siang hari yaitu pada rentang waktu (12:00 - 19:59).
> *  jumlah kejahatan relatif meningkat pada bulan Maret-Agustus
> *  rata-rata tindak kejahatan di weekday cenderung lebih tinggi dibandingkan tindak kejahatan di weekend, teruma pada hari jumat, kejahatan cenderung meningkat.

## **Rekomendasi**
1. Memberikan pelatihan Pertolongan Pertama pada polisi yang berjaga agar polisi yang datang terlebih dahulu ke lokasi dapat memberikan pertolongan pertama terhadap korban/individu yang mungkin dapat menentukan keselamatan korban.
2. Pihak Kepolisian berkoordinasi dengan beberapa Rumah sakit terdekat dimana tindakan kriminal yang membutuhkan bantuan medis sering terjadi yaitu di distrik Roxbury dan distirk Dorchester, serta memastikan bahwa peralatan medis dirumah sakit tersebut lengkap dan memadai.
3. Pihak Kepolisian bisa melakukan penambahan jumlah polisi yang patroli diwaktu-waktu tindak kejahatan mengalami kenaikan yaitu pada Siang Hari (12:00-19.59), terutama pada weekdays di hari jumat. selain itu kepolisian juga bisa menambah perhatian pada bulan Maret-Agustus karena dibulan tersebut kasus kejahatan cenderung meningkat. Penambahan jumlah polisi tersebut dapat mencegah terjadinya tindakan kejahatan, dimana Pencegahan Kejahatan Situasional (Situasional Crime Prevention) merupakan suatu strategi untuk mengurangi meningkatnya resiko kejahatan (Clarke,1995).
