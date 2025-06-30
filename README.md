# Klasifikasi Genre Buku berdasarkan Sinopsis Menggunakan SVM (Support Vector Machine)

Proyek ini bertujuan untuk mengklasifikasikan genre buku secara otomatis berdasarkan sinopsis menggunakan pendekatan Natural Language Processing (NLP) dan machine learning. Dengan memanfaatkan teks sinopsis sebagai data utama, proyek ini dikembangkan untuk mengeksplorasi bagaimana algoritma klasifikasi dapat mengenali pola bahasa dan menentukan kategori genre buku seperti fiksi, fantasi, misteri, atau lainnya. Proyek ini dibuat sebagai bentuk implementasi praktis dari penerapan NLP dalam bidang klasifikasi teks, serta untuk mendorong otomatisasi pengelompokan buku dalam skala besar secara efisien.


Dataset pada proyek ini diperoleh melalui proses web scraping menggunakan BeautifulSoup dari situs Goodreads. Data yang dikumpulkan mencakup judul buku, sinopsis, dan label genre yang tertera pada masing-masing buku. Proses scraping dilakukan untuk memperoleh data teks yang dibutuhkan dalam membangun model klasifikasi genre berdasarkan sinopsis.

Pendekatan dan langkah-langkah utama:
1. Pembersihan dan praproses teks sinopsis (lowercasing, remove punctuation, tokenisasi, stopwords, lematisasi).
2. Ekstraksi fitur teks menggunakan TF-IDF
3. Pemisahan data menjadi data latih dan data uji.
4. Pelatihan model klasifikasi (SVM)
5. Evaluasi performa model menggunakan metrik akurasi, precision, recall, dan F1-score.
6. Confussion Matrix
