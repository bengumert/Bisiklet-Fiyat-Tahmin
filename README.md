# Bisiklet Fiyat Tahmini Projesi

Bu proje, bisiklet fiyatlarını tahmin etmek için veri analizi ve makine öğrenimi tekniklerini kullanmaktadır. Proje, veri ön işleme adımlarını Pandas ile gerçekleştirirken, tahmin modeli oluşturma ve eğitmeyi TensorFlow kütüphanesi ile yapmaktadır.

## İçerik

Bu depo aşağıdaki Jupyter Notebook dosyalarını içermektedir:

* **`pandasBisikletFiyatları.ipynb`**: Bu not defteri, bisiklet fiyat veri setinin Pandas kütüphanesi kullanılarak temel veri analizi, keşfi ve ön işleme adımlarını içermektedir. Verilerin yüklenmesi, temizlenmesi, dönüştürülmesi ve ilk analizlerinin yapılması bu bölümde ele alınır.
* **`tensorflowBisiklerFiyaları.ipynb`**: Bu not defteri, Pandas ile hazırlanan veriler üzerinde TensorFlow ve Keras kullanarak bir regresyon modeli oluşturmayı ve eğitmeyi göstermektedir. Modelin performansı değerlendirilir ve yeni bisikletler için fiyat tahmini yapılır.

## Özellikler

* Bisiklet fiyat veri setinin detaylı incelenmesi ve temizlenmesi.
* Veri görselleştirmeleri ile özelliklerin fiyat üzerindeki etkisinin anlaşılması.
* TensorFlow kullanarak esnek ve güçlü bir regresyon modeli oluşturma.
* Modelin eğitimi, doğrulanması ve performans değerlendirmesi.
* Eğitilmiş model ile yeni tahminler yapma yeteneği.
  

 **Gerekli Kütüphaneler**
    Bu proje için aşağıdaki Python kütüphanelerine ihtiyacınız olacaktır:
    * `pandas`
    * `numpy`
    * `tensorflow`
    * `matplotlib`
    * `seaborn`


## Kullanılan Teknolojiler

* **Python**
* **Pandas**: Veri manipülasyonu ve analizi için.
* **NumPy**: Sayısal işlemler için.
* **TensorFlow / Keras**: Derin öğrenme modeli oluşturma ve eğitme için.
* **Matplotlib / Seaborn**: Veri görselleştirmeleri için.
