# Submission Tugas Explorasi ResNet
- ## Nama Kelompok : salt
- ## Nama Anggota  :  Mychael Daniel N, Fajrul Ramadhana Aqsa, Ichsan Kuntadi Baskara
- ## Nim Anggota : 122140104, 122140118 ,122140117


## Plain34


### Perbandingan Metrik 

![Deskripsi foto](images/FotoPlain.jpg "ABCD")

1. Training Accuracy
- Plain-34 : 0,52

2. Validation Accuracy
- Plain-34 : 0,47

3. training loss
- Plain-34 : 1.24

4. validation loss
- Plain-34 : 1,30



## Resnet34

![Deskripsi foto](images/FotoResnet.jpg "ABCD")

1. Training Accuracy
- Resnet-34 : 0,7379

2. Validation Accuracy
- resnet- 34 : 0,6712

3. training loss
- resnet- 34 : 0,8046

4. validation loss
- resnet- 34 : 1.0348


### Grafik Sederhana

## Analisis singkat 
Residual connection itu intinya adalah “jalan pintas” (shortcut) di dalam jaringan deep learning, khususnya di arsitektur seperti **ResNet**. Jalan pintas ini memungkinkan input dari suatu layer langsung diteruskan ke layer yang lebih jauh, tanpa harus melewati semua proses transformasi di tengah. Tanpa residual connection, informasi harus melewati banyak lapisan, sehingga sinyal gradien bisa semakin lemah saat proses backpropagation. Akibatnya, model yang sangat dalam sering susah dilatih karena **vanishing gradient**—gradien mengecil sampai hampir hilang.

Dengan adanya residual connection, gradien punya jalur alternatif untuk mengalir balik ke layer awal. Ini membuat model bisa belajar lebih stabil, bahkan ketika jumlah layer sangat banyak. Secara performa, model dengan residual connection biasanya **lebih cepat konvergen** (cepat mencapai akurasi tinggi) dan bisa menghasilkan akurasi lebih baik dibanding model “plain” (tanpa shortcut), karena informasi penting tidak mudah hilang. Jadi perbedaan utamanya: jaringan **plain** cenderung stagnan atau overfit saat makin dalam, sedangkan jaringan dengan residual connection tetap “sehat” meski sangat dalam dan bisa menangkap pola yang lebih kompleks.


## Konfigurasi Hyperparamter yang digunakan untuk kedua eksperimen

## link colab 
(https://colab.research.google.com/drive/1eQjvAdTxYh4CxwY_quDHLVQ9ZXE7eAjG?usp=sharing)

(https://colab.research.google.com/drive/1eQjvAdTxYh4CxwY_quDHLVQ9ZXE7eAjG?usp=sharing)