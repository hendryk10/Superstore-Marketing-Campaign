# Superstore-Marketing-Campaign
Project ini mengambil permasalahan pada sebuah Superstore yang ingin melakukan campaign lewat telpon untuk menawarkan membership kepada customernya,dimana harga gold membership dipatok dengan harga 499 USD dan akan naik menjadi 999 USD di lain hari. Demi mengurangi biaya campaign,pihak Superstore memerintahkan untuk membuat model yang dapat memprediksi customer yang diklasifikasikan akan membeli membership tersebut.

Model yang digunakan adalah XGBoost yang telah melalui proses Hyperparameter Tuning dan juga Undersampling dengan F1 Score sebesar 0.53 dan Recall 0.80,yang artinya model dapat memprediksi 53 % dari data yang secara real membeli membership.

Jenis customer yang perlu dihubungi untuk campaign selanjutnya adalah :
- Pelanggan dengan total pembelanjaan diatas 1200 USD
- Pelanggan dengan status pernikahan single dan divorced
- Pelanggan dengan jangka waktu pembelian di range 0 - 20 hari dari tanggal pembelian terakhir
- Pelanggan yang melakukan pembelian lebih dari 10 kali lewat katalog,web dan Store
- Pelanggan yang tidak memiliki anak kecil maupun dewasa



