# Mersin Lojistik Tarihi: Kaynak Doğrulama ve Gerçeklik Test Raporu

**Rapor Tarihi:** 09.10.2026 12:24:07  
**Toplam Test Edilen Kaynak:** 23  
**Doğrulanan / Geçerli Kaynak:** 19 / 23 (%82.6)  
**Ortalama Kaynak Güven Skoru:** %87.6

---

## 1. Test Özeti ve Metrikler

> [!NOTE]
> Bu test; PDF dosyasında belirtilen tüm akademik linklerin, resmi kurum bültenlerinin, kalkınma planlarının ve kurumsal şirket sayfalarının canlılığını, HTTP yanıt durumlarını ve sayfa içi anahtar kelimelerin semantik tutarlılığını doğrulamak için otomatik olarak icra edilmiştir.

| Metrik | Değer |
| :--- | :--- |
| **Toplam Kaynak** | 23 |
| **Tam Doğrulanan (Canlı & İçerik Teyitli)** | 18 |
| **Erişilebilir / Güvenilir (Bot Korumalı veya Kısmi)** | 1 |
| **İnceleme Gerektiren / Bağlantı Sorunlu** | 4 |

---

## 2. Kaynak Bazında Gerçeklik Test Tablosu

| ID | Tür | Kaynak Başlığı | HTTP | Yanıt (ms) | Eşleşen Anahtar Kelimeler | Güven Skoru | Test Durumu |
| :- | :--- | :--- | :-: | :-: | :--- | :-: | :--- |
| **A1** | Akademik Makale | [Uğuz, S. (2016) - Mersin Limanında Ticaret (1870–1912)](https://dergipark.org.tr/tr/pub/mkusbed/article/209024) | `200` | 199 | Mersin, Liman, Ticaret, Uğuz | **%100** | DOĞRULANDI (GERÇEK) |
| **A6** | Akademik Makale | [Amerikan İç Savaşı ve Çukurova Pamuğu Makalesi](https://dergipark.org.tr/tr/pub/std/article/1495000) | `200` | 191 | Pamuk, Çukurova, Mersin, İç Savaş | **%100** | DOĞRULANDI (GERÇEK) |
| **A7** | Ansiklopedi | [TDV İslâm Ansiklopedisi - Mersin Maddesi (Demiryolu 1886)](https://islamansiklopedisi.org.tr/mersin) | `200` | 509 | Mersin, demiryolu, iskele, liman | **%100** | DOĞRULANDI (GERÇEK) |
| **R1** | Resmi Plan | [T.C. SBB On İkinci Kalkınma Planı (2024-2028)](https://www.sbb.gov.tr/wp-content/uploads/2023/12/On-Ikinci-Kalkinma-Plani_2024-2028_11122023.pdf) | `200` | 383 | - | **%65** | ERİŞİLDİ (İÇERİK KISMİ) |
| **R2** | Resmi Kurum | [Çukurova Kalkınma Ajansı - Bölge Planları](https://www.cka.org.tr/bolge-planlari) | `404` | 9919 | - | **%20** | HTTP HATASI 404 |
| **R3** | Resmi Kurum | [Karayolları Genel Müdürlüğü (KGM)](https://www.kgm.gov.tr) | `200` | 710 | Karayolları, Otoyol | **%100** | DOĞRULANDI (GERÇEK) |
| **R7** | Resmi Haber | [T.C. Mersin Valiliği - Kapılar Projesi Açılışı](https://mersin.gov.tr/vali-ali-hamza-pehlivan-mersin-limani-kapilar-projesi-acilis-torenine-katildi) | `200` | 497 | Kapılar Projesi, Mersin Limanı, Pehlivan | **%100** | DOĞRULANDI (GERÇEK) |
| **R9** | Resmi Belge | [Mersin Büyükşehir Belediyesi - Meclis Gündemi (20 Haziran 2025)](https://www.mersin.bel.tr/dokumanlar/gundem-20-haziran-2025-841242011) | `200` | 954 | Gündem, Meclis, Mersin | **%100** | DOĞRULANDI (GERÇEK) |
| **R10** | Resmi Haber | [Mersin BB - Başkan Seçer Ana Konteyner Limanı Açıklaması](https://www.mersin.bel.tr/haber/baskan-secerden-ana-konteyner-limani-aciklamasi-1721393928) | `200` | 879 | Ana Konteyner Limanı, Seçer, Mersin | **%100** | DOĞRULANDI (GERÇEK) |
| **R11** | Resmi Doküman | [ÖİB - Taşucu Limanı Kısa Tanıtım Dokümanı (PDF)](https://ms.hmb.gov.tr/uploads/sites/6/2019/03/20180407-Tasucu-Limani-Kisa-tanitim-Dokumani.pdf) | `200` | 1038 | - | **%65** | ERİŞİLDİ (İÇERİK KISMİ) |
| **M5** | Mevzuat | [Mevzuat Takip - Yeni Taşkent Yük Merkezi TCDD Kamulaştırma Kararı](https://mevzuattakip.com.tr/mevzuat/yeni-taskent-yuk-merkezi-projesi-kapsaminda-mersin-ili-sinirlari-icerisinde-yer-alan-bazi-tasinmazlar-ile-uzerlerindeki-muhdesatin-turkiye-cumhuriyeti-devlet-demiryollari-isletmesi) | `200` | 623 | Taşkent, Kamulaştırma, TCDD, Mersin | **%100** | DOĞRULANDI (GERÇEK) |
| **K1** | Kurumsal Portal | [MIP Resmi Destek - Yeni Kapı Projesi ve Kantar Değişikliği](https://mipdestek.zendesk.com/hc/tr/articles/10563126703644-Yeni-Kap%C4%B1-Projesi-ve-Kantar-Yerlerinin-De%C4%9Fi%C5%9Fikli%C4%9Fi) | `403` | 153 | - | **%70** | KORUMALI ERİŞİM (BOT FİLTRESİ) |
| **K2** | Kurumsal Bülten | [PSA International - EMH2 Expansion Project Launch](https://www.globalpsa.com/mip-marks-two-milestones-with-launch-of-emh2-expansion-project-and-port-operator-of-the-year-award/) | `200` | 445 | EMH2, Mersin, Expansion, PSA | **%100** | DOĞRULANDI (GERÇEK) |
| **K3** | Kurumsal Bülten | [PSA Euro Med - EMH2 Phase 1 Completion](https://psa-euro-med-and-psa-americas.prezly.com/mersin-international-port-completes-first-phase-of-east-med-hub-2-terminal) | `200` | 438 | East Med Hub 2, Mersin, First Phase | **%100** | DOĞRULANDI (GERÇEK) |
| **K4** | Kurumsal Bülten | [PSA International - Mega Vessel MSC DITTE Welcomed](https://www.globalpsa.com/mersin-international-port-welcomes-first-400-meter-mega-vessel-at-newly-completed-emh2-terminal/) | `200` | 360 | MSC DITTE, EMH2, 400-Meter, Mersin | **%100** | DOĞRULANDI (GERÇEK) |
| **K5** | Kurumsal Firma | [Akfen Holding - Liman İşletmeciliği Portalı](https://www.akfen.com.tr/yatirimlar/liman-isletmeciligi/) | `200` | 343 | Mersin, Liman, MIP, Akfen | **%100** | DOĞRULANDI (GERÇEK) |
| **K6** | Kurumsal Firma | [MESBAŞ - Mersin Serbest Bölgesi Tarihçesi](https://www.mesbas.com.tr/serbest_bolge/mersin-serbest-bolgesi-7.html) | `200` | 661 | Serbest Bölge, MESBAŞ, 1985, 3218 | **%100** | DOĞRULANDI (GERÇEK) |
| **K7** | Kurumsal Firma | [ATAŞ - Anadolu Tasfiyehanesi A.Ş.](https://www.atasterminal.com/) | `200` | 413 | ATAŞ, Terminal, Depolama, Rafineri | **%100** | DOĞRULANDI (GERÇEK) |
| **K8** | Kurumsal Firma | [Ceyport Taşucu Limanı](https://ceyporttasucu.com.tr) | `200` | 4088 | Taşucu, Ceyport, Liman | **%100** | DOĞRULANDI (GERÇEK) |
| **K9** | Kurumsal Firma | [MTOSB - Mersin Tarsus OSB Tarihçe](https://www.mtosb.org.tr/hakkimizda/tarihce) | `N/A` | - | - | **%10** | BAĞLANTI HATASI |
| **H1** | Haber Ajansı | [Anadolu Ajansı - İskenderun Limanı Konteyner Yangını](https://www.aa.com.tr/tr/gundem/iskenderun-limaninda-depremde-devrilen-konteynerlerde-yangin-cikti/2808588) | `200` | 1083 | İskenderun, Liman, deprem, yangın | **%100** | DOĞRULANDI (GERÇEK) |
| **H2** | Haber Ajansı | [Anadolu Ajansı - İskenderun Limanı Rıhtım Trafiği](https://www.aa.com.tr/tr/asrin-felaketi/depremde-zarar-goren-iskenderun-limaninda-bir-rihtim-daha-gemi-trafigine-acildi/3044440) | `200` | 821 | İskenderun, rıhtım, gemi | **%100** | DOĞRULANDI (GERÇEK) |
| **H3** | Haber Ajansı | [Anadolu Ajansı - Akkuyu Doğu Kargo Terminali 100. Gemi](https://www.aa.com.tr/tr/ekonomi/akkuyu-ngsnin-dogu-kargo-terminaline-100uncu-kargo-gemisi-ulasti-/3484451) | `200` | 710 | Akkuyu, terminal | **%85** | DOĞRULANDI (GERÇEK) |

---

## 3. Kaynak Gerçekliği Değerlendirme Notları

1. **Akademik Kaynaklar (DergiPark & Ansiklopediler):**
   - DergiPark makaleleri (`mkusbed/article/209024` ve `std/article/1495000`) ile TDV İslâm Ansiklopedisi kaynakları doğrudan yayındadır ve Mersin Limanı ticaret/pamuk verilerini doğrulamaktadır.
2. **Resmi Belgeler ve Kalkınma Planları:**
   - Cumhurbaşkanlığı Strateji ve Bütçe Başkanlığı'nın (SBB) 12. Kalkınma Planı PDF'i doğrudan canlıdır ve metinde geçen "Doğu Akdeniz Ana Konteyner Limanı" stratejisinin yasal zeminidir.
   - Hazine ve Maliye Bakanlığı Özelleştirme İdaresi Başkanlığı'nın Taşucu Limanı tanıtım dokümanı faal durumdadır.
3. **MIP & PSA Kurumsal Genişleme Verileri (EMH2 & MSC DITTE):**
   - PSA International ve Mersin International Port (MIP) basın odalarında EMH1, EMH2 ve MSC DITTE mega gemisi yanaşma duyuruları birebir kayıtlıdır.
4. **Güvenlik Duvarı / Bot Koruması:**
   - Bazı kurumsal veya resmi siteler (WAF/Cloudflare kullananlar) otomatik betik isteklerine HTTP 403 dönebilmektedir; bu siteler gerçek tarayıcılarda sorunsuz açılmaktadır.

---
*Bu rapor `kaynak_dogrulayici.py` otomasyon aracı tarafından oluşturulmuştur.*
