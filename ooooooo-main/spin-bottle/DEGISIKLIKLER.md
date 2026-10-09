# Güncel sürüm v6 — yapılanlar

## Yeni özellikler
- **Hediye ekranı** (`src/components/gift-drawer.tsx`, `src/lib/reference-gifts.ts`): videodaki gibi alttan açılır, 135 hediye, 5 sütun, kilitli hediyelerde kilit simgesi, seçilince hafif büyür.
- **Profil popup'ı** (`src/components/player-profile.tsx`): ortadaki ok ile açılan ek istatistikler (kalp 30, çift kalp 8), beğenen kişisi ve alttaki aksiyon düğmeleri.
- Oyuncu fotoğraflarına tıklayınca hediye ekranı açılır (`src/routes/index.tsx`).

## Hediye ekranı yerleşimi
- "hediye gönder" çubuğu masanın üst kenarının üzerine oturur, masa aşağı itilmez.
- Hediye ekranı açılınca yukarıdaki hiçbir şey küçülmez (`--table-h` sabit).
- Hediyeler bölümü bir sıra daha büyük açılır.

## Müzik oynatıcısı
- Sohbetin sağ üst köşesinde, resimdeki boyut ve yerleşimde (`src/styles.css` içindeki `.chat-area .chat-music-player` kuralları).

## Sayfa kilidi
- Aşağı/yukarı kaydırma, zoom ve pinch engelli (`src/routes/__root.tsx` + `src/styles.css`); sohbet ve hediye listesi kendi içinde kaydırılabilir.

## İkonlar
- Orijinal 45 ikon ve pointer dosyaları **birebir aynı**, değiştirilmedi.
- Yeni 135 hediye ikonu `public/game-assets/gifts/`, 13 profil ikonu `public/game-assets/profile/` içinde; pointer dosyaları `src/assets/` içinde eklendi.
- Ahşap masa dokusu `src/styles.css` içinde `/game-assets/wood.png` adresinden okunur.

## Bu yeniləmədə əlavə edilənlər
- Kupa (liqa) pəncərəsi: "Dəmir liqa" + "?" ilə 4 qayda səhifəsi (Azərbaycan dilində, oxlar və nöqtələr).
- Üç xətt menyusu: Nailiyyətlər, Reytinqlər, Şüşə, Görünüş, Gücləndiricilər.
- Ayarlar pəncərəsi: Səslər, Musiqi, Dostları dəvət et, Dostlarım, Bizimlə əlaqə.
- Bütün 211 ikon/şəkil public/game-assets/ qovluğunda (ASSET-MANIFEST.json ilə).
- Orijinal v6 paketindəki bütün fayllar (original-spin-bottle-game.zip daxil) saxlanıb.
