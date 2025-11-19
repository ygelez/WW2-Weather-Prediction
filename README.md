2. Dünya Savaşı Hava Durumu Tahmini (Linear Regression)

Bu proje, 2. Dünya Savaşı sırasındaki hava durumu verilerini kullanarak bir Makine Öğrenmesi modeli geliştirmek amacıyla yapılmıştır.

Amaç:
Gece ölçülen en düşük sıcaklık (`MinTemp`) verisini kullanarak, gün içindeki en yüksek sıcaklığı (`MaxTemp`) tahmin etmek.

Sonuçlar:
Model olarak **Basit Doğrusal Regresyon (Simple Linear Regression)** kullanılmıştır.
* **R2 Skoru:** 0.55
* **Ortalama Hata (MAE):** ~1.9 Derece

Nasıl Çalıştırılır?
1. Bu repoyu indirin.
2. `Summary of Weather.csv` dosyasının notebook ile aynı klasörde olduğundan emin olun.
3. `.ipynb` dosyasını çalıştırın.
