# Osmanisch-Lesetrainer (YAMA)

Osmanlıca metinleri kelime kelime okuma antrenörü — beamer/derslik için tasarlandı.

## Özellikler
- Kelime kartları (tıkla-aç): Osmanlıca → transkripsiyon → anlam → imla kuralı
- Metin okuma: satır satır Osmanlıca → transkripsiyon → çeviri
- Beamer modu (büyük yazı), klavye navigasyonu (← → Space, B)
- TR/DE dil desteği, tamamen çevrimdışı, tek dosya

## İçerik ekleme (motor + içerik ayrımı)
`index.html` içindeki `<script id="icerik">` bloğunu düzenleyin.
Her ders bir nesnedir: `type:"words"` (kelime kartları) veya `type:"text"` (metin).
Koda dokunmadan yeni ders/kelime eklenebilir.

## Telif notu
İçerikteki örnekler özgün olarak hazırlanmıştır; telifli ders kitaplarından
birebir alıntı yapılmamıştır. Yeni içerik eklerken aynı ilkeye dikkat edin.
