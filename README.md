Sentetik Kişilik Üretimi Projesi

Proje Hakkında

Bu proje, iki farklı gerçek kişiye ait görsel, ses ve metin verileri kullanılarak, var olmayan bir üçüncü kişinin yapay olarak oluşturulmasını amaçlamaktadır.
Üretilen kişi; özgün yüz özellikleri ve kişilik metrikleriyle, herhangi bir gerçek kişiye doğrudan benzemeyen ancak iki kaynağın karışımını taşıyan sentetik bir bireydir.

Amaç

Veri gizliliğini ihlal etmeden gerçekçi insan temsilleri üretmek

Medya içeriklerinde kullanılmak üzere telifsiz, sentetik karakterler oluşturmak

Yapay zeka ile dijital kimlik üretiminin etik sınırlarını araştırmak


Kullanılan Teknolojiler

Python 3.10

DeepFaceLab / FaceSwap – Yüz sentezi ve morflama

StyleGAN2 / StyleGAN3 – Sentetik yüz üretimi

Tacotron2 + WaveGlow – Ses sentezi

BERT / GPT – Kişilik metni üretimi

OpenCV / dlib – Görsel işleme


Veri Kaynakları

Gerçek kişi A: Görsel + ses + metin

Gerçek kişi B: Görsel + ses + metin


Veriler etik kurallar çerçevesinde ve izinli olarak temin edilmiştir.

Adımlar

1. Veri Toplama: İki kişiye ait yüz, ses ve metin verileri toplanır.


2. Embed Kodlama: Her veri türü embedding'e dönüştürülür.


3. Birleştirme: Embedding'ler belirli ağırlıklarla birleştirilerek yeni bir profil oluşturulur.


4. Yüz Üretimi: VAE ile özelleştirilmiş embedding'e uygun yüz sentezlenir.





Çıktılar

Gerçekçi görünümlü bir yüz görüntüsü
