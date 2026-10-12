Hai, aku Anestasya sharing tentang hasil final task mengikuti Project Based Internship dari Rakamin Academy. Syntax adalah query untuk extract dataset menggunakan Google BigQuery.
Pada pengolahan Query dibantu dengan Google BigQuery
Cari menu BigQuery pada bar sebelah kiri, lalu klik studio
Lakukan "create project", dalam syntax ini aku menuliskan "anestasya10102026"
Setelah membuat project, pada halaman project "anestasya10102026" buat dataset baru dengan nama "rakamin_kimiafarma" (bisa diubah)
Jika dataset sudah muncul, upload file dataset yang kita miliki. Dalam project ini saya upload manual dari file csv

*File dataset pada project ini"
1. kf_final_transaction
transastion_id
date (yyyy-mm-dd)
branch_id
customer_name
product_id
price
discount_percentage
rating
2. kf_inventory
Inventory_ID
branch_id
product_id
product_name
opname_stock
3. kf_kantor_cabang
branch_id
branch_category
branch_name
kota
provinsi
rating
4. kf_product
product_id
product_name
product_category
price

*Final Task: Membuat Dataset Baru dengan Ketentuan*
Isi Tabel Analisa
transaction_id : kode id transaksi
date : tanggal transaksi dilakukan
customer_name : Nama customer yang melakukan transaksi
discount_percentage : Persentase diskon yang diberikan pada obat
rating_transaksi : penilaian konsumen terhadap transaksi yang dilakukan
branch_id : kode id cabang Kimia Farma,
branch_name : nama cabang Kimia Farma
kota : kota cabang Kimia Farma
provinsi : provinsi cabang Kimia Farma
rating_cabang : penilaian konsumen terhadap cabang Kimia Farma 
product_id : kode product obat
product_name : nama obat
actual_price : harga obat
persentase_gross_laba : Persentase laba yang seharusnya diterima dari obat dengan ketentuan berikut: Harga <= Rp 50.000 -> laba 10% Harga > Rp 50.000 - 100.000 -> laba 15% Harga > Rp 100.000 - 300.000 -> laba 20% Harga > Rp 300.000 - 500.000 -> laba 25% Harga > Rp 500.000 -> laba 30%, 
nett_sales : harga setelah diskon, 
nett_profit : keuntungan yang diperoleh Kimia Farma
