
# ✨ Analisis data e-commerce Brasil✨

Dashboard interaktif untuk menganalisis data e-commerce Brasil, mulai dari tren pesanan harian, performa produk dan seller, hingga segmentasi pelanggan menggunakan analisis RFM.

---

## 🛠️ Setup Environment

### 🔹 Menggunakan Anaconda

```bash
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
```

### 🔹 Menggunakan Shell/Terminal (Pipenv)

```bash
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt
```

---

## 🚀 Menjalankan Aplikasi Streamlit

```bash
streamlit run dashboard.py
```

---

## 📦 Requirements

Pastikan file `requirements.txt` tersedia di direktori kerja. Isi utamanya mencakup:

- `streamlit`
- `pandas`
- `matplotlib`
- `seaborn`
- `Babel`

---

## 📁 File yang Dibutuhkan

- `dashboard.py` → file utama untuk menjalankan Streamlit dashboard (dashboard.py berada di All_data.7z)
- `all_data.csv` → dataset yang dianalisis

---

## 📸 Tampilan Dashboard

Dashboard mencakup:

- Daily Order & Revenue
- Distribusi pelanggan berdasarkan kota
- Tren pesanan & revenue 5 kota terbesar
- Metode pembayaran
- Produk terlaris & tidak laris
- Performa seller
- Analisis RFM pelanggan

---

© 2025 - Dashboard by [Ipan Apres!]
