# Intel-Image-Classification
Bu proje, Akbank Derin Öğrenme Bootcamp kapsamında, Convolutional Neural Network (CNN) mimarisi kullanarak Intel Image Classification veri setini sınıflandırmayı amaçlamaktadır. Proje, görüntü sınıflandırması, veri analizi, model geliştirme ve değerlendirme gibi konularda pratik deneyim kazanmak için tasarlanmıştır. 

Bu projede, 6 farklı doğal ve yapay ortamı (Binalar, Orman, Buzul, Dağ, Deniz, Sokak) içeren **Intel Image Classification** veri seti kullanılacaktır. 

Veri seti, yaklaşık 25.000 eğitim ve 14.000 test görüntüsünden oluşmaktadır.


Veri Ön İşleme: Görüntüler uygun formata dönüştürülmüş, etiketlenmiş ve eğitim, doğrulama (validation) ve test setlerine ayrılmıştır.


Veri Çoğaltma (Data Augmentation): Model başarımını artırmak için döndürme (Rotation), çevirme (Flip) ve yakınlaştırma (Zoom) gibi veri çoğaltma teknikleri kullanılmıştır.



Model Geliştirme: Evrişimsel katmanlar (Convolutional Layers), Havuzlama katmanları (Pooling Layers), Dropout ve Tam Bağlantılı (Dense) katmanları içeren bir CNN modeli geliştirilmiştir.


Model Değerlendirme: Modelin performansı, doğruluk (Accuracy) ve kayıp (Loss) grafikleri, Karmaşıklık Matrisi (Confusion Matrix) ve Sınıflandırma Raporu ile değerlendirilmiştir.


Hiperparametre Optimizasyonu: Katman sayısı, filtre sayısı ve öğrenme oranı gibi parametreler üzerinde denemeler yapılarak modelin performansı optimize edilmiştir.

Modelin eğitim ve doğrulama seti üzerindeki performansı, çizilen grafiklerle analiz edilmiştir.

Test verisi üzerinde, modelin sınıflandırma doğruluğu ve yanlış tahminleri Karmaşıklık Matrisi ile gösterilmiştir.



Kaggle Not Defteri:
Bu projenin tüm kodları ve ayrıntılı teknik anlatımları aşağıdaki Kaggle not defterinde yer almaktadır:https://www.kaggle.com/code/ysrapaal/ntel-mage-classfication
