# ♻️ Klasifikasi Sampah AI

Sistem klasifikasi sampah berbasis Deep Learning menggunakan arsitektur **ResNet50** dan **MobileNetV2** dengan framework TensorFlow dan Flask.

---

## 📌 Fitur

- Upload gambar sampah
- Prediksi otomatis menggunakan AI
- Menampilkan hasil klasifikasi
- Menampilkan nilai confidence
- Antarmuka berbasis web menggunakan Flask

---

## 📂 Dataset

Dataset terdiri dari **6 kelas**:

- Cardboard
- Glass
- Metal
- Paper
- Plastic
- Trash

Dataset diproses menjadi dataset seimbang dengan **600 gambar setiap kelas**.

Total dataset:

| Dataset | Jumlah |
|----------|---------|
| Train | 2880 |
| Validation | 360 |
| Test | 360 |

---

## 🧠 Model Deep Learning

Model yang digunakan:

- MobileNetV2
- ResNet50

Model terbaik yang digunakan pada aplikasi web adalah:

**ResNet50**

---

## 📈 Hasil Evaluasi

### ResNet50

| Metric | Nilai |
|---------|-------|
| Accuracy | 93.33% |
| Precision | 93% |
| Recall | 93% |
| F1-Score | 93% |

### MobileNetV2

| Metric | Nilai |
|---------|-------|
| Accuracy | 91.11% |
| Precision | 91% |
| Recall | 91% |
| F1-Score | 91% |

---

## 📁 Struktur Project

```
Klasifikasi-Sampah-AI
│
├── dataset
├── dataset_processed
├── dataset_split
├── model
├── notebooks
├── result
├── web
│   ├── static
│   ├── templates
│   └── app.py
│
└── README.md
```

---

## ⚙️ Cara Menjalankan

### Clone Repository

```bash
git clone https://github.com/USERNAME/Klasifikasi-Sampah-AI.git
```

Masuk folder project

```bash
cd Klasifikasi-Sampah-AI
```

Install dependency

```bash
pip install -r requirements.txt
```

Masuk folder web

```bash
cd web
```

Jalankan Flask

```bash
python app.py
```

Buka browser

```
http://127.0.0.1:5000
```

---

## 📸 Tampilan Sistem

### Halaman Utama

*(Tambahkan screenshot halaman utama di sini)*

### Hasil Prediksi

*(Tambahkan screenshot hasil prediksi di sini)*

---

## 🛠️ Teknologi

- Python
- TensorFlow
- Flask
- NumPy
- Matplotlib
- HTML
- CSS

---

## 👨‍💻 Pengembang

Proyek ini dibuat sebagai implementasi Deep Learning untuk klasifikasi sampah berbasis citra menggunakan ResNet50 dan MobileNetV2.