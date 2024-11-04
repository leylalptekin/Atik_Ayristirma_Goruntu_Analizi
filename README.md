# Atik_Ayristirma_Goruntu_Analizi

 ![atık ayrıltır](https://github.com/user-attachments/assets/6e195f64-2bf9-4fd2-bd1e-203f76e99c2d)

 ## Proje Hakkında

Bu proje, atık ayrıştırma sürecini geliştirmek amacıyla görsel analiz tekniklerini kullanarak, farklı atık türlerinin otomatik olarak tanımlanmasını sağlamayı hedeflemektedir. Derin öğrenme yöntemleri ve bilgisayarla görme teknikleri kullanılarak, atıkların türlerine göre ayrıştırılması için bir model geliştirilmiştir.


👉Kullanılan Teknolojiler

Python

TensorFlow/Keras

OpenCV

Matplotlib

NumPy

Pandas

Jupyter Notebook

👉Veri Seti

Veri seti, veri kaynağı üzerinden temin edilmiştir. Veri seti, farklı atık türlerine ait görselleri içermektedir. Her bir görsel, etiketlenmiş olup, hangi atık türüne ait olduğu belirtilmiştir.

👉Sütunlar

Image: Görsel dosyası

Label: Atık türü (plastik, kağıt, cam, organik vb.)

### Görsel Analiz Süreci

Proje sürecinde aşağıdaki adımlar izlenmiştir:

Veri Yükleme ve Ön İşleme: Görsel verilerin yüklenmesi, boyutlandırılması ve normalleştirilmesi.

Model Eğitimi: Derin öğrenme modeli kullanılarak görseller üzerinden atık türlerinin tanımlanması için model eğitimi gerçekleştirilmiştir.

Görselleştirme: Eğitilen modelin performansını değerlendirmek amacıyla, doğruluk oranları ve kayıp grafikleri oluşturulmuştur.

Tahminleme: Yeni atık görselleri üzerinde modelin test edilmesi ve tahmin sonuçlarının görselleştirilmesi.

👉Sonuçlar

Bu projeden elde edilen bulgular:

Model Başarısı: Eğitim süreci sonucunda, modelin %95'lik bir doğruluk oranına ulaşması sağlanmıştır. Bu, atık türlerinin büyük bir başarı ile ayrıştırılabildiğini göstermektedir.

Görsel Analiz Yöntemleri: Kullanılan CNN (Convolutional Neural Network) mimarisi, atık türlerinin doğru bir şekilde tanınmasında etkili olmuştur. Eğitilen model, daha önce görülmemiş görsellerde de yüksek doğruluk oranları ile sonuçlar vermiştir.

Uygulama Alanları: Elde edilen sonuçlar, atık yönetimi süreçlerinde otomasyon sağlamak için kullanılabilir. Bu model, geri dönüşüm tesislerinde veya atık toplama araçlarında entegre edilerek iş gücü verimliliği artırılabilir.

Gelecek Çalışmalar: Projenin ilerleyen aşamalarında, farklı atık türlerinin daha fazla örneği ile modelin güçlendirilmesi ve yeni algoritmalarla performansının artırılması hedeflenmektedir.

