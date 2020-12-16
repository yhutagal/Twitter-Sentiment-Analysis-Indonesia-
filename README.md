# Twitter-Sentiment-Analysis-Indonesia-
Menggunakan tweepy dan textblob di Jupyter Notebook.
Cara yang digunakan :
1. Tarik data di twitter menggunakan tweepy dan sudah berhasil request di developer twitter
   (Dalam hal ini pencarian menggunakan bahasa indonesia, dengan jumlah tweet dibatasi 100)
2. Bersihkan data yang didapat
3. Translate data menjadi bahasa inggris karena kita menggunakan library TextBlob
4. Polarisasi menggunakan TextBlob untuk menentukan Apakah sentiment +/-/Netral
5. Bersihkan duplicate (Retweet)
6. Hitung Jumlah Sentiment Positif, Negative dan netral
