---
title: Prompting — Claude'la Düşünmenin Temeli
description: Claude'la etkili iletişim kurmak bir beceridir. Bu bölüm 4D Çerçevesi, prompt yapısı, ileri teknikler ve yaygın hataları kapsar.
tags:
  - prompting
  - giris
---

# Prompting

Claude'la çalışmanın en öğretilebilir becerisi. Ve en yaygın şekilde kötü kullanılan.

Çoğu kişi Claude'la başarısız olur çünkü ona **Google'a sorar gibi sorar** — kısa, anahtar kelimeli, bağlamsız. İyi bir prompt bu reflekse direnen, yapılandırılmış bir düşünce metnidir.

Bu bölüm, prompting becerisini dört açıdan kapsar: kavramsal çerçeve (4D), temel yapı, ileri teknikler ve hatalar.

## Bu Bölümdeki Sayfalar

<div class="grid cards" markdown>

-   :material-compass-outline:{ .lg .middle } **4D Çerçevesi**

    ---

    Anthropic'in resmi AI Fluency çerçevesi — Delegation, Description, Discernment, Diligence. Bütün promptingin kavramsal zemini.

    [:octicons-arrow-right-24: 4D Çerçevesi](4d-cercevesi.md)

-   :material-text-box-outline:{ .lg .middle } **Temel İlkeler**

    ---

    Bir promptun beş bileşeni: rol, bağlam, görev, format, kısıtlar. Pratik şablon ve gerçek örneklerle.

    [:octicons-arrow-right-24: Temel İlkeler](temel-ilkeler.md)

-   :material-code-tags:{ .lg .middle } **İleri Seviye**

    ---

    XML tag'leri, few-shot prompting, prompt chaining, adaptif düşünme. Temellerin üstüne inşa edilen teknikler.

    [:octicons-arrow-right-24: İleri Seviye](ileri-seviye.md)

-   :material-alert-circle-outline:{ .lg .middle } **Yaygın Hatalar**

    ---

    Çoğu kullanıcının düştüğü on tuzak ve her birinin spesifik düzeltmesi. Zamana oturumlarından damıtılmış.

    [:octicons-arrow-right-24: Yaygın Hatalar](yaygin-hatalar.md)

</div>

## Öğrenme Sırası

Bu bölümü yeni okuyorsanız:

1. **[4D Çerçevesi](4d-cercevesi.md)** — Kavramsal zemini oturtun. Neden, nasıldan önce gelir.
2. **[Temel İlkeler](temel-ilkeler.md)** — Beş bileşen yapısı. Ezberleyene kadar, bir hafta kullanın.
3. **[Yaygın Hatalar](yaygin-hatalar.md)** — Kendi promptlarınızı bu listeye karşı denetleyin.
4. **[İleri Seviye](ileri-seviye.md)** — Temelleri oturtanadık sonra. Erken dönmek boşa yatırımdır.

Bir çalışanın prompting becerisi eğitim programının birinci saatinde başlar, **haftalarca gelişmeye devam eder**. Bu bölüm bir kere okunup kapanan değil, aylar boyunca geri dönülen bir kaynaktır.

## Ana Fikir

Bölümün özeti tek cümleye indirgenirse:

> **Prompt, Claude'la konuştuğunuz metin değil — Claude'un düşünmesi için size verdiği bir çerçevedir. Çerçeveyi ne kadar iyi kurarsanız, çıktı o kadar iyi olur.**

Bu, Claude'u "sihirli kutu" olarak görmekten çok uzaktır. Claude bir düşünme ortağıdır. İyi bir düşünme ortağı, **iyi bir sohbet partneri** gerektirir. Siz o partner olursunuz.

## 4D, Temel ve İleri Arasında

Üç sayfanın ilişkisini netleştirmek gerekirse:

- **4D Çerçevesi** → **NE?** (Neye dikkat ediyorum? Ne için sorumluyum?)
- **Temel İlkeler** → **NASIL?** (Promptu pratik olarak nasıl yazarım?)
- **İleri Seviye** → **DAHA İYİ NASIL?** (Kaliteyi katlayan teknikler nelerdir?)

Üçü birlikte tam resmi verir. Biri olmadan diğeri eksik kalır — ama **temel ilkeler** zeminine basmayan ileri teknik havada kalır. Sırayı atlamayın.

## Zamana'da Prompting Öğretimi

Eğitim programında prompting birden fazla katmana yayılır:

- **1. Oturum, 2. saat:** Description'a özel pratik (4D'nin D2'si). Çalışan üç gerçek iş problemini yüksek sesle çerçevelemeyi öğrenir.
- **1. Oturum, 3. saat:** Tek bir gerçek çıktı üretmek. İlk prompt kütüphanesi girişi.
- **2. Oturum Blok 3:** Prompt Kütüphanesi genişletme (30 dakika).
- **Retainer boyunca telefonla destek:** Prompt sorunlarının çoğu iki kategoriye girer — bağlam eksikliği veya iterasyon eksikliği. İkisi de bu bölümdeki içerikle düzeltilir.

Programdan ayrılırken çalışanın elinde **30-50 promptluk kişisel bir kütüphane** olması hedefidir. Bu kütüphane, eğitimin en somut kalıntısıdır.

## Nereye Gitmeli?

Prompting'i okuduysanız:

- [**Yetenekler**](../yetenekler/index.md) — Promptların üstüne Skills, Artifacts, Agents
- [**CLAUDE.md**](../claude-md/index.md) — Her prompttan önce yüklenen kalıcı bağlam
- [**Departmanlar**](../departmanlar/index.md) — Rolünüze göre gerçek prompt örnekleri

--8<-- "retainer-cta.md"
