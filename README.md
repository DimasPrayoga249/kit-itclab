# IMPLEMENTASI SVM SEBAGAI PENGGANTI PENGENDALI PID PADA KIT ITCLAB

![JUDUL](https://github.com/Aliefindymillani/Mikrokontroler/assets/89888415/cd78f8b6-163b-4944-a817-e28578725250)

## Mikrokontroler
Mikrokontroler adalah perangkat semikonduktor yang terdiri dari CPU, memori, dan perangkat input/output terpadu, dirancang khusus untuk aplikasi dalam sistem tertanam. Berbeda dengan mikroprosesor yang hanya menyediakan CPU, mikrokontroler memiliki komponen yang diperlukan untuk menjalankan program secara mandiri. Komponen utama mikrokontroler melibatkan CPU sebagai pusat pemrosesan, memori untuk menyimpan program dan data, serta perangkat input/output (I/O) seperti pin digital dan analog, komunikasi serial, serta timer dan counter untuk penghitungan waktu atau peristiwa tertentu. Dengan ukuran kecil, konsumsi daya rendah, dan fleksibilitas pemrograman, mikrokontroler banyak digunakan dalam kendali otomatis, elektronika konsumen, kendaraan, peralatan medis, dan berbagai aplikasi lainnya. Keunggulannya terletak pada kemampuan untuk memberikan kontrol dan otomatisasi pada perangkat dengan efisien dan fleksibel. Sebagai inti dari inovasi di berbagai industri, mikrokontroler terus berperan penting dalam perkembangan teknologi.

## IOT
Internet of Things (IoT) adalah paradigma teknologi yang menghubungkan dan memungkinkan berkomunikasi antara perangkat fisik melalui internet. Dalam ekosistem IoT, objek sehari-hari seperti perangkat rumah tangga, kendaraan, atau bahkan pakaian dilengkapi dengan sensor, perangkat lunak, dan konektivitas internet. Ini memungkinkan perangkat tersebut untuk mengumpulkan, mentransmisikan, dan menerima data secara real-time, membuka pintu untuk berbagai aplikasi dan layanan yang inovatif. IoT memainkan peran penting dalam mendukung konsep kota pintar (smart cities), rumah pintar (smart homes), serta aplikasi industri, pertanian, dan kesehatan. Kelebihan utama IoT mencakup pemantauan dan kendali jarak jauh, analisis data yang mendalam, dan kemampuan untuk meningkatkan efisiensi operasional. Namun, seiring dengan manfaatnya, aspek keamanan dan privasi juga menjadi perhatian, dan pengembang IoT terus bekerja untuk mengatasi tantangan tersebut demi menciptakan lingkungan yang lebih terkoneksi dan cerdas.

## Sistem Kendali PID
Sistem Kendali Proporsional Integral dan Derivatif (PID) adalah metode kendali otomatis yang efektif digunakan dalam berbagai aplikasi untuk mengatur sistem dinamis. PID bekerja dengan memonitor perbedaan antara setpoint (nilai yang diinginkan) dan output aktual dari sistem, lalu meresponsnya dengan menghitung tiga komponen utama: Proporsional (P), Integral (I), dan Derivatif (D). Komponen Proporsional memberikan respons terhadap kesalahan saat ini, Integral mengatasi kesalahan kumulatif dari waktu, dan Derivatif mengantisipasi perubahan kesalahan di masa depan. Gabungan ketiga komponen ini memberikan kendali yang adaptif dan responsif terhadap fluktuasi dalam sistem. PID telah diterapkan dalam berbagai konteks, termasuk kendali suhu, robotika, industri, dan proses otomatisasi. Keunggulan PID terletak pada kemampuannya untuk memberikan respons yang cepat dan stabil, membuatnya menjadi algoritma kendali yang sangat umum dan efektif dalam mengoptimalkan kinerja sistem dinamis. Meskipun begitu, konfigurasi parameter PID yang tepat diperlukan untuk memastikan optimalitas dalam pengendalian berbagai jenis sistem.

## Deep Learning
Deep Learning adalah cabang dari machine learning yang mengeksplorasi penggunaan jaringan saraf tiruan (neural networks) dengan struktur yang lebih kompleks, terdiri dari banyak lapisan (layers). Dengan konsep terinspirasi dari cara kerja otak manusia, deep learning memiliki kemampuan untuk memahami dan memodelkan pola yang sangat kompleks dari data. Keunggulan utama deep learning terletak pada kemampuannya untuk secara otomatis mengekstrak fitur yang relevan dari data tanpa memerlukan pemrograman manual. Arsitektur deep learning yang terkenal seperti deep neural networks (DNN), convolutional neural networks (CNN), dan recurrent neural networks (RNN) telah memberikan kontribusi besar dalam pencapaian tingkat akurasi yang tinggi dalam tugas-tugas seperti pengenalan gambar, pengenalan suara, dan bahkan pemrosesan bahasa alami. Deep learning digunakan dalam berbagai industri, termasuk pengembangan produk kecerdasan buatan, analisis data, serta proyek-proyek yang melibatkan pengolahan dan interpretasi data kompleks. Meskipun keberhasilannya yang luar biasa, pelatihan model deep learning memerlukan volume data yang besar dan sumber daya komputasi yang kuat. Selain itu, interpretasi dan keamanan model juga menjadi pertimbangan penting seiring dengan pertumbuhan kompleksitas arsitektur deep learning.

## SVM
Support Vector Machine (SVM) adalah model pembelajaran mesin yang digunakan untuk klasifikasi dan regresi. SVM bekerja dengan menemukan hyperplane terbaik yang memisahkan dua kelas dalam ruang fitur. Hyperplane ini dipilih sedemikian rupa sehingga jarak antara hyperplane dan instance terdekat dari masing-masing kelas, yang disebut sebagai support vectors, maksimal. SVM sangat efektif dalam menangani data berdimensi tinggi dan mampu menangani situasi di mana batas keputusan antara kelas-kelas tersebut tidak linear. Terlepas dari kemampuannya untuk menangani masalah klasifikasi biner, SVM juga dapat diperluas untuk menangani klasifikasi multi-kelas dan regresi. Keunggulan SVM melibatkan kemampuannya untuk menangani data yang tidak teratur dan keberhasilannya dalam situasi di mana ada hubungan kompleks antara variabel-variabel input. Meskipun demikian, pemilihan kernel dan parameter SVM dapat mempengaruhi kinerja model, dan pemrosesan data skala besar mungkin memerlukan sumber daya komputasi yang signifikan. SVM digunakan secara luas dalam berbagai aplikasi seperti pengenalan pola, klasifikasi teks, dan analisis biomedis.

## Metode Penelitian

![Metode](https://github.com/DimasPrayoga249/kit-itclab/blob/eeb84f4e16f32c0d5b51d41276a0c00a11ebaa8d/assets/metode_penelitian.jpg)

Metode penelitian merupakan pendekatan yang digunakan dalam menghimpun, menganalisis, dan mengartikan data untuk menjawab pertanyaan penelitian atau mencapai tujuan penelitian yang telah ditetapkan. Dalam bagian ini, kami bertujuan untuk menguraikan metode penelitian yang diterapkan dalam kajian ini, mencakup tahapan pengumpulan data, pra-proses data, pelatihan model, dan proses evaluasi.

### Pengumpulan Data
Dalam penelitian ini, data dikumpulkan dengan menggunakan perangkat lunak emulasi iTCLab. Pada tahap pengumpulan data, emulator iTCLab diatur pada kecepatan 100 kali. Selama simulasi, nilai setpoint suhu bervariasi untuk mencerminkan berbagai target suhu yang diinginkan dalam pengendalian. Variasi pada setpoint diterapkan untuk memastikan kualitas pelatihan model. Emulator iTCLab dijalankan selama 540 loop. Loop atau siklus pengendalian suhu mengacu pada jumlah iterasi di mana emulator iTCLab membaca suhu sensor dan mengatur aktuator suhu untuk mencapai setpoint yang telah ditetapkan. Pada setiap iterasi, sensor suhu membaca nilai aktual, dan aktuator disesuaikan untuk mendekati setpoint yang diinginkan. Dataset setpoint yang digunakan untuk melatih model juga diilustrasikan dalam penelitian ini.

![Pengumpulan Data](https://github.com/DimasPrayoga249/kit-itclab/blob/cea01f5e8e468851f3ae05e755960eb04827c8bb/assets/pengumpulan_data.png)

### Pra Proses Data
Setelah memperoleh data set point dan error dari fase pengumpulan data, dilakukan tahap pra proses data untuk mempersiapkan data sebelum memasuki tahap pelatihan model. Salah satu langkah kunci dalam pra proses data adalah seleksi fitur atau ciri yang akan digunakan. Dalam penelitian ini, fitur yang terpilih meliputi set point dan error. Set point mewakili nilai target suhu dalam pengendalian suhu, sedangkan error adalah selisih antara set point dan suhu aktual yang terukur. Selain itu, output yang akan diprediksi dalam penelitian ini adalah Q, yang merupakan hasil penjumlahan dari tiga komponen, yaitu P (Proporsional), I (Integral), dan D (Derivative). Komponen-komponen ini merujuk pada algoritma kontrol PID (Proporsional-Integral-Derivative) yang digunakan untuk mengendalikan suhu.

Proses pemilihan fitur dan pembentukan output juga melibatkan normalisasi data. Normalisasi dilakukan untuk mengubah rentang nilai setiap fitur sehingga sejajar dan dapat diolah secara efektif oleh model pembelajaran mesin. Dalam penelitian ini, metode normalisasi yang digunakan adalah Min-Max Scaling, suatu teknik yang mengubah skala nilai data dari rentang nilai aktual menjadi rentang nilai antara 0 hingga 1 atau -1 hingga 1 (Naufal et al., 2023). Formula Min-Max Scaling diterapkan untuk mencapai normalisasi, di mana X scaled merupakan hasil dari skala data ke-i, 𝑥 adalah nilai asli dari data ke-i, xmin adalah nilai minimum dari X, dan xmax adalah nilai maksimum dari X.

![Pra Proses Data](https://github.com/DimasPrayoga249/kit-itclab/blob/cea01f5e8e468851f3ae05e755960eb04827c8bb/assets/pra_proses_data.png)

### Pelatihan Model
Proses pelatihan model dalam kerangka SVM (Support Vector Machine) mengacu pada langkah-langkah di mana algoritma SVM memanfaatkan data latihan untuk mengembangkan model yang nantinya dapat digunakan untuk melakukan prediksi atau klasifikasi pada data yang belum pernah dilihat sebelumnya. Dalam SVM, tujuan model yang dihasilkan adalah untuk mengelompokkan data ke dalam kelas-kelas yang berbeda dengan menemukan hyperplane (bidang pemisah) yang optimal. Proses pelatihan SVM melibatkan dua tahap utama, yaitu pembentukan model dan penentuan parameter.

![SVM](https://github.com/DimasPrayoga249/kit-itclab/blob/cea01f5e8e468851f3ae05e755960eb04827c8bb/assets/svm.png)

Tujuan dari proses pelatihan model SVM adalah mencapai generalisasi yang optimal, di mana model dapat melakukan klasifikasi data baru dengan tingkat akurasi yang tinggi. Mengetahui dengan baik karakteristik data, bijaksana dalam memilih parameter, dan melakukan validasi menjadi faktor penting untuk memastikan kinerja model yang optimal terhadap data yang tidak terlihat selama proses pelatihan.

### Evaluasi
Proses evaluasi dilakukan untuk memperbandingkan performa implementasi jaringan SVM sebagai alternatif pengendali PID dalam sistem kontrol. Evaluasi ini akan mengevaluasi tiga parameter utama, yaitu rising time, settling time, dan overshoot. Rising time mencerminkan durasi yang diperlukan oleh sistem untuk mencapai 90% dari nilai setpoint setelah terjadi perubahan input. Semakin cepat sistem mencapai nilai setpoint, semakin efisien kinerjanya. Settling time mengacu pada waktu yang dibutuhkan oleh sistem untuk mencapai nilai yang mendekati setpoint secara stabil, umumnya dalam rentang toleransi tertentu. Semakin singkat settling time, semakin baik kinerja sistemnya. Overshoot mencerminkan kelebihan nilai output yang melampaui setpoint sebelum akhirnya mencapai nilai stabil. Overshoot yang signifikan menunjukkan ketidakstabilan atau respons sistem yang tidak diinginkan. Oleh karena itu, semakin rendah nilai overshoot, semakin optimal kinerja sistemnya. Dalam evaluasi ini, efisiensi jaringan LSTM akan dibandingkan dengan pengendali PID tradisional dan pengendali PID yang memanfaatkan deep learning berdasarkan kriteria-kriteria tersebut.

## Hasil Penelitian
Dalam penelitian ini, terjadi penilaian performa antara pengendali PID konvensional, pengendali PID yang memanfaatkan deep learning, dan pengendali berbasis LSTM. Tiga indikator evaluasi utama yang digunakan mencakup rising time, settling time, dan overshoot.

![PID_Result](https://github.com/DimasPrayoga249/kit-itclab/blob/cea01f5e8e468851f3ae05e755960eb04827c8bb/assets/PID_Result.png)

PID RESULT

![SVM_Result](https://github.com/DimasPrayoga249/kit-itclab/blob/cea01f5e8e468851f3ae05e755960eb04827c8bb/assets/SVM_Result.png)

SVM RESULT

Grafik evaluasi kinerja PID berbasis deep learning membandingkan aspek kritis antara sistem PID tradisional dan PID SVM. Dalam hal rising time, sistem PID tradisional menunjukkan kinerja yang lebih cepat, dengan selisih waktu 15 detik lebih singkat dibandingkan dengan PID SVM. Ini mengindikasikan bahwa PID tradisional lebih efisien dalam mencapai 90% dari nilai setpoint setelah perubahan input.

Meskipun demikian, perbandingan settling time menunjukkan hasil yang berbeda. Sistem PID tradisional memerlukan waktu lebih lama 1 detik dibandingkan PID SVM untuk mencapai nilai yang mendekati setpoint secara stabil. Ini menandakan bahwa, meskipun PID tradisional lebih cepat mencapai 90% setpoint, PID SVM lebih unggul dalam mencapai penyelesaian yang stabil dan mendekati setpoint dengan lebih efisien.

Selain itu, analisis overshoot menunjukkan bahwa PID tradisional memiliki nilai overshoot yang lebih kecil, yaitu sebesar 0.81%, dibandingkan dengan PID SVM. Ini menunjukkan bahwa sistem kontrol PID tradisional lebih mampu menghasilkan respons yang lebih stabil dan minim overshoot dibandingkan dengan implementasi PID SVM.

Dengan demikian, hasil grafik kinerja memberikan gambaran menyeluruh tentang kelebihan dan kekurangan masing-masing metode pengendalian, memungkinkan pemahaman yang lebih baik tentang kinerja keduanya dalam konteks sistem dan tujuan kontrol yang spesifik.

## Kesimpulan
Berdasarkan evaluasi performa sistem kendali, dapat disimpulkan bahwa sistem kendali yang berbasis SVM menunjukkan potensi sebagai opsi menarik untuk menggantikan sistem kendali PID konvensional. PID SVM menunjukkan performa yang lebih unggul terutama dalam aspek settling time dan overshoot, menunjukkan kemampuan sistem untuk mencapai nilai yang mendekati setpoint secara stabil dengan waktu yang lebih efisien dan respons yang lebih terkontrol dengan overshoot yang lebih kecil dibandingkan dengan PID tradisional. Meskipun demikian, perlu dicatat bahwa PID SVM memiliki sedikit kekurangan dalam hal rising time, yang menunjukkan waktu yang diperlukan oleh sistem untuk mencapai 90% dari nilai setpoint setelah terjadi perubahan input. Walaupun demikian, keunggulan pada settling time dan overshoot dapat dianggap sebagai indikator positif, menunjukkan bahwa pengendalian SVM memiliki kinerja yang sangat baik dalam mencapai stabilisasi dan respons yang diinginkan dalam suatu sistem. Oleh karena itu, implementasi sistem kendali berbasis SVM dapat menjadi pilihan yang lebih optimal, bergantung pada kebutuhan khusus dan prioritas performa kendali yang diinginkan dalam suatu aplikasi.














