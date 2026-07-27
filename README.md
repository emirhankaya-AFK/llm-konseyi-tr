# 🏛️ LLM Konseyi (LLM Council TR) — Claude Code & AI Skill

> Claude veya Yapay Zekanızın ilk verdiği cevaba hemen güvenmeyin. Kararlarınızı, fikirlerinizi ve stratejilerinizi 5 farklı yapay zeka danışmanının tartıştığı, birbirini anonim olarak eleştirdiği ve 100 üzerinden skorladığı **LLM Konseyi** süzgecinden geçirin.

[Andrej Karpathy'nin LLM Council](https://x.com/karpathy/status/1962263486196867115) metodolojisinden esinlenerek Claude Code ve Antigravity AI ortamları için Türkçe olarak geliştirilmiştir.

---

## 🚀 Öne Çıkan Özellikler

- 🕵️ **5 Farklı Danışman Rolü:** Contrarian (Aykırı Düşünen), First Principles (Temel İlkeler), Expansionist (Büyüme Odaklı), Outsider (Dış Göz), Executor (Uygulamacı).
- 📊 **100 Üzerinden Mantıklılık Skoru (Council Score Gauge):** Fikrinizin ne kadar uygulanabilir olduğunu tek bakışta görün (0-100).
- ⚖️ **Anonim Çapraz İnceleme (Peer-Review):** Danışmanlar birbirlerinin fikirlerini kimin söylediğini bilmeden objektif olarak eleştirir.
- 🎯 **Risk & Getiri Matrisi:** Seçeneklerin risk, ROI ve zaman maliyetini kıyaslayan tablo.
- 🌐 **Otomatik HTML Dashboard & Markdown Raporu:** Görsel HTML rapor otomatik oluşturulur ve tarayıcınızda açılır.
- 📁 **Özel Klasör Kaydı:** Tüm kararlar otomatik olarak `Desktop/mahmut/Konsey Kararları` klasörüne arşivlenir.

---

## 📦 Kurulum

### Yöntem 1 — Git ile Klonlama (Önerilen)

Terminal veya PowerShell açıp şu komutu çalıştırın:

```bash
git clone https://github.com/KULLANICI_ADINIZ/llm-council-tr ~/.claude/skills/llm-council
```

### Yöntem 2 — Manuel Kurulum

1. `~/.claude/skills/llm-council/` klasörünü oluşturun.
2. `SKILL.md` ve `README.md` dosyalarını içine kopyalayın.

---

## 💬 Nasıl Kullanılır?

Claude Code veya Antigravity AI içerisinde aşağıdaki tetikleyici ifadelerden birini yazarak sorunuzu sorun:

- `konsey topla: [Sorunuz]`
- `konseyi çalıştır: [Sorunuz]`
- `bunu tartış: [Sorunuz]`
- `bunu test et: [Sorunuz]`
- `council this: [Sorunuz]`

### Örnek Kullanım:

> **konsey topla:** İki YouTube kanalımdan hangisine daha fazla zaman ayırmalıyım? Kararı büyüme potansiyeli, otomasyon kolaylığı, gelir ihtimali, rekabet ve sürdürülebilirlik açısından değerlendir.

---

## 📈 Rapor Çıktıları

Her konsey oturumu 2 dosya üretir ve varsayılan olarak `C:\Users\emirh\Desktop\mahmut\Konsey Kararları\` klasörüne kaydeder:

1. `council-report-[timestamp].html` *(Görsel HTML Dashboard - Otomatik açılır)*
2. `council-transcript-[timestamp].md` *(Tüm konuşmaların ve incelemelerin tam dökümü)*

---

## ⚖️ Lisans & Teşekkür

- Metodoloji: [Andrej Karpathy - LLM Council](https://x.com/karpathy/status/1962263486196867115)
- Türkçe Geliştirme & Özelleştirme: Community / MIT License
