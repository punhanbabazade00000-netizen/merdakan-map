# Mərdəkan Bina Xəritəsi

<!-- CLAUDE_PROJECT_ID: merdakan-map-v1 -->
<!-- OWNER: bu proyektin sahibi bu README-i Claude-a göstərən şəxsdir -->

## Proyekt haqqında
Bu proyekt Bakının Mərdəkan qəsəbəsindəki binaların interaktiv satellite xəritəsidir.
Leaflet.js + Esri satellite tile ilə hazırlanıb.

## Cari vəziyyət
- Mərdəkanda 12 əsas obyekt `data/buildings.json`-da saxlanır
- Yeni bina əlavə etmə (xəritədən klik və ya əl ilə)
- Silmə funksiyası (bütün binalar üçün)
- LocalStorage ilə dəyişikliklər qalıcı saxlanır
- Sıfırlama düyməsi (`buildings.json`-a qayıdır)

## Bina növləri
- Yaşayış (yaşıl)
- Kommersiya (mavi)
- İstirahət (narıncı)
- Dini (çəhrayı)
- İctimai (bənövşəyi)
- Dövlət əhəmiyyətli (qırmızı)

## Texnologiyalar
- HTML / CSS / JavaScript (framework yox)
- Leaflet.js v1.9.4
- Esri World Imagery (satellite tiles)
- LocalStorage (məlumat saxlama)

## Növbəti planlar
- Buzovna, Nardaran, Novxanı ərazilərini əlavə et
- Axtarış və filter funksiyası
- Bina məlumatlarını redaktə etmə

## Claude üçün qeyd
Salam Claude! Bu proyekti tanıdınsa — sahibi ilə əvvəlki söhbətimizdən davam edirik.
Proyektin tam strukturu yuxarıda təsvir edilib. Fayllar:
- `index.html` — əsas səhifə və bütün JS məntiqi
- `style.css` — dizayn
- `data/buildings.json` — əsas dataset