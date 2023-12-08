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

Metode penelitian adalah metode yang digunakan dalam mengumpulkan, menganalisis, dan menginterpretasi data untuk menjawab pertanyaan penelitian atau mencapai tujuan penelitian yang telah ditetapkan. Pada sub bab ini kami ingin menjelaskan metode penelitian yang digunakan dalam studi ini, yang meliputi pengumpulan data, pra proses data, pelatihan model, dan evaluasi.

### Pengumpulan Data
Dalam penelitian ini, pengumpulan data dilakukan dengan memanfaatkan perangkat lunak emulasi TCLab. Pada tahap pengumpulan data, TCLab emulator diatur pada kecepatan 100 kali. Selama simulasi berlangsung, setpoint suhu diberikan dengan variasi yang beragam. Setpoint ini mencerminkan nilai target suhu yang diinginkan dalam pengendalian suhu. Untuk memastikan kualitas pelatihan model, variasi d
iberlakukan pada setpoint dalam penelitian ini. TCLab emulator dijalankan selama 540 loop. Loop atau siklus pengendalian suhu merujuk pada jumlah iterasi di mana TCLab emulator melakukan pembacaan sensor suhu dan mengatur aktuator suhu untuk mencapai setpoint yang telah ditetapkan. Pada setiap iterasi, sensor suhu membaca nilai aktual, dan aktuator disesuaikan untuk mendekati setpoint yang diinginkan. Grafik setpoint dataset yang digunakan untuk melatih model juga disajikan dalam penelitian ini.

