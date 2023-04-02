# Lab4web
Membuat kode tentang database

Aktifkan terlebih dahulu xampp control panel
![Screenshot (31)](https://user-images.githubusercontent.com/127826461/229359188-9e408ae9-a9b5-4cf9-bfdf-12863c592037.png)

lalu buat folder baru di htdocs dengan nama lab4_php_modulator
Dan buat file baru dengan nama (header.php),(footer.php),(home.php),(about.php),dan(index.php)
# Membuat Routing
Routing digunakan untuk mempermudah akses halaman web agar SEO Friendly.
Langkah awal adalah menyiapkan file utama (index.php) yang berisi routing untuk mengakses banyak halaman. 

Aktivasi mod_rewrite (.htaccess)
Mod_rewrite digunakan untuk mengubah URL dari query string menjadi SEO Friendly.
Langkah awal yang harus disiapkan adalah aktivasi mod_rewrite pada webserver Apache2 pada
configurasi httpd.conf.
![Screenshot (39)](https://user-images.githubusercontent.com/127826461/229359926-ed79c185-fd25-44a7-8919-0e08c6812595.png)

Aktifkan LoadModule mod_rewrite dengan cara melakukan un-comment pada baris tersebut,
kemudian restart Apache2.
Langkah berikutnya adalah membuat file .htaccess

Dan hasilnya seperti ini:
![Screenshot (37)](https://user-images.githubusercontent.com/127826461/229360132-e1a367fa-2749-4922-80af-a9de905f07dc.png)
![Screenshot (38)](https://user-images.githubusercontent.com/127826461/229360149-c7588ea0-0ce0-4eb6-bf2a-6bee3b5f5822.png)
