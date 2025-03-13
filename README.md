
## Proyek Analisis Data (Bike-Sharing Dataset)

## Deskripsi Proyek
Dashboard interaktif yang dibuat dengan **Streamlit** untuk menganalisis bagian data hour.csv & day.csv dari bike sharing analysis. Proyek ini mencakup analisis pengaruh hari libur terhadap jumlah peminjaman sepeda, pola penyewaan sepeda berdasarkan jam dalam 1 hari, serta analisis RFM dan mendapatkan beberapa *insight* menarik di dalam data

## Struktur Direktori
- /dataset berisi data mentah yang digunakan dalam proyek
- /dashboard berisi dashboard.py yang digunakan untuk membuat streamlit dari hasil analisa data serta dataset yang sudah di **assess** & **cleaning**
- tugasML.ipynb adalah **notebook** yang digunakan dalam analisa data
 
## Langkah Instalasi
1. Silahkan clone repository ini ke **local computer** anda, lakukan langkah dibawah ini
   ```shell
   git clone https://github.com/MFirdaus20/bike-sharing-dashboard
   ```
 2. Install python (jika belum memilikinya), jika sudah memiliki **environment** silahkan jalankan perintah berikut untuk menginstall pustaka yang dibutuhkan
    ```shell
    pip install -r requirements.txt
    ```

## Penggunaan
1. Masuk ke direktori proyek local :
   ```shell
   cd Tugas ML 1/ dashboard/
   streamlit run dashboard/dashboard.py
   ```
   anda bisa melihat aplikasi yang telah di deploy di streamlit dalam [link berikut](https://bike-sharing-dashboard-oyeqysdvdncyuru6rrrpcf.streamlit.app/)
