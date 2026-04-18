# LightGBM Classifier - Titanic Survival Prediction

Bu proje, popüler **Titanic** veri seti üzerinde **LightGBM** algoritmasını kullanarak yolcuların hayatta kalma durumlarını tahmin eden bir makine öğrenmesi modelidir. Proje kapsamında veri ön işleme, keşifçi veri analizi (EDA) ve model performans değerlendirmesi adımları uygulanmıştır.

## 📊 Proje Özeti

- **Veri Seti:** Seaborn kütüphanesi üzerinden yüklenen Titanic veri seti.
- **Model:** LightGBM (Light Gradient Boosting Machine).
- **Hedef Değişken:** `survived` (Hayatta kaldı mı?).
- **Kütüphaneler:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, LightGBM.

## 🛠️ Kurulum

Yerel ortamınızda çalıştırmak için şu adımları izleyebilirsiniz:

1. Bu depoyu klonlayın:
   ```bash
   git clone [https://github.com/erdemozkan1/LightGbM-Classifier.git](https://github.com/erdemozkan1/LightGbM-Classifier.git)
   ```
2.Gerekli kütüphaneleri yükleyin:

```Bash
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm
```
## 🚀 Model Performansı
Modelin test verileri üzerindeki başarım sonuçları:

Accuracy (Doğruluk): %82

F1-Score (Sınıf 1): 0.77

F1-Score (Sınıf 0): 0.85

## Karmaşıklık Matrisi (Confusion Matrix):
Plaintext
[[115  19]
 [ 21  68]]
## 📂 Dosya Yapısı
LightGBM-classifier.ipynb: Tüm analiz ve modelleme adımlarını içeren Jupyter Notebook dosyası.

README.md: Proje hakkında bilgi veren döküman.

👨‍💻 Hazırlayan
Erdem - GitHub Profilim

Bu proje, makine öğrenmesi çalışmaları kapsamında eğitim amaçlı geliştirilmiştir.


### Nasıl Ekleyeceksin?
1. Bilgisayarındaki klasörde sağ tıkla -> Yeni Metin Belgesi oluştur.
2. Adını `README.md` yap (sonundaki `.txt` uzantısını sildiğinden emin ol).
3. Yukarıdaki kodu içine yapıştır ve kaydet.
4. Ardından terminale şu komutları yazarak GitHub'a gönder:

```bash
git add README.md
git commit -m "README dosyası eklendi"
git push origin main
```
