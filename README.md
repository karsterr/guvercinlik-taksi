# 🚕 Güvercinlik-Mumcular Taksi Durağı Web Sitesi

Modern, animasyonlu ve kullanıcı dostu bir taksi durağı tanıtım web sitesi.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📋 İçindekiler

- [Özellikler](#-özellikler)
- [Teknolojiler](#-teknolojiler)
- [Kurulum](#-kurulum)
- [Kullanım](#-kullanım)
- [Sayfa Bölümleri](#-sayfa-bölümleri)
- [Tasarım](#-tasarım)
- [Özelleştirme](#-özelleştirme)
- [Lisans](#-lisans)

## ✨ Özellikler

### Görsel ve Animasyonlar

- 🎨 **Modern Tasarım**: Sarı, beyaz ve siyah renk paleti
- 💫 **Zengin Animasyonlar**: Smooth scroll, parallax efektler, hover animasyonları
- 📱 **Responsive Design**: Mobil, tablet ve masaüstü uyumlu
- 🎭 **İnteraktif Arayüz**: Kullanıcı etkileşimlerine canlı geri dönüşler
- ✨ **Yüzen İkonlar**: Arkaplan animasyonlu taksi ikonları
- 🔄 **Scroll Reveal**: Sayfa kaydırdıkça görünen animasyonlar

### Fonksiyonel Özellikler

- 🏢 **İki Ayrı Durak**: Güvercinlik ve Mumcular için ayrı iletişim bilgileri
- 📞 **Direkt Arama**: Telefon numaralarına tek tıkla arama
- 🚨 **Korsan Taksi Uyarısı**: Kullanıcıları bilgilendiren özel uyarı bölümü
- 🧭 **Smooth Navigation**: Yumuşak sayfa içi gezinme
- 🍔 **Mobil Menü**: Hamburger menü ile mobil uyumlu navigasyon

## 🛠 Teknolojiler

- **HTML5**: Semantik ve erişilebilir yapı
- **CSS3**: Modern stil ve animasyonlar
  - CSS Grid & Flexbox
  - CSS Animations & Transitions
  - Custom Properties (CSS Variables)
  - Responsive Media Queries
- **JavaScript (Vanilla)**: İnteraktif özellikler
  - Intersection Observer API
  - Event Listeners
  - DOM Manipulation
- **Font Awesome 6.4.0**: İkon kütüphanesi

## 📦 Kurulum

### Gereksinimler

- Modern bir web tarayıcı (Chrome, Firefox, Safari, Edge)
- (Opsiyonel) Yerel sunucu için Python veya Node.js

### Adımlar

1. **Projeyi klonlayın**

```bash
git clone https://github.com/karsterr/guvercinlik-taksi.git
cd guvercinlik-taksi
```

2. **Dosyaları açın**

   **Seçenek 1: Doğrudan tarayıcıda**

   - `index.html` dosyasını çift tıklayarak açın

   **Seçenek 2: Python ile yerel sunucu**

   ```bash
   python3 -m http.server 8000
   ```

   Ardından tarayıcınızda `http://localhost:8000` adresine gidin

   **Seçenek 3: Node.js ile yerel sunucu**

   ```bash
   npx http-server -p 8000
   ```

## 🚀 Kullanım

### Telefon Numaralarını Güncelleme

`index.html` dosyasında telefon numaralarını güncelleyin:

**Güvercinlik Durağı:**

```html
<p class="contact-detail">0xxx xxx xx xx</p>
<a href="tel:0xxxxxxxxxx" class="btn btn-primary btn-small"></a>
```

**Mumcular Durağı:**

```html
<p class="contact-detail">0xxx xxx xx xx</p>
<a href="tel:0xxxxxxxxxx" class="btn btn-primary btn-small"></a>
```

### Renk Paletini Değiştirme

`styles.css` dosyasındaki CSS değişkenlerini düzenleyin:

```css
:root {
  --primary-yellow: #ffd700; /* Ana sarı renk */
  --dark-yellow: #ffa500; /* Koyu sarı */
  --black: #000000; /* Siyah */
  --white: #ffffff; /* Beyaz */
  --gray: #333333; /* Gri */
}
```

## 📄 Sayfa Bölümleri

### 1. 🏠 Ana Sayfa (Hero)

- Etkileyici başlık ve slogan
- İki CTA butonu (Hemen Ara, Daha Fazla Bilgi)
- Animasyonlu arka plan ve yüzen ikonlar
- Parallax scroll efekti

### 2. ℹ️ Hakkımızda

- 4 özellik kartı:
  - 🛡️ Güvenilir Hizmet
  - ⏰ 7/24 Hizmet
  - 💰 Uygun Fiyat
  - 🚗 Konforlu Araçlar
- Hover animasyonları ve ikon rotasyonu

### 3. 👨‍✈️ Şoförlerimiz

- 3 özellik kartı:
  - 👔 Lisanslı Şoförler
  - 🗺️ Bölge Bilgisi
  - 🎓 Eğitimli Kadro
- Gradient arka plan ve ışık efektleri

### 4. ⚠️ Korsan Taksi Uyarısı

- Dikkat çekici uyarı kutusu
- 5 önemli bilgilendirme noktası
- Animasyonlu uyarı ikonu
- Pulse efekti

### 5. 📞 İletişim

**İki Ayrı Durak Bölümü:**

#### Güvercinlik Taksi Durağı

- Telefon numarası ve direkt arama butonu
- Adres bilgisi
- Çalışma saatleri

#### Mumcular Taksi Durağı

- Telefon numarası ve direkt arama butonu
- Adres bilgisi
- Çalışma saatleri

### 6. 🔗 Footer

- Logo ve slogan
- Hızlı linkler
- İletişim bilgileri
- Copyright bilgisi

## 🎨 Tasarım

### Renk Paleti

- **Sarı (#FFD700)**: Taksi teması, vurgu rengi
- **Siyah (#000000)**: Arka planlar, metin
- **Beyaz (#FFFFFF)**: Kartlar, metin
- **Gri (#333333)**: İkincil metin

### Tipografi

- **Font**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- **Başlıklar**: 2rem - 4rem, bold
- **Metin**: 1rem - 1.2rem, normal/medium

### Animasyonlar

- **Fade In Up**: Kartların görünme animasyonu
- **Slide Down**: Navbar açılış animasyonu
- **Pulse**: Logo ve uyarı animasyonu
- **Float**: Yüzen ikon animasyonları
- **Bounce**: Zıplayan ikonlar
- **Ripple**: Buton tıklama efekti
- **3D Tilt**: Kart eğilme efekti

## ⚙️ Özelleştirme

### Yeni Bölüm Ekleme

1. HTML'e yeni section ekleyin
2. CSS'te stil tanımlayın
3. Navbar'a link ekleyin
4. JavaScript'te animasyon ekleyin (opsiyonel)

### Animasyon Hızını Değiştirme

`styles.css` dosyasında animation süresini değiştirin:

```css
.about-card {
  animation: fadeInUp 0.8s ease-out forwards; /* 0.8s'yi değiştirin */
}
```

### Mobil Breakpoint'i Değiştirme

```css
@media (max-width: 768px) {
  /* 768px'i değiştirin */
  /* Mobil stiller */
}
```

## 📱 Responsive Tasarım

- **Desktop**: 1200px+ (Grid layout, 3-4 kolon)
- **Tablet**: 768px - 1199px (Grid layout, 2 kolon)
- **Mobile**: <768px (Single kolon, hamburger menü)

## 🌐 Tarayıcı Desteği

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

## 📝 Dosya Yapısı

```
guvercinlik-taksi/
│
├── index.html          # Ana HTML dosyası
├── styles.css          # Tüm stiller ve animasyonlar
├── script.js           # JavaScript fonksiyonları
└── README.md           # Proje dokümantasyonu
```

## 🔧 Geliştirme

### JavaScript Özellikleri

- **Mobil Menü**: Hamburger menü toggle
- **Smooth Scroll**: Sayfa içi yumuşak geçişler
- **Scroll Reveal**: İçerik görünme animasyonları
- **Navbar Scroll**: Scroll'da navbar efekti
- **Parallax**: Hero section parallax efekti
- **Ripple Effect**: Buton tıklama animasyonu
- **3D Tilt**: Kart mouse tracking efekti
- **Custom Cursor**: Özel mouse cursor (opsiyonel)

### Performans İpuçları

- CSS animasyonları GPU hızlandırmalı (transform, opacity)
- Lazy loading için Intersection Observer kullanılıyor
- Minimum DOM manipülasyonu
- Optimize edilmiş CSS selectors

## 🐛 Hata Ayıklama

### Animasyonlar Çalışmıyor

- Tarayıcı konsolunu kontrol edin
- `script.js` dosyasının yüklendiğinden emin olun
- CSS değişkenlerinin doğru tanımlandığını kontrol edin

### Mobil Menü Açılmıyor

- JavaScript hatalarını kontrol edin
- Event listener'ların doğru bağlandığından emin olun

### Font Awesome İkonları Görünmüyor

- İnternet bağlantısını kontrol edin
- CDN linkinin doğru olduğundan emin olun

## 🚀 Gelecek Özellikler

- [ ] Google Maps entegrasyonu
- [ ] İletişim formu ekleme
- [ ] Çoklu dil desteği (TR/EN)
- [ ] Dark mode
- [ ] Online rezervasyon sistemi
- [ ] Şoför profilleri ve fotoğrafları
- [ ] Müşteri yorumları bölümü
- [ ] SSS (Sık Sorulan Sorular) bölümü

## 📞 İletişim

Proje hakkında sorularınız için:

- GitHub: [@karsterr](https://github.com/karsterr)
- Proje: [guvercinlik-taksi](https://github.com/karsterr/guvercinlik-taksi)

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

---

**⭐ Projeyi beğendiyseniz yıldız vermeyi unutmayın!**

Made with ❤️ for Güvercinlik-Mumcular Taksi Durağı

## 🚀 Başlangıç ve Vizyon

Bu proje, Bodrum'un önemli ulaşım noktaları olan **Güvercinlik** ve **Mumcular** Taksi Kooperatiflerini dijital platforma taşımak üzere **yeni başlatılmıştır**. Amacımız, kooperatifin hizmetlerini, iletişim bilgilerini ve kurumsal kimliğini modern, hızlı ve mobil uyumlu bir web sitesi aracılığıyla 7/24 erişilebilir kılmaktır.

Bu README, projenin **yol haritasını** ve **planlanan teknik yapısını** özetlemektedir, çünkü geliştirme süreci **henüz başlamamıştır**.

---

## 🎯 Proje Hedefleri (Neler Yapılacak?)

Sitenin geliştirme tamamlandığında ulaşması beklenen ana hedefler şunlardır:

1.  **Hızlı İletişim:** Ziyaretçilerin tek bir dokunuşla taksi durağına ulaşabilmesi için anında arama ve WhatsApp butonları.
2.  **Hizmet Alanı Tanıtımı:** Güvercinlik ve Mumcular'ın Bodrum Havalimanı (BJV), çevre oteller ve popüler destinasyonlar için sunduğu güzergah ve transfer hizmetlerinin detaylı sunumu.
3.  **Mobil Odaklılık:** Tüm tasarımların öncelikle mobil cihazlar düşünülerek, en yüksek kullanıcı deneyimi (UX) ile oluşturulması.
4.  **Güvenilirlik:** Kooperatifin adres, çalışma saatleri ve hizmet kalitesini yansıtan güvenilir bir kurumsal dijital varlık oluşturulması.

---

## 🛠 Planlanan Teknik Yığın

Proje, güncel teknolojiler kullanılarak hızlı performans ve kolay bakım hedefiyle inşa edilecektir:

| Alan                    | Planlanan Teknoloji                            | Neden Tercih Edildi?                                                                       |
| :---------------------- | :--------------------------------------------- | :----------------------------------------------------------------------------------------- |
| **Ön Yüz (Frontend)**   | HTML5, CSS3, JavaScript                        | Hafif, hızlı yüklenen ve sade bir arayüz için ideal.                                       |
| **Çerçeve (Framework)** | **Statik Site Oluşturucu (Örn: Hugo/Jekyll)**  | Dinamik bir içerik yönetim sistemi (CMS) gerektirmeyen, **maksimum hız** ve güvenlik için. |
| **Arka Yüz (Backend)**  | **Gerek yok** / (Basit İletişim Formu Servisi) | Çoğunlukla tanıtım amaçlı olacağı için, karmaşık bir arka uca ihtiyaç duyulmayacaktır.     |
| **Veritabanı**          | **Yok**                                        | Veriler dosya tabanlı (Markdown/YAML) olarak yönetilecektir.                               |

---

## 🗺 Yol Haritası (Geliştirme Planı)

Proje, bu aşamada belirlenen aşağıdaki adımlarla ilerleyecektir:

### Aşama 0: Hazırlık (Şu Anda Buradayız)

- ✅ Proje hedefleri ve kapsamının belirlenmesi.
- ✅ Teknik yığın kararlarının verilmesi.
- ⬜ Tasarım ve içerik materyallerinin (logo, fotoğraflar, güzergah listeleri) toplanması.

### Aşama 1: Çekirdek Geliştirme (Başlanacak)

- ⬜ Statik site çatısının kurulması.
- ⬜ Ana Sayfa ve İletişim Sayfası'nın kodlanması.
- ⬜ Mobil (Responsive) tasarımın %80 oranında tamamlanması.
- ⬜ Hızlı arama ve WhatsApp butonlarının entegrasyonu.

### Aşama 2: İçerik ve İyileştirme

- ⬜ Çoklu dil desteği (İngilizce) eklenmesi.
- ⬜ Google Haritalar entegrasyonu ve durak konumlarının işaretlenmesi.
- ⬜ İlk SEO (Arama Motoru Optimizasyonu) ayarlarının yapılması.

### Aşama 3: Yayınlama

- ⬜ Tüm testlerin tamamlanması.
- ⬜ Sitenin canlı sunucuya yüklenmesi ve alan adının bağlanması.
- ⬜ Kooperatif üyelerine sitenin tanıtılması ve eğitimin verilmesi.

---

## 🤝 Katkıda Bulunma

Proje henüz planlama aşamasında olduğu için kod katkıları için biraz beklemekte fayda var. Ancak **tasarım önerileri**, **içerik fikirleri** veya **teknik mimari tavsiyeleri** her zaman açıktır. Lütfen fikirlerinizi paylaşmaktan çekinmeyin!

## 📄 Lisans

Bu proje, açık kaynaklı **MIT Lisansı** altında lisanslanacaktır.
