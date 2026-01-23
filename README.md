# Proyek UAS Deep Learning

📌 Nama : Arman Surahman, NIM : 2230511032, Mata Kuliah : Deep Learning
<p align="justify">
📌 Latar Belakang dan Tujuan
Perkembangan deep learning telah memberikan dampak besar dalam bidang pengolahan citra digital. Salah satu metode yang paling efektif untuk klasifikasi citra adalah Convolutional Neural Network (CNN). Proyek ini bertujuan untuk membangun dan mengevaluasi model CNN dalam melakukan klasifikasi citra menggunakan dataset CIFAR-10, serta memahami tahapan pra-pemrosesan, pelatihan, dan evaluasi model sesuai ketentuan UAS.
</p>
<p align="justify">
📌 Deskripsi Dataset
Dataset yang digunakan adalah CIFAR-10, yang terdiri dari 60.000 citra berwarna berukuran 32×32 piksel dengan 10 kelas objek. Dataset ini dibagi menjadi 50.000 data training dan 10.000 data testing. Dataset diperoleh langsung melalui library Keras sehingga tidak memerlukan proses unduhan manual.
</p>
<p align="justify">
📌 Metodologi dan Arsitektur Model
Model dibangun menggunakan arsitektur Convolutional Neural Network (CNN) yang terdiri dari beberapa convolutional layer, pooling layer, dan fully connected layer. Convolutional layer berfungsi mengekstraksi fitur citra, sedangkan pooling layer mengurangi dimensi data. Model dikompilasi menggunakan optimizer Adam dan fungsi loss categorical crossentropy karena permasalahan bersifat multi-kelas.
</p>
<p align="justify">
📌 Pra-Pemrosesan Data
Tahap pra-pemrosesan meliputi normalisasi nilai piksel ke rentang 0–1 dan konversi label ke bentuk one-hot encoding. Langkah ini bertujuan untuk meningkatkan stabilitas pelatihan dan menyesuaikan data dengan kebutuhan model CNN.
</p>
<p align="justify">
📌 Proses Pelatihan Model
Model dilatih menggunakan data training dengan sejumlah epoch tertentu. Selama proses pelatihan, dilakukan pemantauan terhadap nilai accuracy dan loss pada data training dan validation. Hasil pelatihan disimpan untuk dianalisis menggunakan learning curve dan loss curve.
</p>
<p align="justify">
📌 Hasil dan Evaluasi Model
Evaluasi model dilakukan menggunakan data testing. Model memperoleh akurasi sebesar sekitar 69,6%. Selain itu, evaluasi dilakukan menggunakan metrik precision, recall, dan F1-score yang diperoleh dari classification report. Confusion matrix digunakan untuk menganalisis kesalahan klasifikasi antar kelas. Grafik learning curve dan loss curve menunjukkan bahwa model belajar dengan baik meskipun terdapat indikasi overfitting ringan.
</p>
<p align="justify">
📌 Analisis dan Pembahasan
Berdasarkan hasil evaluasi, model CNN mampu mengklasifikasikan citra CIFAR-10 dengan performa yang cukup stabil. Beberapa kelas memiliki tingkat kesalahan lebih tinggi akibat kemiripan visual antar objek. Perbedaan antara akurasi training dan validation menunjukkan adanya overfitting ringan, namun model masih mampu melakukan generalisasi.
</p>
<p align="justify">
📌 Kesimpulan
Model CNN yang dibangun berhasil melakukan klasifikasi citra CIFAR-10 dengan akurasi sekitar 70%. Proyek ini telah memenuhi seluruh kriteria UAS, mulai dari pemilihan dataset, pra-pemrosesan, pelatihan, hingga evaluasi model.
</p>
<p align="justify">
📌 dataset : https://www.cs.toronto.edu/~kriz/cifar.html, 
📌 notebook colwb : https://colab.research.google.com/drive/1sIXnyv-DG2FwTYYE9aGnXQm9ZyL3MS-E#scrollTo=TedXuxQEQ6vY
</p>

