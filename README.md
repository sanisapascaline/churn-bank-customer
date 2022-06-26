# Prediksi Churn Nasabah di Bank Menggunakan Model Machine Learning: Artificial Neural Network
## Aplikasi ini dikerahkan ke streamlit.io, dan dapat ditemukan di [🔗LINK](https://share.streamlit.io/danielp56/deplot-model/main/project.py) ini

Churn merupakan kejadian dimana pelanggan/klien pergi meninggalkan/beralih dari bisnis yang kita miliki. sudah jelas bahwa churn rate sangat tidak menguntungkan bagi para pemilik bisnis. namun, churn rate dapat diprediksi menggunakan neural network sederhana dari machine learning. dengan prediksi yang dihasilkan, pemilik bisnis dapat mempersiapkan strategi bisnisnya sebelum para pelanggan/klien beralih ke bisnis lain.
====
Dataset ini saya dapatkan dari kaggle dengan link sebagai berikut:[🔗LINK](https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers). Terdapat total 14 kolom pada dataset tersebut, yaitu: RowNumber, CustomerId, Surname, CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary, Exited. dari 14 parameter tersebut ada beberapa parameter yang tidak akan digunakan yaitu, RowNumber, CustomerId, Surname hal ini dikarenakan 3 parameter tersebut bersifat ‘unik’ dan tidak terdapat kesamaan/hubungan/pengaruh terhadap parameter yang lainnya.

* CreditScore memiliki pengaruh terhadap peluang churn klien, berdasarkan data yang ada nasabah dengan nilai CreditScore yang lebih tinggi memiliki kemungkinan meninggalkan bank lebih kecil.

* Geography, kondisi geografi nasabah juga mempengaruhi keputusan nasabah untuk meninggalkan bank

* Gender, yaitu jenis kelamin dari klien. parameter ini nampaknya tidak terlalu berpengaruh, tapi cukup menarik untuk ditelusuri lebih jauh.

* Tenure, mengacu pada jumlah tahun nasabah telah menjadi nasabah bank. Biasanya, klien yang lebih tua lebih setia dan kecil kemungkinannya untuk meninggalkan bank.

* Balance merupakan indikator yang cukup berpengaruh terhadap churn klien, karena nasabah dengan saldo yang lebih tinggi di rekening mereka cenderung tidak meninggalkan bank dibandingkan dengan mereka yang memiliki saldo lebih rendah.

* NumOfProducts mengacu pada jumlah produk yang telah dibeli pelanggan melalui bank.

* HasCrCard menunjukkan apakah nasabah memiliki kartu kredit atau tidak. Kolom ini juga relevan, karena nasabah dengan kartu kredit cenderung tidak meninggalkan bank.

* IsActiveMember, nasabah yng aktif cenderung tidak meninggalkan bank.

* EstimatedSalary, seperti halnya saldo, nasabah dengan gaji lebih rendah lebih mungkin meninggalkan bank dibandingkan dengan mereka yang gajinya lebih tinggi.

* Exited, apakah nasabah meninggalkan bank atau tidak.
