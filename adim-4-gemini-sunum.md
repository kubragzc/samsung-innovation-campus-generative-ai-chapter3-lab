# Adım 4: Gemini ile Görsel Sunum Oluşturma (20 dk)

**Görev:** Analize dayanarak Gemini'ye 3–5 slaytlık, metin + görsel içeren bir sunum ürettirmek. Amaç fikirleri yalnızca metinle değil **görsel olarak** iletmek.

## Gemini'ye Yapıştırılacak Hazır Prompt

Aşağıdaki promptu Gemini'ye (gemini.google.com) yapıştırın. İsterseniz önce üç belgeyi ve adım 1–3 dosyalarını da sohbete ekleyerek Gemini'nin gerçek analizimize dayanmasını sağlayın:

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

## Yapılacaklar (Gemini'de)

1. Promptu yapıştırın, gerekirse "Slayt 3'ün grafiğini üret" gibi takip istekleriyle görselleri tek tek aldırın.
2. Üretilen slayt görsellerini indirin veya ekran görüntüsü alın.
3. Dosyaları bu depodaki [sunum/](sunum/) klasörüne `slayt-1.png` … `slayt-4.png` adlarıyla koyun (varsa dışa aktarılmış PDF'i de ekleyin).

## Slayt Tasarım Kararlarım (slayttaki 3 kontrol noktası)

1. **Mantıksal akış / slayt başına tek ana mesaj:** Problem (tahmin) → Çözüm (belge) → Kanıt (5 kriter) → Genelleme (RAG mimarisi). Her slaytın başlığı ana mesajın kendisi.
2. **Görsel öğeli yapılandırılmış düzen:** Slayt 3'te tablo + grafik, Slayt 4'te akış diyagramı özellikle istendi — metin ağırlıklı slayt yok.
3. **Ton ve teknik seviye:** Hedef kitle sınıf arkadaşları olarak tanımlandı; teknik terim serbest ama jargon sınırlı.
