# MacroLog

Basit, localStorage tabanlı kalori ve makro takip PWA'sı.

## Özellikler

- Kayıtlı besinler: değerler 100 g üzerinden tutulur.
- Serbest porsiyon: o öğünde yediğin toplam kcal/protein/karbonhidrat/yağ değerlerini doğrudan girebilirsin.
- Porsiyon yemek presetleri: serbest porsiyonlardan bağımsız, tekrar kullanılabilir hazır yemek kayıtları.
- Günlük kalori, protein, karbonhidrat ve yağ hedefleri.
- 02:00 gün değişimi: 00:00–01:59 arasında ana sayfa önceki gün olarak kalır.
- Haftalık görünüm: pazartesi–pazar günleri ve her günün özetleri.
- Haftadaki geçmiş günlerin kayıtlarını açma, düzenleme ve silme.
- Her yeni haftada önceki haftanın günlük kayıtları otomatik temizlenir. Kayıtlı besinler, presetler ve hedefler korunur.
- PWA / offline cache.

## GitHub Pages

Dosyaları aynı klasörde tut:

- `index.html`
- `manifest.json`
- `service-worker.js`
- `icon-192.png`
- `icon-512.png`

GitHub Pages'i repository'nin `main` branch / root klasöründen yayınlayabilirsin.

## Veri notu

Kayıtlar tarayıcının `localStorage` alanında tutulur. Tarayıcı verileri temizlenirse günlük kayıtlar da silinebilir.
