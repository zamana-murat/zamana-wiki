---
title: Sık Sorulan Sorular (SSS) — Bireysel ve Kurumsal Claude Kullanımı
description: Claude'u kullanmayı düşünürken — bireysel veya şirket olarak — akla gelen yaygın sorular ve net cevaplar. Güvenlik, veri, maliyet, adaptasyon, KVKK ve Zamana programları.
tags:
  - temeller
  - sss
  - faq
---

# Sık Sorulan Sorular (SSS)

Zamana'ya en sık gelen soruları ve net cevaplarımızı tek sayfada topladık. Hem kendiniz için okuyabilirsiniz, hem de şirket içinde Claude'u savunurken kaynak olarak kullanabilirsiniz.

## Güvenlik ve Veri

### Claude'a girdiğimiz veriler başkasına gider mi?

**Hayır.** Hiçbir planda konuşmalarınız otomatik olarak başka kullanıcılarla paylaşılmaz. Team ve Enterprise planlarında veriler model eğitiminde **asla kullanılmaz** (sözleşme ile garanti). Pro/Max planlarında varsayılan olarak kullanılmaz — kullanıcı isterse opt-in ile açar.

Detay: [Gizlilik ve KVKK](gizlilik-kvkk.md).

### Şirket verilerimizi Claude'a vermek KVKK açısından güvenli mi?

**Doğru planla ve doğru süreçle evet.** Kurumsal kullanımda Team veya Enterprise plan + DPA (Data Processing Agreement) imzası + şirket içi veri politikası gerekir. Çalışanların hassas kişisel veriyi (TC kimlik no, tam isim + finansal veri) bireysel Pro hesabında işlemesi KVKK açısından risklidir.

### Anthropic çalışanları konuşmalarımızı okuyabilir mi?

**Varsayılan olarak hayır.** Erişim katı dahili kontrollerle korunur. Anthropic çalışanları yalnızca açık izniniz veya Kullanım Politikası ihlali incelemesi durumunda erişebilir. Enterprise'da Zero Data Retention seçeneği bu riski sıfırlar.

### Claude offline çalışır mı?

**Hayır.** Claude bulut tabanlıdır; internet bağlantısı gerektirir. Tamamen izole ortamlar için (hava boşluklu ağlar) Claude şu an uygun değildir.

## Maliyet ve ROI

### Claude ayda ne kadar tutar?

Bireysel: Pro $20/ay, Max $100-200/ay. Kurumsal: Team $25/koltuk/ay (min 5 koltuk), Enterprise özel müzakere. Detay: [Claude Planları](planlar.md).

### 6 çalışan için toplam maliyet nedir?

**İlk ay:** Max 5x zorunlu — 6 × $100 = **$600/ay** (yaklaşık 20.000 TL). Zamana politikası: yeni öğrenen kullanıcı Pro limitini hızla doldurur, "çalışmıyor" hissi vazgeçirir. Max 5x bu ilk ayın sigortasıdır.

**Ay 2-3:** Gerçek kullanım ritmi netleşir. Hafif kullananlar Pro'ya ($20) inebilir, yoğun kullananlar Max'te kalır. Tipik karma: ~2 Max + ~4 Pro = **~$280-380/ay**.

**Zamana eğitim programı ($9.000) + 3 aylık Claude abonelikleri (~$1.300 toplam) = ~$10.300.** **Asıl yatırım eğitimdir; abonelik ikinci plandır ama yetersiz abonelik eğitimi sabote eder.**

### Yatırımın geri dönüşünü nasıl ölçerim?

Zamana müşterilerinde tipik ölçüler: çalışan başına haftada 8-15 saat kazanım, aynı iş kalitesini %40-60 daha hızlı üretim, yıllık dokümantasyon geriliminin ortadan kalkması. Somut ölçüm için eğitim öncesi ve 3 ay sonrasını karşılaştırın.

### Küçük şirketim için fazla mı?

Bireysel başlangıç için **Claude Max 5x ilk ay ($100)** + sonrası duruma göre Pro ($20). Wiki ve CLAUDE.md örnekleri ücretsiz — **her büyüklükteki şirkete** ve bireysel profesyonele faydalıdır.

## Çalışan Adaptasyonu

### Çalışanlarım Claude'u kullanmak istemezse?

