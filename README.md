# Electric_Vehicle_Population_Data
Capstone Project
#  Capstone Project – Electric Vehicle Population Data 2025  
Data Classification & Summarization | Washington State  
Deadline: 31 Agustus 2025 | 23.59 WIB  

---

## 📌 Project Overview  
Proyek ini menganalisis dataset *Electric Vehicle (EV) Population Washington State 2025* untuk memahami tren adopsi EV berdasarkan:  
- *Merek & Model* → produsen dominan & model favorit  
- *Tahun Produksi* → tren pertumbuhan & penurunan EV  
- *Wilayah (County)* → distribusi spasial adopsi EV  

Selain analisis eksploratif (EDA), proyek ini memanfaatkan *AI (IBM Granite via Replicate)* untuk menghasilkan *summarization & rekomendasi berbasis data*.  

---

## 📊 Dataset  
- *Sumber:* [Kaggle – Electric Vehicle Population Data 2025](https://www.kaggle.com/datasets/yanghu583/electric-vehicle-population-data-2025)  
- *Asal Data:* Washington State Department of Licensing (Open Data Program)  
- *Fitur Utama:*  
  - Make, Model, Model Year, County, Electric Vehicle Type, CAFV Eligibility, VIN  

---

## ⚙️ Analysis Workflow  
1. *Data Preprocessing* → membersihkan duplikat & missing values  
2. *EDA (Exploratory Data Analysis)* → Python (pandas, matplotlib, seaborn)  
3. *Visualisasi* → Top 10 brand, model, tren produksi tahunan, distribusi county  
4. *AI-assisted Summarization* → insight via IBM Granite (Replicate)  
5. *Recommendations* → untuk produsen, pemerintah, konsumen  

---

## 🔎 Key Findings  

### 🔟 Top EV Manufacturers  
TESLA        105,253  
CHEVROLET     18,223  
NISSAN        16,085  
FORD          13,492  
KIA           12,171  
BMW           10,551  
TOYOTA        10,429  
HYUNDAI        8,328  
RIVIAN         7,637  
VOLVO          6,570  

*AI Insight:* Tesla sangat dominan, namun produsen mapan (GM, Nissan, Ford, Toyota) menunjukkan peningkatan signifikan. Rivian muncul sebagai pendatang baru dengan segmen pickup/SUV.  

---

### 📈 EV Production Trend per Year  
2023 → 59,273 (puncak)  
2024 → 49,710  
2025 → 23,319  
2026 → 2,190  

*AI Insight:*  
- Pertumbuhan stabil sejak 2011, puncak pada 2023  
- Penurunan tajam pasca-2023, kemungkinan akibat supply chain, kebijakan, atau pasar mulai jenuh  

---

### 🌍 Top 5 Counties by EV Registration  
King        124,211  
Snohomish    31,031  
Pierce       20,829  
Clark        15,279  
Thurston      9,175  

*AI Insight:* Konsentrasi tinggi di *Seattle Metro Area (King, Snohomish, Pierce)* karena infrastruktur charging, kebijakan progresif, dan daya beli tinggi.  

---

### 🚘 Top 10 EV Models  
MODEL Y           51,903  
MODEL 3           37,334  
LEAF              13,959  
MODEL S            7,883  
BOLT EV            7,598  
MODEL X            6,660  
MUSTANG MACH-E     5,472  
ID.4               5,252  
WRANGLER           4,706  
IONIQ 5            4,682  

*AI Insight:* Tesla Model Y & 3 mendominasi. Nissan Leaf populer karena affordability. Tren konsumen bergeser ke SUV/crossover (Mach-E, ID.4, Ioniq 5).  

---

## 💡 Recommendations  

### 🔹 Untuk Produsen  
- Fokus produksi *Model Y & 3* sesuai demand  
- Gandeng *King County* sebagai pusat promosi & pilot project  
- Diversifikasi segmen → SUV & pickup EV  

### 🔹 Untuk Pemerintah Daerah  
- Perluas *charging station* di daerah suburban & rural  
- Berikan *insentif lebih merata*, bukan hanya di urban area  
- Monitor *stabilitas supply chain* agar tidak ada penurunan produksi ekstrem  

### 🔹 Untuk Konsumen  
- *Tesla Model Y/3* → pilihan aman (infrastruktur + resale value tinggi)  
- EV keluaran *2023 ke atas* → teknologi & fitur lebih baru  
- Maksimalkan subsidi & insentif lokal di wilayah masing-masing  

---

## 🤖 AI Support Explanation  
AI (IBM Granite via Replicate) digunakan untuk:  
- Merangkum hasil EDA secara efisien  
- Mengidentifikasi pola adopsi yang tidak langsung terlihat  
- Menyusun rekomendasi strategis berbasis data  

---

## 📂 Repository Structure  
electric-vehicle_population_summarization/  
│  
├── data/                  # dataset (opsional, gunakan link Kaggle jika besar)  
├── notebooks/             # Jupyter / Colab notebooks untuk analisis  
├── results/               # grafik, summary, output visualisasi  
├── slides/                # presentasi final (PPT/PDF)  
├── README.md              # dokumentasi utama  
├── .gitignore             # exclude file besar / temporary  
└── LICENSE                # lisensi proyek  

---

## 🛠️ Tools & Tech Stack  
- *Python* → pandas, seaborn, matplotlib  
- *AI* → IBM Granite via [Replicate](https://replicate.com)  
- *Environment* → Google Colab, GitHub  

---

✍️ *Authors*: Capstone Data Science Team – 2025  
📌 Repo: [electric-vehicle_population_summarization](https://github.com/yourusername/electric-vehicle_population_summarization)
