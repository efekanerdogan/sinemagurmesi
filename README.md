# 🎬 Sinema Gurmesi - AI Destekli Film Keşif Platformu

![Project Status](https://img.shields.io/badge/status-active-brightgreen)
![Tech](https://img.shields.io/badge/tech-HTML5%20%7C%20Tailwind%20%7C%20Gemini%20AI-blue)
![License](https://img.shields.io/badge/license-MIT-purple)

**"Bugün ne izlesem?" derdine son.**
Sinema Gurmesi, sıradan film öneri sitelerinin aksine, **Google Gemini 2.0** yapay zeka modelini kullanarak ruh halinize, spesifik isteklerinize ve zevklerinize göre nokta atışı film önerileri sunan modern bir web uygulamasıdır.

**Canlı Demo: https://efekanerdogan.github.io/sinemagurmesi/

---

## 📸 Ekran Görüntüleri

<img width="1920" height="1085" alt="Screenshot 2025-12-06 at 21-18-10 Sinema Gurmesi - AI Destekli Film Platformu" src="https://github.com/user-attachments/assets/e79e1fd3-7d8f-4a45-8f8b-2056ef7bbc21" />


---

## ✨ Özellikler

Bu proje sadece rastgele film önermez; bir "Sinefil" gibi düşünür.

* 🧠 **Yapay Zeka Destekli:** "Beynimi yakacak, tek mekanda geçen bir gerilim" gibi doğal dilde (natural language) yazdığınız istekleri anlar.
* 🚫 **Klişelerden Uzak:** IMDB Top 20 listesindeki herkesin bildiği filmleri değil, kıyıda köşede kalmış hazineleri (hidden gems) bulmaya odaklanır.
* 🎨 **Modern UI/UX:** Tailwind CSS ile hazırlanmış, **Glassmorphism** etkili, karanlık mod (Dark Mode) tasarımı.
* 📱 **Tam Responsive:** Mobilde, tablette ve masaüstünde kusursuz çalışır.
* 💾 **İzlenecekler Listesi:** Beğendiğiniz filmleri tarayıcı hafızasına (Local Storage) kaydeder. Üyelik gerektirmez.
* 🎬 **OMDb Entegrasyonu:** Filmlerin posterlerini, IMDb puanlarını ve detaylarını otomatik çeker.
* 🎲 **Şansımı Dene:** Ne izleyeceğini bilmeyenler için yapay zekaya rastgele ve yaratıcı promptlar gönderir.

---

## ⚙️ Kurulum ve Kullanım

Bu proje **Serverless** (Sunucusuz) yapıdadır. Sadece `index.html` dosyası ile çalışır.

### 1. Yerel Çalıştırma (Local)
Projeyi bilgisayarınıza indirin ve `index.html` dosyasını tarayıcınızda açın. Bu kadar!

### 2. API Anahtarları (Önemli!) 🔑
Uygulama demo modunda çalışabilir ancak limitlere takılmamak için kendi API anahtarlarınızı girmeniz önerilir.

1.  Sitenin sağ üst köşesindeki **Ayarlar (Dişli İkonu)** butonuna tıklayın.
2.  **Google Gemini API Key:** [Google AI Studio](https://aistudio.google.com/app/apikey) adresinden ücretsiz alabilirsiniz.
3.  **OMDb API Key:** [OMDb API](https://www.omdbapi.com/apikey.aspx) adresinden ücretsiz alabilirsiniz (Posterler için gereklidir).
4.  Kaydet butonuna basın. Anahtarlarınız sadece tarayıcınızda saklanır, sunucuya gönderilmez.

---

## 🛠️ Kullanılan Teknolojiler

* **Core:** HTML5, JavaScript (ES6+)
* **Styling:** Tailwind CSS (CDN)
* **AI Model:** Google Gemini 2.0 Flash (`generativelanguage.googleapis.com`)
* **Data API:** OMDb API (Open Movie Database)
* **Font & Icons:** Google Fonts (Outfit), FontAwesome

---
## ⚠️ Yasal Uyarı

Bu proje eğitim ve hobi amaçlı geliştirilmiştir. Film verileri OMDb API üzerinden sağlanmaktadır. Yapay zeka (Gemini) bazen halüsinasyon görebilir (var olmayan filmler önerebilir), ancak kod içerisindeki algoritmalar bunu minimize etmeye çalışır.

---

## 📄 Lisans

[MIT](LICENSE) © 2025 Efekan Erdoğan
