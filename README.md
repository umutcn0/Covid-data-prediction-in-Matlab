# Amaç
Tüm dünyayı etkisi altına alan covid-19 virüsünün Türkiye'deki yayılımın hızının geçmiş verileri kullanarak tahmin edilmesi ve insanların gerekli tedbirleri almasının somut verilerle sağlanması.

## Gereklilikler
- Matlab

## Materyal ve Yöntem
T.C. Sağlık Bakanlığı'nın günlük olarak yayınlanmış olduğu yaklaşık 1 aylık verileri baz alarak Matlab üzerinden nntool aracılığıyla fitting öğrenme modeli üzerinde levenberg algoritması kullanılarak program yapılmıştır. Proje üzerinde öğretim modeli danışmalı öğrenmedir. Sisteme verdiğimiz girdi-çıktı karşılıkları için model de bulunan ağırlıkların en uygun değerini bularak güncellenecektir.

### Bu çalışmadaki girdilerimiz:
  - Günlük Test Sayısı
  - Vaka Sayısı
  - Entube Sayısı
  - Yoğun Bakım Sayısı
  - Ölüm Sayısı
  - İyileşen Hasta Sayısı

### Çıktılarımız:
  - Gelecek Test Sayısı
  - Vaka Sayısı
  - Entube Sayısı
  - Yoğun Bakım Sayısı
  - Ölüm Sayısı
  - İyileşen Hasta Sayısı

**Not :** Daha çok veri kullanılarak ve hastaların özelliklerinden yararlanılarak daha doğru çözümlere ulaşmak olasıdır.
