# mi_card_flutter

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

Catatan pribadi :

// Container
Container widget untuk menata aplikasi (widget yang memungkinkan kita untuk meposisikan widget lain dan mengatur ukuran widget lainnya). 
Container widget hanya dapat memiliki 1 child karna merupakan single-child layout widget.

Margin menggunakan EdgeInsets, beberapa macam EdgeInsets :
a. EdgeInsets.all() untuk set ukuran margin secara keseluruhan (kiri,kanan,atas,bawah)
b. EdgeInsets.symmetric() untuk set ukuran margin hanya atas dan bawah saja.
c. EdgeInsets.only() : jika hanya ingin set margin untuk 1 sisi sajad. 
d. EdgeInsets.LTRB() untuk set ukuran yang berbeda di setiap sisi.

padding juga menggunakan EdgeInsets.
intinya margin for the outside of container and padding for the inside of container widget.

// Row and Column

Row and colums is multi child layout widget dimana bisa menggunakan banyak child(children).

KOLOM : main untuk vertikal dan cross untuk horizontal
BARIS : main untuk horizontal dan cross untuk vertikal

contoh untuk kolom sebagai berikut (untuk baris lakukan sebaliknya) : 
a. mainAxisAlignment: untuk mengatur jarak container pada kolom :
    1. mainAxisAlignment.start : untuk mengatur jarak agar container dekat dengan posisi start 
    2. mainAxisAlignment.end : untuk mengatur jarak agar container dekat dengan posisi bawah 
    3. mainAxisAlignment.center : untuk mengatur jarak agar container berada di posisi tengah
    4. mainAxisAlignment.spaceEvenly : untuk memisahkan jarak container 1 dengan container lain secara merata diseluruh kolom
    5. mainAxisAlignment.spaceBetween : untuk memisalhkan jarak container agar posisi nya ada yang diatas, ditengah maupun dibawah.

b. mainAxisSize: untuk mengatur penempatan pada kolom . mainAxisSize dibagi menjadi :
    1. mainAxisSize.min : untuk mengecilkan batas kolom menjadi ukuran yang sesuai dengan 3 container diatas.

c. verticalDirection menentukan arah kolom :
    1. verticalDirection.up untuk meletakan nya dari arah bawah ke atas.
    2. verticalDirection.down untuk meletakan nya dari arah atas ke bawah.

d. crossAxisAlignment bersifat mengatur jarak secara horizontal sedangankan yg main vertikal.
e. mengatur space antara container bisa menggunakan Sizedbox( ),