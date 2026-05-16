# NutriFirst - Capstone Project Codingcamp DBS Foundation x Dicoding 2026
ID Tim Capstone Project: CC26-PSU102
List Anggota:
1. [CFCC185D6Y2119] - Benediktus Pascal Sanjaya - Full-Stack Web Developer 
2. [CFCC185D6Y2818] - Benediktus Geraldi - Full-Stack Web Developer 
3. [CDCC185D6Y2675] - Arel Lafito Dinoris - Data Scientist 
4. [CDCC185D6Y2746] - Jose Morinho Ngadio - Data Scientist 
5. [CACC126D6Y0062] - Farid Rilani Hakim - AI Engineer 
6. [CACC126D6Y0053] - Mahendra Agyal Kautsar - AI Engineer 

## Deskripsi
NutriFirst adalah aplikasi web personalisasi yang memberikan rekomendasi menu makanan berdasarkan budget untuk memberikan rekomendasi menu makanan dengan detail analisis gizi (protein, kalori, lemak, karbohidrat) untuk membantu penurunan angka stunting.

## Fitur Utama
- **Filter Interaktif (Slicer)**: Filter berdasarkan bahan dasar, harga, kalori, protein
- **Pagination**: Navigasi halaman untuk melihat daftar menu
- **Analisis Harga**: Distribusi dan statistik harga per bahan dasar
- **Analisis Gizi**: Hubungan protein vs lemak, matriks korelasi
- **Rekomendasi Diet**: Menu dengan protein tinggi, rendah lemak & karbo
- **Korelasi Harga vs Protein**: Insight apakah harga mahal menjamin protein tinggi

## Cara Instalasi

### Manual
- Akses Github: https://github.com/CC26-PSU102/nutrifirst-dashboard
- Clone repository: `git clone https://github.com/CC26-PSU102/nutrifirst-dashboard.git`
- Masuk ke folder: `cd nutrifirst-dashboard`
- Install dependencies: `pip install -r requirements.txt`
- Jalankan dashboard: `cd dashboard && streamlit run dashboard.py`

### Otomatis
- Akses Github: https://github.com/CC26-PSU102/nutrifirst-dashboard
- Buka file `url.txt`
- Klik URL yang ada di dalam file tersebut

## Struktur File
```
nutrifirst-dashboard/
├── dashboard/
│   ├── main_data.csv
│   └── dashboard.py
├── data/
│   └── nutrition_with_price.csv
├── notebook.ipynb
├── README.md
├── requirements.txt
└── url.txt
```