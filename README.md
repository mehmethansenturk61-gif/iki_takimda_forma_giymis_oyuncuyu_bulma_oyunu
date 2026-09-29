# ⚽ Futbolcu Tahmin Oyunu

İki kulüp gösterilir, ortak oynamış bir futbolcuyu (ipucu, çoktan seçmeli veya doğrudan yazarak) tahmin edersin. Tek kişilik pratik modu ve arkadaşınla aynı soruları çözüp skorları karşılaştırabileceğin oda kodlu çok kişilik mod içerir.

## Özellikler

- 260 kulüplük veritabanı, gerçek amblemlerle (Wikipedia + TheSportsDB üzerinden otomatik çekilir)
- Tek kişilik mod: süreye karşı, zorluk seviyesi seçilebilir (Kolay / Orta / Zor)
- Yazarak cevaplama veya 4 seçenekli çoktan seçmeli mod
- Arkadaşla oda kodu ile eşleşip aynı soruları çözme, skor karşılaştırma
- En yüksek skor, seri (streak) takibi, oyuncu profili/avatar

## Kullanılan Teknolojiler

- React (hooks: `useState`, `useEffect`, `useRef`, `useCallback`)
- [lucide-react](https://lucide.dev/) ikon seti
- Vite (geliştirme/derleme aracı)

## Kurulum ve Çalıştırma

```bash
npm install
npm run dev
```

Tarayıcıda `http://localhost:5173` adresini aç.

## Nasıl Oynanır?

1. Ana menüden **Tek Kişilik** veya **Arkadaşınla Oyna**'yı seç.
2. Ekranda gösterilen iki kulüpte birlikte oynamış bir futbolcuyu bul.
3. Yazarak ya da 4 seçenekten doğru olanı işaretleyerek cevapla.
4. Süre bitmeden ne kadar çok doğru bilirsen skorun o kadar yüksek olur.

## Katkı

Pull request'ler ve öneriler memnuniyetle karşılanır. Yeni kulüp/oyuncu eklemek için ilgili veri dizilerini (`CLUBS`, `PLAYERS`) düzenleyip PR açabilirsin.

## Lisans

Bu proje kişisel/eğitim amaçlı geliştirilmiştir. Kulüp amblemleri ilgili kulüplerin tescilli markalarıdır ve Wikipedia/TheSportsDB üzerinden çalışma zamanında (runtime) çekilir; repo içinde saklanmaz.
