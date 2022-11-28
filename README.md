# basic-text-processing

Langkah - Langkah :
1. Mengimport library yang dibutuhkan seperti regex, string, pandas, dan nltk
2. Mengimport dataset yang dibutuhkan yaitu yelp_labelled dari kaggle
3. Kemudian drop column dataset yang tidak diperlukan
4. Selanjutnya rename nama column untuk memudahkan proses deklarasi
5. Tahap pertama dalam preprocessing yaitu case folding dan removing, mengubah text huruf kapital menjadi huruf kecil. Selanjutnya menghilangkan angka. Kemudian menghilangkan special character dan tanda baca
6. Tahap terakhir yaitu filtering, yaitu menghilangkan kata tidak penting yang terdapat dalam kamus stopword yang sudah di import atau download sebelumnya
