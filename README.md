# Proyek Akhir Arsitektur Jaringan Modern: Implementasi & Analisis Multipath SPF

[cite_start]Proyek ini bertujuan untuk mengevaluasi performa algoritme **Multipath SPF** dibandingkan dengan algoritme **Single-path** (Dijkstra & Bellman-Ford) pada lingkungan SDN menggunakan **OSKen** dan **Mininet**[cite: 1, 167].

## 👥 Anggota Kelompok
* **Ibnu Nabel Fauzi** - PM & Data Analyst
* **Amos Juang** - Network Designer
* **Sandhika Rizqi Ramadhan** - Multipath Developer
* **Aldersyifan Arzada Ahmad** - Single-path Developer
* **Aero Nathanael Silalahi** - QA & Test Engineer

## 🚀 Desain Eksperimen
[cite_start]Eksperimen dilakukan pada dua jenis topologi untuk melihat pengaruh struktur jaringan terhadap performa[cite: 30, 169]:
1. [cite_start]**Topologi Diamond**: Baseline dengan 2 jalur alternatif yang setara[cite: 173].
2. [cite_start]**Topologi Partial Mesh**: Skenario kompleks dengan >2 jalur alternatif[cite: 173].

## 🛠️ Cara Menjalankan Eksperimen

### 1. Prasyarat
Pastikan sistem Anda telah terinstal:
* [cite_start]Python 3 [cite: 83]
* [cite_start]Mininet [cite: 82]
* [cite_start]OSKen Controller [cite: 81]

### 2. Menjalankan Controller
Buka terminal baru dan jalankan controller yang diinginkan (contoh Multipath):
```bash
osken-manager controllers/multipath_spf.py
