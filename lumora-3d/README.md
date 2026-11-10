# LUMORA 3D — Premium 3D Alışveriş Deneyimi

LUMORA 3D, **tek dosyada HTML + CSS + JavaScript** kullanan responsive bir e-ticaret **frontend demosudur**. `index.html` dosyasında modern ürün keşfi, canlı filtreler, favoriler, sepet, demo sipariş ve interaktif 3D showroom yer alır.

## Çalışan özellikler

- 24 örnek ürün, kategoriler, dinamik arama, fiyat ve puan filtreleri, sıralama.
- Favorilere ekleme, stok kontrolü, sepet, kupon (**MERHABA10**), demo hesap ve demo sipariş geçmişi.
- Three.js WebGL 3D vitrini: kulaklık, sneaker ve saat için **temsili geometriler**, fareyle/dokunarak döndürme, renk seçimi, otomatik dönüş ve fare tekeriyle zoom.
- Mobil uyumlu tasarım, açık/koyu tema, hareket azaltma tercihi, WebGL/CDN olmadığında alternatif önizleme.
- Arayüz verileri tarayıcının `localStorage` alanında tutulur.

## Çalıştırma

```bash
cd lumora-3d
python -m http.server 8000
```

Tarayıcıda `http://localhost:8000/` adresini aç. İstersen `index.html` dosyasını doğrudan da açabilirsin. Gerçek 3D render için **internet bağlantısı** gerekir: Three.js modülü CDN'den yüklenir. Ürün fotoğrafları Unsplash kaynaklıdır; yüklenemezse alternatif emoji görselleri kullanılır.

## Lovable / Base44 tarzı geliştirme

**Bu demo Lovable veya Base44 hesabına bağlı değildir.** Tasarım ve ürün geliştirme yaklaşımı bu platformlardan ilham alır. Gerçek mağazaya dönüştürmek için:

1. Base44 veya seçilen backend üzerinde ürün, kategori, stok, kullanıcı, sepet, sipariş, sipariş kalemi, adres ve kampanya veri modelleri oluştur.
2. Gerçek kimlik doğrulama, yetkilendirme ve yönetici paneli kur.
3. Ödeme sağlayıcısını yalnızca güvenli backend fonksiyonları üzerinden bağla. Kart bilgilerini localStorage'a kaydetme.
4. Stok, fiyat, indirim, vergilendirme ve sipariş tutarını sunucuda yeniden doğrula.
5. KVKK, mesafeli satış, kargo ve iade akışlarını tamamla.
6. Canlıya çıkmadan önce yetki, güvenlik, erişilebilirlik ve mobil uçtan uca testleri yap.

## Kaynak ve referanslar

- [Agentic Awesome Skills](https://github.com/sickn33/agentic-awesome-skills) — frontend tasarımı, QA ve erişilebilirlik kılavuzları
- [Awesome](https://github.com/sindresorhus/awesome) — geliştirici kaynak indeksleri
- [Lovable dokümantasyonu](https://docs.lovable.dev/)
- [Base44 developers](https://base44.com/developers)

## Önemli

**Bu sitede gerçek tahsilat, kargo, üyelik doğrulama veya sunucu siparişi yapılmaz.** Ürün, fiyat, yorum ve 3D modeller temsili örneklerdir. API anahtarlarını repoya yüklemeyin.
