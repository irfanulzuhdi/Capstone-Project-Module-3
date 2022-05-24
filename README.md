# Capstone-Project-Module-3

Introduction :

## **Business Problem Understanding**

**1. Context**
Dataset Daegu apartment, merupakan data harga jual apartment Daegu dengan berbagai macam fasilitan yang dimiliki. Bangunan yang paling tua didirikan tahun 1978 dan bangunan paling baru didirikan tahun 2015.Setiap baris data merepresentasikan informasi terkait jarak apartment ke berbagai bagian penting, tahun berdiri, dan harga jual. Total fitur yang dimiliki pada dataset ini adalah 10 fitur termasuk 1 target('SalePrice') dengan 4123 jumlah data.

Daegu merupakan kota metropolitan terbesar ke-4 di Korea Selatan setelah Seoul, Busan, dan Incheon. Keberadaan Kota Daegu di perbukitan dengan pemandangan yang Indah dan penuh dengan kawasan wisata yang menarik, menjadikan Daegu sebagai target wisatawan lokal maupun mancanegara. Kota metropolitan yang padat akan penduduk, menjadikan apartment sebagai pilihan tepat sebagai tempat tinggal. Berbagai macam pertimbangan untuk memilih apartment terbaik dengan harga yang terjangkau. Pemilik properti akan membertimbangkan harga jual apartement dari fitur atau fasilitas yang diberikan, hanya saja mereka tidak bisa menempatkan harga yang tepat untuk penjualan apartment mereka. Fitur-fitur yang menjadi pertimbangan tersebut akan memberikan pengaruh terhadap harga sewa atau jual dari apartement tersebut. Hal ini juga akan memudahkan customer jika ingin mencari apartment sesuai dengan fasilitas yang mereka inginkan dengan harga yang sesuai.

**2. Problem Statement**

Dalam melakukan penjualan atau penyewaan dalam sektor real estat, seperti dalam masalah bisnis ini memiliki tantangan terbesar yaitu, penentuan harga jual/sewa apartemen di daerah Daegu, Korea Selatan berdasarkan fasilitas atau fitur-fitur yang diberikan.
Oleh karena itu, dibutuhkan penyelesaian masalah yang dapat mengatasi masalah ini. Pemecahan masalah ini nantinya diharapkan dapat memberi keuntungan secara finansial kepada pemilik properti untuk menentukan harga jual/sewa apartemen mereka menyesuaikan dengan harga jual/sewa apartemen yang sudah ada berdasarkan dengan fasilitas yang diberikan pula. Dengan penjelasan lain, agar harga jual/sewa apartemen dalam wilayah Daegu memiliki rata-rata harga yang tidak berbeda jauh antar satu dengan yang lainnya menyesuaikan fasilitas yang diberikan.

**3. Goal**

Untuk melakukan prediksi harga jual/sewa apartment di Daegu, Korea Selatan

**4. Analytic Approach**

Jadi yang perlu dilakukan untuk menemukan harga jual yang sesuai dengan pengaruh fitur-fitur yang ada adalah pertama, melakukan analisis data untuk mengetahui informasi dari data yang ada. Selanjutnya membangun algoritma untuk menemukan model regresi yang akan membantu pemiliki properti menentukan harga jual/sewa apartment sesuai fitur yang ada pada apartment. Selain itu, menemukan fitur yang berpengaruh besar terhadap target('SalePrice') agar model yang dibangun lebih simpel, namun tetap memiliki akurat yang baik.

**5. Metric Evaluation**

Metrik yang akan digunakan untuk model regresi yang dibangun adalah RMSE, karena melakukan prediksi terhadap harga jual/sewa dari apartement.

**Attributes Information**

Features

| **Attribute** | **Data Type** | **Description** |
| --- | --- | --- |
| HallwayType | Object | Tipe Hallway dari apartment |
| TimeToSubway | Object | Waktu yang dibutuhkan untuk sampai ke subway terdekat|
| SubwayStation | Object | Nama subway terdekat |
| N_FacilitiesNearBy(ETC) | Float | Total fasilitas ETC terdekat |
| N_FacilitiesNearBy(PublicOffice) | Float | Total kantor publik terdekat |
| N_SchoolNearBy(University) | Float | Total universitas terdekat |
| N_Parkinglot(Basement) | Float | Luas area parkir apartment |
| YearBuilt | Integer | Tahun dibangunnya apartment  |
| N_FacilitiesInApt | Integer | Total fasilitas dalam apartemen|
| Size(sqf) | Integer | Ukuran apartment |
| SalePrice | Integer | Harga jual apartment |

<br>
