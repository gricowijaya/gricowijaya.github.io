## Pembelajaran selama satu semester ?

<div style="text-align: justify;">

- Konsep Dasar dari OS
- Evolusi OS 
- Fungsionalitas OS
- Konsep dasar NOS
- Infrastruktur pendukung NOS.
- Karakteristik dari NOS, dalam jaringan komputer.

Praktik mandiri untuk belajar menggunakan OS: OS Linux, Free BSD.
Misalnya seperti dengan menggunakan _network thetering_ maka dari _handphone_ tersebut dapat dilihat siapa saja yang menggunakan _Network_ tersebut. 


## Sistem Operasi

Sistem Operasi merupakan suatu sistem yang tersusun tersusun dari kumpulan _hardware_ dan __software__ dan terdapat _firmware_. 

Menurut __William Stalling__ yaitu dia memiliki _layer_ yang dimana menjalankan aplikasi-aplikasi yang digunakan untuk _interface_ antara _hardware_ dengan __software__ lainnya. Yang dimana artinya menjembatani _hardware_ dengan aplikasi. Jika terdapat _hardware_ yang tidak terbaca maka dapat diinstall sebuah _driver_ agar dapat proses kinerja dari _hardware_ yang ingin digunakan seperti misalnya jika anda menggunakan linux untuk GPU Nvidia terdapat _driver open source_ agar anda dapat melakukan konfigurasi _hardware_ tersebut.   

Peran OS : 

1. Memindahkan pengguna komputer.
2. Efisiensi sumber daya komputasi. Seperti dalam satu kantor yaitu dengan memberikan banyak _file_ dalam  satu kantor baik melewati intranet atau lainnya. 
3. Membantu pengembangan, pengujian, perbaikan aplikasi dan layanan.
4. Membantu pengembangan _software_ IDE, Debugger, editor dengan menggunakan bahasa pemrograman seperti _low level language_ seperti C.
5. Eksekusi program .
6. Akses ke IO _Device_.
7. Kontrol akses _file_ dan data _privilege_ adalah bagaimana file tersebut memiliki hak akses untuk penggunanya. 
8. Akses ke sistem (_root_ seperti administrator atau akses keseluruhan, user). Akses _root_ juga dapat beresiko seperti dengan aplikasi yang memiliki malware.
9. Deteksi error dan penanganan. Misalkan didalam jaringan terdapat melakukann unduan dari jaringan yang menjadi corrupt. Penanganan-penanganan tersebut terdapat pada OS lagi.
10. Menghitung statistik penggunaan _resource_ komputasi seperti misalnya memiliki 16 GB memori yang dimana menjadikan resource tersebut memiliki proses yang tidak diperlukan maka dapat dilakukan penghapusan. Untuk di jaman sekarang dapat menggunakan docker karena dapat menggunakan sebuah environment yang dapat digunakan untuk pengujian aplikasi.
11. Manajemen intruksi melalui bahasa mesin (_software_) dan _hardware_. Seperti dengan menggunakan C dengan __malloc__ maka dapat melakukan alokasi memori yang dimana dapat melakukan manajemen sistemnya tersebut.
12. Penanganan data binary. Seperti dengan data multimedia seperti JPEG, PNG dll. Komputer melihat _file_ tersebut sebagai urutan binary saja.
13. Penyediaan API sehingga dapat lebih mudah untuk meakukan pengembangan sebuah _software_.

## OS dan Resrource Management 

OS Menangani langsung instruksi ke processor untuk mengeksekusi program. Terdapat waktu Eksekusi serta juga PID atau _Process ID_, Dalam Hal ini dalam sebuah OS _modern_ terdapat beberapa penjadwalan untuk _multitasking_ yang diman digunakan seperti penjadwalan pada umumnya agar sebuah proses dari suatu kegiatan tidak menggunakan tenaga yang banyak. Dari penjadwalan tersebut terdapat beberapa algoritma-algoritma yang dapat mengatur agar dapat mengatur jadwal sesuai dengan studi kasus.

_Memory Translation_ Dalam _Stack_ itu akan mustahil bila wajib terdapat sistem operasi yang dimana akan berkomunikasi langsung dengan hardware tersebut. Maka tanpa Sistem Operasi inilah maka _memory translation_ tersebut tidak akan berjalan yang dimana _memory translation_ ini biasanya menggunakan _low level language_.


## OSI (Open System Interconnection) Layer 

_Physical Layer_ : Artinya semua yang terhubung ke jaringan maka dapat terhubung dalam jaringan apapun ataupun terhadap kartu jaringannya lalu setelah membaca dari Physical Network lalu pengalamatannya secara fisik (MAC Address) karena tidak memiliki pengalamatan secara _software_ (IP _Address_).

</div>
