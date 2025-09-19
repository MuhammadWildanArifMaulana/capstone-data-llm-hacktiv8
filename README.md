# Proyek Capstone: Klasifikasi dan Ringkasan Data Menggunakan IBM Granite

## Deskripsi Proyek

Proyek ini merupakan bagian dari kelas Hacktiv8 X IBM Skills Build yang bertujuan untuk melakukan klasifikasi dan ringkasan teks menggunakan model bahasa besar (LLM) IBM Granite. Dataset yang digunakan adalah Sentiment Analysis Product At E-Commerce Tokopedia.

## Teknologi yang Digunakan

- **Platform:** Google Colab
- **Model LLM:** IBM Granite 3.3-8b-instruct
- **Bahasa Pemrograman:** Python
- **Library:** `replicate`, `langchain_community`, `pandas`

## Langkah-langkah Pengerjaan

1.  **Setup API:** Mengatur token API Replicate di Google Colab Secrets.
2.  **Pemuatan Data:** Memuat dataset data_real.csv ke dalam notebook menggunakan pandas.
3.  **Klasifikasi Teks:** Menerapkan model IBM Granite untuk mengklasifikasikan sentimen ulasan teks menjadi 'positif' atau 'negatif'.
4.  **Ringkasan Teks:** Menerapkan model untuk meringkas teks panjang dari dataset.

## Hasil Analisis

- **Klasifikasi Sentimen:** Tampilkan contoh output klasifikasi yang menunjukkan ulasan dan label sentimennya.
- **Ringkasan Teks:** Tampilkan contoh output ringkasan dari salah satu teks panjang.

## Cara Menjalankan Proyek

1.  Kloning repositori ini.
2.  Buka file `Copy_of_Wildan_Arif_SDI_Data_Session_3_(18_September_2025).ipynb` di Google Colab.
3.  Tambahkan token API Replicate Anda ke bagian Secrets di Google Colab.
4.  Jalankan setiap sel kode secara berurutan.

link google colab -> https://colab.research.google.com/drive/1tsXuYLheadGHUYB-5ItepTk4964nu7on?usp=sharing
