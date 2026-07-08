# Adım 1: Belgesiz Sorular — Taban Çizgisi (5 dk)

**Görev:** Hiçbir belge yüklemeden / referans vermeden modele soruları sormak.
**Uygulama:** Lab yönergesine uygun olarak her soru **ayrı bir oturumda** soruldu. (Koşular Claude ile yapıldı; bkz. README notu.)

## Sorular ve Belgesiz Yanıtlar

### Soru 1 — Fiyat ve kampanya
> AeroVista Drone Eğitim Akademisi'nin Profesyonel Pilotaj paketi ne kadar ve erken kayıt indirimi ne zaman bitiyor?

**Model yanıtı (özet):**
> "AeroVista Drone Eğitim Akademisi'nin güncel fiyatlarına dair bilgim yok. Türkiye'de profesyonel drone pilotaj eğitimleri genellikle 15.000–40.000 TL aralığında değişiyor; erken kayıt kampanyaları da çoğunlukla dönem başlamadan birkaç hafta önce sona eriyor. Kesin bilgi için kurumun resmî sitesini kontrol etmenizi öneririm."

**Gözlem:** Model dürüstçe bilmediğini söyledi ama yine de *makul görünen* bir aralık verdi. Fiyat sorusuna kullanılabilir bir cevap yok.

### Soru 2 — İade
> AeroVista'ya kayıt olduktan 12 gün sonra iptal edersem ne kadar iade alırım?

**Model yanıtı (özet):**
> "Bu kurumun iade politikasını bilmiyorum; ancak Türkiye'de mesafeli sözleşmelerde genellikle 14 günlük cayma hakkı bulunur. 12. günde iptal ediyorsanız büyük olasılıkla ücretin tamamını iade alabilirsiniz."

**Gözlem:** En tehlikeli yanıt bu: kulağa mantıklı ve kendinden emin geliyor, genel bir hukuki bilgiye dayanıyor — ama kurumun gerçek politikasına göre **yanlış** (12. gün %75 iade bandında). Tipik halüsinasyon/yanlış genelleme riski.

### Soru 3 — Üyelik kapsamı
> AeroVista Pro üyeliği simülatör erişimi içeriyor mu? Ayda kaç saat?

**Model yanıtı (özet):**
> "Bu tür akademilerin ücretli üyelikleri genellikle simülatör erişimi içerir; ayda 8–10 saat civarında olması muhtemeldir, ancak bu bir tahmindir."

**Gözlem:** Model tahmin ettiğini söylese de somut bir sayı üretti (8–10 saat). Gerçek değer 6 saat — tahmin yanlış ve sayı verilmiş olması yanıtı olduğundan güvenilir gösteriyor.

## Adım 1 Genel Gözlemi

Belgesiz durumda model üç davranıştan birini gösteriyor: (1) bilmediğini söyleyip cevabı erteliyor, (2) genel sektör/hukuk bilgisinden *makul ama doğrulanmamış* çıkarım yapıyor, (3) temkinli dille de olsa somut sayı uyduruyor. Üç durumda da yanıtlar kurumsal bir kullanım için **işe yaramaz veya risklidir** — kaynak yok, doğruluk garantisi yok.
