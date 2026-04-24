---
title: Sık Sorulan Sorular (SSS) — Kurumsal Claude Kullanımı
description: Claude'u şirketinize getirmeyi düşünürken akla gelen yaygın sorular ve net cevapları. Güvenlik, veri, maliyet, çalışan adaptasyonu, KVKK ve daha fazlası.
tags:
  - temeller
  - sss
  - faq
  - kurumsal-alici
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

Pro planında 6 × $20 = $120/ay (yaklaşık 4.000 TL). Zamana eğitim programının tamamı (3 ay × $3.000 = $9.000) bu Claude abonelik maliyetinin çok üstünde — **asıl yatırım eğitimdir, abonelik değildir.**

### Yatırımın geri dönüşünü nasıl ölçerim?

Zamana müşterilerinde tipik ölçüler: çalışan başına haftada 8-15 saat kazanım, aynı iş kalitesini %40-60 daha hızlı üretim, yıllık dokümantasyon geriliminin ortadan kalkması. Somut ölçüm için eğitim öncesi ve 3 ay sonrasını karşılaştırın.

### Küçük şirketim için fazla mı?

Claude Pro aylık $20 — bir çalışanın yarım günlük maliyetinin çok altında. Zamana retainer programı 6 çalışanlı orta ölçekli şirket içindir, ama ücretsiz wiki ve CLAUDE.md örnekleri **her büyüklükteki şirkete** faydalıdır.

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

## Zamana Programı

### Zamana eğitim programı nedir?

3 ay süren kurumsal eğitim programı. 6 çalışana 2'şer hafta özel eğitim + 3 ay boyunca telefon desteği. $3.000/ay, toplam $9.000. Detay: [zamana.com.tr](https://zamana.com.tr).

### Kaç çalışana eğitim vermek gerekir?

Tek çalışan bireysel Pro + wiki ile de başarılı olabilir. Kurumsal transformasyon için Zamana **6 çalışan** önerir — yeterli kritik kütle oluşturan sayı.

### Eğitim sonrası sürdürülebilir mi?

Evet. Programın tasarımı **öğrenen çalışanın kendi kendini yeterli** hale gelmesine göre yapılmıştır. Prompt kütüphanesi + CLAUDE.md + iş akışları elinde kaldığında çalışan aylar boyunca bağımsız ilerler.

### Programdan önce ne yapmalıyım?

1. Eğitim alacak 6 çalışanı belirleyin
2. Her biri için Claude Pro aboneliği alın
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
