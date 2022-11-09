# C-Program-to-Find-Minimum-Path

Program ini digunakan nutuk mencari setiap jalur dari  vertex asal ke vertex tujuan yang terdapat pada
suatu Graphs. Jalur tersebut harus dapat mencapai tujuan dengan edges yang dilalui berjumlah tepat
sesuai dengan masukan pengguna. Graphs yang digunakan direpresentasikan dalam bentuk adjacent
matrix yang terdapat pada file eksternal. Adjacent matrix ini merupakan representasi graph dalam bentuk
matriks sebesar banyak vertex dengan isi yang menunjukkan hubungan antar vertex.
![alt text](https://github.com/fauzan-2405/C-Program-to-Find-Minimum-Path/blob/main/messageImage_1667968443171.jpg)
Gambar di sebelah kanan adalah graph dan gambar di sebelah kiri adalah adjacent matrix. Matriks
tersebut merepresentasikan masing-masing vertex dan angka 1 menunjukkan adanya hubungan antara
vertex tersebut dengan vertex lainnya. Lebih jelasnya adjacent matrix akan berbentuk seperti tabel
berikut.
![alt text](https://github.com/fauzan-2405/C-Program-to-Find-Minimum-Path/blob/main/messageImage_1667968639507.jpg)
Kemudian program mencari semua kombinasi jalur yang terdapat pada Graphs tersebut lalu mencetak
jumlahnya pada layar. Selain itu, program juga akan menghasilkan file eksternal yang berisi seluruh
kombinasi jalur yang ada.

## Input
Input dari program ini berupa sebuah file eksternal, vertex asal, vertex tujuan, dan jumlah edges yang diberikan oleh pengguna ketika program dijalankan. File eksternal tersebut berisi data banyaknya vertex beserta adjacent matrix. Struktur file eksternal yang digunakan dapat dilihat pada keterangan berikut.
![alt text](https://github.com/fauzan-2405/C-Program-to-Find-Minimum-Path/blob/main/messageImage_1667968842667.jpg)

## Output
Output dari program ini adalah:
1. Jumlah jalur pada graphs yang diberikan
2. Semua kombinasi jalur pada graphs yang ditampilkan pada layar
3. File eksternal yang berisi seluruh kombinasi jalur pada graphs

File eksternal yang dihasilkan akan memiliki format tampilan persis seperti pada layar. Nama file eksternal yang dihasilkan akan memiliki format jalur-file sumber.txt
![alt text](https://github.com/fauzan-2405/C-Program-to-Find-Minimum-Path/blob/main/messageImage_1667968831269.jpg)
