# MacroLog v3

LocalStorage tabanlı, offline çalışabilen MacroLog PWA.

Bu sürüm; mevcut besin/preset/günlük/haftalık kayıt mantığını koruyup öğün şablonları,
favoriler, son kullanılanlar, global arama, özel gruplar, su/lif takibi, hedefler,
Undo, notlar, haftalık istatistikler ve responsive premium arayüz ekler.

## Yayınlama
`index.html`, `manifest.json`, `service-worker.js`, `icon-192.png` ve `icon-512.png`
aynı klasörde tutulup GitHub Pages root üzerinden yayınlanabilir.

## Veri
Yeni sürüm `macrolog_v3` kullanır ve mevcut `macrolog_v2` / `macrolog_v1` verisini
mümkün olduğunca geriye dönük okuyarak korur. Veriler localStorage'dadır; düzenli
JSON yedeği alınması önerilir.
