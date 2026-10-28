# Bomonti Komşu

Mahall Bomonti (Halkapınar, Konak, İzmir) sakinleri için bağımsız bir portal: duyurular, canlı hava durumu, ulaşım, işletmeler, etkinlikler ve komşu panosu.

- 7 dil: Türkçe, Deutsch, English, 한국어, Español, Français, Русский
- Hava durumu: [Open-Meteo](https://open-meteo.com) (API anahtarı gerekmez, 15 dakikada bir yenilenir)
- Tek dosya: `index.html`, derleme adımı yok

## Drone videosu ekleme

`bomonti.mp4` dosyasını `index.html` ile aynı klasöre yükleyin ve `index.html` içindeki açıklamada (`Drone video:` satırı) anlatıldığı gibi `<svg class="bg">` yerine `<video>` etiketini koyun.

## İçeriği güncelleme

Duyurular, işletmeler ve metinler `index.html` içindeki `Component` bölümündedir (her dil için ayrı).

Bu site Mahall Bomonti veya Türkerler Holding ile resmi olarak bağlantılı değildir.
