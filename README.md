# Kecerdasan-Buatan

Nim 	  : 131112071

Nama 	  : Idral Zuanda.AR

Kelas 	: TP-A Pagi

Tugas 	: Kecerdasan Buatan


Apakah anda setuju dengan pendapat Turing?
Jawab : Saya setuju.

Apakah menurut anda akan ada computer yang melewati tes Turing?
Jawab : Kemungkinan ada, karena setiap hari ada perubahan teknologi yang canggih untuk memaksimalkan pekerjaan manusia.

Halangan apa saja yang menurut anda menghambat perkembangan komputer untuk melewati tes Turing?
Alan Turing, ahli matematika berkebangsaan Inggris yang dijuluki bapak komputer modern dan pembongkar sandi Nazi dalam era Perang Dunia II tahun 1950, kecerdasan buatan adalah jika komputer tidak dapat dibedakan dengan manusia saat berbincang melalui terminal komputer, maka bisa dikatakan komputer itu cerdas, mempunyai intelegensi. Tidak semua orang dapat membangun sebuah mesin berpikir yang dilakukan oleh Turing.

Istilah – istilah pada bidang AI
Natural Language Processing
Natural Language Processing biasa disebut dengan Pemrosesan Bahasa Alami adalah Bidang Artificial Intelligence yang berurusan dengan pemahaman bahasa (alami) manusia (bahasa inggris, jerman, Indonesia dan lain-lain). Bahasa alami atau yang disebut dengan natural language adalah suatu bahasa yang diucapkan, ditulis, disyaratkan oleh manusia untuk berkomunikasi umum. Jadi bahasa alami/ natural language yaitu bahasa yang dimengerti oleh manusia. Bahasa alami pada prinsipnya adalah suatu bentuk representasi dari suatu pesan yang akan dikomunikasikan antar manusia. Representasinya dapat berupa ucapan/ suara  (spoken language), namun juga bisa dinyatakan berupa tulisan.

Dalam Pengolahan bahasa alami terdiri dari bagian-bagian utama, yaitu : parser, sistem representasi pengetahuan dan pengolahan output.

- Parser.
Adalah suatu sistem untuk mengambil kalimat input, dan menguraikannya kata per kata serta untuk menentukan jenis kata apa saja yang dapat mengikuti kata tersebut. (menguraikan ke dalam beberapa bagian gramatikal seperti kata kerja, kata benda, kata sifat, kata kerja).

- Sistem Representasi Pengetahuan.
Adalah Suatu sistem yang menganalisis output parser untuk menentukan maknanya.

- Output Translator.
Adalah Suatu terjemahan yang merepresentasikan sistem pengetahuan serta melakukan langkah- langkah yang berupa jawaban atas bahasa alami. Output translator merupakan Output khusus yang sesuai dengan program komputer lainnya.

Knowledge Representation ( Representasi Pengetahuan )
Suatu proses untuk menangkap sifat-sifat penting problema dan membuat informasi tersebut dapat diakses oleh prosedur pemecahan permasalahan. Bahasa Representasi harus dapat membuat seorang pemrogram mampu mengekspresikan pengetahuan yang diperlukan untuk mendapatkan solusi permasalahan.
Entiti Representasi Pengetahuan
Fakta adalah kejadian sebenarnya. Fakta inilah yang akan kita representasikan.
Representasi dari fakta :
Bagaimana cara untuk memodelkan fakta. Dari representasi ini, kita akan dapat memanipulasinya.

Representasi yang baik
•	Mengemukakan hal secara eksplisit
•	Membuat masalah jadi tranparan
•	Komplit dan efisien
•	Menampilkan batasan – batasan alami yang ada
•	Menekan / menghilangkan detil – detil yang diperlukan
•	Dapat dilakukan komputasi ( ada batasan / constraint )

Kategori Representasi
•	Representasi Logika : Representasi jenis ini menggunakan ekpresi – ekpresi dalam logika formal untuk merepresentasikan basis pengetahuan.
•	Representasi Prosedural : Representasi menggambarkan pengetahuan sebagai kumpulan instruksi untuk memecahkan suatu problema.
•	Representasi Network : Representasi ini menangkap pengetahuan sebagai sebuah graph dimana simpul-simpulnya menggambarkan objek atau konsep dari problema yang dihadapi, sedangkan edge-nya menggambarkan hubungan atau asosiasi antar mereka.
•	Representasi Terstruktur : Representasi terstruktur memperluas network dengan cara membuat setiap simpulnya menjadi sebuah struktur data kompleks.
•	Dan lain – lain ( Kromosom, jaringan syaraf, gen, dll ).

Reasoning (penalaran)
Reasoning (penalaran), yakni teknik penyelesaian masalah dengan cara merepresentasikan masalah ke dalam basis pengetahuan (knowledge base) menggunakan logic atau bahasa formal (bahasa yang dipahami komputer). Saya akan memfokuskan pembahasan pada tiga buah logic untuk merepresentasikan pengetahuan dan melakukan penalaran, yaitu : propositional logic (logika proposisi), first order logic atau predicat calculus (kalkulus predikat), dan fuzzy logic (logika samar). Dua logic pertama digunakan untuk masalah yang memiliki kepastian. Sedangkan fuzzy logic digunakan untuk menyelesaikan masalah yang memiliki ketidakpastian (uncertainty).

