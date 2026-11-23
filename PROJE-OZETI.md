# MORFOSE FABRIC — Dijital Dönüşüm Proje Özeti
_Hazırlanma: 17 Kasım 2026 · Kaynak: Gemini sohbeti "MORFOSE FABRİC" (53 mesaj, 21 Ağu – 17 Kas 2026), ham metin `kaynaklar/gemini-sohbet-MORFOSE-FABRIC.txt`_

## 1. İşletme
- **Firma:** Morfose Fabric Tekstil San. ve Tic. Ltd. Şti. — Bursa / Yıldırım, Duaçınarı (küçük sanayi sitesi), 510 m² kapalı alan, 6 çalışan, kiracı.
- **Ürün:** Erkek gömleklik dokuma kumaş (İtalyan çizgisi, premium "shirting").
- **Koleksiyon (%100 pamuk flamlı, gramaja göre):** Soil → Wood → Stone → (yeni, daha tok kalite: *Iron* / *Basalt* önerildi, karar bekliyor).
- **Yeni kalite:** Soil Flam benzeri likralı — isim önerileri: Soil Flex, Terra Flex, Soil-X… (karar bekliyor).
- **2026 ilk 6 ay net satış:** ~11,04 milyon TL (mizana göre). İlk madde-malzeme stoku ~9,7 milyon TL.
- **Hedef müşteri:** Fiyat kıran kurumsal devler yerine İngiltere / İtalya / Fransa'daki butik ve bespoke gömlek markaları.
- **Tedarik:** İplikçiler Kestel / Barakfakih bölgesinde; boyahane fason; fason iplik çekimi (Kahramanmaraş, Adana, Gaziantep) araştırıldı.

## 2. Web sitesi (Gemini + ChatGPT notlarında karara bağlananlar)
- **Konsept:** Ürün kataloğu DEĞİL → marka vitrini + **"Private Access"** (kapalı B2B müşteri portalı). Herkese açık: hikâye, değerler, üretim gücü, sürdürülebilirlik, blog. Kapalı: kumaşlar, kartelalar, fiyatlar.
- **Sayfalar:** Ana sayfa · Hikâye/Kurumsal · Değerler/Yaklaşım · Üretim (İplik → Dokuma → Boyahane → Kalite kontrol) · Sürdürülebilirlik · Blog · İletişim · Private Access (giriş / erişim talebi).
- **Hero metni:** "We Don't Just Produce Fabric. We Build the Foundation of Your Collection." / "Biz kumaş üretmeyiz. Koleksiyonların temelini inşa ederiz."
- **Değerler:** Precision · Consistency · Discipline · Partnership.
- **Görsel dil:** Sessiz lüks, minimal; siyah/lacivert/kömür + mat altın; sürdürülebilirlik bölümlerinde zümrüt yeşili. Logo kartela/kartvizitte beyaz üzerine siyah.
- **Zorunlu:** Mobil uyum, güçlü SEO ("erkek gömlek kumaşı üretici", "premium shirt fabric Turkey", "cotton shirting fabric supplier"), TR/EN dil, WhatsApp, Instagram/LinkedIn.
- **Blog otomasyonu:** Claude API ile SEO makaleleri üretip siteye yayınlama fikri.
- **İleri fikirler:** Kartela/numunelerde QR "kumaş pasaportu" (iplik kaynağı, sertifika no, reçete), müşteri favorileri, PDF kartela indirme, otomatik takip e-postaları.
- **Teknik öneri:** Next.js + Tailwind (TypeScript). Alan adı: morfosefabric.com (e-posta info@morfosefabric.com mevcut).

## 3. İşletme uygulaması (ERP) — hedef 1 Ocak 2027
Bugün Excel'de olanlar: satış hesapları, tedarik hesapları, kumaş analizleri, ürün ağacı, stok takibi, boyahane takibi, satış irsaliyeleri, kalite maliyet analizleri, üretim planlama.

| Modül | İçerik |
|---|---|
| Cari & Ön muhasebe | Müşteri/tedarikçi, bakiyeler, tahsilat/ödeme, çekler |
| Ürün ağacı & kumaş analizi | Kalite reçeteleri: iplik, sıklık, gramaj, fire % |
| Stok & barkod/QR | İplik, ham kumaş, boyalı top; her topa QR/barkod |
| Boyahane sevkiyatı | Boyahaneye giden/gelen metre-kg, parti, renk, apre, fire |
| Satış sevkiyatı | Sipariş, PDF irsaliye |
| Üretim planlama | Tezgâh/iş emri planı |
| Kalite maliyet analizi | Hata, fire, ikinci kalite maliyetleri |
| AI asistan | Verilere Türkçe soru sorma, özet ve uyarılar |

> Not: Resmi muhasebe (e-fatura, yasal defterler, beyannameler) mali müşavirin GİB entegre programında kalmalı; bizim uygulama **ön muhasebe + operasyon** tarafını yönetir ve gerekirse oraya veri aktarır.

## 4. Diğer açık işler (sohbetten)
- OEKO-TEX Standard 100 (Hohenstein İstanbul) — iplikçilerden sertifika toplama, başvuru.
- Sonraki sertifikalar: BCI, GOTS, ileride EcoVadis.
- KOSGEB İş Geliştirme / Kapasite Geliştirme başvurusu; KOBİ sınıfı güncellemesi (2026 cirosu).
- BTSO KOBİ OSB'ye taşınma (510 m² → ~2.000 m²).
- Kartela: A3 katlamalı premium kapak, ofiste basım (A3 lazer yazıcı ~35.000 TL değerlendirmesi).
- İçerik üretimi: masa düzeni, tripod + ışık, Instagram.
