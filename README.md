   Derin Öğrenme ile Deri Hastalıkları Sınıflandırma ve Karar Destek Sistemi
Bu proje, dermatolojik teşhis süreçlerine yardımcı olmak amacıyla geliştirilmiş, 5 farklı cilt hastalığını yüksek doğrulukla ayırt edebilen bir yapay zeka sistemidir.

   Proje Özeti ve Başarı Oranları
Çalışma kapsamında 8 farklı hazır mimari ve 2 özgün mimari (Custom CNN ve Hibrit) test edilmiştir. * ResNet50V2 (En İyi): %94.9 Doğruluk * InceptionResNetV2: %94.9 Doğruluk * Custom CNN (Kendi Tasarımım): %94.1 Doğruluk * Hibrit Model (CNN+LSTM): %91.4 Doğruluk 

   Veri Seti Bilgileri
* Toplam Görüntü: 9.548 adet * Sınıflar: Nail Psoriasis, SJS-TEN, Vitiligo, Akne ve Hiperpigmentasyon . * Eğitim Stratejisi: %80 Eğitim, %20 Doğrulama (Validation) olarak ayrılmış; veri artırma (Data Augmentation) teknikleri uygulanmıştır.

   Teknik Detaylar
Dil: Python (Jupyter Notebook) * Kütüphaneler: TensorFlow, Keras, MobileNetV2, DenseNet121, InceptionV3 . * Optimizasyon: Batch Normalization, Dropout (%20-40) ve L2 Regularization kullanılarak ezberleme (overfitting) önlenmiştir.# YAPAY-ZEKA-DERI-HASTALIKLARI-MODEL-GELISTIRIP-DOGRULUK-SINIFLANDIRMA
"Derin öğrenme ve bilgisayarlı görü teknikleri kullanılarak deri hastalıklarını görüntü üzerinden teşhis eden yapay zeka modeli."
