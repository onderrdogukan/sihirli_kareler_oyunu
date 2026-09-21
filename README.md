# Sihirli Kare (Magic Square) Algoritması ve Oyunu

Matematiksel kurallara dayanan, HTML5, CSS3 ve saf (Vanilla) JavaScript ile geliştirilmiş
dinamik bir sihirli kare (magic square) bulmaca ve algoritma simülasyonudur.
Bu proje, harici kütüphaneler kullanılmadan karmaşık 2D matris (array) operasyonlarının ve algoritmik validasyonların web ortamında nasıl kurgulanabileceğini göstermektedir.

## Temel Özellikler
* **Algoritmik Otonom Çözüm (Auto-Solve):** N boyutlu ızgaralar için tek sayılı (odd) ve 4'e bölünebilen çift sayılı (doubly-even) sihirli kare matrislerini
 matematiksel formüllerle anlık olarak hesaplar ve çizer.
* **Dinamik Grid Üretimi:** Kullanıcının belirlediği N boyutuna (3x3 ile 15x15 arası) göre DOM üzerinde CSS Grid mimarisiyle anlık esnek tablo üretimi.
* **Matris Validasyonu:** Satır, sütun ve çapraz eksen (diagonal) toplamlarının `m = n(n²+1)/2` formülüne uygunluğunu
 ve sayıların benzersizliğini (Set mimarisi ile) denetleyen kontrol algoritması.
* **Durum Yönetimi:** Kullanıcı etkileşimleri, hata mesajları ve ipucu (hint) sistemleri tamamen olay güdümlü (event-driven) JavaScript ile yönetilir.

## Kullanılan Teknolojiler
* **Geliştirme:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **Tasarım:** Responsive CSS Grid ve Flexbox mimarisi
* **Veri Yapıları:** 2D Arrays (Matrisler), Set (Benzersizlik kontrolü)

## Canlı Demoyu İncele
**[Projeyi Tarayıcıda Çalıştırmak İçin Tıklayın](https://onderrdogukan.github.io/sihirli_kareler_oyunu/)

---
Geliştirici: Doğukan Önder - 2026
