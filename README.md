# Program3 Biaya pengiriman
![gambar1](https://github.com/Raihanardiansyah/Program3/blob/main/ss/ss1%20(1).png?raw=true)
### 1.Langkah-langkah dalam Fungsi:   
### Inisialisasi Biaya Awal:   

Fungsi dimulai dengan biaya pengiriman dasar yang ditetapkan sebesar 10.000 (biaya = 10000).
Cek Berat Barang:

Fungsi memeriksa apakah berat barang lebih dari 5 kilogram.
Karena berat yang diberikan adalah 6 kilogram (lebih dari 5), biaya pengiriman akan ditambah sebesar 5.000 (biaya += 5000).
Biaya setelah langkah ini menjadi:
10.000 + 5.000 = 15.000.
Cek Jarak Pengiriman:

Fungsi kemudian memeriksa apakah jarak pengiriman lebih dari 10 kilometer.
Karena jarak yang diberikan adalah 15 kilometer (lebih dari 10), biaya pengiriman akan ditambah lagi sebesar 8.000 (biaya += 8000).
Biaya setelah langkah ini menjadi:
15.000 + 8.000 = 23.000.
Cek Pengiriman Ekspres:

Fungsi memeriksa apakah pengiriman menggunakan layanan ekspres.
Karena parameter express=True, biaya pengiriman akan ditambah sebesar 20.000 (biaya += 20000).
Biaya setelah langkah ini menjadi:
23.000 + 20.000 = 43.000.
Cek Status Anggota:

Fungsi memeriksa apakah pelanggan adalah anggota yang berhak mendapatkan diskon.
Karena parameter member=True, biaya pengiriman akan mendapatkan diskon sebesar 10%.
Diskon dihitung dengan mengalikan biaya dengan 0.9 (biaya *= 0.9).
Biaya setelah diskon menjadi:
43.000 * 0.9 = 38.700.
Mengembalikan Biaya Akhir:

Fungsi mengembalikan nilai biaya akhir sebagai angka bulat, yaitu 38.700.
Nilai ini adalah biaya total pengiriman setelah semua tambahan dan diskon diterapkan.
