# 📊 Enflasyonist Dönemde Gerçekten Kim Krizdeydi?

### 🧠 Türkiye Perakende Sektöründe 2020–2024 Arası Kârlılık ve İstihdam Analizi

---

## 📌 Proje Özeti

Bu proje, Türkiye’de 2020–2024 yılları arasında yaşanan yüksek enflasyon sürecinde  
perakende sektöründe faaliyet gösteren dört büyük şirketin — **BİM, Migros, Şok Marketler ve CarrefourSA** —  
finansal performansları ile istihdam düzeyleri arasındaki ilişkiyi incelemektedir.

**Ana soru:**  
> “Enflasyonist kriz döneminde gerçekten kim krizdeydi?”

---

## 🎯 Amaç

Bu çalışmanın amacı, ekonomik kriz söylemlerinin şirketlerin finansal verileriyle ne kadar örtüştüğünü  
ve bu dönemde **çalışan başına kârlılığın** nasıl değiştiğini ortaya koymaktır.  

Projede kullanılan temel metrikler:
- Reel (enflasyondan arındırılmış) hisse fiyatları  
- Yıllık TÜFE oranları  
- Yıllara göre toplam çalışan sayıları  
- Personel başına düşen kâr oranı

---

## 🧩 Veri Kaynakları

| Veri Türü | Kaynak |
|:--|:--|
| Hisse Fiyatları | Yahoo Finance API (`yfinance` kütüphanesi) |
| Enflasyon (TÜFE) | TÜİK Resmî İstatistikleri |
| Çalışan Sayıları | Şirketlerin Faaliyet Raporları ve KAP Bildirimleri |
| Manuel Ek Veriler | 2020–2024 TÜFE oranları (TÜİK yıllık ortalamaları) |

---

## 📈 Analiz Adımları

1. **Veri Toplama:**  
   `yfinance` API ile 4 şirketin 2020–2024 arası hisse fiyatları çekilmiştir.  
2. **TÜFE Entegrasyonu:**  
   TÜFE verileri manuel olarak tabloya eklenerek nominal fiyatlar reel değerlere çevrilmiştir.  
3. **Personel Verileri:**  
   Şirket faaliyet raporlarından yıllara göre çalışan sayıları eklenmiştir.  
4. **Kârlılık Hesaplaması:**  
   Reel fiyat değişimleriyle birlikte, **çalışan başına kâr oranı** hesaplanmıştır.  
5. **Görselleştirme:**  
   Matplotlib & Seaborn ile yıllık bazda trend grafikleri oluşturulmuştur.  

---

## 📊 Bulgular

- Tüm şirketlerde 2020–2024 arasında **toplam kâr artarken**, istihdam artışı sınırlı kalmıştır.  
- Özellikle BİM ve Migros, kriz yıllarında **personel başına kârlılığı 3–4 katına kadar yükseltmiştir.**  
- CarrefourSA istihdamını koruyamamış; Şok Marketler ise en hızlı genişleyen firmalardan olmuştur.  

---

## 🧮 Kullanılan Teknolojiler

- **Python**  
- **Pandas**, **Matplotlib**, **Seaborn**  
- **Google Colab**  
- **Yahoo Finance API (yfinance)**  
- **Markdown & Creative Commons Lisanslama**

---


## 🧾 Lisans

Bu proje,  
**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** lisansı ile korunmaktadır.  

🔗 [Lisansı Görüntüle](https://creativecommons.org/licenses/by-nc/4.0/legalcode)

© 2025 Deniz Atabey  


👤 **Deniz Atabey**  


