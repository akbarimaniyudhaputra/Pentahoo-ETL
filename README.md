
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

- 2.) Tampil/muncul jendela/lembar kerja baru 
Klik Input > klik CSV file input > klik 2 kali/drag CSV file input ke lembar kerja
###

- 3.) Klik Output > klik XML output > klik 2 kali/drag XML output ke lembar kerja
###

- 4.) Input, Get Kolom/field, Ekstrak data di file CSV
Klik 2 kali step CSV file input > muncul jendela baru > step nama untuk mengubah/memberi nama pada step > Filename untuk memasukkan file CSV-nya > Delimiter untuk menentukan pembatas cell/data pada file CSV menggunakan koma/titik koma > klik Get Fields > muncul jendela baru klik OK > akan muncul data-nya kolom/field 
###

Klik Preview > muncul jendela baru klik ok > muncul jendela baru lagi yang menampilkan data jadi untuk mengecek datanya sudah ter-ekstraksi atau belum > jika sudah dicek klik close > klik ok
###

- 5.) Kemudian kita simpan ke tempat/file baru berformat XML 
Menghubungkan step input ke output menggunakan yang namanya hop

klik sekali pada step input  

###



Menghubungkan dua step input & output
