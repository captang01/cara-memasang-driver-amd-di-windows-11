# Cara memasang Driver AMD di Windows 11

# ! Disclaimer !

ini hanya berdasarkan pengalaman pribadi saya ketika ingin menginstall ulang windows 11 jadi jika teman teman punya cara sendiri silahkan tapi ini hanya untuk sekedar membantu teman teman yang ingin memulihkan drivernya dan tujuan dari pemasangan driver ini di lakukan karena saya tidak bisa mengatur kecerahan, lalu itu juga mempengaruhi pada kecepatan saat coding atau sekedar untuk bermain game.

# Lihat Driver dulu
teman teman bisa mempraktikkan ini tidak harus berpatokan dengan amd tapi juga bisa menggunakan driver lain seperti Intel atau pun Nvidia
contohnya temen temen bisa masuk ke dxdiag caranya
1. pencet windows+r, setelah itu ketik dxdiag. 
<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/c47faf87-6ca4-4a3e-a4ca-43f7e4bcb4b3" />

2. setelah itu klik oke dan temen temen bisa masuk dan liat di bagian proccesor, kenapa saya melihatnya di bagian proccesor karena amd proccesor dan driver itu       sama jadi tidak ada bedanya.
   <img width="726" height="534" alt="image" src="https://github.com/user-attachments/assets/38486795-ea87-4874-acc5-ba9b99b755ec" />

# Cara mendownload Driver
nah setelah temen temen melihat Proccesor nya sekarang teman-teman harus mendownloadnya menggunakan DriverPack agar bisa mendapatkan drivernya.
tapi sebelum kita tau driver kita teman teman harus melihat kode driver di display adapter di laptop teman-teman.
oke caranya:

1. teman teman masuk ke bagian Device Manager

2. setelah masuk teman-teman bukan Display Adapter ,nah di bagian display saya disitu tertulis "Microsoft Basic Display Adaper" yang dimana itu bukan driver saya     melainkan driver default dari windows oleh itu kita harus mengantinya.
   <img width="327" height="60" alt="image" src="https://github.com/user-attachments/assets/c2ec98f6-7157-4f97-a079-2fc840ce1347" />

3. oke setelah itu teman teman klik kanan pada bagian properties di "Microsoft Basic Display Adaper"

4. masuk ke bagian Details, di bagian property di ubah ke Hardware ids dan salin kode yang bagian atas karena itu driver yang akan kita download.
<img width="507" height="567" alt="image" src="https://github.com/user-attachments/assets/56225b7f-4d0e-4239-a95f-d58e918953af" />

5. setelah di salin kita masuk ke situs DriverPack ini link nya: https://driverpack.io/
   setelah masuk ke situs pilih search driver dan masukkan kode nya.
   <img width="1911" height="862" alt="image" src="https://github.com/user-attachments/assets/11ae46b7-1bac-453c-b564-70ec17781bf9" />

6. setelah itu klik Find

7. lalu setelah masuk scroll ke bagian bawah dan download link yang ini
   <img width="1447" height="533" alt="image" src="https://github.com/user-attachments/assets/d41f5ece-e357-497b-9d55-66598e1ffad6" />

8. setelah di download kita bisa extract ke folder partisi yang kita gunakan.
   <img width="686" height="402" alt="image" src="https://github.com/user-attachments/assets/5d5bb6d0-77d8-43f0-936c-a0aa0e6aa91a" />

9. selamat penginstalan Driver sudah selesai sekarang kita lanjut ke pemasangan driver di display adapter

# Pemasangan Driver
1. setelah itu klik kanan pada "Microsoft Basic Display Adaper" dan pilih update driver.
2. setelah masuk klik pilihan yang paling bawah: 
   
   -Browse my computer for drivers
   
   -kemudian sebelum memilih Let me pick froma a list of available driver on my computer pastikan include subfolders sudah di centang

3. setelah itu pilih Have Disk dan sesuaikan dengan file driver yang kita download untuk mencari file dengan format (.inf)
   <img width="1706" height="761" alt="image" src="https://github.com/user-attachments/assets/d6144234-281b-478c-b0d2-3312944e1650" />
   kira-kira seperti ini. setelah itu klik open file lalu akan muncul banyak pilihan driver dan pilih yang sesuai dengan laptop teman-teman.
   kalo di sini saya menggunakan "AMD Radeon(TM) RX Vega 8 Processor Graphics".
   
4. setelah itu klik next dan pilih yes, maka akan otomatis terinstall
   <img width="607" height="467" alt="image" src="https://github.com/user-attachments/assets/34e5982b-67b2-42b8-86cf-5c42b9b58627" />

5. dan selamat Driver kalian sudah terpasang.


