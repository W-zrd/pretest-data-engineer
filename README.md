# soal untuk pretest-data-engineer

## Knowledge Base
1. **Apa yang Anda ketahui tentang Data Engineer ?**
   - Data Engineer bertanggung jawab untuk membangun, mengelola, dan mengoptimalkan infrastruktur data yang memungkinkan analisis data dan pengambilan keputusan. Mereka mengolah data dari berbagai sumber, membersihkan, dan mengintegrasikannya ke dalam sistem yang siap digunakan oleh Data Scientist atau Analyst.
2. **Ceritakan pengalaman Anda dalam mengolah data?**
   - Saya memiliki pengalaman mengolah data dalam **proyek mata kuliah** AI dan statistika, **serta kompetisi data mining**. Di proyek kampus, saya melakukan proses pengolahan dataset sebelum akhirnya diproses untuk training model, melakukan visualisasi data, hingga menguji model pada dataset testing. Hasil dan analisis mengenai projek ini dapat dilihat pada [repositori saya berikut](https://github.com/W-zrd/KNN-BinaryClasification). 
   - Di kompetisi data mining pun demikian. Namun bedanya saya sering bekerja dengan dataset yang lebih besar dan kompleks, melakukan cleaning data, mengolah data menggunakan library python, seperti Pandas atau Numpy, hingga mengevaluasi model menggunakan scikit learn.
3. **Apa yang kamu ketahui tentang AI**
   - AI adalah teknologi yang memungkinkan mesin atau komputer untuk melakukan tugas yang biasanya memerlukan kecerdasan manusia, seperti pengenalan pola, pengambilan keputusan, atau pemrosesan bahasa alami. AI menggunakan algoritma dan model untuk belajar dari data dan membuat prediksi atau keputusan secara otomatis.
4. **Mengapa Data menjadi sesuatu yang sangat penting sekarang, dan apa dampak dari kebocoran data**
   - Data sangat penting karena menjadi dasar dalam pengambilan keputusan. Data memungkinkan perusahaan untuk memahami tren, memprediksi perilaku, dan meningkatkan efisiensi. Kebocoran data dapat menyebabkan kerugian finansial, merusak reputasi, dan pelanggaran privasi, serta dapat menimbulkan masalah hukum.
5. **Apa yg anda ketahui mengenai model generative AI ? dan apa saja penerapannya**
   - Model generative AI adalah jenis model AI yang bisa menghasilkan konten baru seperti teks, gambar, atau suara yang mirip dengan data yang sudah dilatih sebelumnya. Contoh penerapannya yaitu pembuatan auto-generated content, AI generative image, dan peningkatan kualitas gambar atau suara.


## Soal Coding
studi kasus = 
seorang data engineer diharuskan oleh klien untuk membuat
blueprint data orchestration di sebuah tools yaitu Kestra.
klien ingin memproses data review lazada (review-lazada.csv).

kami sudah menyediakan akses kestra di
[Kestra](https://kestra-magang.t-dev.site/) - https://kestra-magang.t-dev.site/ 
silahkan pelajari kestra lihat dokumentasinya 
dan silahkan lakukan proses dibawah ini:

1. satu flows untuk proses data cleansing dimana bersihkan data reviewnya kemudian export ke csv
2. satu flows untuk proses menghitung sentiment analysis berdasarkan kolom rating

Keterangan :
flow kestra dan script python sertakan dalam git kalian ketika pelaporan

### Answer
Berikut adalah flow yang sudah saya buat mengenai [Data Cleaning](/data_cleaning_flow.yml) dan [Sentiment Analysis](/sentiment_analysis_flow.yml). Kedua flow berjalan dengan lancar dan menghasilkan output yang sesuai dengan yang diminta soal.

![alt](/img/kestra.png)


Adapun berikut hasil visualisasi sentiment analysis berdasarkan flow tersebut.

![alt](/img/visualisation.png)