# Aritmetik

DersPortal tarzı, başka siteye yönlendirmeden aritmetik pratik uygulaması.

## Özellikler
- Karışık / 4 işlem / işlem önceliği / hız turu
- Zorluk ve soru sayısı
- Hız bazlı puan
- Profil ve yerel istatistikler
- Global liderlik tablosu
- Supabase yoksa otomatik yerel fallback
- GitHub Pages uyumlu

## Supabase kurulumu
1. Supabase'te bir proje oluştur.
2. SQL Editor'da `supabase/schema.sql` içeriğini çalıştır.
3. Project URL ve publishable/anon key'i `js/config.js` içine yaz.
4. GitHub Pages'te repo'yu yayınla.

> Frontend'e service_role/secret key koyma.