---
name: llm-konseyi
description: "Herhangi bir kararı, fikri veya stratejiyi 5 farklı yapay zeka danışmanından oluşan bir konseye sunar. Danışmanlar bağımsız analiz yapar, birbirlerinin fikirlerini anonim olarak çapraz incelemeye (peer-review) tabi tutar, 100 üzerinden mantıklılık skoru belirler ve nihai bir karar raporu üretir. ZORUNLU TETİKLEYİCİLER: 'konsey topla', 'konseyi çalıştır', 'bunu tartış', 'bunu test et', 'bunu analiz et', 'konsey kararı'. GÜÇLÜ TETİKLEYİCİLER: 'şunu mu yapsam bunu mu', 'hangi seçeneği seçmeliyim', 'sence bu fikir mantıklı mı', 'risk analizi yap', 'kararsız kaldım'. Basit bilgi sorularında çalıştırmayın; sadece yüksek riskli, stratejik veya ikilemli kararlarda çalıştırın."
---

# Yapay Zeka Konseyi (LLM Konseyi) — Claude Code & AI Skill

Tek bir yapay zekaya soru sorduğunuzda tek bir bakış açısı alırsınız. Bu yanıt harika da olabilir, sıradan da. Tek bir perspektif gördüğünüz için bunu ayırt edemezsiniz.

**Yapay Zeka Konseyi** bu sorunu çözer. Kararınızı, her biri tamamen farklı bir düşünce ekolüne sahip **5 bağımsız danışmana** sunar. Ardından danışmanlar birbirlerinin yanıtlarını anonim olarak eleştirir. Son olarak **Konsey Başkanı** tüm verileri sentezleyerek **100 üzerinden Mantıklılık Skoru**, Risk/Getiri değerlendirmesi ve net bir uygulama planı sunar.

---

## 🎯 Ne Zaman Çalıştırılmalı?

Konsey, **yanlış karar almanın pahalı olduğu** durumlar içindir.

**İdeal Konsey Soruları:**
- "97$'lık canlı atölye mi düzenlemeliyim yoksa 497$'lık kurs mu hazırlamalıyım?"
- "İki YouTube kanalımdan hangisine daha fazla zaman ayırmalıyım?"
- "X modelinden Y modeline geçmeyi düşünüyorum, bu mantıklı mı?"
- "Açılış sayfası (Landing Page) metnim burada. Zayıf noktaları neler?"
- "Önce bir asistan mı işe almalıyım yoksa otomasyon mu kurmalıyım?"

**Konseye Gönderilmemesi Gerekenler:**
- "Fransa'nın başkenti neresidir?" (Tek doğrusu olan bilgi soruları)
- "Bana bir tweet yaz" (İçerik üretim görevleri)
- "Bu makaleyi özetle" (İşleme görevleri)

---

## 🕵️ 5 Danışman (Düşünce Modelleri)

### 1. Aykırı Düşünen (Şüpheci Danışman)
Neyin yanlış gideceğine, neyin eksik olduğuna ve neyin başarısız olacağına odaklanır. Fikirde ölümcül bir kusur arar. Karamsar değildir; sizi kötü bir yatırımdan koruyan dürüst dosttur.

### 2. Temel İlkeler Danışmanı
Yüzeydeki soruyu görmezden gelir ve *"Burada asıl çözmeye çalıştığımız sorun ne?"* diye sorar. Varsayımları yıkar, problemi sıfırdan inşa eder.

### 3. Büyüme ve Fırsat Danışmanı
Herkesin kaçırdığı potansiyeli ve fırsatları arar. *"Bu fikir beklenenden iyi çalışırsa ne kadar büyüyebilir?"* sorusuna yanıt arar. Riskle ilgilenmez, ölçekle ilgilenir.

### 4. Dış Göz (Tarafsız Danışman)
Sektörünüz, geçmişiniz veya uzmanlığınız hakkında sıfır ön yargıya sahiptir. Olaya tamamen dışarıdan bir izleyici gözüyle bakar. Uzman körlüğünü engeller.

### 5. Uygulamacı Danışman (Eylemdar)
Tek bir şeyle ilgilenir: *"Bu iş gerçekten yapılabilir mi ve Pazartesi sabahı atılacak ilk adım ne olmalı?"* Teoriyi bırakır, zaman ve kaynak verimliliğine bakar.

---

## 🔄 Konsey Oturumu Nasıl Çalışır?

### Adım 1: Bağlam Zenginleştirme ve Soruyu Çerçeveleme
Konsey çalışmadan önce çalışma alanındaki `CLAUDE.md`, hafıza dosyaları veya proje belgeleri taranarak soruya bağlam eklenir.

### Adım 2: 5 Danışmanın Paralel Çalıştırılması
5 danışman aynı anda (paralel) çalıştırılır. Her biri kendi rolüne tam sadık kalarak 150-300 kelimelik bağımsız analiz üretir.

### Adım 3: Anonim Çapraz İnceleme
Tüm yanıtlar A, B, C, D, E olarak anonimleştirilir. 5 danışman bu yanıtları inceler:
1. En güçlü yanıt hangisi ve neden?
2. En büyük kör nokta hangi yanıtta var?
3. Tüm yanıtların gözden kaçırdığı ortak nokta ne?

### Adım 4: Konsey Başkanı Sentezi
Konsey başkanı tüm girdi ve eleştirileri toplayarak şu yapıda nihai kararı üretir:
- **0-100 Mantıklılık Skoru (Konsey Skoru)**
- **Konseyin Uzlaştığı Noktalar**
- **Konseyin Ayrıştığı Noktalar**
- **Yakalanan Kör Noktalar**
- **Nihai Tavsiye**
- **Pazartesi Sabahı Atılacak İlk Tek Adım**

### Adım 5: Görsel HTML Raporu ve Markdown Transkript Oluşturulması
Tüm veriler otomatik olarak aşağıdaki klasöre 2 dosya halinde kaydedilir:
`C:\Users\emirh\Desktop\mahmut\Konsey Kararları\`

1. `konsey-raporu-[timestamp].html` (Otomatik açılan görsel rapor)
2. `konsey-transkripti-[timestamp].md` (Tüm detaylı konuşma dökümü)

---

## 📂 Çıktı Formatı ve Konum

Tüm çıktılar doğrudan şu klasöre kaydedilir:
`C:\Users\emirh\Desktop\mahmut\Konsey Kararları\`

Görsel HTML raporu oluşturulduktan sonra otomatik olarak varsayılan tarayıcıda açılır.
