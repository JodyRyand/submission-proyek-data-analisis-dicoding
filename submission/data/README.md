\# Bike Sharing Analytics Dashboard 🚲



Aplikasi dashboard interaktif untuk menganalisis tren penyewaan sepeda berdasarkan pengaruh cuaca/musim serta pola jam sibuk (\*peak hours\*).



\## Struktur Direktori

\- `dashboard/`: Berisi berkas utama aplikasi Streamlit (`dashboard.py`) dan dataset olahan (`main\_data.csv`).

\- `data/`: Berisi berkas dataset mentah asli (`day.csv` dan `hour.csv`).

\- `notebook.ipynb`: Berkas Jupyter Notebook yang berisi alur lengkap analisis data (Data Wrangling, EDA, Visualisasi, Kesimpulan).

\- `README.md`: Berkas petunjuk penggunaan dashboard ini.

\- `requirements.txt`: Berkas berisi daftar pustaka/library Python yang dibutuhkan.

\- `url.txt`: Berkas berisi tautan deployment Streamlit Cloud (opsional).



\## Cara Menjalankan Dashboard Secara Lokal



\### 1. Setup Environment

Disarankan untuk membuat virtual environment terlebih dahulu:



```bash

python -m venv venv

\# Windows

venv\\Scripts\\activate

\# Mac/Linux

source venv/bin/activate

