# Laporan Proyek Machine Learning - Winata Pranata

## Domain Proyek
Cryptocurrency sudah ada sekitar sepuluh tahun lalu dan kini telah menjadi cukup populer, tersebar luas , serta dilingkupi juga atas banyak kontroversi dari perkembangan yang inovatif, Cryptocurrency adalah mata uang digital dimana transaksi dapat dilakukan dengan transaksi online, tidak seperti mata uang umum Cryptocurrency dirancang beradasarkan Kriptografi, Bitcoin adalah salah satu jenisnya. Karakteristik unik Bitcoin adalah fluktuasi harga harian dan selalu berubah setiap hari. Oleh karena itu dilakukan sebuah penelitian harga bitcoin dengan menggunakan machine learning, yang mana dengan adanya machine learning ini diharapkan dapat memprediksi harga bitcoin dimasa mendatang, Sehingga dapat mengurangi resiko kerugian.

## Business Understanding

### Problem Statements

Berdasarkan latar belakang diatas, permasalahan yang akan diselesaikan yaitu:
- Bagaimana cara memproses data harga mata uang Bitcoin sehingga dapat di latih dengan baik oleh model?
- Bagaimana menentukan model machine learning yang dapat memprediksi harga bitcoin dengan baik di masa yang akan datang?

### Goals

Tujuan dibuatnya proyek ini adalah sebagai berikut:
- Menghasilkan data harga bitcoin yang dapat digunakan dengan baik untuk model machine learning
- Menentukan model machine learning yang paling sesuai
- Dapat memprediski harga bitcoin di masa mendatang

## Data Understanding
Dataset yang digunakan pada proyek ini merupakan dataset riwayat harga mata uang bitcoin yang diperoleh dari website kaggle: [Cryptocurrency Bitcoin Historical Prices](https://www.kaggle.com/datasets/sudalairajkumar/cryptocurrencypricehistory?select=coin_Bitcoin.csv).

Informasi dari data sebagai berikut:

* Format dataset yaitu CSV (Comma-Seperated Values)
* Jumlah kolom data yang terdapat didalam dataset berjumlah 10 kolom, antara lain: _SNo, Name, Symbol, Date, High, Low, Open, Close, Volume, Marketcap_.
* Terdapat 2991 jumlah sample yang terdapat didalam dataset.
* Terdapat 6 kolom data yang memiliki tipe data Float yaitu (_High, Low, Open, Close, Volume, Marketcap_), 
* Terdapat 1 kolom data yang memiliki tipe data Integer yaitu (_SNo_)
* Terdapat 2 kolom data yang memiliki tipe data Object atau String yaitu (_Name, Symbol_)
* Tidak terdapat _missing value_ pada dataset
### **Variabel-variabel pada dataset adalah sebagai berikut:**

* Name: Nama mata uang kripto
* Symbol: Simbol mata uang kripto
* Date: Tanggal pencatatan data
* High : Harga tertinggi pada hari tertentu
* Low : Harga terendah pada hari tertentu
* Open : Harga pembukaan pada hari tertentu
* Close : Harga penutupan pada hari tertentu
* Volume : Volume transaksi pada hari tertentu
* Mastercap : Kapitalisasi pasar dalam USD

*Menangani Oulier*

## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. Anda perlu menjelaskan tahapan dan parameter yang digunakan pada proses pemodelan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan kelebihan dan kekurangan dari setiap algoritma yang digunakan.
- Jika menggunakan satu algoritma pada solution statement, lakukan proses improvement terhadap model dengan hyperparameter tuning. **Jelaskan proses improvement yang dilakukan**.
- Jika menggunakan dua atau lebih algoritma pada solution statement, maka pilih model terbaik sebagai solusi. **Jelaskan mengapa memilih model tersebut sebagai model terbaik**.

## Evaluation
Pada bagian ini anda perlu menyebutkan metrik evaluasi yang digunakan. Lalu anda perlu menjelaskan hasil proyek berdasarkan metrik evaluasi yang digunakan.

Sebagai contoh, Anda memiih kasus klasifikasi dan menggunakan metrik **akurasi, precision, recall, dan F1 score**. Jelaskan mengenai beberapa hal berikut:
- Penjelasan mengenai metrik yang digunakan
- Menjelaskan hasil proyek berdasarkan metrik evaluasi

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.