Pada Reasoning ini berbeda dengan Searching yang mempresentasikan masalah ke dalam state dan ruang masalah serta menggunakan strategi pencarian untuk menemukan solusi, sedangkan Reasoning merepresentasikan masalah ke dalam basis pengetahuan dan melakukan proses penalaran untuk menemukan solusi. Pada teknik searching, dua masalah utama yang dihadapi adalah kesulitan dalam menentukan apakah aturan produksi (operator) sudah lengkap atau belum. 
Jika masalah yang dihadapi cukup kompleks, maka akan terjadi ketidak-efisienan representasi keadaan (state).

Misalkan, untuk masalah 8-puzzle,  representatisi suatu state adalah delapan posisi angka, satu parent, dan maksismum 4 suksesor. Bagaimana jika masalahyang dihadapi adalah permainan catur. Satu state harus direpresentasikan sebagai 32 posisi buah catur dan satu state bisa memiliki sangat banyak suksesor (faktor percabangannya sangat besar). Solusi yang mungkin untuk memecahkan permasalahan diatas adalah menggunakan representasi yang jauh lebih sederhana yaitu menggunakan logic.


Machine Learning
Machine Learning adalah bagian dari Artificial Intelligence. Intinya tentang bagaimana sebuah mesin “belajar” dan mengenali bahasa manusia. Proses di dalamnya melibatkan rumus-rumus yang rumit dan juga proses trial and error dari banyak pihak. Ilmu ini berkembang pesat, dan nampaknya di Indonesia juga semakin banyak yang tertarik dengan dunia ini.
Contoh Machine Learning :
Berikut ini gambaran machine learning diterangkan oleh masternya, Jim Geovedi, dengan bahasa yang gamblang. Oh iya, Jim menerangkan ini kepada neng yuke dan lola yang notabene adalah Event Organizer, maka perumpamaan yang diambil seputar band. Semoga hal ini bisa jadi acuan tentang bagaimana menerangkan machine learning, atau umumnya AI, kepada masyarakat lebih luas. Teks di bawah ini saya kutip sesuai aslinya.
neng yuke dan lola kan biasa ngurus acara yang melibatkan banyak band. dan suatu ketika manage suatu acara yang melibatkan beberapa band dengan berbagai genre. masalah muncul ketika harus bikin rundown atau membedakan stage setiap group band, supaya tidak class genre dan punya rundown yang enak.
nah, cara yang paling mudah mungkin langsung bertanya dengan personil atau manajemen band tersebut, atau ke orang lain yang sudah lebih dulu mengenal band tersebut. tapi mungkin kalian iseng… coba untuk mengidentifikasi berdasarkan sejumlah informasi yang sifatnya terbatas. misalnya, nama band, kota asal, logo band, kemudian jumlah personil dan instrumen yang digunakan.
contoh yang paling mudah, ini adalah contoh nama-nama band: ‘besok bubar’, ‘suffocation’, ‘om soneta’, ‘runtah’, ‘ragaji mesin’, ‘death vomit’, ‘seringai’, ‘dewa’, ‘kahitna’, ‘java jive’, ‘ dan ‘padi’


berbekal pengalaman terdahulu, ada stereotype dari penamaan band seperti:
– kalau band metal biasanya punya nama-nama gahar, gak jauh-jauh dari unsur terror, horror, death, dsb.
– kalau band dangdut biasanya dimulai dengan awalan ‘om’ (orkes melayu)
– band punk atau hardcore punya nama yang cenderung umum namun gak lazim digunakan.
– band pop atau rock, cenderung netral
dari beberapa nama tersebut, sudah mulai bisa diklasifikasikan:
– band metal: [‘suffocation’, ‘death vomit’]
– band dangdut: [‘om soneta’]
– band punk/hardcore: [‘besok bubar’, ‘seringai’, ‘ragaji mesin’]
– band pop/rock: [‘dewa’, ‘padi’, ‘kahitna’, ‘java jive’]
kemudian dari koleksi band pop/rock [‘dewa’, ‘padi’, ‘kahitna’, ‘java jive’] ingin diketahui mana band rock dan mana band pop. informasi yang sudah diketahui adalah jumlah personil band rock biasanya berjumlah 5 orang atau kurang dengan 2 pemain gitar (lead & rhythm), dan ada beberapa yang extra keyboard player. sementara band pop ada kecenderungan punya beberapa vokalis dan biasanya punya keyboard player.
dari informasi tersebut akhirnya diklasifikasikan:
– band rock: [‘dewa’, ‘padi’]
– band pop: [‘kahitna’, ‘java jive’]
nah, dalam teknologi machine learning, informasi nama band, kota asal, logo band, kemudian jumlah personil dan instrumen yang digunakan itu dikenal sebagai ‘features’. kemudian, informasi stereotype yang diketahui dikenal sebagai ‘frequency distribution’.
dengan membandingkan features dan frekuensi, bisa data bisa diproses. tingkat akurasinya tergantung berapa besar features yang dimiliki dan seberapa sering features yang berhubungan dengan data tersebut muncul untuk kasus-kasus lain. dan tentunya tidak 100% akurat karena akan ditemukan penyimpangan di sana-sini. misalnya band ‘kuburan’ yang mungkin akan diklasifikasikan sebagai band ‘metal’, namun ternyata genrenya ‘rock’ (walaupun pada kenyataannya benar dulu mereka main metal, namun namanya masih dipertahankan).

