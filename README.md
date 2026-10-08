# Analisis Sentimen Twitter #WorldCup2022

Analisis dan preprocessing data tweet berbahasa Inggris terkait FIFA World Cup 2022 yang mengandung hashtag #WorldCup2022. Project ini berfokus pada text preprocessing dan text vectorization sebagai tahap awal dalam analisis sentimen.

## Dataset

Dataset yang digunakan adalah:

**FIFA World Cup 2022 Tweets**

Source: Kaggle  
https://www.kaggle.com/datasets/tirendazacademy/fifa-world-cup-2022-tweets

Dataset berisi 22.524 tweet berbahasa Inggris yang mengandung hashtag #WorldCup2022.

## Text Preprocessing

Tahapan preprocessing yang dilakukan meliputi:

- Lowercasing
- URL removal
- Username dan hashtag removal
- Emoji removal
- Number removal
- Punctuation removal
- Extra whitespace removal
- Slang word mapping
- Stopword removal
- Lemmatization
- Short word removal
- Tokenization

Preprocessing dilakukan untuk mengurangi noise dan menghasilkan teks yang lebih konsisten sebelum dilakukan proses text vectorization.

## Text Vectorization

Dua metode representasi teks digunakan untuk mengubah data teks menjadi bentuk numerik:

### Bag of Words

Bag of Words digunakan untuk merepresentasikan teks berdasarkan frekuensi kemunculan kata dalam dokumen.

### TF-IDF

TF-IDF (Term Frequency-Inverse Document Frequency) digunakan untuk memberikan bobot pada kata berdasarkan tingkat kepentingannya dalam kumpulan dokumen.

## Analysis

Project ini membandingkan karakteristik representasi teks menggunakan Bag of Words dan TF-IDF, termasuk kelebihan dan keterbatasan masing-masing metode dalam merepresentasikan data tweet.

## Tools

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

## Usage

Notebook utama:

`Analisis_Sentimen_WorldCup2022.ipynb`

Notebook berisi proses loading dataset, text preprocessing, dan text vectorization menggunakan Bag of Words dan TF-IDF.

## Results

Hasil preprocessing menghasilkan teks yang lebih terstruktur dan siap digunakan untuk tahap analisis sentimen atau pemodelan machine learning selanjutnya.

Representasi teks yang dihasilkan meliputi:

- Bag of Words matrix
- TF-IDF matrix

Eugenia Bening Sekar Pavita
