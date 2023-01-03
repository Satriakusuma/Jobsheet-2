# Jobsheet-2
PROTOKOL KOMUNIKASI DAN SENSOR


ALAT DAN BAHAN
1) ESP32
2) Breadboard
3) Kabel jumper
4) Sensor DHT 11, RFID
5) LED (5) dan Push Button (3)
6) Servo
7) Resistor 330,1K, 10K Ohm (@ 3)



A. ESP32 Capacitive Touch Sensor


1. Percobaan A_6 yaitu ESP32 Capacitive Touch Sensor yaitu program ini akan menghasilkan output apabila ujung kabel disentuh maka maka lampu akan menyala dan apabila dilepaskan lampu akan mati.

https://user-images.githubusercontent.com/121172074/208909207-4c32b9a6-571a-4fe0-98e7-18e72b6fd76f.mp4



2. Percobaan A_7 diharapkan bisa menghasilkan output apabila ujung kabel disentuh lampunya seperti percobaan diatas hanya saja lampunya menyala secara blink


https://user-images.githubusercontent.com/121172074/208910871-3720d39f-62e5-4327-ac85-8bebf27581ea.mp4




3. Program pada percobaan ini menghasilkan output menampilkan angka yang akan bertambah setiap kali sensor disentuh di serial monitornya. 



https://user-images.githubusercontent.com/121172074/208914185-7d7f34f5-b107-4a96-be78-0cd465022d54.mp4



4. Percobaan A_9 menambahkan 2 LED, lalu membbuat program yang apabila sensor disentuh LED menyala menjadi running LED.
Nyala running LED tersebut adalah bergerak dari kiri ke kanan, kemudian kanan ke kiri secara kontinyu.



https://user-images.githubusercontent.com/121172074/208920571-7cf527f0-7c90-45a9-a8a2-ea49112761e4.mp4



B. Mengakses Sensor DHT 11 (Single Wire / BUS)


1. program agar ketika suhu rungan mencapai 30 derajat celcius, maka ESP32 akan menyalakan LED Merah dan buzzer secara beep (blink). Apabila suhu dibawah 30 derajat, ESP32 akan mematikan buzzer dan menyalakan LED berbentuk running LED seperti pada Percobaan A. 


https://user-images.githubusercontent.com/121172074/208926339-5eb58d6d-7362-4665-9356-8d230525552a.mp4



C Mengakses Sensor RFID (SPI Communication)


1. Pada percobaan kali ini akan menghasilkan apabila kartu ditempelkan akan nyala lampunya


https://user-images.githubusercontent.com/121172074/208933106-2445d852-4ccd-4a75-b6a1-50789c3c5e51.mp4


2.  pada pemrograman ini menghasilkanoutput agar Tag RFID yang terbaca sebelumya dapat digunakan untuk hak akses. Apabila Tag RFID didekatkan pada Reader, maka LED Hijau akan menyala, servo akan bergerak ke kanan (lalu kembali ke posisi semula setelah 3 detik) dan di Serial Monitor akan tertampil pesan “Akses Diterima, Silahkan Masuk”. Apabila Tag RFID tidak dikenali, maka LED Merah akan menyala, servo tidak bergerak dan di Serial Monitor akan tertampil pesan “Akses Ditolak”. Gunakan Tag RFID lain untuk mencoba.


https://user-images.githubusercontent.com/121172074/208933147-ab38b290-973d-490c-983c-9c1c081c9bc7.mp4