Pengertian dan Penerapan Computer Vision
Computer Vision adalah kombinasi antara Pengolahan Citra dan Pengenalan Pola. Pengolahan Citra (Image Processing) merupakan bidang yang berhubungan dengan proses transformasi citra/gambar (image). Proses ini bertujuan untuk mendapatkan kualitas citra yang lebih baik.

Beberapa applikasi yang dihasilkan dari Computer Vision antara lain :

1. Robotic – navigation and control
2. Medical Image Analysis – measurement and interpretation of many types of images
3. Industrial Inspection – measurement, fault checking, process control 
4. Optical Character Recognition – text reading 
5. Remote Sensing – land use and environmental monitoring
6. Psychology, AI – exploring representation and computation in natural vision

Contoh penerapan Computer Vision diantaranya :

Bidang Industri.

Kadang-kadang disebut visi mesin, dimana informasi ini diekstraksi untuk tujuan mendukung proses manufaktur. Salah satu contohnya adalah kendali mutu dimana rincian atau produk akhir yang secara otomatis diperiksa untuk menemukan cacat. Contoh lain adalah pengukuran posisi dan orientasi rincian yang akan dijemput oleh lengan robot. Mesin visi juga banyak digunakan dalam proses pertanian untuk menghilangkan bahan makanan yang tidak diinginkan dari bahan massal, proses yang disebut sortir optik.

Bidang Kecerdasan Buatan.

Keterkaitan dengan perencanaan otonom atau musyawarah untuk sistem roboticaluntuk menavigasi melalui lingkungan. Pemahaman yang rinci tentang lingkungan inidiperlukan untuk menavigasi melalui mereka. Information about the environment could beprovided by a computer vision system, acting as a vision sensor and providing high-levelinformation about the environment and the robot. Informasi tentang lingkungan dapatdiberikan oleh sistem visi komputer, bertindak sebagai sensor visi dan memberikan informasitingkat tinggi tentang lingkungan dan robot. Buatan kecerdasan dan visi lain berbagi topik komputer seperti pengenalan pola dan teknik pembelajaran. Akibatnya, visi komputerkadang-kadang dilihat sebagai bagian dari bidang kecerdasan buatan atau ilmu bidangkomputer secara umum.

Bidang Fisika.

Fisika merupakan bidang lain yang terkait erat dengan Computer vision. sistem Computervision bergantung pada sensor gambar yang mendeteksi radiasi elektromagnetik yangbiasanya dalam bentuk baik cahaya tampak atau infra-merah sensor dirancang denganmengunakan fisika solid-state. Proses di mana cahaya merambat dan mencerminkan off permukaan dijelaskan menggunakan optik. sensor gambar canggih bahkan memintamekanika kuantum untuk memberikan pemahaman lengkap dari proses pembentukangambar. Selain itu, berbagai masalah pegukuran fisika dapat di atasi dengan menggunakanComputer Vision, untuk gerakan misalnya dalam cairan.




Definisi Robot
Istilah ini pertama kali diperkenalkan ke dalam bahasa Inggris oleh penulis dan dramawan asal Chechnya, Karel Capek, yang memiliki arti pekerja dalam aksi panggungya yang berjul R.U.R (Rossum's Universal Robots) pada tahun 1921.

Pengertian Robotika
Istilah robotik atau robotika dapat dimaknai sebagai ilmu yang mematerikan kecerdasan/intelegensia terhadap energi, artinya pengendalian secara cerdas  terhadap gerakan yang terkoordinasi secara nyata. Istilah ini diperkenalkan oleh Isaac Asimov untuk pertama kalinya dalam cerita pendeknya yang berjudul Runaround yang terbit tahun 1942.

Sejarah Robotik, Robot dan Robotika
Isaac Asimov dalam cerita pendeknya yang berjudul I, Robot mencetuskan suatu filosofi agar pembuatan robot sejak awal dan sampai masa yang akan datang diharapkan dapat memenuhi tiga aturan yang dikenal sebagai Asimov's Asimov's Tree Laws of Robotic :

1.	Robot tidak boleh menyakiti manusia
2.	Robot harus mematuhi manusia selama tidak bertentangan dengan hukum 1
3.	Robot harus dapat melindungi dirinya selama tidak bertentangan dengan hukum 1 dan 2



