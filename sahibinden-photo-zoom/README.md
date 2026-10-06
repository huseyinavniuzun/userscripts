# Sahibinden Fotoğraf Büyütme

Sahibinden.com'daki küçük ilan fotoğrafının üzerine fareyi getirdiğinizde, fotoğrafı karartılmış bir arka plan üzerinde büyük gösterir. Fareyi fotoğraftan çekince önizleme kapanır.

## Nasıl çalışır?

- `thmb_` veya `lthmb_` içeren görsel adreslerini bulur.
- Daha büyük sürümler için `x16_`, `x5_` ve `big_` gibi adresleri sırayla dener; yüklenemeyen adreslerde sonraki seçeneğe geçer.
- Sayfaya sonradan eklenen içerikleri MutationObserver ile tarar.
- Önizleme kapandığında büyük görselin kaynağını temizler.

Yalnızca `https://www.sahibinden.com/*` adreslerinde çalışır. Görüntü kalitesi, sunucuda bulunan fotoğraf sürümleriyle sınırlıdır.

## Kurulum ve kullanım

Tampermonkey veya Violentmonkey kurduktan sonra [Greasy Fork sayfasındaki](https://greasyfork.org/tr/scripts/536346-sahibinden-foto%C4%9Fraf-b%C3%BCy%C3%BCtme) “Bu scripti kur” bağlantısını kullanın. Sahibinden.com'u açıp küçük bir ilan fotoğrafının üzerine fareyi getirin.

Kaynak: [sahibinden-photo-zoom.user.js](sahibinden-photo-zoom.user.js)

Sürüm: **1.0** · Yazar: **Hüseyin Avni UZUN** · Lisans: **MIT** (orijinal üst bilgilerde belirtildiği şekliyle).
