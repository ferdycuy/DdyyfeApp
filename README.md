# UAS Pemograman Mobile

Nama    : Ferdyana Eka Prasetya

NIM      : 312210121

Kelas    : TI.22.A.1

Dosen   : Donny Maulana, S.Kom., M.M.S.I.


### Alhamdulilah hirabbil 'alamin

Telah sampai pada akhir mata kuliah pemrograman mobile di bawah bimbingan Pak Donny Maulana, S.Kom., M.M.S.I. Saya ingin menyampaikan terima kasih kepada Pak Donny atas dedikasi dan bimbingannya selama mata kuliah ini.
</br>
</br>
Tugas UAS terakhir menjadi langkah akhir kita dalam menjelajahi dunia pemrograman mobile. Mari kita selesaikan dengan penuh semangat, mengaplikasikan pengetahuan yang telah kita peroleh.
</br>
</br>
Semoga apa yang telah kita pelajari di sini menjadi landasan untuk kesuksesan di masa depan. Terima kasih kepada Pak Donny dan selamat Membaca!
</br>

# TUGAS
Perintah tugas kali ini adalah mengumpulkan semua hasil yang sudah dibuat dari pertemuan pertama sampai akhir, hasil - hasil tersebut digabungkan dalam satu Aplikasi. Berikut ini semua code yang telah Saya buat.

# Penjelasan Aplikasi
Saya akan menjelaskan terlebih dahulu, apa saja isi dari aplikasi yang saya buat ini.Berikut penjelasannya:
</br>
- Activity Hello World , di activity ini adalah awal dari pengenalan terhadap software Android studio. Didalam activity ini hanya terdapat kalimat yang bertuliskan "Hello_World"
- Activity Count , activity ini berisi program penghitungan bilangan fibonnaci yang sebelumnya telah diperintahkan untuk dibuat,
- Activity Scroll Movie , activity ini berisi sinopsis film dokumenter ICE COLD, sinopsis yang banyak digunakan untuk pembelajaran fungsi scroll didalam aplikasi android ini.
- Activity TwoActivity , twoactivity ini adalah sebuah program perpesanan atau chatting, yang menggunakan dua activity.
- Program Open Alarm , nah program ini berbeda dari sebelumnya, disini tidak menggunakan layout activity.xml karena program ini hanya berfungsi sebagai pembuka dan pengatur alarm dalam sebuah smartphone android.
- Program Open Map , sama seperti program alarm, program open map ini hanya berupa sebuah tombol yang berfungsi sebagai pembuka aplikasi google maps yang tersedia di dalam smartphone Android.
- Activity Fragment , activity ini adalah sebuah activity yang terdiri dari beberapa fragment. Disini fragmentnya berperan sebagai penampil film dengan genre yang berbeda, seperti action, comedy, dan romance.

## Semua Source Code & Hasil Run nya
Disini saya tidak akan menampilkan source codenya disini, karena akan terlalu banyak dan memakan tempat, sebagai gantinya saya akan menaruh beberapa file yang penting penting saja yang sudah saya push dan saya akan sedikit menjelaskan dari apa yang sudah saya kerjakan.
</br>
- **Source Code Splash Launcher**
  
  - SplashScreen.java [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/7ed372c138c37dd5efbecbd8f637053433b14228/main/java/com/example/tugassembilan/SplashScreen.java)
    
    Berisi code java, untuk menjalankan fungsi splash launcher.Splash launcher ini adalah menampilkan gambar/logo/icon ketika kita pertama kali membuka aplikasi, atau sebelum menuju kehalaman utama.

  - backgroundlauncher.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/7ed372c138c37dd5efbecbd8f637053433b14228/main/res/drawable/backgroundlauncher.xml)
    
    Ini adalah logo yang saya gunakan, Saya menggunakan logo dari channel youtube yang saya punya yaitu CREATIVEGG.

 - **Hasil Run :**


https://github.com/ferdycuy/DdyyfeApp/assets/115714443/36ef9fad-bd0c-4a58-b636-68aa6ebfa513

- **Source Code Tampilan Utama**

   - MainActivity.java [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/7ed372c138c37dd5efbecbd8f637053433b14228/main/java/com/example/tugassembilan/MainActivity.java)

     Di MainActivity ini berisi program java yang memiliki fungsi penghubung dari semua activity yang disebut intent dan fungsi tombol open alarm dan open map. Saya beri nama file ini Main karena disinilah 
     fungsi paling awal dari halaman awal.

   - activity_main.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/7ed372c138c37dd5efbecbd8f637053433b14228/main/res/layout/activity_main.xml)

    Ini adalah layout dari halaman awal aplikasi ini. Layout ini terhubung dengan MainActivity.java tadi. Dilayout ini menampilkan semua tombol tombol dari berbagai activity dan program yang sudah dijelaskan 
    diatas. Beginilah tampilan dari layoutnya :
  
   <img src="https://github.com/ferdycuy/DdyyfeApp/assets/115714443/a2237441-bdf6-44ec-befc-f567337c59f6" width="300" height="500">

   - AndroidManifest.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/e8a5a7cbb0f61d5568a9cf3c581283c1eefde468/main/AndroidManifest.xml)

      Di AndroidManifest.xml ini berfungsi untuk mengaktifkan permission yang dibutuhkan dibeberapa activity. Selain itu, AndroidManifest.xml ini juga harus dilakukan pengeditan jika kita menambah sebuah 
      tombol atau activity baru yang berhubungan dengan intent, agar activity tersebut dapat dibuka nantinya.

   - string.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/e8a5a7cbb0f61d5568a9cf3c581283c1eefde468/main/res/values/strings.xml)
    
      String.xml ini adalah sebuah values, values ini berisi teks-teks dari tombol - isi - atau apapun itu yang berhubungan dengan teks.

   - colors.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/e8a5a7cbb0f61d5568a9cf3c581283c1eefde468/main/res/values/colors.xml)

       Sama seperti string, colors.xml ini juga merupakan sebuah values, tapi bedanya values ini berisi code-code warna yang sudah dibuat menjadi ID atau identitas yang bertujuan untuk memudahkan dalam 
       pemanggilan warnanya di dalam coding.
     
- **Source Code Activity Hello World**

   - HelloActivity.java [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/e8a5a7cbb0f61d5568a9cf3c581283c1eefde468/main/java/com/example/tugassembilan/HelloActivity.java)
     
     Disini saya tidak mengubah apapun isi dari javanya, dengan kata lain saya buat default sedari awal dibuat.
     
   - activity_hello.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/e8a5a7cbb0f61d5568a9cf3c581283c1eefde468/main/res/layout/activity_hello.xml)
     
     Seperti yang sudah diketahui ini merupakan layout yang terhubung dengan java nya. Saya hanya menambahkan textview untuk menampilkan android:text "hello_world" nya (text sudah ada di string.xml), selain 
     itu saya juga mengubah warna text dan menambahkan background agar terlihat lebih menarik.

- **Hasil Run**
  

https://github.com/ferdycuy/DdyyfeApp/assets/115714443/6dd2daeb-c7f5-459c-b064-e93ba1c01df3















    
  
  
   
