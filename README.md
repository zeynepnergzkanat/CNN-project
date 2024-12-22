# CNN project
 **Animal Classification Project**

Proje Açıklaması

Bu proje, hayvanların görüntü sınıflandırmasını gerçekleştirmek için bir Derin Öğrenme modeli oluşturmayı hedeflemektedir. Model, farklı manipülasyon teknikleri uygulanmış test verileri üzerinde de değerlendirilmiştir.

Kullanılan Veri Seti

Veri Seti Adı: Animals with Attributes 2Kaynak: Animals with Attributes 2Veri Seti İçeriği:

8 farklı hayvan sınıfına ait görüntüler.

Her sınıftan 650 örnek kullanılmıştır.

Görseller 224x224 boyutunda normalize edilmiştir.

Proje Adımları

Veri Setinin Hazırlanması

Veriler belirtilen dizinden okunarak yüklenmiştir.

Görüntüler yeniden boyutlandırılmış ve normalizasyon işlemi uygulanmıştır.

Veri Ön İşleme

Eğitim ve test setleri %70 - %30 oranında ayrılmıştır.

Veri artırma (Augmentation) teknikleri uygulanarak modelin çeşitliliği artırılmıştır.

Model Oluşturma

Convolutional Neural Network (CNN) tabanlı bir model geliştirilmiştir.

Model, Batch Normalization, Dropout ve MaxPooling katmanları içermektedir.

Adam optimizasyon algoritması ve Sparse Categorical Crossentropy kayıp fonksiyonu kullanılmıştır.

Model Eğitimi ve Performans Analizi

Erken durdurma ve model kontrolü (checkpoint) gibi geri çağrımlar eklenmiştir.

Modelin doğrulama ve eğitim kayıpları grafiksel olarak analiz edilmiştir.

Manipüle Edilmiş Test Setleri Üzerinde Değerlendirme

Parlaklık artırma ve renk sabitleme teknikleri ile manipüle edilmiş test setleri oluşturulmuştur.

Model bu manipüle edilmiş veriler üzerinde de test edilerek dayanıklılığı analiz edilmiştir.

Başarı Oranı Karşılaştırması

Orijinal ve manipüle edilmiş veri setleri için başarı oranları grafiklerle görselleştirilmiştir.

Kullanılan Kütüphaneler

TensorFlow/Keras

OpenCV

NumPy

Matplotlib

Scikit-learn

Kod Yapısı

data_preprocessing.ipynb: Veri işleme ve görselleştirme kodları.

model_training.ipynb: Model oluşturma, eğitim ve değerlendirme kodları.

evaluation.ipynb: Manipülasyon testleri ve sonuç karşılaştırmaları.

Kaggle Linki: Kaggle Proje Linki
