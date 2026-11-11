# rad—io · binlerce canlı radyo

Dünyanın dört bir yanından **binlerce canlı radyo**, sade bir Japon estetiğiyle tarayıcında.
Kurulum yok, hesap yok. Aç, çevir, dinle.

**▶ Canlı:** https://hechecik.github.io/rad-io/

## Özellikler

- **Her açılışta farklı istasyon:** Günün saatine göre bir mod seçilir (sabah kafe, gündüz çalışma, gece uyku…), istasyon da o havuzdan rastgele gelir
- **📻 Frekansı çevir:** Tek tuşla dünyanın herhangi bir yerinden rastgele canlı yayın, geçişte analog radyo paraziti
- **🗺 Canlı dünya haritası:** Binlerce istasyon haritada birer ışık noktası. Sürükle, yakınlaştır, bir noktaya dokun ve o şehri dinle; ⏭ seni komşu şehre götürür. Çalan istasyonun etrafında yayın dalgası atar
- **🌗 Gece / gündüz:** Haritada gerçek zamanlı gece gölgesi ve güneşin tepede olduğu nokta. Her istasyonda "☀ orada gündüz / ☾ orada gece / 🌅 gün doğuyor" bilgisi
- **📔 Radyo günlüğü ve pasaport:** Toplam dinleme süresi, gezilen ülke sayısı, üst üste dinlenen gün sayısı, son 7 gün grafiği, en çok dinlenen istasyonlar ve her ülke için bir pasaport damgası. Özetini tek tuşla paylaşabilirsin. Veriler yalnızca cihazında tutulur
- **📍 Yakınımdakiler:** Konumuna en yakın radyolar, yakından uzağa sıralı
- **🌍 Dünya turu:** Her 8 dakikada başka bir ülkeye geçer. Önce ülke seçilir, sonra istasyon; böylece küçük ülkeler de eşit şans alır
- **⏰ Radyolu çalar saat:** Seçtiğin saatte çalan istasyon, favorilerinden biri, kafe modu ya da dünyadan sürpriz bir yayınla, ses 60 saniyede yavaşça açılarak uyandırır
- **12 mod:** Çalışma, Kafe, Sürüş, Koşu, Uyku, Şifa, Klasik, Türkçe, Kürtçe, 90'lar, Indie, Dünya
- **Ülkeler:** Bayrağa dokun, o ülkenin popüler ve trend yayınları gelsin
- **Keşfet:** Trend, popüler, çok dinlenen, yeni ve rastgele sıralama; tür/dil/ülke filtreleri; arama; "daha fazla" sayfalama
- **Kitaplık:** Favoriler ve son dinlenenler cihazda kalıcı; JSON ile dışa/içe aktarma
- **Paylaş:** Her istasyonun kendi bağlantısı var (`#s=<uuid>`), açan kişi doğrudan o yayına düşer
- **Uyku zamanlayıcı:** 15 / 30 / 60 / 90 dk, sonunda sesi yavaşça kısar
- **Canlı sayaç:** Radio Browser'daki çalışan istasyon, ülke ve son 1 saatteki dinlenme sayısı
- Kilit ekranı ve kulaklık kontrolleri (Media Session), açık/koyu tema, mobil uyumlu, ana ekrana eklenebilir (PWA)
- Yalnızca HTTPS yayınlar listelenir, böylece GitHub Pages'te "açılmayan istasyon" sorunu azalır. Açılmayan yayın otomatik atlanır

## Kısayollar

| Tuş | İşlev |
|---|---|
| `boşluk` | oynat / duraklat |
| `R` | frekansı çevir |
| `G` | dünya haritası |
| `W` | dünya turu |
| `← →` | önceki / sonraki |
| `↑ ↓` | ses |
| `F` | favori |
| `M` | sessiz |
| `/` | ara |
| `D` `L` `Q` | keşfet / kitaplık / sıra |
| `T` | tema |
| `?` | yardım |

## Teknik

Tek `index.html`, bağımlılık yok. Veri: [Radio Browser API](https://www.radio-browser.info/) (topluluk tarafından tutulan, 50 binden fazla istasyon).

```
index.html            uygulama
manifest.webmanifest  PWA tanımı
icon.svg              ikon
```

Yerelde çalıştırmak için: `python3 -m http.server` → http://localhost:8000

---
by [@hechecik](https://github.com/hechecik)
