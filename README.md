## Application Programming Interface (API)
> Sebuah interface yang dapat menghubungkan aplikasi satu dengan aplikasi lainnya. Jadi, API berperan sebagai perantara antar berbagai aplikasi berbeda, baik dalam satu platform yang sama atau lintas platform. Tujuan penggunaan dari API adalah untuk saling berbagi data antar aplikasi yang berbeda tersebut, dan juga untuk mempercepat proses pengembangan aplikasi dengan cara menyediakan function yang terpisah sehingga para developer tidak perlu lagi membuat fitur yang serupa. [Learn more...](https://www.niagahoster.co.id/blog/api-adalah/)

## Rest API
> REST merupakan kependekan dari Representational State Transfer. REST API merupakan salah satu dari desain arsitektur yang terdapat di dalam API itu sendiri. Prinsip kerja dari  REST API adalah client akan menganggap  server sebagai object yang dapat dibuat, diupdate, dihapus dan juga dibaca. Standarisasi HTTP verbs ada 5 yaitu :
1. GET: untuk membaca sebuah record atau daftar record
2. POST: untuk menambah sebuah record
3. PUT: untuk mengupdate semua field dalam sebuah record
4. PATCH: untuk mengupdate beberapa field dalam sebuah record
5. DELETE: untuk menghapus sebuah record
[Learn more...](https://www.proweb.co.id/articles/restful/restful-api.html)

## Retrofit
> Retrofit adalah sebuah library android yang membantu pengembang untuk melakukan request ke sebuah endpoint REST API. Tidak hanya untukmengakses REST API dengan proses sederhana (GET, POST, PUT, DELETE) retrofit jugamendukung berbagai macam format authentikasi via http, menambahkan header pada request, menambahkan parameter serta mengirim data berupa image ke server.

## Volley
> Volley Library merupakan merupakan produk yang diperkenalkan oleh Google untuk mempermudah pertukaran data tanpa harus membuat deretan kode yang sangat panjang. Secara default volley menggunakan metode singkronisasi.

## Retrofit vs Volley
### Kemudahan penggunaan
- Retrofit : Mudah digunakan. Dapat menggunakan API ini dengan method sederhana dari Java menggunakan interface. 
- Volley : Sedikit lebih rumit. Volley hanya mendukung beberapa response yaitu String, Image, JSONObject dan JSONArray.
### Performan dan Caching 
- Retrofit : Caching harusnya bisa berjalan jika server menetapkan header control yang benar. 
- Volley : Volley memiliki mekasnisme chacing yang lebih rumit dan fleksibel, memanfaatkan untuk membuat caching bitmaps yang lebih besar.
### POST requests + multipart uploads 
- Retrofit : Memiliki dukungan penuh untuk permintaan POST dan upload file yang multi, dengan API Sweet untuk boot. 
- Volley : Support untuk POST request tetapi harus melakukan convert terlebih dahulu terhadap Java objek yang menjadi JSONObject

## Dota API
![Screenshot_2021-05-10-12-44-11-97_1b86d187608a18ef43fdbde6990e9818](https://user-images.githubusercontent.com/60590053/117612242-11159980-b18f-11eb-8123-b03b38f5bae0.jpg)
