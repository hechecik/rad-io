# rad—io · binlerce canlı radyo

*Thousands of live radio stations from around the world — Turkish & English UI.*

Dünyanın dört bir yanından **binlerce canlı radyo**, sade bir Japon estetiğiyle tarayıcında.
Kurulum yok, hesap yok. Aç, çevir, dinle.

**▶ Canlı:** https://hechecik.github.io/rad-io/

## Özellikler

- **🌐 Türkçe / English:** Tarayıcı diline göre otomatik seçilir; ülke adları her dilde yerel olarak gösterilir
- **🌍 3D dünya küresi:** Döndür, yakınlaştır, dokun ve dinle. Gerçek zamanlı gece hilali, çalan istasyonda yayın dalgası. Düz harita da istenirse tek tıkla açılır
- **🖼 Kartpostal (P):** Çalan istasyon için paylaşılabilir görsel: istasyonun üzerinde duran bir küre, şehir/ülke ve "orada gece/gündüz" bilgisi. Renkleri istasyonun o anki gün ışığına göre değişir (gece koyu, gündüz açık, şafak sıcak tonlu)
- **🚗 Araç modu (C):** Büyük dokunmatik butonlar, saat, ekranın kapanmaması (wake lock), sağa/sola kaydırarak istasyon değiştirme, tek dokunuşla favoriler; dikey ve yatay ekrana uyar
- **📶 Kopmayan yayın:** Tünelde ya da zayıf sinyalde önce aynı yayına yeniden bağlanır (3 deneme), olmazsa sıradakine geçer. İnternet kesilirse bekler, gelince kaldığı yerden devam eder
- **📡 Hoparlöre / TV'ye yayın:** Chromecast (Android Chrome) ve AirPlay (Safari) destekleniyorsa buton kendiliğinden çıkar

- **Her açılışta farklı istasyon:** Günün saatine göre bir mod seçilir (sabah kafe, gündüz çalışma, gece uyku…), istasyon da o havuzdan rastgele gelir
- **📻 Frekansı çevir:** Tek tuşla dünyanın herhangi bir yerinden rastgele canlı yayın, geçişte analog radyo paraziti
- **🗺 Canlı dünya haritası:** Binlerce istasyon haritada birer ışık noktası. Sürükle, yakınlaştır, bir noktaya dokun ve o şehri dinle; ⏭ seni komşu şehre götürür. Çalan istasyonun etrafında yayın dalgası atar
- **🌗 Gece / gündüz:** Haritada gerçek zamanlı gece gölgesi ve güneşin tepede olduğu nokta. Her istasyonda "☀ orada gündüz / ☾ orada gece / 🌅 gün doğuyor" bilgisi
- **📔 Radyo günlüğü ve pasaport:** Toplam dinleme süresi, gezilen ülke sayısı, üst üste dinlenen gün sayısı, son 7 gün grafiği, en çok dinlenen istasyonlar ve her ülke için bir pasaport damgası. Özetini tek tuşla paylaşabilirsin. Veriler yalnızca cihazında tutulur
- **📍 Yakınımdakiler:** Konumuna en yakın radyolar, yakından uzağa sıralı
- **🌍 Dünya turu:** Her 8 dakikada başka bir ülkeye geçer. Önce ülke seçilir, sonra istasyon; böylece küçük ülkeler de eşit şans alır
- **⏰ Radyolu çalar saat:** Seçtiğin saatte çalan istasyon, favorilerinden biri, kafe modu ya da dünyadan sürpriz bir yayınla, ses 60 saniyede yavaşça açılarak uyandırır
- **14 mod:** Çalışma, Kafe, Sürüş, Koşu, Uyku, Şifa, Klasik, Türkçe, Kürtçe, 90'lar, Indie, Dünya ve güneşe bağlı iki mod:
  - **◐ Şafak:** Şu an güneşin doğduğu şehirlerin radyoları, ülkeler arasında dengeli dağıtılır
  - **✶ Gece:** Dünyanın o an derin gecede olan yarısından yayınlar
