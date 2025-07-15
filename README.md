# 🎲 Pig Game - Zar Oyunu

## 📝 Proje Açıklaması

Pig Game, iki oyunculu klasik bir zar oyunudur. Oyuncular sırayla zar atarak puan toplamaya çalışırlar ve ilk 100 puana ulaşan oyuncu kazanır. Oyun tamamen **Vanilla JavaScript** ile geliştirilmiştir ve modern web teknolojileri kullanılmıştır.

## 🎮 Oyun Kuralları

- **Amaç**: İlk 100 puana ulaşan oyuncu kazanır
- **Oynanış**:
  - Oyuncular sırayla zar atar
  - Zar 1 gelirse, oyuncu sıra kaybeder ve o turdaki puanı sıfırlanır
  - Zar 1 değilse, oyuncu puanı biriktirir ve:
    - **Hold** yaparak birikmiş puanı ana skoruna ekleyebilir
    - Veya risk alarak zarı tekrar atabilir
- **Kazanan**: İlk 100 puana ulaşan oyuncu oyunu kazanır

## 🛠️ Kullanılan Teknolojiler

- **HTML5**: Oyun yapısı ve semantic markup
- **CSS3**:
  - Modern gradient background
  - Flexbox layout
  - Responsive design
  - Smooth transitions ve animations
  - Google Fonts (Nunito)
- **Vanilla JavaScript**:
  - DOM manipulation
  - Event handling
  - Game logic
  - Random number generation
  - State management

## 🎯 Özellikler

- ✅ İki oyunculu oyun
- ✅ Responsive tasarım
- ✅ Modern ve şık arayüz
- ✅ Smooth animasyonlar
- ✅ Gerçek zamanlı skor takibi
- ✅ Yeni oyun başlatma
- ✅ Görsel zar gösterimi (1-6 arası)

## 🚀 Kurulum ve Çalıştırma

1. Projeyi klonlayın veya indirin
2. `final` klasörüne gidin
3. `index.html` dosyasını web tarayıcınızda açın
4. Oyun hazır! 🎮

## 📁 Proje Yapısı

```
final/
├── index.html      # Ana HTML dosyası
├── script.js       # Oyun mantığı
├── style.css       # Stil dosyası
├── dice-1.png      # Zar görselleri
├── dice-2.png
├── dice-3.png
├── dice-4.png
├── dice-5.png
└── dice-6.png
```

## 🎨 Tasarım

- Modern gradient arkaplan
- Cam efektli (glassmorphism) oyun paneli
- Responsive tasarım
- Smooth geçiş animasyonları
- Temiz ve kullanıcı dostu arayüz

## 🔄 Oyun Akışı

1. Oyun başlar, Player 1 aktif olur
2. "Roll dice" ile zar atılır
3. Zar 1 gelirse sıra değişir
4. Zar 1 değilse puan birikir
5. "Hold" ile birikmiş puan ana skora eklenir
6. İlk 100 puana ulaşan kazanır
7. "New game" ile oyun sıfırlanır

## 📱 Tarayıcı Uyumluluğu

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅

---

_Bu proje eğitim amaçlı geliştirilmiştir ve Vanilla JavaScript öğrenimi için mükemmel bir örnektir._
