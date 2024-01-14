# UAS Pemograman Mobile

Nama    : Ferdyana Eka Prasetya

NIM      : 312210121

Kelas    : TI.22.A.1

Dosen   : Donny Maulana, S.Kom., M.M.S.I.


### Alhamdulillah hirabbil 'alamin

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
    
    Ini adalah logo yang saya gunakan, Saya menggunakan logo Instagram yang saya punya yaitu Ddyyfe.

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

- **Source Code Activity Count**
  
   - CountActivity.java [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/java/com/example/tugassembilan/CountActivity.java)
     
     Tentunya disini berisi code java untuk menjalankan fungsi perhitungan dari rumus fibonnaci. Bilangan fibonnaci adalah bilangan yang rumusnya adalah menambah sebuah bilangan dengan 
     bilangan sebelumnya. Contohnya 1, 1, 2, 3, 5, 8...
     
   - activity_count.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/res/layout/activity_count.xml)
     
     Ini adalah layout dari activity count, ada beberapa tombol disini seperti set limit, count, dan reset. Angka yang ditampilkan juga sudah menggunakan code warna, agar setiap angka 
     yang ditampilkan memiliki warna yang berbeda dengan angka sebelumnya.

- **Hasil Run**
  
https://github.com/ferdycuy/DdyyfeApp/assets/115714443/23e6da86-735a-48c0-978b-6d8a39cdeb5c

- **Source Code Activity Scroll Movie**
   
   - SianidaActivity.java [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/java/com/example/tugassembilan/SianidaActivity.java)
     
     Disini saya tidak mengubah apapun isi dari javanya, dengan kata lain saya buat default sedari awal dibuat.
     
   - activity_sianida.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/res/layout/activity_sianida.xml)
     
     Layout inilah yang mempengaruhi dan memberikan alasan kenapa di javanya tidak ada perubahan. Disini, digunakan sebuah scrollview yang bisa menjadikan text yang begitu panjang dan 
     tidak muat dalam satu layar penuh, maka dengan ini kita bisa membaca semua isi kontennya hanya dengan cara scroll layar.

- **Hasil Run**
  
https://github.com/ferdycuy/DdyyfeApp/assets/115714443/96e8d013-baa8-4405-8a13-07a4fe8e20fd

- **Source Code Activity TwoActivity**
  
   - PesanctActivity.java [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/java/com/example/tugassembilan/PesanActivity.java) & Pesan2Activity.java [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/java/com/example/tugassembilan/Pesan2Activity.java)
     
     Kedua java berisi fungsi untuk menjalankan program perpesanan. Kedua java tersebut memiliki peran masing-masing, yang pertama untuk pengirim dan yang kedua untuk fungsi ketika 
     pesan berhasil terkirim.

   - activity_pesan.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/res/layout/activity_pesan.xml) & activity_pesan2.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/res/layout/activity_pesan2.xml)
    
     Kedua layout ini merupakan tampilannya, yang pertama berfungsi menampilkan saat mengirim pesan dan yang kedua menampilkan saat pesan berhasil terkirim.

- **Hasil Run**

https://github.com/ferdycuy/DdyyfeApp/assets/115714443/e8d0397c-04e7-4e6f-9d3b-1279baba48f8

- **Source Code Program Alarm**
  
   - Karena program ini hanya merupakan tombol, maka hanya tinggal menambahkan baris code berikut :
     ```
       # Tambahkan code ini didalam protected void OnCreate :
      findViewById(R.id.btnSetAlarm).setOnClickListener(v -> {
          // Panggil metode untuk mengatur alarm
          setAlarm();
      });
     }

     # Lalu code tambahkan fungsi intent untuk tombolnya :
     private void setAlarm() {
      Intent alarm = new Intent(AlarmClock.ACTION_SET_ALARM);
      startActivity(alarm);
     }
     
     ```

   - Tidak hanya itu, perlu ditambahkan juga beberapa baris code di AndroidManifest.xml, seperti ini

     ```
     <uses-permission
      android:name="com.android.alarm.permission.SET_ALARM" />

     dan
         <action android:name="android.intent.action.SET_ALARM" />
     ```

- Hasil Run

  

https://github.com/ferdycuy/DdyyfeApp/assets/115714443/d5ce083d-7530-4d3b-8161-4f6da51300c5

- **Source Code Program Open Map**
  
   - Sama seperti program alarm yang hanya menggunakan fungsi sebuah tombol, maka hanya code inilah yang diperlukan untuk dapat menjalankan dan membuka maps nya. :

     ```
            # Tambahkan code ini didalam protected void OnCreate :
     ImageButton btnshowMap = findViewById(R.id.btnshowMap);
     btnshowMap.setOnClickListener(v -> {
        Intent map = new Intent(Intent.ACTION_VIEW, Uri.parse("geo:-6.324307,107.169273"));
        map.setPackage("com.google.android.apps.maps");
        startActivity(map);
     });
     ```
     
