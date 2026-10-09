# Pari Mersin Lojistik Tarihi Araştırması ve Kaynak Doğrulama Sistemi

Bu depo, **Mersin Limanı'nın Tarihsel Gelişimi ve Dönüşüm Evreleri** başlıklı çalışmada yer alan tüm tarihsel dönemleri, niceliksel ve sayısal verileri, dayanak kaynakları ve bu kaynakların doğrulanabilirliğini test eden otomasyon araçlarını içerir.

---

## 📁 Proje Dosya Yapısı

| Dosya Adı | Açıklama |
| :--- | :--- |
| **[`Lojistik Tarihi.pdf`](./Lojistik%20Tarihi.pdf)** | Orijinal araştırma ve kronoloji metni (PDF). |
| **[`lojistik_tarihi_rakamlar_ve_veriler.md`](./lojistik_tarihi_rakamlar_ve_veriler.md)** | PDF metnindeki tüm dönemler, rakamlar, tonajlar, kapasiteler, yatırımlar ve sürelerin ayrıntılı dökümü. |
| **[`lojistik_tarihi_kaynaklar.md`](./lojistik_tarihi_kaynaklar.md)** | Tüm akademik, resmi kurum, mevzuat, kurumsal ve haber kaynaklarının kategorize edilmiş kaynakça kataloğu. |
| **[`kaynak_kod_eslestirme_rehberi.md`](./kaynak_kod_eslestirme_rehberi.md)** | Doğrulama raporundaki test kodları (`A1-A8`, `R1-R12`, `M1-M5`, `K1-K10`, `H1-H8`) ile metindeki verileri birebir eşleştiren rehber. |
| **[`kaynak_dogrulama_raporu.md`](./kaynak_dogrulama_raporu.md)** | Kaynakların canlılık (HTTP 200/403/404), yanıt süreleri ve anahtar kelime eşleşme sonuçlarını içeren test raporu. |
| **[`kaynak_dogrulayici.py`](./kaynak_dogrulayici.py)** | Kaynakları internet üzerinden otomatik olarak test eden, çok iş parçacıklı (multithreaded) Python test aracı. |
| **[`kaynak_dogrulama_sonuclari.json`](./kaynak_dogrulama_sonuclari.json)** | Yapılan testlerin makine tarafından okunabilir JSON formatındaki ham çıktıları. |

---

## 📊 Sayısal Göstergeler Özeti

* **Demiryolu:** 1886 Adana-Mersin Demiryolu (67 km), Yenice Lojistik Merkezi (416.000 m², 531,5 Milyon TL, >1M ton/yıl potansiyel).
* **Sanayi & Depolama:** 1993 MTOSB (380 hektar 1. etap), 1998 OPET Terminali (240.000 m³ akaryakıt depolama).
* **Özelleştirme & Sermaye:** 2007 MIP devir bedeli (755 Milyon USD, 36 yıl), 2017 IFM %40 hisse satışı (869 Milyon USD, ~2,17 Milyar USD şirket değerlemesi).
* **Konteyner Kapasitesi:** 1,8M TEU ➔ 2,6M TEU (EMH1) ➔ 3,6M TEU (EMH2, 455 Milyon USD yatırım).
* **Mega Gemi Operasyonu:** 10 Ekim 2025'te 880 metrelik yeni EMH2 rıhtımına yanaşan *MSC DITTE* (400 metre boy, 19.313 TEU kapasite).
* **Taşucu Limanı:** 1984 SEKA kuruluşu, 2022'de 40 yıllığına CEY Grubu'na (Ceyport Taşucu) devir teslimi.
* **Hava Kargo & YHT:** Ağustos 2024 Çukurova Uluslararası Havalimanı (9 Milyon yolcu ve kargo kapasitesi), Mersin-Adana YHT için 24 ay tren seferi durdurulması.

---

## 🛠️ Kaynak Doğrulama Aracının Çalıştırılması

Bu test aracı, herhangi bir harici kütüphane kurulumu gerektirmeden standart Python kütüphaneleriyle çalışır:

```bash
# Testi çalıştırmak için:
python kaynak_dogrulayici.py
```

Test aracı çalıştırıldığında:
1. Kaynak URL'lerinin canlılığını ve HTTP durum kodlarını kontrol eder.
2. Sayfaların içeriğinde beklenen anahtar kelimelerin geçip geçmediğini denetler.
3. Sonuçları `kaynak_dogrulama_raporu.md` ve `kaynak_dogrulama_sonuclari.json` olarak otomatik günceller.
