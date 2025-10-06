~ Panduan Instalasi & Error Handling
1. Deskripsi Proyek

Proyek ini menggunakan Python untuk melakukan Exploratory Data Analysis (EDA) pada dataset Ecommerce_Data_2024-2025.csv.
Library utama yang digunakan adalah:

pandas → untuk membaca, membersihkan, dan mengolah data.

matplotlib → untuk membuat visualisasi dasar.

seaborn → untuk visualisasi yang lebih estetik dan informatif.

2. Persyaratan Sistem

Python 3.8 atau lebih baru

PIP (Python Package Installer)

3. Instalasi Library

Jika saat menjalankan kode muncul error seperti:

ModuleNotFoundError: No module named 'pandas'
ModuleNotFoundError: No module named 'matplotlib'
ModuleNotFoundError: No module named 'seaborn'


Itu berarti library belum terinstall.
Ikuti langkah-langkah berikut:

🔹 Windows / MacOS / Linux

Buka terminal atau command prompt, lalu jalankan:

pip install pandas matplotlib seaborn

🔹 Jika menggunakan Jupyter Notebook

Jalankan perintah berikut di cell notebook:

!pip install pandas matplotlib seaborn

🔹 Jika menggunakan Anaconda
conda install pandas matplotlib seaborn

4. Verifikasi Instalasi

Setelah instalasi, cek apakah berhasil dengan menjalankan:

import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns


Jika tidak ada error, berarti instalasi berhasil ✅.

5. Tips Mengatasi Error Umum

Error pip not found → pastikan Python sudah terinstall dan tambahkan ke PATH.

Versi lama → update pip dengan:

pip install --upgrade pip


Virtual environment → jika menggunakan venv atau conda, pastikan aktifkan environment sebelum install.
