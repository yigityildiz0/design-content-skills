<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <img src="assets/hero-light.svg" width="1280" alt="Design &amp; Content Skills — clear questions, repeatable workflows, reviewable results">
</picture>

# Design & Content Skills

[English](README.md) · [Türkçe](README.tr.md)

![Edition](https://img.shields.io/badge/edition-2026.10.14.2-0f6e8c) [![Validate](https://github.com/yigityildiz0/design-content-skills/actions/workflows/validate.yml/badge.svg)](https://github.com/yigityildiz0/design-content-skills/actions/workflows/validate.yml) [![Release](https://img.shields.io/github/v/release/yigityildiz0/design-content-skills?display_name=tag&sort=date)](https://github.com/yigityildiz0/design-content-skills/releases/latest) ![Skills](https://img.shields.io/badge/skill-16-b0303f) ![Languages](https://img.shields.io/badge/EN%20%2B%20TR-guides-e0a43a)

**Arayüz, görsel sistem, yazı, düzenlenebilir PowerPoint sunumları, HTML slayt ve görsel/video iş akışları.**

16 bakımı sürdürülen giriş noktası. Göreve göre birini seç; tüm kütüphaneyi bağlama yükleme.

[Başla](docs/INSTALL.md) · [Katalog](https://yigityildiz0.github.io/universal-ai-skill-library/) · [İndirmeler](DOWNLOADS.md) · [Bakım modeli](MAINTAINING.md)

## Bu sürümde yeni (2026.10.14.2)

- **presentation-studio** (yeni): düzenlenebilir PowerPoint sunumu baştan sona — hoca kuralları varsayılan, slayt planı, lisanslı gerçek fotoğraflar, JS ve Python tasarım kitleri, süreli ve okunuşlu konuşmacı notları, PowerPoint render kontrolü, `pptx_audit.py` ve sunum öncesi okuma kılavuzu.
- **pdf-studio** (yeni): güvenilir PDF — önce sorular, tasarım dilleri, baskıya uygun sayfalama (bölünen tablo, yalnız kalan başlık ve taşma yok), denetim ve yapay zekâ PDF hatalarının araştırılmış listesi.
- `slides` artık **html-slides**: yalnız tarayıcı sunumları; PowerPoint istekleri presentation-studio'ya gider.
- academic-study-coach, office-docs-qa, design ve design-system sunum üretimini presentation-studio'ya devreder (kırık PPTX bağlantısı düzeltildi).
- Gemini paketleri (CLI klasörleri ve filtreli Gemini uygulaması yüklemeleri), her uygulama için kurulum tablosu ve SHA-256 özetli gerçek GitHub Release.
- Her uygulama için skill başına tek ZIP, parçalara bölünmez; masaüstü sürümünde Claude için toplu yükleme grupları var.

## Hangi uygulamada?

| Uygulama | Paket |
|---|---|
| Claude Code | taşınabilir klasör → ~/.claude/skills |
| Claude.ai | skill başına bir yükleme ZIP'i |
| Codex / ChatGPT desktop | Codex.zip → ~/.codex/skills |
| ChatGPT web | hesap içe aktarma sunuyorsa eklenti ZIP'i |
| Gemini CLI / app | ~/.gemini/skills · Skills yükleme (filtreli kopya) |
| OpenCode · DeepSeek Harness | taşınabilir klasör + skills yolu |

Ayrıntılı adımlar: [Kurulum](docs/INSTALL.md). Dosyanın diskte olması etkin olduğunu kanıtlamaz; bir örnek istekle dene.

## Yapmak istediğin işi seç

<details open>
<summary><strong>Öğrenme ve yazı</strong> · 3</summary>

| Skill | Ne işe yarar? |
|---|---|
| [office-docs-qa](docs/skills/office-docs-qa.tr.md) | Belge yapısı, içerik ve görünümü açık doğrulama sınırlarıyla kontrol eder. |
| [pdf-studio](docs/skills/pdf-studio.tr.md) | Güvenilir PDF hazırlar: önce sorular, baskıya uygun HTML/CSS ve tasarım dilleri, sayfa sayfa denetim: bölünen tablo, yalnız kalan başlık, taşma ve bozuk harf. |
| [yigit-writer](docs/skills/yigit-writer.tr.md) | Olgusal anlamı değiştirmeden açık mesaj, yazı ve akademik metin üretir/düzenler. |

</details>

<details open>
<summary><strong>Tasarım ve üretim</strong> · 13</summary>

| Skill | Ne işe yarar? |
|---|---|
| [ai-image-video-studio](docs/skills/ai-image-video-studio.tr.md) | Yerel ComfyUI dahil görsel/video üretimini planlar ve sorun giderir. |
| [banner-design](docs/skills/banner-design.tr.md) | Gerçek platform ölçüsü, okunabilir mesaj ve belirgin eylem etrafında banner tasarlar. |
| [brand](docs/skills/brand.tr.md) | Görsel kimlik, üslup ve mesajı farklı çıktılarda tutarlı tutar. |
| [campaign-plan](docs/skills/campaign-plan.tr.md) | Kitle, kanal, içerik, kaynak ve ölçülebilir sonuçlarla kampanya planlar. |
| [design](docs/skills/design.tr.md) | Tasarım işini uygun marka, arayüz, ikon, banner veya sunum akışına yönlendirir. |
| [design-system](docs/skills/design-system.tr.md) | Tasarım tokenları, bileşen özellikleri ve hedef kitleye uygun sunumları bağlar. |
| [html-slides](docs/skills/html-slides.tr.md) | Chart.js, tasarım token'ları ve duyarlı yerleşimle tarayıcıda çalışan HTML sunumlar; PowerPoint sunumları presentation-studio'ya aittir. |
| [presentation-studio](docs/skills/presentation-studio.tr.md) | Düzenlenebilir PowerPoint sunumunu baştan sona hazırlar: hoca kuralları varsayılan, slayt planı, lisanslı gerçek fotoğraflar, tasarım kiti, süreli ve okunuşlu konuşmacı notları, render kontrolü ve denetim. |
| [site-seo-audit](docs/skills/site-seo-audit.tr.md) | Öneriler uygulanmış gibi göstermeden gözlenebilir teknik/içerik SEO denetimi yapar. |
| [ui-styling](docs/skills/ui-styling.tr.md) | Projenin mevcut bileşenlerini ve tokenlarını koruyan arayüz stili uygular. |
| [ui-ux-pro-max](docs/skills/ui-ux-pro-max.tr.md) | Stil, palet, tipografi, grafik ve platform stackleri arasında tasarım bilgisi arar. |
| [web-animation](docs/skills/web-animation.tr.md) | Erişilebilirlik ve mevcut entegrasyonu koruyarak GSAP/Motion örüntüleri uygular. |
| [web-ui-design](docs/skills/web-ui-design.tr.md) | Gerçek görev, hiyerarşi, responsive düzen ve erişilebilirlik etrafında arayüz tasarlar. |

</details>

## Bir skill nasıl çalışır?

~~~mermaid
flowchart LR
 A[Your goal] --> B[Match the skill]
 B --> C[Load relevant module]
 C --> D[Use available tools]
 D --> E[Verify and explain]
~~~

Bu bir iş akışıdır; araç çalıştırıldığı veya bütün sonuçların doğrulandığı iddiası değildir. Her skill sayfasında örnek istek, tetikleme, mekanik, girdi/çıktı ve kaynak modüller var.

## Tek kaynak, kalıcı koleksiyonlar

Ana kaynak [Universal AI Skill Library](https://github.com/yigityildiz0/universal-ai-skill-library). Alan depoları aynı sürümün seçilmiş görünümleridir; ayrı ayrı çatallanıp elle düzenlenmez. Mevcut bağlantılar ve geçmiş korunur.

[All collections / Tüm koleksiyonlar](COLLECTIONS.md) · [Legacy/community resources](LEGACY.md) · [Licenses & provenance](docs/LICENSE-SCOPE.md)

## Dürüst kapsam

- Skill kurmak model eğitmek veya hesap/araç bağlamak değildir.
- Yerel dosya ile web hesabına yükleme farklıdır; desteklenen host akışını kullan.
- Ek ücretli API veya model indirme otomatik yapılmaz.
- Eski topluluk kataloğu güncel giriş noktalarının sayısına veya test iddiasına dahil değildir.
- Kaynak lisansları korunur; bütün üçüncü taraf içeriğine tek lisans varsayılmaz.

---
Maintained by [Yigit Yildiz](https://github.com/yigityildiz0) · Source edition 2026.10.14.2