![Pengumpulan Data](https://github.com/DimasPrayoga249/kit-itclab/blob/cea01f5e8e468851f3ae05e755960eb04827c8bb/assets/pengumpulan_data.png)

### Pra Proses Data
Setelah mendapatkan data set point dan error dari tahap pengumpulan data, dilakukan pra proses data untuk menyiapkan data sebelum memasuki tahap pelatihan model. Salah satu langkah kunci dalam pra proses data adalah pemilihan fitur atau ciri yang akan digunakan. Dalam penelitian ini, fitur yang terpilih adalah set point dan error. Set point merepresentasikan nilai target suhu dalam pengendalian suhu, sementara error adalah perbedaan antara set point dan suhu aktual yang terukur. Selain itu, output yang akan diprediksi dalam penelitian ini adalah Q, yang merupakan hasil penjumlahan dari tiga komponen, yaitu P (Proporsional), I (Integral), dan D (Derivative). Komponen-komponen ini merujuk pada algoritma kontrol PID (Proporsional-Integral-Derivative) yang digunakan untuk mengendalikan suhu.

Selain pemilihan fitur dan pembentukan output, tahap pra proses data juga mencakup normalisasi data. Normalisasi dilakukan untuk mengubah rentang nilai setiap fitur agar sejajar dan dapat diolah dengan baik oleh model pembelajaran mesin. Dalam penelitian ini, digunakan normalisasi Min-Max Scaling, suatu metode yang mengubah skala nilai data dari rentang nilai aktual menjadi rentang nilai antara 0 hingga 1 atau -1 hingga 1 (Naufal et al., 2023). Formula Min-Max Scaling digunakan untuk mencapai normalisasi, dengan X scaled sebagai hasil scaling data ke-i, 𝑥 sebagai nilai asli data ke-i, xmin sebagai nilai minimum dari X, dan xmax sebagai nilai maksimum dari X.

![Pra Proses Data](https://github.com/DimasPrayoga249/kit-itclab/blob/cea01f5e8e468851f3ae05e755960eb04827c8bb/assets/pra_proses_data.png)

### Pelatihan Mode
Pelatihan model dalam arsitektur SVM (Support Vector Machine) merujuk pada proses di mana algoritma SVM belajar dari data latihan untuk membuat model yang dapat digunakan untuk melakukan prediksi atau klasifikasi pada data baru. Dalam SVM, model yang dihasilkan bertujuan untuk memisahkan data ke dalam kelas-kelas yang berbeda dengan menemukan hyperplane (bidang pemisah) optimal. Proses pelatihan ini melibatkan dua tahap utama: pembentukan model dan penentuan parameter.

![SVM](https://github.com/DimasPrayoga249/kit-itclab/blob/cea01f5e8e468851f3ae05e755960eb04827c8bb/assets/svm.png)

Proses pelatihan model SVM ini bertujuan untuk mencapai generalisasi yang baik, di mana model dapat mengklasifikasikan data baru dengan akurasi tinggi. Penting untuk memahami karakteristik data, memilih parameter dengan bijak, dan melakukan validasi untuk memastikan kinerja model yang baik pada data yang tidak terlihat selama pelatihan.

### Evaluasi
Proses evaluasi dilakukan untuk membandingkan kinerja implementasi jaringan SVM sebagai pengganti pengendali PID dalam sistem kontrol. Evaluasi ini akan menilai tiga indikator utama, yakni rising time, settling time, dan overshoot. Rising time mengindikasikan durasi yang dibutuhkan oleh sistem untuk mencapai 90% dari nilai setpoint setelah terjadinya perubahan input. Semakin cepat sistem mencapai nilai setpoint, semakin optimal kinerja sistemnya. Settling time merujuk pada waktu yang diperlukan oleh sistem untuk mencapai nilai yang mendekati setpoint secara stabil, biasanya dalam rentang toleransi tertentu. Semakin singkat settling time, semakin baik kinerja sistemnya. Overshoot mencerminkan kelebihan dari nilai output yang melebihi setpoint sebelum akhirnya mencapai nilai stabil. Overshoot yang tinggi menunjukkan ketidakstabilan atau respons sistem yang tidak diinginkan. Oleh karena itu, semakin rendah nilai overshoot, semakin optimal kinerja sistemnya. Dalam evaluasi ini, kinerja jaringan LSTM akan dibandingkan dengan pengendali PID tradisional dan pengendali PID yang menggunakan deep learning berdasarkan kriteria-kriteria tersebut.

## Hasil Penelitian
Dalam penelitian ini, dilakukan evaluasi kinerja antara pengendali PID tradisional, pengendali PID berbasis deep learning, dan pengendali berbasis LSTM. Tiga metrik evaluasi utama yang digunakan adalah rising time, settling time, dan overshoot.

![PID_Result](https://github.com/DimasPrayoga249/kit-itclab/blob/cea01f5e8e468851f3ae05e755960eb04827c8bb/assets/PID_Result.png)

PID RESULT

![SVM_Result](https://github.com/DimasPrayoga249/kit-itclab/blob/cea01f5e8e468851f3ae05e755960eb04827c8bb/assets/SVM_Result.png)

SVM RESULT

Grafik kinerja PID berbasis deep learning memperlihatkan perbandingan antara sistem PID tradisional dan PID SVM dalam beberapa aspek kritis. Pertama, dari segi rising time, sistem PID tradisional menunjukkan kinerja lebih cepat, dengan perbedaan waktu 15 detik lebih singkat dibandingkan dengan PID SVM. Artinya, PID tradisional lebih efisien dalam mencapai 90% dari nilai setpoint setelah terjadinya perubahan input.

Namun, perbandingan pada settling time menunjukkan hasil sebaliknya. Sistem PID tradisional memerlukan waktu lebih lama 1 detik daripada PID SVM untuk mencapai nilai yang mendekati setpoint secara stabil. Ini menunjukkan bahwa, meskipun PID tradisional lebih cepat mencapai 90% setpoint, PID SVM lebih unggul dalam mencapai penyelesaian yang stabil dan mendekati setpoint dengan lebih efisien.

Selanjutnya, analisis pada overshoot menunjukkan bahwa PID tradisional memiliki nilai overshoot yang lebih kecil, yaitu sebesar 0.81%, dibandingkan dengan PID SVM. Hal ini menandakan bahwa sistem kontrol PID tradisional lebih mampu menghasilkan respons yang lebih stabil dan minim overshoot jika dibandingkan dengan implementasi PID SVM.

Dengan demikian, hasil grafik kinerja memberikan gambaran yang komprehensif tentang keunggulan dan kelemahan masing-masing metode pengendalian, memungkinkan pemahaman yang lebih baik tentang performa keduanya dalam konteks spesifik sistem dan tujuan kontrol yang diinginkan.

## Kesimpulan
Berdasarkan hasil evaluasi kinerja sistem kendali, dapat disimpulkan bahwa sistem kendali berbasis SVM memiliki potensi sebagai alternatif yang menarik untuk menggantikan sistem kendali PID tradisional. PID SVM menunjukkan kinerja yang lebih baik dalam hal settling time dan overshoot, menandakan bahwa sistem ini mampu mencapai nilai yang mendekati setpoint secara stabil dengan waktu yang lebih efisien serta menghasilkan respons yang lebih terkontrol dengan overshoot yang lebih kecil dibandingkan dengan PID tradisional. Meskipun demikian, perlu diperhatikan bahwa PID SVM memiliki sedikit kelemahan dalam hal rising time, yang menunjukkan waktu yang dibutuhkan oleh sistem untuk mencapai 90% dari nilai setpoint setelah terjadinya perubahan input. Meskipun demikian, kelebihan pada settling time dan overshoot dapat dianggap sebagai faktor positif yang menunjukkan bahwa pengendalian SVM memiliki performa yang sangat baik dalam mencapai stabilisasi dan respons yang diinginkan dalam suatu sistem. Oleh karena itu, implementasi sistem kendali berbasis SVM dapat menjadi pilihan yang lebih optimal tergantung pada kebutuhan spesifik dan prioritas performa kontrol yang diinginkan dalam suatu aplikasi.









