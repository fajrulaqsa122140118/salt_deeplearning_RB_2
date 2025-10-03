<div align="center">

# 🔬 Submission Tugas Explorasi ResNet

![Deep Learning](https://img.shields.io/badge/Deep%20Learning-ResNet-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

</div>

---

## 👥 **Tim Pengembang**

<table align="center">
<tr>
<td><strong>📋 Nama Kelompok</strong></td>
<td><strong>salt</strong></td>
</tr>
<tr>
<td><strong>👨‍💻 Nama Anggota</strong></td>
<td>Mychael Daniel N, Fajrul Ramadhana Aqsa, Ichsan Kuntadi Baskara</td>
</tr>
<tr>
<td><strong>🎓 Nim Anggota</strong></td>
<td>122140104, 122140118 ,122140117</td>
</tr>
</table>

---

## 🧠 **Plain34**

<div align="center">

### 📊 **Perbandingan Metrik**

<img src="images/FotoPlain.jpg" alt="Plain34 Results" width="600"/>

</div>

<table>
<tr>
<th>📈 Metrik</th>
<th>📊 Plain-34</th>
</tr>
<tr>
<td><strong>1. Training Accuracy</strong></td>
<td>0,502</td>
</tr>
<tr>
<td><strong>2. Validation Accuracy</strong></td>
<td>0,47</td>
</tr>
<tr>
<td><strong>3. training loss</strong></td>
<td>1.24</td>
</tr>
<tr>
<td><strong>4. validation loss</strong></td>
<td>1,30</td>
</tr>
</table>

---

## 🚀 **Resnet34**

<div align="center">

<img src="images/FotoResnet.jpg" alt="ResNet34 Results" width="600"/>

</div>

<table>
<tr>
<th>📈 Metrik</th>
<th>🎯 Resnet-34</th>
</tr>
<tr>
<td><strong>1. Training Accuracy</strong></td>
<td>0,7379</td>
</tr>
<tr>
<td><strong>2. Validation Accuracy</strong></td>
<td>0,6712</td>
</tr>
<tr>
<td><strong>3. training loss</strong></td>
<td>0,8046</td>
</tr>
<tr>
<td><strong>4. validation loss</strong></td>
<td>1.0348</td>
</tr>
</table>

---

## 📊 **Grafik kualitas model**

### 🔵 **Plain34**

<div align="center">

<img src="images/grafik_plain.jpg" alt="Plain34 Quality Graph" width="650"/>

</div>

### 🟢 **Resnet34**

<div align="center">

<img src="images/grafik_resnet.jpg" alt="ResNet34 Quality Graph" width="650"/>

</div>

---

## 📈 **Analisis singkat**

### 🔍 **Perbandingan Plain34 vs ResNet34**

<details>
<summary><strong>📘 1. Plain34</strong></summary>

> - **🔄 Pola Loss**: Validation loss awal sangat tinggi, lalu cepat turun dan stabil.  
> - **⚡ Performa**: Train loss dan validation loss konvergen di nilai rendah setelah beberapa epoch.  
> - **💡 Interpretasi**: Mampu belajar dengan baik, ada ketidakstabilan awal, namun tidak ada tanda overfitting parah.

</details>

<details>
<summary><strong>🎯 2. ResNet34</strong></summary>

> - **📊 Pola Loss**: Tren lebih mulus; train loss konsisten menurun, validation loss ikut turun dengan gap kecil.  
> - **🚀 Performa**: Kedua loss stabil di nilai rendah dengan generalisasi lebih baik.  
> - **✨ Interpretasi**: Lebih efisien, cepat konvergen, dan stabil; residual block efektif mengatasi vanishing gradient.

</details>

---

## 🧪 **Hasil Testing Model**

### 🔵 **Hasil Pada Test Model Plain34**

<div align="center">

<img src="images/test_plain.jpg" alt="Plain34 Test Results" width="600"/>

</div>

### 🟢 **Hasil Pada Test Model Resnet34**

<div align="center">

<img src="images/test_resnet.jpg" alt="ResNet34 Test Results" width="600"/>

</div>

---

## ⚙️ **Konfigurasi Hyperparamter yang digunakan untuk ketiga eksperimen**

<div align="center">

<img src="images/hyperparameter.jpg" alt="Hyperparameter Configuration" width="700"/>

</div>

<table>
<tr>
<th>🎛️ Parameter</th>
<th>🔧 Value</th>
<th>📝 Description</th>
</tr>
<tr>
<td><code>num_epochs</code></td>
<td><strong>30</strong></td>
<td>jumlah putaran lewat seluruh dataset saat training</td>
</tr>
<tr>
<td><code>patience</code></td>
<td><strong>10</strong></td>
<td>berhenti dini jika 10 epoch berturut-turut tak membaik</td>
</tr>
<tr>
<td><code>label_smoothing</code></td>
<td><strong>0.05</strong></td>
<td>target dihaluskan agar prediksi tak over-confident</td>
</tr>
<tr>
<td><code>learning_rate (lr)</code></td>
<td><strong>0.0006</strong></td>
<td>besar langkah update bobot tiap iterasi</td>
</tr>
<tr>
<td><code>weight_decay</code></td>
<td><strong>1e-4</strong></td>
<td>regularisasi L2 untuk mengurangi overfitting</td>
</tr>
<tr>
<td><code>step_size</code></td>
<td><strong>5</strong></td>
<td>interval epoch untuk menurunkan learning rate (StepLR)</td>
</tr>
<tr>
<td><code>gamma</code></td>
<td><strong>0.1</strong></td>
<td>faktor penurun lr tiap `step_size` (lr baru = lr × 0.1)</td>
</tr>
</table>

---

## 🔗 **link colab**

<div align="center">

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Ni0mQ7qrZmD0QmIXqFltyQ3dwOLQXGSr?usp=sharing)

### https://colab.research.google.com/drive/1Ni0mQ7qrZmD0QmIXqFltyQ3dwOLQXGSr?usp=sharing

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Ni0mQ7qrZmD0QmIXqFltyQ3dwOLQXGSr?usp=sharing)

</div>

---

<div align="center">

**🎓 Tugas Deep Learning - Semester 7**

*Made with ❤️ by Team Salt*

</div>