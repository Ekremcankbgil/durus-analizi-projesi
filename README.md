# 🎯 Duruş Analizi Projesi

Bu proje, Python kullanılarak geliştirilen **gerçek zamanlı bir duruş analizi sistemidir**.  
Kamera üzerinden kullanıcıyı izleyerek yaygın duruş bozukluklarını tespit eder ve kullanıcıyı uyarır.

## 🔍 Tespit Edilen Durumlar
- Ekrana çok yakın oturma
- Omuzların yana eğilmesi
- Boynun öne eğilmesi (telefon boynu)

## ⚙️ Özellikler
- MediaPipe Pose ile vücut noktalarının tespiti
- Kişiye özel kalibrasyon
- Gerçek zamanlı görsel ve sesli uyarılar
- Hata durumlarında kanıt fotoğrafı kaydı
- CSV formatında detaylı oturum raporu
- Debug modu (teknik detaylar için)

## ⌨️ Kontroller
- **K** → Kalibrasyon
- **D** → Debug modu aç/kapat
- **R** → Oturumu sıfırla
- **Q** → Çıkış

## ▶️ Çalıştırma
Gerekli kütüphaneleri yükle:
```bash
pip install -r requirements.txt
python durus_analizi.py

