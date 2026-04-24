---
title: İlk 7 Gün — Claude ile Başlangıç Rehberi
description: Claude'u işinize getirirken ilk 7 günde ne yapmalısınız. Gün gün checklist, ilk iş akışları, kaçınılması gereken hatalar.
tags:
  - temeller
  - baslangic
  - checklist
  - onboarding
---

# İlk 7 Gün — Claude ile Başlangıç Rehberi

İlk haftayı **doğru** geçirirseniz Claude'un günlük iş akışınızda kalıcı bir parçası olma ihtimali çok artar. Yanlış geçirirseniz — "denedim, işe yaramadı" grubuna katılırsınız.

Bu sayfa Zamana eğitim programlarının birinci haftasının damıtılmış halidir. Gün gün ne yapacağınızı, hangi hatalara düşmeyeceğinizi ve haftanın sonunda nerede olacağınızı anlatır.

> **Tahmini süre:** Her gün **45-90 dakika**. Çok zorlayıcı değil, ama tutarlılık şart.

---

## Gün 0 — Hazırlık (Başlamadan Önce)

Claude Desktop'ı henüz indirmeyin. Önce dört şeyi kontrol edin:

### 1. Claude Max 5x Aboneliği

[claude.ai](https://claude.ai)'da giriş yapın. Plan sayfasından **Max 5x**'e yükseltin ($100/ay).

> **Neden Pro değil, Max 5x?** İlk ay agresif keşif modundasınız — connector kuracak, skill deneyecek, uzun belgelerle oynayacaksınız. Pro'nun ($20) kullanım limiti bu ritimde birkaç saatte dolar. "Çalışmıyor" hissiyle yanlış ilk izlenim oluşur ve çoğu insan bırakır.
>
> **Max 5x bu ilk ayın sigortasıdır.** Bir ay sonra gerçek kullanım ritminiz ortaya çıkar — eğer Max 5x'te kullanıyor değilseniz Pro'ya ($20) indirirsiniz. Eğer limitlere yine de ulaşıyorsanız Max 20x'e ($200) çıkabilirsiniz.
>
> **Free ile kesinlikle başlamayın.** Cowork modu yok, kullanım limitleri çok dar.

### 2. Bilgisayar Kontrolü

- Windows 10/11 (64-bit) veya macOS 12+
- En az 8 GB RAM (16 GB tavsiye)
- Stabil internet bağlantısı

### 3. IT ile Kısa Konuşma (Şirket çalışanı iseniz)

Bireysel kendi bilgisayarınızda kuruyorsanız bu adım atlanır. Şirket bilgisayarında çalışıyorsanız IT'den şunları isteyin:

- Anthropic domain'lerini whitelist yapmaları: `claude.ai`, `anthropic.com`, Claude Desktop backend endpoint'leri
- Claude Desktop kurulumuna izin vermeleri (yönetici hakkı veya ön-onay)
- Eğer VPN kullanıyorsanız, Claude Desktop ile uyumluluğu test etmeleri

### 4. Workspace Klasörü Seçimi

Bilgisayarınızda Claude'un çalışacağı gerçek klasör. Önerilenler:

- **Windows:** `C:\ClaudeWorkspace\`
- **macOS:** `~/ClaudeWorkspace/`

**OneDrive / Google Drive / iCloud içine koymayın** — senkronizasyon çakışmaları yaşayabilir. Yerel disk en iyisi.

---

## Gün 1 — Kurulum ve İlk Konuşma (45 dk)

**Amaç:** Claude Desktop çalışır halde, Cowork açık, ilk sohbeti yapmış olmak.

### Adımlar

1. [claude.ai](https://claude.ai) → **Download** → işletim sisteminize uygun sürümü indirin (10 dk)
2. Kurulum adımlarını izleyin (5 dk)
3. Claude hesabınızla giriş yapın (2 dk)
4. **Cowork modunu etkinleştirin** (Settings'den) (3 dk)
5. **Workspace klasörünüzü bağlayın** — Gün 0'da seçtiğiniz klasör (2 dk)
6. İlk konuşma: Claude'a kendinizi tanıtın (10 dk)

### İlk Konuşma Örneği

> *"Merhaba. Ben [Ad], [Şirket]'te [Pozisyon] olarak çalışıyorum. [Sektör] alanındayız, [ürün/hizmet] yapıyoruz. Türkçe konuşuyorum. Şimdilik sadece seni tanımak istiyorum — bana kendini tanıt ve işimde en çok hangi konularda yardımcı olabileceğini söyle."*

Claude'un cevabını okuyun. Tonunu, detay seviyesini gözleyin. Ne kadar kişiselleştirilmiş olduğuna dikkat edin (**çok değil** — çünkü CLAUDE.md yok henüz).

### Gün 1 Sonunda Nerede Olmalısınız

- ✅ Claude Desktop yüklü ve açık
- ✅ Cowork modu aktif
- ✅ Workspace klasörü bağlı
- ✅ Bir tanışma konuşması yapılmış

---

## Gün 2 — CLAUDE.md Yazımı (60 dk)

**Amaç:** Kalıcı hafıza dosyanızı kurmak — Claude artık her oturumda sizi tanıyacak.

Detaylı rehber: [CLAUDE.md Nasıl Yazılır?](../claude-md/nasil-yazilir.md)

### Adımlar

1. Workspace klasörünüzün kök dizininde `CLAUDE.md` adlı boş dosya oluşturun (2 dk)
2. VS Code veya Notepad ile açın (1 dk)
3. [CLAUDE.md Nasıl Yazılır sayfasındaki şablonu](../claude-md/nasil-yazilir.md) kopyalayın (2 dk)
4. Kendi bilgilerinizle doldurun — 5 bölümü atlamayın (45 dk)
5. Rolünüze en yakın [örnekten](../claude-md/ornekler.md) 2-3 fikir alın (10 dk)

### Günün Sonunda Test

Cowork'ü açın. Sorun:

> *"CLAUDE.md dosyamı okudun. Beni kısaca özetle — kim olduğumu, ne iş yaptığımı, nasıl çalışmayı tercih ettiğimi."*

Claude özeti çıkarsın. Yanlış veya eksik bir şey varsa CLAUDE.md'ye geri dönüp düzeltin.

### Gün 2 Sonunda Nerede Olmalısınız

- ✅ CLAUDE.md yazılı (en az 80 satır)
- ✅ Claude sizi doğru biçimde özetleyebiliyor
- ✅ Ton tercihleriniz, "her zaman/asla" kurallarınız dosyada

---

## Gün 3 — İlk Gerçek İş Çıktısı (90 dk)

**Amaç:** Bugün Claude'la **gerçek bir işinizi** halledin. Hayali bir egzersiz değil — gerçekten elinizde olan bir şey.

### Adımlar

1. Bu hafta yapmanız gereken gerçek bir işi seçin — tercihen yazılı bir çıktı (5 dk)
   - Teklif yazısı
   - Rapor özeti
   - Müşteri e-postası
   - Politika taslağı
   - Sunum planı

2. Claude'a tam bağlamla getirin: (15 dk)
   - Ne istediğinizi açık tarif edin
   - Hedef kitle, uzunluk, ton, kısıtlar
   - [Prompting Temel İlkeleri](../prompting/temel-ilkeler.md) 5 bileşen yapısını takip edin

3. İlk çıktıyı alın. Okuyun. (10 dk)

4. **Zamana altın kuralı:** Çıktıya bakıp *"Bunu şu an müdürüme göndermeye razı mıyım?"* sorun. (2 dk)

5. Hayırsa iterasyon yapın — spesifik geri bildirim: (30 dk)
   - "İkinci paragraf zayıf, şunu ekle..."
   - "Ton çok resmi, biraz yumuşat"
   - "Kapanış çok uzun, tek cümleye indir"

6. Son çıktıyı gerçekten gönderdiğiniz yere gönderin (15 dk)

7. Prompt'u kaydedin — Gün 5'te "prompt kütüphanesi"nin ilk girdisi olacak (5 dk)

8. Not tutun: Bu iş Claude olmadan kaç dakika sürerdi? Şimdi kaç dakika sürdü? (5 dk)

### Gün 3 Sonunda Nerede Olmalısınız

- ✅ Gerçek bir iş Claude'la bitmiş
- ✅ İterasyon deneyimi yaşanmış
- ✅ İlk prompt saklanmış
- ✅ Tasarruf edilen süre ölçülmüş

---

## Gün 4 — İlk Skill ve İlk Connector (60 dk)

**Amaç:** Cowork'ün iki gücüyle tanışın — skills ve connector'lar.

### Bölüm A: Skill (30 dk)

Bir Word, Excel veya PowerPoint dosyası üretmek gerekiyorsa:

1. Cowork'te `/` yazın. Skill listesi açılır
2. `docx`, `xlsx` veya `pptx` seçin
3. Ne istediğinizi tarif edin — Claude ilgili skill'i çağırıp profesyonel dosya üretir
4. Workspace klasörünüze bağlantı verir, tıklayıp açın

Detay: [Skills](../yetenekler/skills.md)

### Bölüm B: İlk Connector (30 dk)

Rolünüze en uygun connector'u kurun — [MCP Bağlantı Listesi](../mcp/baglanti-listesi.md)'nden seçin:

- Satış: **CRM** (Salesforce / HubSpot)
- Pazarlama: **Google Workspace** veya **Slack**
- Finans: **Microsoft 365 / Google Sheets**
- İK: **Microsoft 365**
- Yönetici Asistanı: **Microsoft 365**
- Operasyon: **Slack** veya **Asana**
- Diğer: en çok kullandığınız ofis paketi

Kurulum:

1. Cowork → **Customize** → Connector seçin → **Install**
2. OAuth ile giriş yapın (tarayıcı açılır, onay verirsiniz)
3. İzin onaylarını yapın
4. Test: Claude'a *"[connected service] içinde bakabiliyor musun?"* diye sorun

### Gün 4 Sonunda Nerede Olmalısınız

- ✅ Bir skill kullanıp gerçek bir dosya üretmiş
- ✅ Bir connector kurulu ve çalışır halde
- ✅ Claude ile şirket araçlarınızı birleştirmiş

---

## Gün 5 — Prompt Kütüphanesi Başlangıcı (45 dk)

**Amaç:** Çalışmış promptlarınızı kaydetmeye başlamak. Uzun vadeli değerin temeli.

### Adımlar

1. Workspace klasörünüzde yeni bir klasör: `prompts/` (1 dk)
2. Gün 3'teki prompt'u bir Markdown dosyasına kaydedin (10 dk)
   - Dosya adı: `teklif-yazisi.md` gibi
   - İçine: başlık, tam prompt metni, kullanım notu, son kullanım tarihi
3. Son 4 günde çalıştığı sırada farkettiğiniz 3-5 prompt daha ekleyin (25 dk)
4. Bir `README.md` yazın — kütüphanenizdeki dosyaların listesi (5 dk)

### Pratik Prompt Şablonu

```markdown
# Prompt: Tedarikçi Reddi Mektubu

## Ne Zaman
Bir tedarikçi teklifini uygun bulmadığımız ama gelecekte müzakere
kapısını açık tutmak istediğimiz durumlarda.

## Prompt
"Sen profesyonel bir tedarikçi ilişkileri yöneticisisin. [TEDARİKÇİ]
firmasından gelen [ÜRÜN] teklifini reddetmem gerekiyor. Teklif fiyatı
[FİYAT] ama bütçemiz [BÜTÇE]. Tedarikçi 2 yıllık iyi bir ilişkimiz
var. 30 gün sonra yeniden müzakereye açık olacağımızı ima eden,
ilişki-koruyucu, 150 kelimeyi geçmeyen profesyonel Türkçe bir yanıt
yaz."

## Değişkenler
- TEDARİKÇİ
- ÜRÜN
- FİYAT
- BÜTÇE

## Notlar
İlk çıktı genellikle iyi. Eğer ton sert çıkarsa "daha yumuşak olsun
ama güç kaybetme" diye iterasyon.

## Son Güncelleme: 2026-04-25
```

### Gün 5 Sonunda Nerede Olmalısınız

- ✅ `prompts/` klasörü hazır
- ✅ En az 3 prompt kaydedilmiş
- ✅ Prompt şablonu alışkanlığa dönüşmüş

---

## Gün 6 — Yaygın Hatalar ve İterasyon (45 dk)

**Amaç:** Bir hafta sonra düşecek tuzaklardan haberdar olmak.

Bugün iş yapmıyoruz — **öğreniyoruz**. [Yaygın Prompting Hataları](../prompting/yaygin-hatalar.md) sayfasını tamamen okuyun.

### Öz-Değerlendirme

Son 5 günde yaptığınız konuşmalara geri dönün. Şu sorularla:

- [ ] Google-tarzı kısa prompt yazdığım oldu mu?
- [ ] Bağlamsız soru sordum mu?
- [ ] Tek atışlık zihniyet mi, yoksa iterasyon mu?
- [ ] Format belirtmeyi unuttum mu?
- [ ] "Bunu müdüre gönderir miydim" testinden geçmemiş çıktıyı kabul ettim mi?

Her "evet" için o prompt'u geri dönün ve iyileştirin. Yeni versiyonu prompt kütüphanenize ekleyin.

### Gün 6 Sonunda Nerede Olmalısınız

- ✅ 10 yaygın hataya hakim
- ✅ Kendi hatalarınızın farkında
- ✅ Prompt kütüphaneniz 5+ girdiye ulaştı

---

## Gün 7 — Refleksiyon ve İkinci Hafta Planı (60 dk)

**Amaç:** Haftayı değerlendirmek ve sonraki hafta için net hedef koymak.

### Refleksiyon Soruları (30 dk)

Kendinize yazılı cevap verin:

1. Bu hafta Claude'la yaptığım **en değerli iş** neydi?
2. En çok **zaman tasarrufu** hangi işte oldu? Dakika bazında ölç.
3. En çok **zorlandığım** nokta neydi? Hangi becerimi geliştirmem lazım?
4. CLAUDE.md'mde **hangi eksiği** farkettim?
5. **Hangi iş akışımı** Claude'a geçirmekten hoşlanırdım?
6. **Bir tane** scheduled task otomatize etmek istersem ne olur?

### İkinci Hafta Hedefi

Cevaplarınıza bakıp **üç spesifik hedef** yazın:

```
İkinci hafta hedeflerim:
1. [Belirli bir iş akışı]'nı Claude'a geçireceğim.
2. Prompt kütüphanemi [X]'ten [Y]'ye çıkaracağım.
3. [Bir skill veya connector]'u denemek istiyorum.
```

Bu hedefleri CLAUDE.md'nize **"Güncel Odak"** bölümüne ekleyin — bir sonraki oturumda Claude size hatırlatır.

### Gün 7 Sonunda Nerede Olmalısınız

- ✅ Net haftalık refleksiyon yapılmış
- ✅ Ölçülebilir ikinci hafta hedefleri belirlenmiş
- ✅ CLAUDE.md güncellenmiş

---

## Bir Haftalık Özet

Yedi gün sonunda elinizde olması gerekenler:

| Bileşen | Durum |
|---|---|
| Claude Desktop + Cowork çalışır halde | ✅ |
| CLAUDE.md tam | ✅ |
| Workspace klasörü organize | ✅ |
| En az bir skill kullanılmış | ✅ |
| En az bir connector kurulu | ✅ |
| Prompt kütüphanesi (5+ girdi) | ✅ |
| 10 yaygın hata bilgisi | ✅ |
| Haftalık refleksiyon | ✅ |
| İkinci hafta hedefleri | ✅ |

Bu liste tamamsa — **bir sonraki seviye için hazırsınız**.

## Ne Yapmamalısınız?

Bir haftada sık yapılan hatalar:

- **Her şeyi bir günde yapmaya çalışmak.** 7 günü 7 güne yaydık sebepten.
- **Gerçek iş yapmamak.** "Hazır olunca başlarım" → hiç başlayamamak.
- **CLAUDE.md'yi atlamak.** Skill'lerden, connector'lardan önce kimlik dosyası gerekir.
- **Bağlamsız prompt yazmak.** Google'a sorar gibi sormak, "genel" cevap almak, "Claude iyi değil" demek.
- **İlk çıktıyı son çıktı saymak.** İterasyon yok.
- **Hataları düzeltmemek.** Yaygın Hatalar sayfasını okumamak.

## Sonraki Adımlar

İlk 7 gün tamam. Şimdi ne?

- **İkinci hafta:** Bir iş akışını tam Claude-destekli yapın. Prompt kütüphaneniz büyüsün.
- **Üçüncü hafta:** Scheduled Task kurun. Haftalık bir raporu otomatize edin.
- **Dördüncü hafta:** Kendi departmanınızın derin uygulamalarına geçin — [Departmanlar](../departmanlar/index.md) sayfası.
- **Ayın sonunda:** Kaç saat kazandığınızı ölçün. Sizin için en değerli kullanım senaryolarını CLAUDE.md'nin "Güncel Odak" bölümüne taşıyın.

Claude bir hafta sonra aracınız; bir ay sonra meslektaşınız; üç ay sonra ekip üyeniz olur. İlk 7 gün bunun temelidir.

## İlgili Sayfalar

- [CLAUDE.md Nasıl Yazılır?](../claude-md/nasil-yazilir.md) — 2. gün için detaylı rehber
- [Prompting Temel İlkeleri](../prompting/temel-ilkeler.md) — 3. gün için prompt yapısı
- [Yaygın Prompting Hataları](../prompting/yaygin-hatalar.md) — 6. gün okuması
- [Claude Planları](planlar.md) — Gün 0 için plan detayları
- [Sık Sorulan Sorular](sss.md) — Kalan tüm sorularınız

--8<-- "retainer-cta.md"
