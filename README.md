# minare-live

Minare uygulamasındaki "Kâbe Canlı" ekranı için Mescid-i Haram canlı yayınının (Suudi Yayın Kurumu – Kur'an-ı Kerim Kanalı, YouTube) güncel video kimliği.

- `live.json` saatte bir GitHub Actions ile YouTube Data API v3 (`search.list`, `eventType=live`) sorgulanarak güncellenir.
- Canlı yayın bulunamazsa son bilinen kimlik korunur.
- Uygulama: `https://raw.githubusercontent.com/xanapps/minare-live/main/live.json`
