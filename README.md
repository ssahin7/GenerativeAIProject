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

DCGAN / FaceSwap – Yüz sentezi ve morflama

BetaVEA/ VAE – Sentetik yüz üretimi

OpenCV / dlib – Görsel işleme


Veri Kaynakları

Gerçek kişi A: Görsel 

Gerçek kişi B: Görsel 


Veriler etik kurallar çerçevesinde ve izinli olarak temin edilmiştir.

Adımlar

1. Veri Toplama: İki kişiye ait videolardan karelema yöntemi ile yüz  verileri toplanır.


2. Embed Kodlama: Her veri türü embedding'e dönüştürülür.


3. Birleştirme: Embedding'ler belirli ağırlıklarla birleştirilerek yeni bir profil oluşturulur.


4. Yüz Üretimi: VAE ile özelleştirilmiş embedding'e uygun yüz sentezlenir.


Çıktılar

Gerçekçi görünümlü bir yüz görüntüsü

Ek

Başarılı Olunmasa da Hibrit VAE-GAN mimarisi de ekstra bir kod dosyası içinde belirtilmiştir. Ayrıca mimarilerin anlatıldığı videoyu da indirip inceleyebilirsiniz.
Veri Setine Ait Videolara da https://drive.google.com/drive/folders/1zi33bhQBbDwTMIgJhID4ZH2QKIeVE7Um?usp=sharing linkinden ulaşabilirsiniz.
