
# Pentahoo-ETL

## A. ETL (Extract Transform Load)
 - Mengekstrak file ke format lain
 - Ekstraksi (Membaca data) > Transformasi (mengubah bentuk/format data) > Load (memindai/scan data ke file/tempat/datawarehouse baru) 


#### Cara Mengekstrak format file CSV ke format file XML
- Mengekstrak file format CSV kemudian di-load/transfer ke file baru dalam bentuk/format XML

Dengan cara sebagai berikut :
- 1.) Membuat lembar kerja baru di Pentahoo
Ctrl+N
###
![1](https://user-images.githubusercontent.com/86678205/157016271-f0d70bcc-6700-432f-a811-1b47026abae2.PNG)

- 2.) Tampil/muncul jendela/lembar kerja baru 
Klik Input > klik CSV file input > klik 2 kali/drag CSV file input ke lembar kerja
###
![2](https://user-images.githubusercontent.com/86678205/157016319-07355d78-e5ab-45a8-bdd0-c62023eb917d.PNG)

- 3.) Klik Output > klik XML output > klik 2 kali/drag XML output ke lembar kerja
###
![3](https://user-images.githubusercontent.com/86678205/157016372-638839cb-ce86-46e1-95a4-d58901ba823d.PNG)

- 4.) Input, Get Kolom/field, Ekstrak data di file CSV
Klik 2 kali step CSV file input > muncul jendela baru > step nama untuk mengubah/memberi nama pada step > Filename untuk memasukkan file CSV-nya > Delimiter untuk menentukan pembatas cell/data pada file CSV menggunakan koma/titik koma > klik Get Fields > muncul jendela baru klik OK > akan muncul data-nya kolom/field 
###
![4](https://user-images.githubusercontent.com/86678205/157016436-1d114646-b81a-430f-8754-1c05a0cd218c.PNG)
###
![4+](https://user-images.githubusercontent.com/86678205/157016525-63b951a1-c68f-4eb1-abf8-670780c2e489.PNG)
###
![4++](https://user-images.githubusercontent.com/86678205/157016570-ea1f2215-b941-453f-8cb5-7370e21c22f8.PNG)

Klik Preview > muncul jendela baru klik ok > muncul jendela baru lagi yang menampilkan data jadi untuk mengecek datanya sudah ter-ekstraksi atau belum > jika sudah dicek klik close > klik ok
###
![4+++](https://user-images.githubusercontent.com/86678205/157016664-38fe2bce-5477-4cf1-9ade-108f5104b51d.PNG)
###
![4++++](https://user-images.githubusercontent.com/86678205/157016745-0d2b9487-b9f4-41df-80ba-f38f6b69c69f.PNG)
###
![4+6+5blm](https://user-images.githubusercontent.com/86678205/157018177-55499aaa-bfe0-4ae2-9273-16213551e1fd.PNG)
###
![4+7](https://user-images.githubusercontent.com/86678205/157018310-33f97e03-e0db-415d-8c69-b6e9153c05b1.PNG)

- 5.) Kemudian kita simpan ke tempat/file baru berformat XML 
####
Menghubungkan step input ke output menggunakan yang namanya hop

klik sekali pada step input > klik hop 
###
![5 1](https://user-images.githubusercontent.com/86678205/157022001-0b6e1c16-04b9-4c16-9d56-19aee589966e.PNG)

Kemudian arahkan hop/mouse ke step output > Klik step output > Klik "Main output of step"
###
![5 2](https://user-images.githubusercontent.com/86678205/157037918-2dc54e63-549a-4df4-8b01-fa82c61a3845.PNG)

Kemudian klik 2 kali pada step output > muncul jendela baru > step nama untuk mengubah/memberi nama pada step > pada Filename klik Browse... untuk memilih lokasi penyimpanannya > beri nama untuk filenya > klik save > klik Ok
###
![5 3](https://user-images.githubusercontent.com/86678205/157054842-5c62bed1-e031-481a-a898-d08e1eb1c55e.PNG)

Kemudian simpan file pentahoonya (klik file > save/save as (Ctrl+S)), selanjutnya run/jalankan > muncul jendela baru bernama run options > klik Run 
###
![5 4](https://user-images.githubusercontent.com/86678205/157055609-3f92bb84-9ea1-48df-83e8-73b2ccd8bf0a.PNG)
###
![5 5](https://user-images.githubusercontent.com/86678205/157055917-8ee93bf0-a56f-4687-9a51-3269ea0bd69e.PNG)

Selesai, cek file output XML & file .ktr (file pentahoo) di direktori yang Anda pilih tadi 




