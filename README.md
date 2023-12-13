# FLO Müşteri Segmentasyonu Projesi


Projenin Amacı
Bu proje, FLO'nun müşterilerini RFM (Recency, Frequency, Monetary) analizi kullanarak segmentlere ayırır ve bu segmentlere göre pazarlama stratejileri belirlemeyi amaçlar.

Veri Seti
Veri seti, 2020-2021 yıllarında OmniChannel (hem online hem offline alışveriş yapan) müşterilerin geçmiş alışveriş davranışlarından oluşur.

Veri Seti Değişkenleri
master_id: Eşsiz müşteri numarası
order_channel: Alışveriş yapılan platform (Android, iOS, Desktop, Mobile, Offline)
first_order_date: İlk alışveriş tarihi
last_order_date: Son alışveriş tarihi
order_num_total_ever_online: Online toplam alışveriş sayısı
order_num_total_ever_offline: Offline toplam alışveriş sayısı
customer_value_total_ever_online: Online toplam harcama
customer_value_total_ever_offline: Offline toplam harcama
interested_in_categories_12: Son 12 ayda alışveriş yapılan kategoriler
Veri Ön İşleme ve Analiz Süreci
flo_data_20K.csv dosyasının okunması ve temel veri keşfi.
Toplam alışveriş sayısı ve harcama için yeni değişkenlerin oluşturulması.
Tarih değişkenlerinin doğru formata dönüştürülmesi.
Müşteri segmentasyonu için RFM metriklerinin hesaplanması.
RFM skorlarının hesaplanması ve müşteri segmentlerine atanması.
RFM Analizi
Recency (R): Müşterinin son alışveriş tarihinden bu yana geçen süre.
Frequency (F): Toplam alışveriş sayısı.
Monetary (M): Toplam harcama miktarı.
Müşteriler bu üç metrik temelinde skorlandırılır ve belirli segmentlere ayrılır: champions, loyal_customers, hibernating vb.

Sonuçlar ve Öneriler
Proje sonucunda, farklı müşteri segmentleri belirlenir ve bu segmentlere göre özelleştirilmiş pazarlama stratejileri geliştirilir. Örneğin, yüksek değerli müşteriler için özel promosyonlar veya uzun süredir alışveriş yapmayan müşterileri geri kazanma kampanyaları planlanabilir.