- **Hasil Run**

https://github.com/ferdycuy/DdyyfeApp/assets/115714443/a3f5da61-d8b8-4022-a2e1-aa37b33e2cbd

- **Source Code Program Fragment**
  
    Berbeda dari activity lain sebelumnya, di activity ini memerlukan banyak java dan layout, karena activity ini terdiri dari beberapa halaman. Perintah tugas dari activity ini adalah, 
    membuat sebuah program atau aplikasi menampilkan daftar film sesuai dengan genre nya. Dan genre yang diperintahkan untuk dibuat ada tiga, yakni Action, Comedy, dan Romance.
  
   - FragmentActivity.java [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/java/com/example/tugassembilan/FragmentActivity.java)
     
     Java yang ini berfungsi sebagai fungsi dari halaman utamanya. Didalamnya terdapat code untuk switch atau berpindah antar fragment dari action/comedy/romance.Oh iya agar code 
     fragment tersebut dapat berjalan, perlu ditambahkan sebuah depedencies baru di build.gradlenya, berikut dependenciesnya :

     ```
     implementation("androidx.fragment:fragment:$fragmentVersion")
     ```
     > **NOTE** jika menambahkan dependencies baru, perlu dilakukan sync terlebih dahulu.
     
   - activity_fragment.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/res/layout/activity_fragment.xml)
     
     Inilah layout yang terhubung dengan FragmentActivity.java, layout ini adalah tampilan basic atau tampilan utama yang masih kosong, didalamnya terdapat 3 tombol untuk berpindah 
     antar fragment nya. 

   - FirstFragment.java [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/res/layout/activity_fragment.xml), SecondFragment.java [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/java/com/example/tugassembilan/SecondFragment.java), ThirdFragment.java [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/java/com/example/tugassembilan/ThirdFragment.java)
     
     Ketiga java ini didalamnya terdapat fungsi untuk menampilkan list film yang ada, dan fungsi memutar trailer video ketika poster atau gambar filmnya ditekan. Video tersebut 
     berasal dari link youtube yang saya tambahkan sesuai dengan film apa yang ada di masing masing fragment nya. Untuk menggunakan fungsi ini perlu ditambahkan depedencies di 
     build.gradle nya. Saya menggunakan library yang bernama youtube player dari pierfrancescosoffritti, berikut dependenciesnya :

     ```
     implementation("com.pierfrancescosoffritti.androidyoutubeplayer:core:11.0.1")
     ```
     > **NOTE** menambahkan dependencies baru, perlu dilakukan sync terlebih dahulu.

   - fragment_first.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/res/layout/fragment_first.xml) , fragment_second.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/res/layout/fragment_second.xml) , fragment_third.xml [Lihat File](https://github.com/ferdycuy/DdyyfeApp/blob/6ea0c34f54e24462d27aae46d24cf0da6fcbc87f/main/res/layout/fragment_third.xml)
   
     Ketiga xml ini merupakan layout atau tampilan dari masing-masing fragment, didalamnya menampilkan daftar film sesuai dengan genrenya. Layout ini terhubung dengan ketiga java diatas.
   - Berikutlah Untuk Tampilannya
     
     <img src="https://github.com/ferdycuy/DdyyfeApp/assets/115714443/f466f8fc-fd88-4bf1-a0f3-1a185add394e"  width="300" height="500">

- **Hasil Run**
  

https://github.com/ferdycuy/DdyyfeApp/assets/115714443/aa69139b-3a47-44cd-844b-1cbdda177fff

# PENUTUP

Saya ucapkan rterima kasih kepada teman-teman yang telah meluangkan waktu untuk membaca secara menyeluruh isi dari repositori ini. Apresiasi yang diberikan sangat berarti bagi saya dan menjadi motivasi untuk terus berkembang.

Saya juga ingin mengucapkan terima kasih kepada Bapak Donny Maulana, S.Kom., M.M.S.I., yang telah menjadi pembimbing dalam pembelajaran pemrograman mobile ini. Beliau telah memberikan bimbingan dan ilmu yang sangat berharga.

Semoga pembelajaran ini menjadi landasan untuk kemajuan lebih lanjut, dan kita semua dapat meraih kesuksesan bersama. Ini adalah akhir dari repository yang telah saya buat ini. Segala kesalahan kata atau kalimat yang mungkin ada, saya sampaikan permohonan maaf.

Jangan ragu untuk menghubungi saya jika Anda memiliki pertanyaan atau umpan balik. Semoga proyek ini bermanfaat!

<p align="center">
  <b>TERIMAKASIH</b>
</p>

<p align="center">
  <em>Copyrights © Ferdyana Eka Prasetya 2024</em>
</p>













    
  
  
   
