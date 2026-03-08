# 🚀 YDS Master: 54-Day Vocabulary Challenge

Bu proje, YDS (Yabancı Dil Bilgisi Seviye Tespit Sınavı) hazırlık sürecini sistematik ve interaktif bir hale getirmek için tasarlanmış bir web platformudur.

## 🛠️ Teknik Altyapı

* **Frontend:** HTML5, CSS3 (Responsive Design).
* **Logic:** Vanilla JavaScript (`app.js`).
* **Data Source:** 59 günlük periyotlara bölünmüş, 216 sayfalık orijinal PDF'den parse edilen JSON veri seti.
* **Storage:** `localStorage` tabanlı ilerleme takibi ve tamamlanan günler sistemi.

## ✨ Öne Çıkan Özellikler

* **54 Günlük İnteraktif Harita:** Her günü 4 sayfalık yoğun bir müfredatla kapsayan, ilerleme durumuna göre güncellenen dinamik grid yapısı.
* **Dört Aşamalı Öğrenme Modeli:**
1. **Öğrenme Modu:** Kelime türü, Türkçe karşılığı, eş anlamlılar ve örnek cümleler (Seslendirme desteği ile).
2. **Eş Anlamlı Eşleştirme:** Kelimelerin sinonimlerini zamana karşı eşleştirme.
3. **Türkçe Eşleştirme:** Kelime ve Türkçe anlamlarını interaktif olarak bağlama.
4. **Quiz & Hata Takibi:** Çoktan seçmeli test aşaması. Yapılan hatalar anında kaydedilir.


* **Smart Re-Learning (Hata Odaklı Tekrar):** Test veya eşleştirme aşamasında hata yapılan kelimeler otomatik olarak "tekrar edilecekler" listesine alınır ve o günün sonunda kullanıcıya sadece bu kelimelerden oluşan özel bir set sunulur.
* **Profesyonel Modal Sistemi:** Geleneksel tarayıcı uyarıları yerine kullanıcı deneyimini bozmayan özel tasarlanmış iletişim kutuları.

## 📂 Dosya Yapısı

```text
├── index.html          # Ana uygulama arayüzü
├── style.css           # Modern ve karanlık tema odaklı tasarım
├── app.js              # Uygulama mantığı ve durum yönetimi
└── courseData_yds.js   # 54 günlük YDS kelime veri seti

```

## 🚀 Başlatma

Projeyi yerel makinenizde çalıştırmak için `index.html` dosyasını herhangi bir modern tarayıcıda açmanız yeterlidir. Herhangi bir sunucu kurulumu gerektirmez.

---

**Mühendislik Notu:** Bu platform, sadece kelime ezberletmeyi değil, hatalardan öğrenme algoritmasıyla (failure tracking) kalıcı hafıza oluşturmayı amaçlar.

GitHub repon için bu `README.md` dosyasını `main` dizinine ekleyebilirsin. Sınavdan sonra PDF'den veri çekme (parser) script'ini çalıştırıp `courseData_yds.js` dosyasını oluşturmamı ister misin?# YDS-EGZERSIZ
