# 🏛️ Yapay Zeka Konseyi (LLM Konseyi TR)

[English](README.md) | [Türkçe](README_TR.md)

> Yapay zekanızın ilk verdiği cevaba hemen güvenmeyin. Kararlarınızı, fikirlerinizi ve stratejilerinizi 5 farklı yapay zeka danışmanının tartıştığı, birbirini anonim olarak eleştirdiği ve 100 üzerinden skorladığı **Yapay Zeka Konseyi** süzgecinden geçirin.

---

## 🚀 Öne Çıkan Özellikler

- 🕵️ **5 Farklı Danışman Rolü:** Aykırı Düşünen (Şüpheci), Temel İlkeler Danışmanı, Büyüme ve Fırsat Danışmanı, Dış Göz (Tarafsız), Uygulamacı (Eylemdar).
- 📊 **100 Üzerinden Mantıklılık Skoru:** Fikrinizin ne kadar uygulanabilir olduğunu tek bakışta görün (0-100).
- ⚖️ **Anonim Çapraz İnceleme:** Danışmanlar birbirlerinin fikirlerini kimin söylediğini bilmeden objektif olarak eleştirir.
- 🎯 **Konsey Başkanı Kararı:** Uzlaşılan noktalar, ayrışılan detaylar ve kaçırılan kör noktalar sentezlenir.
- 🌐 **Otomatik Görsel HTML Rapor:** Rapor otomatik oluşturulur ve tarayıcınızda açılır.
- 📁 **Özel Klasör Arşivi:** Tüm kararlar otomatik olarak `Masaüstü/mahmut/Konsey Kararları` klasörüne arşivlenir.

---

## 📦 Kurulum

### Yöntem 1 — Git ile Klonlama (Önerilen)

Terminal veya PowerShell açıp şu komutu çalıştırın:

```bash
git clone https://github.com/KULLANICI_ADINIZ/llm-konseyi-tr ~/.claude/skills/llm-konseyi
```

### Yöntem 2 — Manuel Kurulum

1. `~/.claude/skills/llm-konseyi/` klasörünü oluşturun.
2. `SKILL.md` ve `README.md` dosyalarını içine kopyalayın.

---

## 💬 Nasıl Kullanılır?

Yapay zeka ortamında aşağıdaki tetikleyici ifadelerden birini yazarak sorunuzu sorun:

- `konsey topla: [Sorunuz]`
- `konseyi çalıştır: [Sorunuz]`
- `bunu tartış: [Sorunuz]`
- `bunu test et: [Sorunuz]`

### Örnek Kullanım:

> **konsey topla:** İki YouTube kanalımdan hangisine daha fazla zaman ayırmalıyım? Kararı büyüme potansiyeli, otomasyon kolaylığı, gelir ihtimali, rekabet ve sürdürülebilirlik açısından değerlendir.

---

## 📈 Rapor Çıktıları

Her oturum 2 dosya üretir ve varsayılan olarak `C:\Users\emirh\Desktop\mahmut\Konsey Kararları\` klasörüne kaydeder:

1. `konsey-raporu-[timestamp].html` *(Görsel HTML Raporu - Otomatik açılır)*
2. `konsey-transkripti-[timestamp].md` *(Tüm konuşmaların ve incelemelerin tam dökümü)*

---

## ⚖️ Lisans

MIT Lisansı — Dilediğiniz gibi kullanabilir ve geliştirebilirsiniz.