Direnç doğaldır ve beklenir. Zamana programının tasarımı tam bu direnci çözer: her çalışan ilk oturumda **kendi gerçek işi için** gerçek bir çıktı üretir. "Buna neden ihtiyacım var?" sorusu o an cevaplanır — soyut değil, somut.

### Yaşlı çalışanlarım teknoloji fobiklerse?

Claude'un büyük avantajı **konuşma arayüzü**. Ne kod, ne karmaşık menü — sadece Türkçe konuşmak. 60 yaşındaki muhasebe müdürü için Claude, 30 yaşındaki yazılımcıdan **daha rahat** olabilir.

### Çalışanlar Claude'a bağımlı hale gelmez mi?

Bu gerçek bir risk. Zamana programının [4D Çerçevesi](../prompting/4d-cercevesi.md) tam bunu hedefler: Diligence (Sorumluluk) boyutu — çalışan her çıktının arkasında durur, sorumluluğu Claude'a devretmez. "Claude yazar, siz karar verirsiniz" kuralı programın her yerinde geçerlidir.

### Claude'a öğrettiklerimiz, çalışan ayrıldığında şirketten gider mi?

**Hayır.** CLAUDE.md dosyası, prompt kütüphanesi ve workspace klasörü **şirketin mülküdür** — çalışanın değil. Bu dosyalar iş bilgisayarında durur ve çalışan ayrıldığında şirketle kalır.

## Teknik Konular

### Hangi Claude modelini kullanmalıyım?

**Sonnet.** Her zaman. [Detay](modeller.md). Model seçimi için enerji harcamayın, çıktı kalitesi için harcayın.

### Claude Türkçeyi iyi konuşur mu?

**Evet, profesyonel düzeyde.** Resmi yazışma, teknik terminoloji, Türk iş kültürü nüansları — Claude 4.x ailesi bunları doğru yakalar. Önemli metinleri her zaman gözden geçirin ama.

### Claude internete bağlı mı?

**Varsayılan olarak hayır.** Web search skill'i etkinleştirilmediği sürece internete bakmaz. Bugünün döviz kuru, son haber, hisse fiyatı gibi güncel bilgiyi doğrudan soramazsınız — ya web search açarsınız ya da bilgiyi manuel verirsiniz.

### Claude kod yazabilir mi?

**Evet, ama Zamana'nın kapsamı dışıdır.** İş profesyoneli için değerli olan kısım: "Bir PowerShell script'i yaz, şunu otomatize et" diyebilmek — çalışan kod öğrenmez, Claude script'i üretir ve çalışan sonucu doğrular. [Bilgi Teknolojileri](../departmanlar/bilgi-teknolojileri.md) sayfasında detay.

### Claude bilgisayarımı kontrol edebilir mi?

**Evet, [Computer Use](../yetenekler/computer-use.md) özelliği ile** — ama her eylem şeffaf ve sizin onayınızla. Bu özellikle API'si olmayan eski sistemlerde (Logo, Netsis, eski ERP) otomasyon için güçlü bir araçtır.

## ChatGPT ve Diğer Alternatifler

### ChatGPT kullanıyoruz — Claude'a geçmemiz gerekir mi?

**Şart değil — ama değer artışı ciddi olabilir.** [Claude vs ChatGPT](claude-vs-chatgpt.md) sayfasında dürüst karşılaştırma var. Kurumsal kullanımda Claude'un avantajları: CLAUDE.md şeffaflığı, uzun belge performansı, Cowork iş akışı, KVKK için daha net veri politikası.

### Hem ChatGPT hem Claude kullanabilir miyim?

Evet. Birçok profesyonel ikisini farklı işler için kullanır. Pratikte her çalışan bir süre sonra birini ana araç olarak seçer — bu tercih role bağlıdır.

### Grok, Gemini, Mistral gibi diğer modelleri denemeli miyim?

Tüketici kullanımı için denenebilir. **Kurumsal iş akışı için** şu an Claude ve ChatGPT'nin sunduğu olgunlukta (CLAUDE.md seviyesi şeffaflık, MCP connector ekosistemi, DPA) alternatif yok. Bu değişirse wiki'yi güncelleriz.

## Zamana Programları

### Zamana eğitim programları nelerdir?

**İki program** sunuyoruz — kim olduğunuza göre seçim:

**Bireysel Program ($1.000)** — Tek kişi için. 3 hafta × 2 saat birebir eğitim + 3 ay telefon desteği. CEO, freelance profesyonel, şirketi olmadan Claude'u öğrenmek isteyen herkes. Hafta sonları veya hafta içi akşam saatlerinde yapılabilir.

