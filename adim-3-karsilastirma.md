# Adım 3: İki Sonucun Karşılaştırılması (15 dk)

**Görev:** Adım 1 ve Adım 2 yanıtlarını verilen beş kritere göre karşılaştırıp temel farkları özetlemek.

## Kriter Bazlı Karşılaştırma

| # | Kriter | Belgesiz (Adım 1) | Belgeli (Adım 2) |
|---|--------|-------------------|------------------|
| 1 | **Doğruluk** | S2 kesin yanlış (%100 ≠ %75), S3 yanlış tahmin (8–10 ≠ 6 saat), S1 cevapsız | Üç soruda da belgeyle birebir doğru |
| 2 | **Spesifiklik** | Genel aralıklar ("15–40 bin TL", "birkaç hafta") | Kesin değerler: 24.900 TL, 15 Ağustos 2026, %75, 6 saat |
| 3 | **Temellendirme (Grounding)** | Kaynak yok; genel sektör/hukuk bilgisinden çıkarım | Her yanıtta belge ve bölüm atfı var |
| 4 | **Halüsinasyon riski** | Yüksek — kendinden emin ama doğrulanmamış sayılar ve kurallar | Düşük — "belgede olmayanı uydurma" talimatıyla belge sınırına kilitli |
| 5 | **Güvenilirlik (iş bağlamı)** | Kullanılamaz: müşteriye %100 iade sözü verilseydi kurum zarara girerdi | Kullanılabilir: yanıt belge üzerinden denetlenebilir, sorumluluk izlenebilir |

## Temel Farkların Özeti

1. **En kritik fark doğrulukta değil, doğrulanabilirlikte:** Belgesiz yanıtın yanlış olduğunu ancak gerçek politikayı bilen biri fark edebilir. Belgeli yanıt ise kaynağını gösterdiği için herkes 30 saniyede kontrol edebilir.
2. **En tehlikeli durum "bilmiyorum" değil, "makul yanlış":** S2'de model 14 günlük cayma hakkı genellemesiyle kendinden emin ve *ikna edici* bir yanlış üretti. Kurumsal kullanımda asıl riski oluşturan tam da bu tür yanıtlar.
3. **Belge, yanıtın kapsamını da iyileştirdi:** Belgeli modelde yanıtlar yalnızca doğru olmakla kalmadı; sorulmayan ama cevabı değiştirebilecek koşulları da (ders saati kesintisi, kampanyalı tutar üzerinden iade) belgeden getirdi.
4. **RAG'in kurumsal gerekçesi:** Şirket verileri (fiyat, politika, sözleşme) modelin eğitim verisinde yoktur ve sürekli değişir. Güvenilir kurumsal yapay zeka, modelin hafızasına değil **kontrollü ve güncel belge kaynağına** dayanmak zorundadır — RAG bu bağlantıyı kuran mimaridir.

## Güvenilirlik ve Halüsinasyon Üzerine Yansıma

Bu deney bana şunu gösterdi: halüsinasyon, modelin "saçmalaması" değil; **eksik bilgiyi akıcı dille doldurması**. Bu yüzden çözüm modeli daha çok uyarmak değil, ona doğru bağlamı vermek. Gerçek bir iş bağlamında güveneceğim yanıtın iki koşulu var: kaynağı gösterilebilir olmalı ve kaynağı ben kontrol edebilmeliyim — belgesiz yanıt bu iki koşulun ikisini de sağlayamıyor.
