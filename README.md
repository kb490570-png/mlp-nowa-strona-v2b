# MLP – projekt poglądowy v2B „Playful, ale z klasą” (10.10.2026)

Statyczny projekt poglądowy nowej strony głównej mlp.opole.pl. Nie jest to strona produkcyjna: `noindex, nofollow`, etykieta „Projekt poglądowy”, formularz nieaktywny.

## Treści
Wszystkie teksty, liczby i opinie pochodzą z obecnej strony mlp.opole.pl (publiczne GET, kopie w ../mockup/ref/).
Liczniki (tylko fakty): 92 opinie Google („Doskonała”), Parlament Europejski od 2017, 500+ uczestników szkoleń EFS 2010–2015, 16 kursów angielskiego branżowego.
Opinie: dosłowne cytaty z widżetu opinii Google na stronie (MydłoWKostce, Jan Wyciślik).
Do uzupełnienia: godziny otwarcia (placeholder), docelowo żywy widżet opinii Google.

## Zdjęcia
- Budynek (Ozimska 63A), sala z tablicą interaktywną (`sala1_panorama4_2.jpg` – **do potwierdzenia przez MLP**), logo, odznaki – z biblioteki mediów MLP.
- Zdjęcia ilustracyjne (Unsplash License, bez podpisów sugerujących uczniów/kadrę MLP):
  - kid-sq-*.webp (hero) – Vitaly Gariev – https://unsplash.com/photos/_z2Ii760I38
  - tutor-*.webp – Vitaly Gariev – https://unsplash.com/photos/EYkx28n9Gi0
  - workshop-*.webp – Centre for Ageing Better – https://unsplash.com/photos/XH8chLuj02g
  - biz-*.webp – Vitaly Gariev – https://unsplash.com/photos/-Lzdk59aldE

## Fonty (SIL Open Font License, self-hosted, subset Latin + polskie znaki)
Bricolage Grotesque (variable, opsz 96, wght 300–800); Inter (variable).

## Technika
HTML/CSS + ~1.5 KB JS (pisane powitania, scroll-reveal, liczniki; wyłączone przy prefers-reduced-motion). WebP + srcset, preload hero.
shots/ – desktop 1440×900 i mobile 390×844 (@2x): first_screen + full_page. lighthouse/ – 3× mobile + 3× desktop (LH 12.8.2), summary.json.
