# 🔪 Entity's Choice — Dead by Daylight Rastgele Build Üretici

Dead by Daylight için rastgele **karakter + 4 perk** üreten, oyundaki gibi **elmas dizilimli** bir web uygulaması.

### 🎮 [Canlı Dene → caramelmisto.github.io/Dead-By-Daylight-Random-Picker](https://caramelmisto.github.io/Dead-By-Daylight-Random-Picker/)

---

## ✨ Özellikler

- 🎲 **3 mod:** Tamamen Rastgele · Sadece Katil · Sadece Kurban
- 🧩 **Elmas dizilim:** 4 perk oyundaki loadout gibi elmas formunda, büyük ikonlarla
- ♻️ **Canlı tier döngüsü:** her perk otomatik **I → II → III** (sarı → yeşil → mor) döner, açıklamadaki **süreler de canlı değişir** (gerçek oyun değerleri)
- 🔒 **Seviye sabitleme:** I / II / III düğmelerine basarak döngüyü durdurup istediğin seviyede kilitleyebilirsin
- 🖱️ **Üstüne gel / dokun:** perkin **sahibi + tam açıklaması** (madde madde) açılır
- 📱 **Mobilde alt panel:** perke dokununca açıklama alttan açılır; **✕ düğmesi**, **karartılmış arka plan** veya **dışarı dokunma** ile kapanır. Panel açıkken tier döngüsü durur, yazı okurken değişmez
- 🔁 **Yeniden At:** mobilde ekranın altında sabit duran düğmeyle aynı modda yeni build
- 🌍 **TR / ENG** dil desteği (perk adları ve açıklamalar dahil)
- 🗂️ **Tam kadro:** 44 katil + 54 kurban + **301 perk** (hepsi güncel)

## 📊 Veri & Görseller

- Perk açıklamaları ve tier değerleri: [Dead by Daylight Wiki (wiki.gg)](https://deadbydaylight.wiki.gg/)
- Karakter portreleri ve perk ikonları **yerelde tutulur** — internetsiz de çalışır
- Başlık yazı tipi (Oswald) Google Fonts'tan gelir; internet yoksa sistem yazı tipine düşer, uygulama yine çalışır

## 🧩 Son eklenenler

| Karakter | Rol | Perkler |
|---|---|---|
| **The Judgment** (Yargı) | Katil | Celestial Witness · Hex: Under Your Thumb · Lay Waste |
| **Aurora Stardotter** | Kurban | Boon: Steadfast · Fruits of Your Labor · Salvation's Cry |
| **Shane Wiigwaas** | Kurban | Cross-Examination · Lend a Hand · Wide Open Throttle |

## 🛠️ Teknoloji

Saf **HTML + CSS + JavaScript** — çerçeve yok, kurulum yok. `index.html`'i açman yeterli.

### Yeni karakter nasıl eklenir?

1. Portreyi `images/killers/<slug>.png` veya `images/survivors/<slug>.png` olarak koy (512×512)
2. 3 perk ikonunu `images/perks/killers/` veya `images/perks/survivors/` altına koy (256×256)
3. `perks.json` ve `perks.js` dosyalarına perkleri ekle (`name`, `role`, `slug`, `desc`, `owner`, `desc_tr`, `name_tr`)
4. `index.html` içindeki `KILLERS` / `SURVIVORS` dizisine karakter adını ekle
5. Katilse `charTR` sözlüğüne Türkçe adını ekle

> **Slug kuralı:** küçük harf, baştaki `The ` atılır, harf/rakam dışındaki her şey `-` olur.
> `The Judgment` → `judgment` · `Salvation's Cry` → `salvation-s-cry`

## ⚖️ Yasal

Bu bir **hayran projesidir**, Behaviour Interactive ile resmi bir bağı yoktur.
Tüm karakter/perk isimleri ve ikonları **© Behaviour Interactive**'e aittir.

---

_Developed by [CaramelMisto](https://github.com/CaramelMisto) 🎮_
