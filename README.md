# develop-hadoop-mapreduce-intellij-windows
Develop Hadoop MapReduce application using Intellij IDEA on Windows 10

Tutorial ini dimuat pada https://www.teknologi-bigdata.com/ website tentang teori dan contoh implementasi teknologi Big Data.

Tutorial ini menggunakan Windows 10.
Software yang diperlukan:
1. JDK 1.8; cara install ada di https://www.teknologi-bigdata.com/2019/01/install-hadoop-2-standalone-windows.html
2. Hadoop-2.7.7; cara install ada di https://www.teknologi-bigdata.com/2019/01/install-hadoop-2-standalone-windows.html

Langkah-langkah menjalankan aplikasi Hadoop MapReduce dengan Intellij IDEA pada OS Windows
1. Start Intellij IDEA as Administrator
2. Buat Maven Project dari menu File > New > Project > Maven ( silakan ikuti sesuai gambar, kemudian terakhir klik Finish ):
3. Muat Hadoop Library dari menu File > Project Structure > Modules > Dependencies > + > 1 JARs or directories…
4. Buat Java Package "wordcount" dengan klik kanan WordCount > src > main > java > New > Package
5. Buat Java Class "WordCount.java" dengan klik kanan WordCount > src > main > java > wordcount > New > Java Class
6. Buka WordCount.java, kemudian copy-paste source code WordCount.java dari Github
7. Edit konfigurasi untuk menjalankan program WordCount dari menu Run > Edit Configuration… > + > Application ( Ingat! buat direktori input, tapi JANGAN buat direktori output. Kemudian taruh sembarang text file direktori input )
8. Jalankan aplikasi dari menu Run > Edit Configuration… > + > Application ( Hasilnya adalah seperti gambar )
