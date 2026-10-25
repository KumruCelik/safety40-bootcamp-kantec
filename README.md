# Safety 4.0 Bootcamp — Kantec ROBOTEGG

**Ders:** Yazılım Mühendisliğinde Güncel Konular
**Öğrenci:** Kumru Çelik
**Konu:** Bir endüstriyel makinenin emniyet (functional safety) ve siber güvenlik (IEC 62443 / CRA) açısından incelenmesi.

İncelenen makine: **Kantec Robotik Sorter & Paletleyici / ROBOTEGG**
(Yaskawa GP225 robot · Siemens PLC · 4 palet istasyonu · paslanmaz hijyenik tasarım).

> ⚠️ Bu depo bir **eğitim çıktısıdır**; resmî denetim, uygunluk değerlendirmesi veya belgelendirme değildir.
> Firmayla iletişime geçilmemiştir; tüm bilgiler internette herkese açık kaynaklardan derlenmiştir.
> "Varsayım" olarak işaretli noktalar, benzer robot hücrelerindeki yaygın uygulamadan çıkarılmıştır.

## İçindekiler

| Dosya | Açıklama |
|---|---|
| [`belgeler/Safety40_Lab_Foyleri_Kantec_ROBOTEGG.pdf`](belgeler/Safety40_Lab_Foyleri_Kantec_ROBOTEGG.pdf) | 7 laboratuvar föyü, Kantec ROBOTEGG'e uyarlanmış ve cevaplanmış (8 sayfa) |
| [`belgeler/Kantec_ROBOTEGG_SWOT.pdf`](belgeler/Kantec_ROBOTEGG_SWOT.pdf) | Makinenin SWOT analizi (tek sayfa) |

### Laboratuvar föyleri

1. **Safety Architecture** — tehlike, emniyet fonksiyonu, PLr/SIL, safe state
2. **IEC 62443 Mini Workshop** — bölge (zone) / geçit (conduit) ayrımı, uzak erişim kararı
3. **Threat & Risk + Risk Matrix** — üç senaryo, L×S×E risk puanlaması
4. **Secure Remote Access** — mevcut → hedef mimari, functional safety köprüsü
5. **SBOM / CVE / Patch** — zafiyet değerlendirme ve yama kararı
6. **CRA Incident Simulation** — olay müdahale zaman çizelgesi (24s / 72s / 14 gün)
7. **AI Safety Challenge** — görüntü işleme için fail-safe karar tablosu

## Kaynaklar

- Kantec ürün sayfaları — https://www.kantec.com.tr
- Yaskawa GP225 teknik verileri — https://www.yaskawa.ie
- Yaskawa YRC1000 / FSU (Functional Safety Unit)
- EN 415-4:2025 (paletleyiciler) · EN ISO 10218-2:2025 (robot hücreleri)
- IEC 62443, (AB) 2024/2847 CRA, 2006/42/AT ve (AB) 2023/1230 Makine mevzuatı