**Kurumsal Program ($9.000)** — Şirket için. 6 çalışana 2'şer hafta özel eğitim + 3 ay telefon desteği. Şirket çapında transformasyon hedefleyen orta ölçekli işletmeler için.

Detay: [zamana.com.tr](https://zamana.com.tr).

### Hangi program bana uygun?

| Durum | Önerilen |
|---|---|
| Tek başıma çalışıyorum (freelance, danışman) | **Bireysel Program** |
| CEO'yum, şirkete getirmeden önce kendim öğrenmek istiyorum | **Önce Bireysel, sonra Kurumsal** |
| Şirketim Claude eğitimi sunmuyor ama kendim öğrenmek istiyorum | **Bireysel Program** |
| 6+ çalışanı eğitmek istiyorum | **Kurumsal Program** |
| Pazar sabahı evimde Claude öğrenmek istiyorum | **Bireysel Program** |
| Küçük işletmeyim (1-3 kişi) | **Her kişi için Bireysel** |

### Bireysel Program nasıl yapılıyor?

3 oturum, her biri 2 saat:

- **Oturum 1** — Sıfırdan Claude'la çalışma (kurulum, CLAUDE.md, ilk gerçek iş)
- **Oturum 2** — Rolünüze derinlemesine (skills, connector, prompt kütüphanesi)
- **Oturum 3** — İş akışı tasarımı ve otomasyon

Sonrasında 3 ay boyunca telefonla destek — 30 dakika kuralı geçerli.

### Eğitim sonrası sürdürülebilir mi?

Evet (her iki programda da). Programın tasarımı **katılımcının kendi kendini yeterli** hale gelmesine göre yapılmıştır. Prompt kütüphanesi + CLAUDE.md + iş akışları elinizde kaldığında aylar boyunca bağımsız ilerlersiniz.

### Bireysel program öncesi ne yapmalıyım?

1. Claude Max 5x aboneliği (ilk ay $100, sonrası kullanıma göre Pro'ya indirilebilir)
2. Bilgisayar (Windows 10/11 veya macOS 12+)
3. Stabil internet
4. Çalışmak isteyeceğiniz gerçek bir iş listeniz (eğitimde hayali görev yok)

### Kurumsal program öncesi ne yapmalıyım?

1. Eğitim alacak 6 çalışanı belirleyin
2. Her biri için **Claude Max 5x aboneliği** alın (ilk ay zorunlu, $100/ay × 6 = $600/ay). Ay 2-3'te kullanıma göre Pro'ya indirme opsiyonu.
3. IT ekibinizden Anthropic domain'lerini whitelist yapmalarını isteyin
4. Şirket KVKK politikanızı yazılı hale getirin

Bu dördü tamamsa 1. Oturum verimli geçer.

## Uygulama ve Güncellik

### Claude ne sıklıkla değişiyor?

Anthropic sık iterasyon yapar — genellikle haftada birkaç küçük güncelleme, ayda 1-2 önemli özellik, çeyrekte önemli yeni model. Wiki'deki bilgiler yaşayan belgelerdir; Zamana müşterileri olarak **güncellemeleri bizden haber alırsınız**.

### Yeni bir özellik çıktığında ne olur?

Zamana wiki güncellenir. Retainer müşterileri telefonda bilgilendirilir. Önemli bir geçişse (örneğin yeni model ailesi) bir iç brief dağıtılır.

### Bu wiki'yi kim güncelliyor?

Murat Özsaygılı ve Zamana ekibi. Claude ekosistemindeki gelişmeleri düzenli takip ederiz; yanlış / eksik bulduğunuz bir şey varsa [murat@zamana.com.tr](mailto:murat@zamana.com.tr) adresine bildirin.

## İlgili Sayfalar

- [Claude Nedir?](claude-nedir.md) — Temel kavram
- [Claude Planları](planlar.md) — Fiyat detayları
- [Claude'un Sınırları](sinirlamalar.md) — Dürüst sınırlar
- [Gizlilik ve KVKK](gizlilik-kvkk.md) — Veri güvenliği detayları
- [Claude vs ChatGPT](claude-vs-chatgpt.md) — Alternatiflerle karşılaştırma

--8<-- "retainer-cta.md"
