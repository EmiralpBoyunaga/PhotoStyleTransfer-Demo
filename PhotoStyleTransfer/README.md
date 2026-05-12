# Starry Night Generator
Bu proje, fotoğraflarınızı anında Vincent van Gogh'un "Yıldızlı Gece" resim stiline dönüştüren yapay zeka tabanlı bir stil transferi uygulamasıdır.

# Özellikler
Hızlı Stil Transferi: Önceden eğitilmiş dönüşüm ağı sayesinde saniyeler içinde sonuç üretir.
Kullanıcı Dostu Arayüz: Gradio arayüzü ile sürükle-bırak fotoğraf yükleme desteği.
Yüksek Çözünürlük: Görüntüleri 512px boyutunda işleyerek kaliteli çıktılar sağlar.

# Teknik Detaylar
Framework: PyTorch
Arayüz: Gradio
Model: Derin Sinir Ağları (CNN tabanlı Dönüşüm Ağı)
Veri Seti: 40,000+ görüntü ile eğitilmiştir.

# Desteklenen Fotoğraf Türleri
Formatlar: JPEG, JPG, PNG, BMP, WEBP
Renk Modu: RGB (Şeffaf PNG'ler otomatik olarak RGB'ye dönüştürülür)
Boyut: Herhangi bir çözünürlük (Uygulama içinde 512px'e optimize edilir)
Öneri: Net hatlara sahip manzara ve şehir fotoğrafları Van Gogh stilini en iyi yansıtan sonuçları verir.

# Kurulum
Projeyi çalıştırmak için aşağıdaki kütüphaneleri yükleyin:

```bash
pip install torch torchvision pillow numpy gradio