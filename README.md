# Sinir Ağları – Cats vs Dogs Classification

Bu proje, **Sinir Ağları** dersi kapsamında hazırlanmış bir final projesidir.
Projede, Evrişimli Sinir Ağları (Convolutional Neural Networks – CNN) kullanılarak
kedi ve köpek görüntülerinin sınıflandırılması amaçlanmıştır.

## Öğrenci Bilgileri
- **Öğrenci Adı:** Alaa Alattar  
- **Öğrenci Numarası:** 22430070902  
- **Ders Adı:** Sinir Ağları  
- **Öğretim Üyesi:** Hüseyin Yanık  

## Kullanılan Teknolojiler
- Python
- TensorFlow / Keras
- Google Colab
- Convolutional Neural Network (CNN)

Kedi ve Köpek Görüntü Sınıflandırma (Cats vs Dogs)
📌 Proje Açıklaması

Bu projede, Cats vs Dogs görüntü veri seti kullanılarak bir Evrişimsel Sinir Ağı (CNN) modeli geliştirilmiştir.
Amaç, verilen bir görüntünün kedi mi yoksa köpek mi olduğunu otomatik olarak sınıflandırmaktır.

Model eğitimi TensorFlow ve Keras kütüphaneleri kullanılarak gerçekleştirilmiş, eğitim süreci ve başarı metrikleri detaylı olarak analiz edilmiştir.

📂 Veri Seti Açıklaması

Veri seti: Kaggle – Cats vs Dogs Dataset

Toplam görüntü sayısı: 24,992

Sınıflar:

Cat

Dog

Eğitim / Doğrulama oranı:

%80 Eğitim

%20 Doğrulama

Görüntü boyutu: 150 × 150 RGB

Eğitim öncesinde bozuk (truncated) görüntüler tespit edilerek veri setinden temizlenmiştir.

🏗️ Model Mimarisi

Bu projede kullanılan model Convolutional Neural Network (CNN) mimarisine sahiptir.

Katmanlar:

Input Layer (150×150×3)

Rescaling (1/255)

Conv2D (32 filtre, ReLU)

MaxPooling2D

Conv2D (64 filtre, ReLU)

MaxPooling2D

Conv2D (128 filtre, ReLU)

MaxPooling2D

Flatten

Dense (128, ReLU)

Dense (1, Sigmoid)

Derleme Ayarları:

Optimizer: Adam

Loss Function: Binary Crossentropy

Metric: Accuracy

📊 Eğitim Sonuçları ve Başarı Metrikleri

Model 5 epoch boyunca eğitilmiştir.

Eğitim Doğruluğu (Accuracy): %91

Doğrulama Doğruluğu (Validation Accuracy): %81

Model, eğitim verisi üzerinde yüksek başarı elde etmiş, doğrulama verisinde ise kabul edilebilir bir genelleme performansı göstermiştir.

✅ Sonuç

Bu projede, CNN tabanlı bir derin öğrenme modeli kullanılarak kedi ve köpek görüntülerinin başarılı bir şekilde sınıflandırılması sağlanmıştır.
Elde edilen sonuçlar, sinir ağlarının görüntü işleme problemlerinde etkinliğini açıkça göstermektedir.
⚠️ Not: Eğitilmiş model dosyası (`.keras`) dosya boyutu nedeniyle GitHub’a yüklenememiştir.
Model, aşağıdaki Google Drive bağlantısı üzerinden erişilebilir durumdadır.

📎 Model Linki (Google Drive):
[https://drive.google.com/......](https://drive.google.com/file/d/12CYod0p9BteU529Pcc4noT1hboF-nU_B/view?usp=sharing)

