
# 🎭 Mood Analysis with AI

## 👩‍💻 Proje Hakkında

**Mood Analysis with AI**, Python ve [DeepFace](https://github.com/serengil/deepface) kütüphanesi kullanılarak geliştirilmiş, yapay zeka destekli bir yüz analiz uygulamasıdır. Bu uygulama sayesinde:

- İki fotoğrafın aynı kişiye ait olup olmadığı tespit edilebilir (yüz tanıma),
- Fotoğraflardaki kişilerin yaş, cinsiyet ve baskın duyguları analiz edilebilir,
- Analiz sonuçları kullanıcı arayüzü üzerinden gösterilir ve `analyze_results.txt` dosyasına kaydedilir.

Uygulama, sade bir **Tkinter arayüzü** ile kullanıcı dostu bir deneyim sunar. Özellikle yapay zekâ tabanlı görüntü işleme alanında başlangıç yapmak isteyenler için ideal bir örnek projedir.

## 🧠 Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|----------|----------|
| Python   | Ana programlama dili |
| Tkinter  | Grafiksel kullanıcı arayüzü (GUI) için |
| PIL (Pillow) | Görüntüleri yüklemek ve yeniden boyutlandırmak için |
| DeepFace | Yüz tanıma ve duygu analizi için derin öğrenme kütüphanesi |

## 📸 Özellikler

- [x] Fotoğraf yükleme desteği
- [x] İki yüz arasında benzerlik analizi (aynı kişi mi?)
- [x] Yaş, cinsiyet ve duygu (emotion) tahmini
- [x] Hata kontrolü ve kullanıcıya geri bildirim
- [x] Tüm analizlerin `.txt` dosyasına yazılması
- [x] Gelişmiş GUI destekli deneyim

## 🚀 Kurulum

Aşağıdaki adımları izleyerek projeyi kendi bilgisayarınızda çalıştırabilirsiniz.

### 1. Gerekli Paketleri Yükleyin

```
pip install deepface pillow
```

### 2. Projeyi Çalıştır

```
python main.py
```

> Not: Python 3.7+ sürümü önerilir.


## 🧪 Örnek Kullanım

1. Uygulama başlatıldığında, arayüzden iki farklı fotoğraf yükleyin.
2. “Analiz Et” butonuna tıklayın.
3. Sistem önce iki fotoğrafın aynı kişiye ait olup olmadığını tespit eder.
4. Ardından yaş, cinsiyet ve duygu analizi gerçekleştirilir.
5. Sonuçlar hem ekranda gösterilir hem de `analyze_results.txt` dosyasına yazılır.

## 🛠️ Karşılaşılan Sorunlar ve Çözümleri

| Sorun | Çözüm |
|------|--------|
| `cv2` modülü bulunamadı hatası | `pip install opencv-python` ile kurun |
| DeepFace analizinde hata | İnternet bağlantısını ve resim kalitesini kontrol edin |

## 👩‍🔬 Geliştirici

**Hatice Gazel**  
[LinkedIn](https://www.linkedin.com/in/gazellhatice) • [GitHub](https://github.com/gazellhatice)

## 📜 Lisans

Bu proje MIT lisansı ile lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakabilirsiniz.

## ⭐ Katkıda Bulunmak İster misin?

Pull request’lere ve issue açmaya her zaman açığım! Projeye katkıda bulunmak istersen:

1. Fork’la 🍴
2. Yeni bir dal oluştur (`git checkout -b yeni-ozellik`)
3. Değişiklikleri yap ve commit et (`git commit -am 'Yeni özellik ekledim'`)
4. Push et (`git push origin yeni-ozellik`)
5. Bir pull request gönder 💥
