Proyek Analisis Data (Bike-Sharing Dataset)

Deskripsi Proyek
Dashboard interaktif yang dibuat dengan **Streamlit** untuk menganalisis data peminjaman sepeda. Proyek ini mencakup analisis pengaruh hari libur terhadap jumlah peminjaman sepeda, pola pengguna baru vs pengguna lama, serta analisis RFM. Proyek ini dilakukanoleh Muhammad Firdaus dengan email firdauspdr20@gmail.com dan ID Dicoding mc211d5y2137.

Library yang digunakan
> Numpy
> Pandas
> Matplotlib
> Seaborn
> Google Colab Drive
 
Data Wrangling
Gathering Data
> Dataset day.csv dan hour.csv diambil dari file di Google Drive
> Dataset day.csv berisi 731 baris dan 16 kolom
> Dataset hour.csv berisi 17379 baris dan 17 kolom

Assessing Data & Cleaning Data
> day.csv:
  - Tidak ada missing value, jadi tidak perlu dilakukan pembersihan
  - Tidak ada data yg duplikat, jadi tidak perlu dilakukan pembersihan
  - Statistik deskriptif menunjukkan tidak ada nilai yang tidak masuk akal
> hour.csv:
  - Tidak ada missing value, jadi tidak perlu dilakukan pembersihan
  - Tidak ada data yg duplikat, jadi tidak perlu dilakukan pembersihan
  - Statistik deskriptif menunjukkan tidak ada nilai yang tidak masuk akal

Langkah Selanjutnya
> Melakukan analisis lebih lanjut untuk menjawab pertanyaan bisnis yang telah ditentukan
> Membuat visualisasi data untuk mendapatkan insight
> Melakukan analisis tambahan 
> Membuat dashboard streamlit

Setup environment
conda create --name mc211d5y2137 python=3.9 conda activate mc211d5y2137 pip install -r requirements.txt

Run streamlit app
streamlit run dashboard\dashboard.py
