# Business Understanding
Topik yang saya pilih adalah mengenai PSSI (Persatuan Sepakbola Seluruh Indonesia). Saya memilih topik PSSI karena saya berharap dapat menganalisis persepsi publik terhadap PSSI melalui sentimen yang terkandung dalam berbagai media sosial. Tujuannya adalah untuk mengidentifikasi bagaimana publik merespons dan memandang PSSI, dan apakah ada tren positif atau negatif. Dengan menggunakan teknik analisis sentimen, saya berharap dapat mengumpulkan data yang akurat dan dapat diandalkan tentang persepsi publik terhadap PSSI. Ini akan membantu PSSI untuk mengidentifikasi bagaimana dapat meningkatkan pengalaman penggemar mereka, dan meningkatkan popularitas mereka di antara masyarakat.
# Data Understanding
## Data Collection
Data yang saya ambil berasal dari twitter pada tanggal 20 Januari 2023 sampai 22 Januari 2023 dengan kata kunci pssi, dan data tambahan dari web kompas dengan tag pssi. 
- Data dari twitter sebanyak 300.
- Data dari web (scrapping) sebanyak 10.
## Data Analysis
### Distribusi frekuensi jumlah huruf per data
<img width="263" alt="image" src="https://github.com/user-attachments/assets/38a43d9f-3b04-43bf-a58b-f900351cfc3d">

Distribusi terbanyak berada pada 10 - 70 huruf per kalimat. Dengan kalimat yang memiliki panjang diatas 20 huruf. 
### Distribusi frekuensi jumlah kata per data
<img width="261" alt="image" src="https://github.com/user-attachments/assets/165e9e2a-cb6c-4647-ac9a-44129c8f5b35">

Distribusi terbanyak berada pada 4 - 10 kata per kalimat. Kalimat dengan jumlah kata diatas 13 tidak terlalu banyak. 
### Distribusi Frekuensi Panjang Kata Rata-Rata Pada Data
<img width="263" alt="image" src="https://github.com/user-attachments/assets/ae91e4bf-25ed-43f3-a1d1-9a4f27de409e">

Distribusi terbanyak berada pada 5 - 7 karakter per kata per tweet. Jumlah huruf pada kata yang umum ada pada bahasa indonesia. 
### Distribusi Frekuensi Kata yang sering keluar
<img width="272" alt="image" src="https://github.com/user-attachments/assets/d5be08d1-fce0-4344-9981-3130ce135314">

Distribusi kata yang sering keluar terdapat pada kata erick, thohir, dan indonesia dengan frekuensi kemunculan diatas 35 kali.
### Distribusi N-gram
<img width="260" alt="image" src="https://github.com/user-attachments/assets/cfb2d81e-f4c6-4da6-b2a1-6659cf735ce8">

Berdasarkan bigram diatas, dapat disimpulkan bahwa isu dan topik yang sedang hangat dibicarakan adalah tentang pemilihan ketua dimana erick tohir merupakan calon ketua yang paling banyak dibicarakan, restu yang diberikan presiden, sepak bola di Indonesia, dan liga Indonesia.
## Data Preprocessing
Pada tahap preprocessing dilakukan empat teknik pembersihan data yaitu case folding, tokenizing, stopwords, dan stemming. Pada gambar diatas kolom text merupakan data mentah yang belum dilakukan preprocessing, sedangkan kolom review merupakan hasil preprocessing dari kolom text. 

# Reporting
## Analisis Akhir
Pada tahap ini dilakukan analisis terhadap sentiment, apakah sentiment tersebut positif, netral, atau negative. Pengelompokan sentiment berdasarkan pada kata-kata yang terdapat pada database kata_positif.txt dan kata_negatif.txt.

<img width="281" alt="image" src="https://github.com/user-attachments/assets/676d900a-3d11-4405-babb-8bf74be8cdb0">

Dari gambar diatas maka data sentiment ini termasuk distribution normal.

<img width="287" alt="image" src="https://github.com/user-attachments/assets/8471e5ad-630c-4124-91a9-b3f8ce5f5b12">

Dari gambar diatas terlihat bahwa lebih banyak sentiment positif dari pada sentiment negatif. Tetapi disamping itu lebih banyak yang memberikan opini netral.
## Kesimpulan
Dari analisa sentiment analysis yang dilakukan pada topik PSSI yang membahas Erick Thohir sebagai calon ketua baru, didapatkan hasil bahwa sentiment netral lebih banyak dibanding sentiment positif, dan sentiment positif lebih banyak dibanding sentiment negatif. Hal ini menunjukkan bahwa mayoritas responden memberikan pendapat yang netral terhadap Erick Thohir sebagai calon ketua baru PSSI. Namun, ada juga sebagian responden yang memberikan pendapat positif dan negatif terhadap Erick Thohir. Hal ini menandakan bahwa mayoritas responden belum yakin terhadap kemampuan Erick Thohir dalam memimpin PSSI. Oleh karena itu, untuk memastikan bahwa Erick Thohir dapat memimpin PSSI dengan baik, pihak yang berwenang harus melakukan lebih banyak riset dan mempertimbangkan pendapat responden sebelum memutuskan Erick Thohir sebagai calon ketua baru PSSI. 
