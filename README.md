# Investigate Hotel Business using Data Visualization: Project Overview 
- Berperan sebagai anggota dari tim **Data Scientist** di sebuah perusahaan hotel, bertanggung jawab untuk memberikan insight-insight yang berhubungan dengan performa bisnis hotel.
- Dataset yang digunakan [hotel_bookings_data.csv](https://github.com/bumianugrahhh/Investigate_Hotel_Business/blob/main/hotel_bookings_data.csv)
- Menghapus data duplicate 
- Membersihkan data dari missing value dengan cara *imputasi(fillna)* dan *menghapus(drop)* row
- Mengganti value yang tidak sesuai pada kolom *meal*
- Membuang data yang tidak memiliki tamu karena data tersebut tidak diperlukan
- Menganalisa bagaiamana perilaku pelanggan dalam memesan tiket hotel dan mencari faktor-faktor yang mempengaruhi pembatalan pemesanan tiket hotel
- Menyajikan insight yang didapatkan menggunakan visualisasi dan data story telling

## Tools
- Python
- Google colab

# Insight/Analisis
1. Analisis Jumlah Pemesanan Hotel per Bulan berdasarkan tipe Hotel
<br><br>
![alt text](https://github.com/bumianugrahhh/Investigate_Hotel_Business/blob/main/Fig/Monthly%20Hotel%20Booking%20Analysis%20Based%20on%20Hotel%20type.png)
<br><br>
Terlihat bahwa kedua type hotel mengalami peningkatan jumlah pemesan dibulan juni dan juli, yang mana pada bulan tersebut bertepatan dengan Hari Raya dan libur anak sekolahan.
Sedangkan pada bulan-bulan lainnya yang tidak bertepatan dengan hari libur, jumlah pemesan cenderung lebih rendah, terutama di bulan Januari – Maret.

2. Analisa Pengaruh Durasi Menginap terhadap tingkat Pembatalan Pemesanan Hotel
<br><br>
![alt text](https://github.com/bumianugrahhh/Investigate_Hotel_Business/blob/main/Fig/Pengaruh%20Durasi%20Menginap%20terhadap%20Tingkat%20Pembatalan%20Pesanan%20Hotel.png)
<br><br>
Cancellation Rate kedua tipe hotel meningkat seiring dengan meningkatnya durasi menginap. Dan pada durasi menginap 5+ minggu mengalami penurunan yang sangat signifikan.

3. Analisis Pengaruh Jarak waktu Pemesanan terhadap Tingkat Pembatalan Pemesanan Hotel
<br><br>
![alt text](https://github.com/bumianugrahhh/Investigate_Hotel_Business/blob/main/Fig/Pengaruh%20Jarak%20Waktu%20Pesanan%20terhadap%20Tingkat%20Pembatalan%20Pesanan%20Hotel.png)
<br><br>
Cancellation Rate kedua tipe hotel cenderung meningkat seiring dengan meningkatnya waktu tunggu.
Akan tetapi bisa dilihat bahwa garis tren Cancelation Rate City Hotel memiliki kemiringan yang sedikit lebih curam dibandingkan dengan Resort Hotel.
City Hotel dan Resort Hotel memiliki Cancelation Rate tertinggi pada Lead Time 10-12 Bulan.



