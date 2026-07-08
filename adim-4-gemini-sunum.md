# Adım 4: Gemini ile Görsel Sunum Oluşturma (20 dk)

**Görev:** Analize dayanarak Gemini'ye 3–5 slaytlık, metin + görsel içeren bir sunum ürettirmek. Amaç fikirleri yalnızca metinle değil **görsel olarak** iletmek.

## Gemini Prompt


```text
Sen sunum tasarımı konusunda deneyimli bir eğitim içeriği tasarımcısısın.
"Belgeli ve Belgesiz Yapay Zeka Yanıtlarının Karşılaştırılması (RAG Kavramı)"
konulu, 4 slaytlık görsel ağırlıklı bir sunum oluştur. Her slayt için hem
içeriği hem de görseli üret.

Hedef kitle: Yapay zeka dersindeki sınıf arkadaşlarım (teknik temeli olan
öğrenciler). Ton: net, öğretici, abartısız; teknik terimler kullanılabilir
ama jargona boğma.

Slayt planı (her slaytın tek bir ana mesajı var):
- Slayt 1 — "Bağlamsız model tahmin eder": Belgesiz sorulan 3 soruda
  modelin verdiği belirsiz/yanlış yanıtlar. Görsel: soru işaretleriyle
  sisli/bulanık bir beyin illüstrasyonu.
- Slayt 2 — "Belge verilince yanıt kesinleşir": Aynı 3 sorunun belgeyle
  alınan net yanıtları (24.900 TL, %75 iade, ayda 6 saat). Görsel:
  belgeye bağlanan ışıklı ok ile netleşen yanıt kartları.
- Slayt 3 — "5 kriterde karşılaştırma": Doğruluk, spesifiklik,
  temellendirme, halüsinasyon riski, güvenilirlik. Görsel: iki sütunlu
  karşılaştırma tablosu VE kriter başına kazananı gösteren basit bir
  grafik.
- Slayt 4 — "Kurumsal kullanım için RAG neden şart?": Görsel: Soru →
  Belge Deposu → İlgili Parçalar → Model → Kaynaklı Yanıt akış diyagramı.
  Altta tek cümlelik sonuç: "Güvenilir kurumsal yapay zeka, modelin
  hafızasına değil kontrollü belge kaynağına dayanır."

Her slayt için: başlık, en fazla 4 madde metin ve görseli üret.
```
