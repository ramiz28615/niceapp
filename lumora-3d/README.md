# LUMORA — Alışverişin Yeni Hali

Özgün, tamamen Türkçe ve Apple'ın Human Interface Guidelines ilkelerindeki açıklık, görsel hiyerarşi, erişilebilirlik ve anlamlı hareket yaklaşımından **ilham alan**, bağımsız bir premium 3D alışveriş **frontend demosu**. Apple ile ilişkili veya Apple onaylı değildir.

## Özellikler

- Tek dosya: `index.html` (HTML + CSS + vanilla JavaScript).
- Büyük premium açılış ekranı, CSS ürün illüstrasyonu, editoryal koleksiyon panoları; mobil ve masaüstü tasarım.
- 24 temsili ürün; arama ve öneriler, kategori, fiyat, puan, stok filtreleri ve sıralama.
- Ürün detayları, favoriler, sepet, indirim kodu `MERHABA10`, demo profil, demo sipariş ve sipariş geçmişi.
- Three.js showroom: kulaklık, sneaker ve saat için **temsili geometriler**, renk seçimi, döndürme, yakınlaştırma, otomatik dönüş.
- Açık/koyu tema, dokunmatik menü, azaltılmış hareket ve WebGL olmadan alternatif önizleme.

## Çalıştırma

```bash
cd lumora-3d
python -m http.server 8000
```

Tarayıcıdan `http://localhost:8000` adresine git. CSS/JS tek dosyadadır, ancak 3D motoru (Three.js) ve bazı fotoğraflar CDN gerektirdiğinden internete ihtiyaç duyar.

## Önemli üretim sınırı

Bu uygulama **gerçek ödeme, kimlik doğrulama, gönderi veya sunucu siparişi yapmaz.** Tüm ürünler, fiyatlar, değerlendirmeler ve siparişler temsili örneklerdir. Bazı demo tercihler tarayıcıda saklanır. Gerçek mağaza için güvenli backend, veritabanı, stok kontrolü, kullanıcı yetkileri, ödeme sağlayıcısı, yasal metinler, KVKK ve testler gerekir. Lovable/Base44 bağlantısı etkin değildir.

## Kaynaklar

- [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/) — genel tasarım ilkeleri
- [Agentic Awesome Skills](https://github.com/sickn33/agentic-awesome-skills)
- [Awesome](https://github.com/sindresorhus/awesome)
- [Lovable](https://docs.lovable.dev/) · [Base44](https://base44.com/developers)

© LUMORA — özgün demo projesi.