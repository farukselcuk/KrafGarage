# KrafGaraj - Motorsiklet Parçaları ve Hizmetleri Web Sitesi

Modern, responsive ve kullanıcı dostu bir motorsiklet parçaları satış web sitesi. WhatsApp entegrasyonu ile kolay iletişim imkanı sunar.

## 🚀 Özellikler

- **Modern Tasarım**: Logo renklerini kullanan vintage/retro tarzı tasarım
- **Responsive**: Tüm cihazlarda mükemmel görünüm
- **WhatsApp Entegrasyonu**: Tek tıkla WhatsApp üzerinden iletişim
- **Ürün Kataloğu**: Gidon, motor parçaları ve özel tasarım ürünler
- **İletişim Formu**: Otomatik WhatsApp mesajı oluşturma
- **Animasyonlar**: Smooth scroll ve hover efektleri
- **Mobil Uyumlu**: Hamburger menü ve touch-friendly tasarım

## 📁 Dosya Yapısı

```
KrafGaraj/
├── index.html          # Ana HTML dosyası
├── styles.css          # CSS stilleri
├── script.js           # JavaScript fonksiyonları
├── logo.png           # Logo dosyası (eklenmeli)
└── README.md          # Bu dosya
```

## 🛠️ Kurulum

1. **Dosyaları İndirin**: Tüm dosyaları web sunucunuza yükleyin
2. **Logo Ekleyin**: `logo.png` dosyasını proje klasörüne ekleyin
3. **WhatsApp Numarası**: `script.js` dosyasında telefon numarasını güncelleyin
4. **İçerik Güncelleyin**: Ürün bilgileri ve fiyatları güncelleyin

## 📱 WhatsApp Entegrasyonu

Site üzerindeki tüm "WhatsApp'tan Bilgi Al" butonları otomatik olarak WhatsApp'ta mesaj oluşturur:

- Ürün bilgisi istekleri
- İletişim formu gönderimi
- Genel bilgi talepleri

## 🎨 Tasarım Özellikleri

- **Renk Paleti**: Logo renklerini kullanan altın (#D4AF37) ve siyah tema
- **Typography**: Roboto font ailesi
- **Animasyonlar**: Smooth transitions ve hover efektleri
- **Responsive Grid**: CSS Grid ile modern layout

## 📋 Sayfalar

1. **Ana Sayfa**: Hero section ve genel bilgiler
2. **Ürünler**: Gidon, motor parçaları, özel tasarım motorlar
3. **Hizmetler**: Bakım, modifikasyon, kurulum hizmetleri
4. **Hakkımızda**: Şirket bilgileri ve istatistikler
5. **İletişim**: İletişim bilgileri ve form

## 🔧 Özelleştirme

### WhatsApp Numarası Değiştirme
```javascript
// script.js dosyasında
const phoneNumber = '905438660674'; // Kendi numaranızı girin
```

### Ürün Ekleme
```html
<!-- index.html dosyasında products-grid içine -->
<div class="product-card">
    <div class="product-image">
        <i class="fas fa-icon-name"></i>
    </div>
    <h3>Ürün Adı</h3>
    <p>Ürün açıklaması</p>
    <div class="product-price">₺Fiyat</div>
    <button class="btn btn-whatsapp" onclick="sendWhatsApp('Ürün hakkında bilgi')">
        <i class="fab fa-whatsapp"></i> WhatsApp'tan Bilgi Al
    </button>
</div>
```

### Renk Değiştirme
```css
/* styles.css dosyasında */
:root {
    --primary-color: #D4AF37;    /* Ana renk */
    --secondary-color: #B8860B;  /* İkincil renk */
    --dark-bg: #1a1a1a;         /* Koyu arka plan */
}
```

## 📞 İletişim Bilgileri

- **Telefon**: +90 543 866 06 74
- **E-posta**: info@krafgaraj.com
- **Adres**: İstanbul, Türkiye

## 🚀 Canlı Demo

Siteyi test etmek için `index.html` dosyasını web tarayıcısında açın.

## 📝 Lisans

Bu proje KrafGaraj için özel olarak tasarlanmıştır.

---

**Not**: Logo dosyasını (`logo.png`) proje klasörüne eklemeyi unutmayın! 