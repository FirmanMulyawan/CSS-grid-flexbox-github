<!-- flex Box  -->
model layout 1 dimensi yang dapat mengatur jarak dan penjajaran antar item dalam sebuah container

1 dimensi ?
hanya dapat mengatur 1 dimensi pada saat tertentu, antara baris atau kolom, tidak bisa keduanya sekaligus.

<!-- flexbox adalah  -->
sebuah modul yang menawarkan cara yang efektif untuk menyusun, mensejajarkan dan mendistribusikan jarak antar item didalam sebuah container, meskipun ukurannya dinamis atau bahkan kita tidak tahu.

<!-- istilah isilah flexbox  -->
## pembungkus = container 
## items = elemen elemen yang ada didalamnya

# main axis = sumbu utama dari sebuah container yang menentukan urutan dari penempatan items secara horizontal

# cross axis = ketika elemen elemen nya sejajar secara vertical

# ukuran container = main size
# ukuran kolom = cross size

# main start = awal dari items yang disimpan di dalam container 

# main end = akhir dari items yang disimpan di dalam container

# main size = ukuran (width/height) dari container yang akan membuat dimensi dari items nya relatif terhadap main size


## property pada container
- display : flex; 
    membuat sebuah element parent menjadi flex box, dan membuat elemen-elemen didalamnya bisa berprilaku flex juga

- flex-direction 
## mengatur arah / urutan dari items didalam container
.container {
    flex-direction: row | row-reverse | column | column-revese;
}

- flex-wrap 
## secara default, semua items didalam container akan berada pada satu baris meskipun ukurannya sudah tidak cukup, wrap memungkinkan untuk memindahkan items ke baris dibawahnya.

.container {
    flex-wrap: nowrap | wrap | wrap-reverse;
}

- justify-content
# mengatur jarak antar items
.container {
    justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly;
}

- align-items 
# mengatur perilaku penjajaran items terhadap cross axis
.container {
    align-items: flex-start | flex-end | center | stretch | baseline;
}

- align-content
# mengatur jarak antar items terhadap cross axis (hanya berfungsi ketika items lebih dari 1 baris)
.container {
    align-content: flex-start | flex-end | center | space-between | space-around;
}

## properti pada items

- order
mengatur urutan dari element 

- flex-grow / flex

- align-self
mengatur perilaku penjajaran sebuah item yang spesifik terhadap cross axis

