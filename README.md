# Mercedes CC Class price prediction

Case Study: UK Used CClass Cars
Soal : Dataset yang digunakan merupakan listing mobil Mercedec CCclass bekas yang diperjualbelikan di Britania Raya. Terdapat sekitar 4.000 mobil CClass bekas di dalam listing tersebut. kalian dapat mempelajari dataset ini dengan lebih lanjut di halaman ini.

**Business objective** yang akan dicapai yaitu memprediksi harga mobil Mercedec CCclass bekas, dengan bbrpa spesifikasi sebgai berikut yaitu : mileage, transmissi, engines size, fuel

**Output** User dapat, memperkirakan variabel mana yang perlu diperhitungkan sebelum membeli mobil bekas

**Machine learning** yang digunakan dalam kasus ini yaitu kasus regresi, model machine learning yang digunakan yaitu : Linear Reggresion, Knn, dan ensemble Random Forrest

**Perfomnce meassure** yang digunakan dalam kasus ini yaitu : r2, mse (mean square error), dan rmse (root mean square error)

**Resiko** yang mungkin ditimbulkan dari project ini kesalahan memprediksi harga mobil, user perlu mempertimbangka juga tahun mobil dan mileage pada mobil Mercedes CCclass ini

Dalam model Machine Learning ada beberapa metode yang diterapkan:

* Sebagai user perlu sangat mempertimbangka umur mobil, dan milage sebelum membeli, karena dua feature tersebut mempunya nilai korelasi yang sangat besar

*   Data Cleaning, dikarenakan data yang sangat kotor, banyak sekali data yang kosong, dan tidak pada tempatnya : tipe data object akan tetapi mewakili numerikal, seperti pada price terdapat currecy label dll
*   Membagi feature yang berisi data kategorikal dan numerikal dan melakukan encoding pada data kategorikal, pada kasus ini digunakan dua cara encoding yaitu : Ordinal encoding pada = tahun, dan sisanya ohe hot encoding
* Scaling pada data yang bersifat numerical
*   Pada Model training menggunakan 3 yaitu Linear Reggresion, KNN, dan Random Forrest 
* Didapatkan model terbaik yaitu random forrest, selanjutnya dilakukan hyper parameter tunnig menggunaka grid search


**Conclusion**

Random Forrest dengan perlakuan tunning pada kasus ini merupakan model terbaik karena memilki r2.score = 0.93 ~ 93%, tidak begitu signifikan kenaikan nilai r2 nya setelah ditunning, hanya naik sekitar 0.01, atau sekitar 1%. Diharapkan model ini berguna untuk user yang ingin membeli mobil mercedes CCclass

