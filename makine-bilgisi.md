# Makine bilgisi: Sonar Yüksek Frekans Jeneratörü

Hazırlayan: Beyza Kuzu

Bu sayfa föylerde kullanılan makine bilgilerini tek yerde toplar. Bilgiler ilan sayfasından ve üreticinin sitesinden alındı (erişim: 23 Ekim 2026). Kaynakta bulunmayan her şey 4. bölümde varsayım olarak listelendi.

> Bu belge yapay zekâ asistanı Claude (Anthropic) desteğiyle hazırlanmıştır.

## 1. Kaynaklar

- **İlan:** [twm.com.tr/tr/ilan/yuksek-frekans-jeneratoru](https://twm.com.tr/tr/ilan/yuksek-frekans-jeneratoru). Site, Ağaç İşleme Makine Sanayicileri Derneği'ne (AİMSAD) ait. Satıcı: Sonar Elektronik ve Mak. San. Tic. Ltd. Şti., 54 Sokak No:3 Sasalı, 35620 Çiğli / İzmir. İlanda telefon, e-posta ve web adresi maskeli.
- **Üretici sitesi:** [sonar.com.tr](https://www.sonar.com.tr/). Ürün tablosunun bulunduğu sayfa "Formlu Kontrplak Üretiminde Yüksek Frekans Teknolojisi" ([TR](https://www.sonar.com.tr/hizmetler/formlu-kontrplak-uretiminde-yuksek-frekans-teknolojisi-34371), [EN](https://www.sonar.com.tr/en/services/high-frequency-technology-in-formed-plywood-production)).

## 2. Teknik özellikler

| Özellik | 30 kW | 45 kW | 60 kW (seçilen) |
|---|---|---|---|
| RF çıkış gücü | 30 kW | 45 kW | **60 kW** |
| Kurulu güç | 40 kVA | 60 kVA | **90 kVA** |
| Çalışma gerilimi | 3 faz / 400 V / 50 Hz | 3 faz / 400 V / 50 Hz | 3 faz / 400 V / 50 Hz |
| Frekans | 13,56 MHz | 13,56 MHz | 13,56 MHz |
| Soğutma | Hava ya da su | Hava ya da su | Hava ya da su |
| RF çıkışı | Sağa ve sola | Sağa ve sola | Sağa ve sola |
| Ölçüler (U × G × Y) | kaynakta eşleşme yok | kaynakta eşleşme yok | 1250 × 1250 × 1800 mm (varsayım) |

İlanda ve üretici sitesinde ölçüler yalnızca iki değerle verilmiş: uzunluk 1050 / 1250 mm, genişlik 1150 / 1250 mm, yükseklik iki kez 1800 mm. Üç güç modelinin hangisinin hangi ölçüye sahip olduğu yazmıyor. Föylerde 60 kW için büyük ölçüler varsayıldı.

**Seçilen model:** 60 kW RF çıkışlı, 90 kVA kurulu güçlü sürüm. Seçim nedeni, en yüksek güçte RF maruziyeti, ark ve aşırı ısınma tehlikelerinin en belirgin hâliyle incelenebilmesi.

## 3. Üreticiden öğrenilenler

### 3.1 Firma

- 1974'te İzmir'de kurulmuş. İlk yıllarda elektronik kart, havya ve TV tamir cihazı üretmiş.
- 1980'lerin başından beri RF tekniğiyle endüktif ve kapasitif ısıtma ve kurutma makineleri üretiyor.
- Sitedeki bir yazıya göre ahşap sektörüne 1990'da girmiş. Ankara'daki bir mobilyacının talebiyle ilk yerli YF makinesi yapılmış. Kullanıcıların bu makinelere "şoklama" dediği aynı yazıda geçiyor.
- Hannover (Mayıs 2023) ve TÜYAP Woodtech (Ekim 2024) fuarlarına katılmış.

### 3.2 Jeneratör ve kullanım

- Sitedeki ifadeye göre YF üreteçleri **çift çıkışlı** tasarlanmış: kesintisiz seri üretim için sırayla iki ayrı prese enerji verebiliyor. Bu, tablodaki "RF çıkışı: sağa ve sola" satırıyla örtüşüyor.
- Jeneratör, üreticinin kendi ürettiği **soğuk hidrolik preslerle** birlikte çalışıyor.
- Kullanım alanları: formlu kontrplak (kaplama ve papellerin yapıştırılıp şekillendirilmesi), düz kontrplak, masif panel ve kiriş, CLT, kapı ve pencere kasası. Masif ahşap bükmede kurutma için de kullanılıyor (üreticiye göre 15–20 dakika; konvansiyonel fırında 18–24 saat).
- Üreticinin öne sürdüğü avantajlar:
  - Dielektrik ısıtmada yalnızca tutkallı bölge ısınır, lameller soğuk ve panel düz kalır.
  - Yapıştırma süresi kısalır.
  - 100–150 mm kalınlığa kadar kontrplak yapıştırılabilir.

### 3.3 Ürün fotoğrafındaki kontrol paneli

Ürün sayfasındaki fotoğrafın ([02_HFGStandard](https://www.sonar.com.tr/ckfinder/userfiles/images/02_HFGStandard(1).jpg)) çözünürlüğü düşük. Aşağıdakiler okunabilen etiketler. Fotoğrafın hangi güç modeline ait olduğu belli değil.

- **Orta bölüm (Y.F. JENERATÖRÜ):**
  - Ölçü aletleri: anot akımı ve grid akımı göstergeleri.
  - Lambalar: anot koruma, grid koruma, fan termiği, triyot termostatı, hazır, R/S/T faz lambaları.
  - Kumanda: reset, jeneratör start/stop, "H.F. ENERJİ" açma-kapama seçicisi ve sarı zeminli **acil stop** butonu.
- **Sol pres ve sağ pres bölümleri:** her birinde analog "ısıtma zamanı" ayarlayıcı, "enerji solda / sağda" lambası, start, stop ve H.F. enerji butonları, 0–100 skalalı **anot ayarı** düğmesi ve bir kademe seçici.
- **Uyarı etiketleri:** iyonlaştırmayan radyasyon uyarısı ve aktif kalp implantı taşıyanlar için yasak işareti. Alt kapakta ana şalter ve elektrik tehlikesi etiketi var.
- **Görünmeyenler:** dokunmatik ekran, PLC, ağ ya da modem bağlantısı.
- **Çıkarım:** "triode thermostat", "anode current" ve "grid current" etiketleri osilatörün triyot lambalı olduğunu düşündürüyor. Bu bir çıkarım, sitede açıkça yazmıyor.

### 3.4 Hidrolik presler (ürün sayfasındaki tablo)

| Model | Tabla (mm) | İki tabla arası (mm) | Baskı (ton, 200 bar) | Silindir | Strok (mm) |
|---|---|---|---|---|---|
| SPR-40 | 800 × 600 | 700 | 40 | 1 | 400 |
| SPR-60 | 1100 × 700 | 1000 | 60 | 2 | 700 |
| SPR-80-1 / 80Y-1 | 1600 × 700 | 1000 | 80 | 2 | 700 |
| SPR-80-2 / 80Y-2 | 1600 × 700 | 1600 | 80 | 2 | 1100 |
| SPR-120-1 / 120Y-1 | 1600 × 1000 | 1600 | 120 | 3 | 1100 |
| SPR-120-2 / 120Y-2 | 2100 × 1000 | 1600 | 120 | 3 | 1100 |

"Y": yan silindirli. Hangi presin hangi jeneratörle eşleştiği yazmıyor.

### 3.5 İlan ile üretici sitesi arasındaki farklar

| Konu | İlan | Üretici sitesi | Föylerde kullanılan |
|---|---|---|---|
| Teknik tablo değerleri | Tablo | Aynı tablo, değerler birebir aynı | Ortak değerler |
| Güç satırının adı | "Kurulu Güç" | TR: "Kurulu Güç", EN: "Input Power" | Kurulu güç (90 kVA) |
| Yapıştırma süresi | Yok | Bir sayfada "1 dakikaya kadar", tarihçe yazısında "1,5 dakikaya kadar" | 1–1,5 dakika aralığı olarak verildi |
| Deneyim süresi | Yok | Ürün sayfasında "33 yıldır", tarihçe yazısında başlangıç 1990 | Başlangıç yılı (1990) |

Sayısal bir çelişki bulunmadı. Farklar etiket ve ifade düzeyinde.

## 4. Föylerde kullanılan varsayımlar

Aşağıdakiler kaynakta yok. Bu sınıf bir makinede olması gereken yapı varsayıldı.

| No | Varsayım | Neden gerekli |
|---|---|---|
| VS-1 | 60 kW, su soğutmalı sürüm; ölçüler 1250 × 1250 × 1800 mm | Soğutma tipi ve ölçü modele göre verilmemiş |
| VS-2 | Jeneratör iki adet SPR-120-1 presi (sol ve sağ) besliyor, formlu kontrplak sandalye parçası üretiliyor | Hücre yerleşimi ve tehlike bölgeleri için somut bir kurulum gerekiyor |
| VS-3 | Osilatör triyot lambalı (panel etiketlerinden çıkarım) | Kabin içi yüksek gerilim ve soğutma tehlikeleri buna göre yazıldı |
| VS-4 | **Bağlı kurulum:** analog zaman ayarı ve elle anot ayarı yerine hat PLC'si ve dokunmatik HMI ile reçete yönetimi | Safety 4.0 konuları dijital bağımlılık gerektiriyor; standart panelde bunlar yok |
| VS-5 | Her presin önünde tip 4 ışık perdesi, yan ve arkada sabit koruyucular, jeneratör kabin kapılarında kilitli kapı anahtarı, acil stoplar ve bunları işleyen bir safety PLC; anot devresinde iki seri yüksek gerilim kontaktörü (K1, K2) | Emniyet donanımı kaynakta belirtilmemiş |
| VS-6 | Üreticinin uzaktan arıza tespiti için kabinde 4G/VPN servis yönlendiricisi | Uzaktan erişim kaynakta yok |
| VS-7 | Kapalı devre su soğutma ünitesi; debi ve sıcaklık sensörleri PLC'ye bağlı | Soğutma arızası senaryoları için |
| VS-8 | PLC, üretim adetlerini tesisin üretim takip bilgisayarına OPC UA ile gönderiyor | Tesis ağı bağlantısı için |
| VS-9 | Ark koruması olarak paneldeki anot ve grid aşırı akım korumaları dikkate alındı; ayrı bir ark dedektörü olup olmadığı bilinmiyor | Yangın tehlikesinin değerlendirilmesi için |
| VS-10 | Kaçak RF alan değerleri bilinmiyor; maruziyet tehlikesi paneldeki uyarı etiketine dayanarak ele alındı | Ölçüm verisi yok |

Hafta 4'te geçen "mevcut uzak erişim" mimarisi de bir varsayımdır: sahada sık rastlanan, aceleyle kurulmuş bir modem bağlantısı örnek alındı. Sonar'ın gerçek uzak servis uygulaması bilinmiyor.

## 5. Bulunamayan bilgiler

- Model adları ve kodları (yalnızca kW değerleri var)
- Ağırlık, verim, şebekeden çekilen akım
- Kaçak RF alan değerleri, ekranlama ve EMC bilgisi
- Uyulan standartlar, CE ya da uygunluk beyanı
- Emniyet fonksiyonları ve performans seviyeleri, safety PLC, ışık perdesi, kapı kilidi
- PLC/HMI, reçete yönetimi, veri kaydı, uzaktan erişim
- Soğutma tipinin modele göre seçimi. Fotoğraftaki panelde fan termiği olduğu için o ünite hava soğutmalı olabilir.

## 6. Mevzuat tarihleri (EUR-Lex'ten doğrulandı)

| Düzenleme | Yayım | Yürürlük | Uygulama |
|---|---|---|---|
| Makine Yönetmeliği (AB) 2023/1230 | OJ L 165, 29.6.2023; düzeltme OJ L 169, 4.7.2023 | 19 Temmuz 2023 | 20 Ocak 2027 (2006/42/AT aynı tarihte yürürlükten kalkar) |
| Siber Dayanıklılık Yasası (AB) 2024/2847 | OJ L, 20.11.2024 | 10 Aralık 2024 | Genel: 11 Aralık 2027; madde 14 (bildirim yükümlülükleri): 11 Eylül 2026; IV. bölüm: 11 Haziran 2026 |

2023/1230'un ilk yayımlanan metninde uygulama tarihi "14 Ocak 2027" yazıyor. Düzeltme ilanı bunu 20 Ocak 2027 olarak değiştirdi. Ek III'te 1.1.9 maddesi (bozulmaya karşı koruma) ve 1.2.1 maddesi (kontrol sistemlerinin güvenliği ve güvenilirliği) bağlı makineler için doğrudan ilgili.

Kaynaklar: [2023/1230](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32023R1230), [düzeltme](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32023R1230R(01)), [2024/2847](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32024R2847).
