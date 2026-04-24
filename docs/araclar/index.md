---
title: Araçlar — Claude'u Nerede Kullanırsınız?
description: Claude'un yedi farklı kullanım aracı — Claude Chat, Projects, Desktop, Cowork, Dispatch, Scheduled Tasks, Voice Mode. Her biri ne zaman doğru seçim?
tags:
  - araclar
  - giris
---

# Araçlar

**Claude'u kullanmanın birden fazla yolu var. Hangisinin hangi iş için doğru olduğu, üretkenlikte ciddi fark yaratır.**

Bu bölüm Claude'un yedi temel aracını tanıtır. Her biri farklı bir senaryo için vardır; hepsini ayrı ayrı bilmek, doğru iş için doğru aracı seçmenizi sağlar.

## Tüm Araçlar Tek Bakışta

<div class="grid cards" markdown>

-   :material-chat-outline:{ .lg .middle } **Claude Chat**

    ---

    Tarayıcı ve mobil uygulamada standart konuşma arayüzü. Hızlı sorular, belge yükleme, web araması.

    [:octicons-arrow-right-24: Claude Chat](claude-chat.md)

-   :material-folder-multiple-outline:{ .lg .middle } **Projects**

    ---

    Claude Chat içindeki kalıcı çalışma alanları. Bilgi tabanı + özel talimatlar + ekip paylaşımı.

    [:octicons-arrow-right-24: Projects](projects.md)

-   :material-desktop-classic:{ .lg .middle } **Claude Desktop**

    ---

    Windows ve macOS için yerel uygulama. Cowork'ün ve tüm ileri özelliklerin giriş kapısı.

    [:octicons-arrow-right-24: Claude Desktop](claude-desktop.md)

-   :material-robot-industrial-outline:{ .lg .middle } **Cowork Modu**

    ---

    Claude'u sohbet arayüzünden tam bir çalışma ortamına dönüştüren mod. Dosyalar, kod, connector'lar.

    [:octicons-arrow-right-24: Cowork Modu](cowork-modu.md)

-   :material-cellphone-link:{ .lg .middle } **Dispatch**

    ---

    Telefonunuzdan masaüstü Cowork'e görev atamanın yolu. Siz toplantıdayken Claude çalışır.

    [:octicons-arrow-right-24: Dispatch](dispatch.md)

-   :material-calendar-clock:{ .lg .middle } **Scheduled Tasks**

    ---

    Her Pazartesi rapor, her sabah brifing — zamanlanmış görevler siz başlatmadan çalışır.

    [:octicons-arrow-right-24: Scheduled Tasks](scheduled-tasks.md)

-   :material-microphone-outline:{ .lg .middle } **Voice Mode**

    ---

    Yazmak yerine Claude'la konuşarak etkileşim. Yolda, yürürken, eller serbest.

    [:octicons-arrow-right-24: Voice Mode](voice-mode.md)

</div>

## Hangi Araç Ne Zaman?

Başlangıç için basit bir karar ağacı:

| Durumunuz | Doğru araç |
|---|---|
| Hızlı bir soru sormak, bir fikir sınamak | **Claude Chat** |
| Ekipçe aynı bağlamla çalışılacak bir proje | **Projects** (Team planında paylaşımlı) |
| Gerçek iş çıktıları üretmek (Word, Excel, PPT) | **Claude Desktop + Cowork** |
| Şirket araçlarına bağlanmak (Slack, Drive, CRM) | **Cowork + connector'lar** |
| Yolda telefondan iş atmak, masada bitmiş bulmak | **Dispatch** |
| Tekrar eden haftalık/aylık bir görevi otomatikleştirmek | **Scheduled Tasks** |
| Yazmaktansa konuşmayı tercih ediyorsanız | **Voice Mode** |

## İki Temel Ayrım

Araçlar kavramsal olarak iki gruba ayrılır:

### 1. Chat Tabanlı (Claude Chat + Projects + Voice Mode)

Tarayıcı veya mobil uygulamada yaşar. Kurulum gerektirmez. Belge yükleme, konuşma geçmişi, web araması gibi özellikler vardır — ama **yerel dosyalarınıza erişmez, otomasyon yapmaz, skill kullanmaz**.

Hızlı iş, mobil kullanım, ekiple paylaşılan kalıcı bağlam için güçlüdür.

### 2. Cowork Tabanlı (Desktop + Cowork + Dispatch + Scheduled Tasks)

Claude Desktop kurulumu gerektirir ve Claude Pro aboneliğine dayanır. **Yerel dosyalara erişir, kod çalıştırır, skills ve plugins kullanır, connector'lar ile şirket araçlarınıza bağlanır, zamanlanmış görevler oluşturur.**

Gerçek iş akışları burada kurulur. Zamana eğitim programının büyük kısmı bu tarafta ilerler.

## Zamana'nın Aracı Kullanma Yolu

Çalışan tipik olarak şu sırayı izler:

1. **Hafta 1 (Oturum 1):** Claude Desktop kurulur → Cowork açılır → CLAUDE.md yazılır → ilk gerçek iş çıktısı üretilir
2. **Hafta 2 (Oturum 2):** Role göre skill'ler ve plugin'ler tanıtılır → ilk connector kurulur (Slack, Drive veya CRM)
3. **Hafta 3-4:** Dispatch kurulumu → ilk zamanlanmış görev (haftalık rapor)
4. **Ay 2-3:** Prompt kütüphanesi büyür, iş akışlarının 2-3 tanesi tamamen otomatikleşir, çalışan işi yeniden tasarlar

Bu sıra tesadüfi değil. Önce temel, sonra genişleme, en sonda otomasyon — öğrenme eğrisini doğal akışta tutan bir dizilim.

## Nereye Gitmeli?

Araçları tanıdıysanız:

- [**CLAUDE.md**](../claude-md/index.md) — Cowork'ü gerçekten etkili kılan kalıcı hafıza dosyası
- [**Prompting**](../prompting/index.md) — Araç ne olursa olsun, iyi prompt yazabilmek
- [**Yetenekler**](../yetenekler/index.md) — Cowork içinde Skills, Artifacts, Agents

--8<-- "retainer-cta.md"
