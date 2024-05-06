This project was prepared for the "Akbank Machine Learning Bootcamp: New Generation Project Camp" assignment... (Global IA Hub)

* Business Problem: Predict the onset of diabetes based on diagnostic measures

* I developed three machine learning models that predict whether people have diabetes and tried to determine the most successful model among them.

* Dataset: Pima Indians Diabetes Database
  https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
  Collaborators : UCI Machine Learning (Owner) and Kaggle Team (Admin)

-----------------------------------------------------------------------------------------------------------------------
Projede istenen gereklilikler (Global AI Hub):

* Bu projede ilk olarak katılımcılar makine öğreniminde iki temel yol arasında seçim
yapacaklardır: sınıflandırma veya regresyon.

* Öğrenciler tahmin amaçlı olarak verileri kategoriler halinde sınıflandırmayı veya
girdi özelliklerine dayalı olarak sürekli değerleri tahmin etmeyi öğreneceklerdir.

* Bu proje, öğrencilere yapay zeka ve makine öğrenmesi alanında sınıflandırma ve
regresyon alanlarında veri analizi, model geliştirme ve değerlendirme teknikleri konusunda
pratik deneyim kazandırmayı amaçlamaktadır.

1- Proje Konusu
İki seçeneğiniz var: Sınıflandırma veya Regresyon.

2 - Veri Setinizi Seçin
Bu aşamada, projenizde kullanacağınız veri setine karar vereceksiniz. Kendi veri setiniz
varsa kullanabilir, verdiğimiz örneklerden birini seçebilir, veya bu dosyanın en altındaki
kaynakları inceleyerek orada yer alan bir veri seti seçebilirsiniz.

3 - Bir Google Colab Dosyası Oluşturun
* Projeniz, .ipynb uzantılı bir dosyada gerçekleştirilmiş olmalı.
* Bu dosyada, kod satırlarının yanı sıra projenizin teknik detaylarını açıkladığınız
yorum hücreleriniz olmalı.

4 - Bir GitHub Reposu & README.md Dosyası oluşturun
* Bir Github reposu oluşturmalısınız.
* Bu repoda .ipynb uzantılı proje dosyanız, veri seti dosyanız ve README.md
dosyanız olmalı.
* Detaylı teknik anlatımlarınız .ipynb dosyasında yer almalıdır. README.md
dosyasında özet bilgilerle projenizden bahsedebilirsiniz.

5 - Keşifsel Veri Analizi (EDA - Exploratory Data Analysis)
Pandas, matplotlib, seaborn vb. ilgili kütüphaneleri kullanarak seçtiğiniz veri setini
açıklayınız. Görselleştirme kütüphaneleri ile görseller, grafikler oluşturup, ilgili pandas
yöntemleriyle veri setine ait genel bilgileri aktarın. Analizlerinizi açıklamak için .ipynb
içerisinde yorum hücrelerini kullanmalısınız.

6 - Veri Ön İşleme
Veri kümenize bağlı olarak gerekli ön işleme adımlarını yapmalısınız. Veri setini
temizlemek, normalleştirme, label-encoding veya one-hot encoding (kategorik
değişkenleriniz varsa), veri kümenizi eğitim ve test kümelerine bölmek vb.

7 - Model Seçimi
* Birkaç sınıflandırma/regresyon modeli seçin ve bunları ön işlemeden geçirdiğiniz
verilerinizle eğitin.
* Çapraz doğrulamayı(cross validation) kullanarak seçilen modellerin performanslarını
inceleyin.
* En iyi performansı gösteren model ile ilerleyin.
Proje dosyasında, yalnızca ilerlemeye karar verdiğiniz modele yer verebilirsiniz.

8 - Hiperparametre Optimizasyonu
* Önceki adımda seçilen modelin hiper parametrelerini uygun bir yöntemle optimize
edin (Grid Search, Randomized Search veya uygun gördüğünüz herhangi biri).

9 - Model Değerlendirme
Uygun model değerlendirme yöntemlerini kullanarak optimize edilmiş modeli
değerlendirin.
- Örneğin Regresyon için kayıp hesaplaması: Ortalama Karesel Hata(Mean Squared Error),
Ortalama Mutlak Hata(Mean Absolute Error) vb. ile,
- Sınıflandırma için karışıklık matrisi(Confusion matrix) oluşturarak:
- Doğruluk(accuracy), kesinlik(precision), duyarlılık(recall), F1 puanı(F1 score)
özelliklerine yer vererek.
