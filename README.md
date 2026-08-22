# minamo-web

Minamo'nun halka açık belgelerini yayınlayan küçük site.

**Canlı adres:** <https://hb4sri.github.io/minamo-web/>
**Gizlilik politikası:** <https://hb4sri.github.io/minamo-web/gizlilik/>

Minamo, su içme takibi için bir Android uygulamasıdır. Hesap istemez, reklam
göstermez ve internet izni yoktur.

---

The small site that publishes Minamo's public documents. Minamo is an Android
app for tracking how much water you drink: no account, no ads, no internet
permission.

## Deponun düzeni

| Dosya | Ne işe yarar |
| --- | --- |
| `gizlilik.md` | Gizlilik politikası (TR + EN). |
| `index.md` | Giriş sayfası. |
| `_layouts/default.html` | Sayfa düzeni ve tema. |
| `_config.yml` | Jekyll ayarları. |
| `yazitipi/` | Yazı tipleri ve lisansları. |

`gizlilik.md`, Minamo uygulama deposundaki `docs/index.md` dosyasının **birebir
kopyasıdır.** İkisi ayrışmasın diye dosya ön bilgi (front matter) taşımaz;
sayfaya özel ne gerekiyorsa `_config.yml` içindeki varsayılanlardan verilir.
Politika değişince kaynak dosya güncellenir ve buraya olduğu gibi kopyalanır.

## Tema

Düzenin tamamı `_layouts/default.html` içinde: tek bir stil bloğu, tek bir
küçük betik. Sayfa hiçbir dış kaynağa istek atmaz, yazı tipleri burada
barındırılır. Renk paleti hb4sri.com ile ortaktır.

## Yazı tipleri

`yazitipi/` altındaki iki aile de SIL Open Font License 1.1 ile dağıtılır ve
lisans metinleri yanlarındadır:

- **Bricolage Grotesque** — `bricolage-OFL.txt`
- **SEKUYA** — `sekuya-OFL.txt`
