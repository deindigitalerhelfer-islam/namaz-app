# 🕌 Namaz Vakti & Kıble v6

GPS tabanlı namaz vakitleri, kıble pusulası, tesbih takibi ve dua kitaplığı.

## Özellikler
- 🕐 Anlık namaz vakitleri (Aladhan API — Diyanet metodu)
- 🧭 Gerçek zamanlı kıble pusulası (cihaz sensörü)
- 📿 Dijital tesbih + haftalık/aylık istatistik
- 📅 İmsakiye tablosu (aylık)
- 🤲 Dua kitaplığı (sabah/akşam/namaz duaları)
- 📖 Namaz rehberi (adım adım)
- ☀️ Canlı hava durumu (Open-Meteo API)
- 🎨 8 tema: 5 koyu (Medine, Gece, Kabe, Osmanlı, Endülüs) + 3 açık (Sabah, Sedef, Krem)
- 💾 Yedekleme & Geri Yükleme (JSON)
- 📱 QR Kod kurulum yardımcısı
- 🌐 3 dil: Türkçe, Deutsch, العربية
- 📲 PWA — Ana ekrana eklenebilir

## Kurulum (Netlify — Ücretsiz)
1. [netlify.com](https://netlify.com) → yeni hesap aç
2. "Deploy manually" → `index.html` dosyasını sürükle bırak
3. Verilen HTTPS adresini al: `https://xxx.netlify.app`
4. Android Chrome → ⋮ → **"Ana ekrana ekle"**
5. iOS Safari → Paylaş → **"Ana Ekrana Ekle"**

## Kurulum (GitHub Pages — Ücretsiz)
1. [github.com](https://github.com) → yeni repo: `namaz-app`
2. `index.html` dosyasını yükle
3. Settings → Pages → Branch: main → Save
4. `https://KULLADIADIN.github.io/namaz-app` adresinden aç

## Teknik
- Tek dosya HTML/CSS/JS (bağımlılık yok)
- API: Aladhan (namaz), Open-Meteo (hava), Nominatim (şehir adı)
- PWA: Service Worker + Web Manifest
- Offline: SW cache (HTTPS gerekir)

## İthaf
Merhum Hacı Hamit Sert ve merhume Hacı Nurgüzel Sert'in ve Bakıcı Ailelerinin ruhlarına ithaf edilmiştir. 🤲
