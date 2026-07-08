# Samsung Innovation Campus — Generative AI / Chapter 3 Lab Ödevi

**[Lab3] Comparing Responses With and Without Document Context (RAG Concept)**

Bu depo, Chapter 3 (AI Foundation Models and Platforms) lab ödevinin çözümünü içerir. Amaç: aynı soruları modele **belgesiz** ve **belge vererek** sorup yanıtları karşılaştırarak bağlam temellendirmenin (grounding / RAG) yanıt kalitesine etkisini deneyimlemek.

## Dosyalar

| Adım | Konu | Dosya |
|------|------|-------|
| — | Alıştırma belgeleri (3 adet, kurgusal) | [belgeler/](belgeler/) |
| 1 | Belgesiz Sorular (Taban Çizgisi) | [adim-1-belgesiz-sorular.md](adim-1-belgesiz-sorular.md) |
| 2 | Aynı Soruları Belgelerle Sorma | [adim-2-belgeli-sorular.md](adim-2-belgeli-sorular.md) |
| 3 | İki Sonucun Karşılaştırılması | [adim-3-karsilastirma.md](adim-3-karsilastirma.md) |
| 4 | Gemini ile Görsel Sunum | [adim-4-gemini-sunum.md](adim-4-gemini-sunum.md) + [sunum/](sunum/) |

## Notlar

- **Alıştırma belgeleri kurgusaldır:** "AeroVista Drone Eğitim Akademisi" ve tüm fiyat/politika bilgileri bu lab için oluşturulmuştur. Kurgusal bir şirket seçilmesi bilinçlidir: modelin belgesiz bu bilgilere sahip olması imkânsız olduğundan, temellendirmenin (grounding) etkisi net biçimde gözlemlenebilir.
- **Model:** Adım 1–2 koşuları Claude (Anthropic) ile yapılmış ve tutanak olarak belgelenmiştir; lab yönergesindeki gibi her soru ayrı oturumda sorulmuştur. Adım 4 (görsel sunum) **Gemini** ile üretilecektir; hazır prompt [adim-4-gemini-sunum.md](adim-4-gemini-sunum.md) dosyasındadır, çıktılar `sunum/` klasörüne eklenecektir.

## Öğrenilen Ana Fikir

Belge bağlamı olmadan model ya bilmediğini söyler ya da makul görünen tahminler üretir (halüsinasyon riski). Belge verildiğinde yanıtlar belgeye dayalı, doğrulanabilir ve kurumsal kullanım için güvenilir hale gelir — kurumsal senaryolarda RAG'in zorunlu olmasının nedeni budur.
