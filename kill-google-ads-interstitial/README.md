# Kill Google Ads Interstitial (INS Overlay)

Sayfanın üstünü kaplayıp tıklamayı engelleyebilen Google reklam katmanlarını kaldırır. Kimliği `gpt_unit_` ile başlayan `<ins>` öğelerini hedefler.

## Nasıl çalışır?

- Sayfa açılırken ve DOMContentLoaded olayında ilgili öğeleri temizler.
- MutationObserver ile sonradan eklenen öğeleri izler ve eşleşenleri kaldırır.
- Temizlik sırasında hedef öğelerin tıklama yakalamasını ve görünmesini de engeller.

`*://*/*` kapsamıyla tüm web sitelerinde çalışır. Genel amaçlı bir reklam engelleyici değildir; yalnızca belirtilen INS öğelerini hedefler. Kod, bu kimlikle eşleşen tüm INS öğelerini kaldırır; tam ekran olup olmadıklarını ayrıca kontrol etmez.

## Kurulum ve kullanım

Tampermonkey veya Violentmonkey kurduktan sonra [Greasy Fork sayfasındaki](https://greasyfork.org/tr/scripts/560987-kill-google-ads-interstitial-ins-overlay) “Bu scripti kur” bağlantısını kullanın. Betik etkin olduğunda temizleme otomatik yapılır; ek bir düğme veya ayar yoktur.

Kaynak: [kill-google-ads-interstitial.user.js](kill-google-ads-interstitial.user.js)

Sürüm: **1.0** · Yazar: **Hüseyin Avni Uzun** · Lisans: **MIT** (orijinal üst bilgilerde belirtildiği şekliyle).
