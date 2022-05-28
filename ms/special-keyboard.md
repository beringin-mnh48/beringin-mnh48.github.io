---
title: Papan Kekunci Istimewa
description: Maklumat penulisan Beringin menggunakan papan kekunci istimewa
lang: ms
---

[← Kembali ke halaman Papan Kekunci](keyboard.html)
{: .back}

Terdapat dua cara utama untuk menulis Beringin, satunya menggunakan [papan kekunci biasa](normal-keyboard.html) manakala yang lainnya menggunakan papan kekunci istimewa. Halaman ini menunjukkan cara untuk menulis tulisan Beringin menggunakan papan kekunci istimewa yang dicipta khusus untuk tulisan Beringin.


## Isi Kandungan

- [Pengenalan](#pengenalan)
- [Daftar Unicode](#daftar-unicode)
- [Papan Kekunci Input Terus](#papan-kekunci-input-terus)
- [Papan Kekunci Penyunting Kaedah Input](#papan-kekunci-penyunting-kaedah-input)
- [Input Manual](#input-manual)
  - [Kekunci Pintasan](#kekunci-pintasan)
  - [Alatan Input](#alatan-input)
    - [Windows](#windows)
    - [Linux](#linux)
    - [macOS](#macos)
    - [Android](#android)
    - [Sistem Pengoperasian Lain](#sistem-pengoperasian-lain)
- [Jadual Unicode](#jadual-unicode)


## Pengenalan

Anda boleh menulis tulisan Beringin dengan menggunakan papan kekunci istimewa yang mencapai Kawasan Kegunaan Peribadi Unicode atau Unicode Private Use Area (PUA). Ini dilakukan dengan mengkaitkan sesetengah kod titik dalam PUA kepada huruf Beringin yang tertentu seperti yang ditetapkan di [jadual ini](unicode-table.html) dan menggunakan fon yang ditentukan yang boleh didapati di [sini](../mnh48-beringin/ms) yang akan memaparkan huruf-huruf Beringin secara sendirinya berlainan daripada huruf Rumi.

Kelebihan:
- Tidak perlu mencampurkan fon jika ingin paparkan tulisan Beringin dan Rumi dalam ayat yang sama, ini membantu dalam sesetengah perisian di mana hanya satu fon boleh digunakan pada keseluruhan tika kerana kebanyakan sistem pengoperasian akan paparkan huruf Rumi daripada fon lain sekiranya fon Beringin digunakan

Kekurangan:
- Fon mesti dipasang

**Sila pastikan anda telah pasangkan fon untuk tulisan Beringin sebelum anda membuat apa-apa, jika tidak huruf Beringin tidak akan muncul dalam sistem anda.** Mana-mana versi fon Beringin yang disediakan [di sini](../mnh48-beringin/en) semuanya mempunyai aksara yang diperlukan untuk memaparkan Beringin dalam PUA, tetapi versi PUA digalakkan kerana ia memang dicipta untuk tujuan ini.


## Daftar Unicode

Tulisan Beringin menggunakan kod titik dalam Kawasan Kegunaan Peribadi Unicode atau Unicode Private Use Area (PUA) yang disenggara bawah persepakatan peribadi di antara beberapa pihak yang berlainan. Pertanyaan telah dihantar kepada [Kreative Korporation](https://www.kreativekorp.com) yang menyenggara senarai Daftar Unicode Tulisan Rekaan Dalam Pembangunan atau [Under-ConScript Unicode Registry](https://www.kreativekorp.com/ucsur/) (UCSUR) untuk menambah kod titik yang digunakan oleh tulisan Beringin ke dalam daftar mereka tetapi masih belum menerima balas daripada mereka setakat ini. Oleh itu, sila elakkan daripada menggunakan kaedah papan kekunci istimewa sehingga mereka menambahnya ke dalam daftar untuk mengelakkan perkaitan semula di kemudian hari.

Pendaftaran diperlukan untuk mengelakkan tulisan lain daripada ditetapkan kepada kod titik yang sama, supaya tulisan Beringin akan dipaparkan secara tekal di kesemua sistem di seluruh alam. Malahan, pencipta fon bukan-Beringin juga mampu menyertakan tulisan Beringin dalam fon mereka bersama-sama tulisan lain sekiranya kod titik ini ditetapkan untuk tulisan Beringin.

Apabila tulisan Beringin ditambah ke daftar UCSUR, maka kaedah papan kekunci istimewa akan menjadi kaedah penggunaan yang digalakkan.

Tiada sebarang rancangan untuk mengemukakan pengekodan keseluruhan bongkah Beringin secara sendirinya ke dalam titik kod Unicode yang biasa (bukan peribadi) kerana terdapat terlalu banyak proses yang perlu ditempuh dan tidak ada entiti formal yang mampu menyandar perkaitan kod Beringin setakat ini. Ia bukanlah mustahil, cuma terlalu banyak proses yang perlu ditempuh dan Unicode Consortium iaitu pihak yang menyenggara Unicode sedang sibuk untuk mengkaitkan pengekodan baharu untuk kod titik yang jauh lebih penting seperti tulisan ibunda dalam bahasa lain yang digunakan sebagai **satu-satunya** sistem tulisan bahasa mereka tetapi belum ada dalam Unicode (tidak seperti tulisan Beringin di mana bahasa yang menggunakannya (bahasa Melayu dan bahasa Indonesia) sudah pun ditulis menggunakan tulisan Rumi, Jawi dan beberapa tulisan lain yang sudah pun dikodkan dalam Unicode).


## Papan Kekunci Input Terus

Papan kekunci input terus ialah kaedah di mana susun atur papan kekunci telah ditetapkan dan aksara dikaitkan secara terus kepada sesuatu tekanan kekunci. Papan kekunci yang selalu digunakan untuk menulis bahasa Inggeris, bahasa Arab, bahasa Rusia dan yang lain ialah contoh papan kekunci input terus.

Ketika ini, belum ada susun atur papan kekunci input terus tersedia untuk tulisan Beringin buat mana-mana sistem pengoperasian. Akan datang.

There are plans for standalone keyboard application for Beringin alphabet and also extensions to support Beringin alphabet for certain existing keyboards on Android. No plan to support iOS since I don't have money to pay to Apple, all developers needs to pay them USD 99 per year just to release on iOS and that amount is a burden due to high currency change.


## Papan Kekunci Penyunting Kaedah Input

Papan kekunci penyunting kaedah input, atau input method editor (IME), ialah kaedah di mana tiada susun atur papan kekunci digunakan. Sebaliknya, anda menaip ejaan Rumi sesuatu perkataan menggunakan papan kekunci Rumi dan sistem IME akan bagi anda pilih huruf, perkataan atau frasa mana yang anda ingin tulis, dan kemudiannya akan tukarkan tulisan Rumi tadi kepada aksara yang telah dipilih. Papan kekunci yang selalu digunakan untuk menulis bahasa Cina, bahasa Jepun, bahasa Korea dan yang lain ialah contoh papan kekunci IME.

Ketika ini, tulisan Beringin boleh digunakan dengan sistem IME fcitx di sistem pengoperasian Linux. Anda boleh lihat arahan pemasangan di [sini](../fcitx-table-beringin/ms).

Belum ada papan kekunci sistem IME disediakan untuk sistem pengoperasian lain lagi buat masa ini. Akan datang.


## Input Manual

Anda juga boleh tulis tulisan Beringin secara manual sekiranya anda tahu titik kod sebenar huruf yang anda ingin tulis dan sistem pengoperasian anda membernarkan anda memasukkan aksara Unicode menggunakan kod titik, atau anda mempunyai alatan yang memberi capaian ke PUA atau keseluruhan Unicode.


### Kekunci Pintasan

Beberapa sistem pengoperasian membenarkan anda menulis aksara melalui kod titik menggunakan kekunci pintasan, atau aplikasi pihak ketiga. Sila lihat [Unicode input](https://en.wikipedia.org/wiki/Unicode_input) (bahasa Inggeris) di Wikipedia untuk maklumat lanjut. Contohnya, menaip `Ctrl+Shift+u` diikuti kekunci `e`, `b`, `a`, `4`, dan `selang` di sistem pengoperasian Linux seperti Ubuntu (dan variasi Unix lain termasuk ChromeOS) akan berikan anda Huruf Beringin Cheh (<span class="brgnpuachar"></span>) yang dikaitkan ke titik kod U+EBA4 dalam PUA.

Jika sistem pengoperasian anda tidak menyokong kekunci pintasan, alatan pihak ketiga mungkin wujud untuk membolehkan anda memasukkan titik kod. Contohnya, aplikasi [Unicode Keyboard](https://play.google.com/store/apps/details?id=org.tiwu.unicodekeyboard&hl=en_US) membolehkan anda masukkan titik kod aksara dalam sistem pengoperasian Android.


### Alatan Input

Beberapa sistem pengoperasian mempunyai alatan yang membolehkan anda mencapai, melihat dan menyalin aksara Unicode. Dalam kesemua alatan ini, anda perlu pergi ke bongkah Kawasan Kegunaan Peribadi atau Private Use Area daripada banyak-banyak bongkah yang ada dalam Unicode. Tulisan Beringin berada di titik kod U+EBA0 hingga U+EBFF dalam bongkah tersebut.


#### Windows

Dalam sistem pengoperasian Windows, alatan ini dikenali sebagai Character Map (Peta Aksara), tetapi ia hanya terbatas kepada Satah Multibahasa Asas atau Basic Multilingual Plane (BMP) dalam Unicode dan bukannya keseluruhan Unicode. Nasib baiknya, PUA ada dalam BMP, jadi tulisan Beringin akan boleh dilihat dan dipilih dalam Character Map. Untuk mencapai aksara lain di luar BMP, anda perlu pasang alatan pihak ketiga seperti BabelMap.


#### Linux

Dalam sistem pengoperasian Linux, kebanyakan sistem pengoperasian yang mempunyai sekitaran atas meja akan didatangkan dengan alatan ini dan perisian sebenar alatan serta namanya berlainan dari sistem ke sistem. Alatan yang paling dikenali ialah Character Map (gucharmap) pada sekitaran atas meja GNOME dan Character Select (kcharselect) pada sekitaran atas meja KDE. Alatan ini selalunya mempunyai capaian ke keseluruhan Unicode tetapi ia bergantung kepada tatarajah dan tetapan anda.


#### macOS

Dalam sistem pengoperasian macOS, alatan ini dikenali sebagai Character Viewer, tetapi tiada maklumat lanjut mengenai cara sebenar untuk mencapai PUA, malah ia akan perlukan cara yang berbeza untuk menatarajah dalam versi mac yang berlainan, kerana macOS ialah sistem pengoperasian jenis bibik yang menyembunyikan kesemua benda teknikal daripada pengguna sasar, dan Character Viewer mereka hanya akan paparkan apa yang pengguna biasa akan capai dalam kegunaan biasa dan bukannya PUA. Anda mungkin inginkan alatan pihak ketiga untuk mencapai PUA.


#### Android

Dalam sistem pengoperasian Android, anda boleh pasang aplikasi pihak ketiga untuk mencapai tulisan Beringin.

1. [Character Pad](https://play.google.com/store/apps/details?id=com.husseinelfeky.characterpad&hl=en)
  - Sentuh butang Menu di sebelah kiri atas
  - Tatal menu dan sentuh pada Private Use Area
  - Tatal ke bawah sehingga anda nampak tulisan Beringin

2. [Unicode Pad](https://play.google.com/store/apps/details?id=jp.ddo.hotmist.unicodepad&hl=en)
  - Pasang fon Beringin di dalam aplikasi kerana ia mempunyai sekitarannya sendiri
  - Sentuh pada tab List jika anda berada di tab lain
  - Sentuh pada senarai jatuh yang berada di bawah tab tersebut
  - Pilih U+E000 Private Use Area
  - Tatal ke bawah sehingga anda nampak tulisan Beringin


#### Sistem Pengoperasian Lain

Cari alatan Unicode khusus untuk sistem anda, jika tidak maknanya anda bernasib malang.


## Jadual Unicode

Jadual Unicode yang menyenaraikan kesemua titik kod yang dikaitkan dengan tulisan Beringin ada [di sini](unicode-table.html).