- **≈ Benzerleri:** Çalan istasyonla ortak etiketi en çok olan yayınlar, aynı ülkeden olanlar önce gelir
- **İzin:** Dinlediğin yerler haritada pembe halka olarak kalır (çok dinlediğin yer daha belirgin), son dinlediklerin kesik bir çizgiyle birbirine bağlanır
- **Ülkeler:** Bayrağa dokun, o ülkenin popüler ve trend yayınları gelsin
- **Keşfet:** Trend, popüler, çok dinlenen, yeni ve rastgele sıralama; tür/dil/ülke filtreleri; arama; "daha fazla" sayfalama
- **Kitaplık:** Favoriler ve son dinlenenler cihazda kalıcı; JSON ile dışa/içe aktarma
- **Paylaş:** Her istasyonun kendi bağlantısı var (`#s=<uuid>`), açan kişi doğrudan o yayına düşer
- **Uyku zamanlayıcı:** 15 / 30 / 60 / 90 dk, sonunda sesi yavaşça kısar
- **Canlı sayaç:** Radio Browser'daki çalışan istasyon, ülke ve son 1 saatteki dinlenme sayısı
- Kilit ekranı ve kulaklık kontrolleri (Media Session), açık/koyu tema, mobil uyumlu, ana ekrana eklenebilir (PWA, 📲 yükle butonu), çevrimdışı açılır
- Yalnızca HTTPS yayınlar listelenir, böylece GitHub Pages'te "açılmayan istasyon" sorunu azalır. Açılmayan yayın otomatik atlanır

## Kısayollar

| Tuş | İşlev |
|---|---|
| `boşluk` | oynat / duraklat |
| `R` | frekansı çevir |
| `G` | dünya haritası |
| `W` | dünya turu |
| `C` | araç modu |
| `P` | kartpostal |
| `← →` | önceki / sonraki |
| `↑ ↓` | ses |
| `F` | favori |
| `M` | sessiz |
| `/` | ara |
| `D` `L` `Q` | keşfet / kitaplık / sıra |
| `T` | tema |
| `?` | yardım |

## Araçta ve telefonda

| Ortam | Durum |
|---|---|
| Bluetooth / AUX / USB ile araç teybi | ✅ Ses telefondan gelir; istasyon adı ve ülke araç ekranında görünür, direksiyondaki ⏮ ⏭ ⏯ tuşları çalışır (Media Session) |
| Kilit ekranı ve bildirim kontrolleri (Android / iOS) | ✅ Kapak görseli ile birlikte |
| Android Auto / Apple CarPlay ekranında ayrı uygulama olarak | ❌ Web uygulamaları bu ekranlarda listelenemez; Google ve Apple bunu yalnızca mağaza uygulamalarına açıyor. Telefon araç moduyla tutucuda kullanılır |
| Ana ekrana ekleme (PWA) | ✅ Android'de "yükle" butonu, iOS'ta Paylaş → Ana Ekrana Ekle |
| iOS'ta arka planda çalma | ✅ Ekran kilitliyken çalmaya devam eder (alarm hariç, o sekme açık ister) |

## Performans

- Harita verisi cihazda 12 saat önbelleklenir: tekrar açılışta ağ isteği yok
- Düz harita statik katmanı (noktalar, gece, iz) önbellekte tutulur; her karede yalnızca hazır görüntü + yayın dalgası çizilir
- Küre: önceden hesaplanmış sin/cos ile 2.500+ nokta bir karede ~0,7 ms
- Çizim döngüsü yalnızca gerektiğinde çalışır (~30 fps sınırı), sekme arka plandayken tamamen durur

## Teknik

Tek `index.html`, bağımlılık yok. Veri: [Radio Browser API](https://www.radio-browser.info/) (topluluk tarafından tutulan, 50 binden fazla istasyon).

```
index.html            uygulama
manifest.webmanifest  PWA tanımı
icon.svg              ikon
sw.js                 service worker (yalnızca uygulama kabuğu, önce ağ)
```

Yerelde çalıştırmak için: `python3 -m http.server` → http://localhost:8000

---
by [@hechecik](https://github.com/hechecik)
