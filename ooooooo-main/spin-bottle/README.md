# Spin Bottle — Güncəl tam paket

Cari önizləmənin bütün mənbə kodu, əvvəlki ekranlar, yeni kupa/liqa pəncərəsi, dörd qayda səhifəsi, üç xətt menyusu və ayarlar pəncərəsi daxildir.

## İşə salmaq

Bun quraşdırıldıqdan sonra bu qovluqda:

```sh
bun install --frozen-lockfile
bun run dev
```

Terminalda göstərilən yerli ünvanı açın. Bu mənbə paketidir; HTML faylını iki dəfə klikləməklə işləməz.

## Şəkillər və ikonlar

Bütün 211 şəkil və ikon `public/game-assets/` qovluğundadır. `src/assets/*.asset.json` fayllarının URL-ləri bu paketdə yerli fayllara yönləndirilib; şəkillər Lovable CDN-dən asılı deyil. `ASSET-MANIFEST.json` ölçüləri və SHA-256 yoxlama dəyərlərini saxlayır.

## Mövcud məhdudiyyətlər

Paket mövcud önizləmə ilə eyni funksionallığa malikdir. Canlı çoxoyunçulu xidmət, hesablar, ödənişlər və real liqa/xal sistemi qoşulmayıb. Musiqi axtarışı qoşulmamış vəziyyəti göstərir. Ayarlardakı dəvət, dostlar və əlaqə seçimləri xidmətə qoşulmayıb. YouTube iframe-i internet tələb edir.

Asılılıqlar, yaradılmış build çıxışları, şəxsi açarlar və Git tarixçəsi daxil edilməyib; asılılıqlar `bun install` ilə quraşdırılır. Host layihənin işləmə konfiqurasiyası qorunub.
