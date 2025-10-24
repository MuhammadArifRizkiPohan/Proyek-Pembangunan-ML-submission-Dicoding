# Proyek-Pembangunan-ML-submission-Dicoding
Submission kelas Belajar Machine Learning untuk Pemula
Proyek Pembangunan Model Supervised dan Unsupervised Learning pada Data Tabular
Membangun model machine learning menggunakan beberapa metode supervised dan unsupervised learning pada kasus nyata.
Tahapan
1. Memuat Dataset dan Melakukan Exploratory Data Analysis (EDA)Menampilkan dataset menggunakan function head().Menampilkan informasi dataset dengan info().Menampilkan statistik deskriptif dataset dengan menjalankan describe() untuk mendapatkan ringkasan data.
2. Pembersihan dan Pra Pemrosesan DataMengecek dataset menggunakan isnull().sum() dan duplicated().sum().Melakukan feature scaling menggunakan MinMaxScaler() atau StandardScalar() untuk fitur numerik.Melakukan feature encoding menggunakan LabelEncoder() untuk fitur kategorikal.Melakukan drop pada kolom yang memiliki keterangan ID seperti TransactionID, AccountID, DeviceID, IPAddress, MerchantID 
3. Membangun Model ClusteringMenggunakan dataset yang sudah dilakukan preprocessing.Melakukan visualisasi Elbow Method untuk menentukan jumlah cluster terbaik menggunakan KElbowVisualizer().Menggunakan algoritma K-Means Clustering dengan sklearn.cluster.KMeans().Menjalankan cell code joblib.dump() dengan nama model_clustering agar reviewer dapat secara otomatis menilai evaluasi model anda. 
4. Interpretasi Hasil ClusteringMenampilkan analisis deskriptif minimal mean, min, dan max untuk fitur numerik.Menjelaskan karakteristik tiap cluster berdasarkan hasil proses agregasi.Mengekspor data training dari proses preprocessing beserta data hasil clustering dan berikan nama untuk kolom tersebut yaitu Target. 
5. Membangun Model KlasifikasiMenggunakan train_test_split() untuk melakukan pembagian dataset.Membangun model dengan algoritma Decision Tree dengan nama decision_tree_model.h5 
