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

## Veri Seti
Projede Kaggle platformunda yer alan **Cats vs Dogs** veri seti kullanılmıştır.
Veri seti, kedi ve köpek görüntülerinden oluşmaktadır.

Veri seti klasör yapısı:

cats_vs_dogs  
└── PetImages  
&nbsp;&nbsp;&nbsp;&nbsp;├── Cat  
&nbsp;&nbsp;&nbsp;&nbsp;└── Dog  

Veri seti Google Drive üzerinden Google Colab ortamına bağlanarak kullanılmıştır.

## Model Mimarisi
Model, aşağıdaki katmanlardan oluşmaktadır:
- Rescaling
- 3 adet Conv2D + MaxPooling katmanı
- Flatten katmanı
- Dense (128 nöron)
- Dense (1 nöron, Sigmoid aktivasyonu)

Kayıp fonksiyonu olarak **Binary Crossentropy**,
optimizer olarak **Adam** kullanılmıştır.

## Eğitim Süreci
Model Google Colab ortamında eğitilmiştir.
Eğitim sırasında doğruluk (accuracy) ve kayıp (loss) değerleri izlenmiştir.
Eğitim ve doğrulama sonuçları grafiklerle görselleştirilmiştir.

## Sonuç
Elde edilen sonuçlar, modelin kedi ve köpek görüntülerini ayırt edebildiğini
göstermektedir. Eğitim ve doğrulama metrikleri, modelin temel sınıflandırma
görevini yerine getirdiğini ortaya koymaktadır.

## Not
Eğitilmiş model dosyası (`.h5`), GitHub dosya boyutu sınırını aştığı için
repository içerisine eklenmemiştir. Model eğitimi Google Colab üzerinde
gerçekleştirilmiştir.
