# SWOT ANALİZİ

## Yüksek Frekans Jeneratörünün SWOT Analizi



| | |
|---|---|
| **Konu alanı** | İç ve dış etkenler · TOWS strateji eşleştirmesi |
| **Makine** | Sonar Elektronik Yüksek Frekans Jeneratörü, 60 kW RF çıkış, 13,56 MHz |
| **Hazırlayan** | Beyza Kuzu |

> Bu belge yapay zekâ asistanı Claude (Anthropic) desteğiyle hazırlanmıştır.

## 1. Amaç ve yöntem

Bu çalışmada Sonar 60 kW YF jeneratörü, bir ahşap işleme firmasının yatırım kararı açısından değerlendirilir. Güçlü ve zayıf yönler makinenin kendisinden çıkarıldı: ilan, üretici sitesi ve ürün fotoğrafı. Fırsatlar ve tehditler dışarıdan geldi: sektör, rakipler, mevzuat ve siber tehditler. Laboratuvar föylerindeki bulgular (özellikle Hafta 3 ve 4) tehdit tarafına taşındı.

Pazar büyüklüğü, rakip payı ya da fiyat gibi sayısal bir veri kullanılmadı. Bu tür maddeler "(yorum)" olarak işaretlendi. Mevzuat tarihleri EUR-Lex'teki metinlerden doğrulandı.

## 2. Makine özeti

- **Ne yapıyor:** 13,56 MHz'de çalışan, çift çıkışlı, sırayla iki soğuk hidrolik prese enerji veren bir YF jeneratörü. Formlu kontrplak, düz kontrplak, masif panel ve CLT yapıştırmada ve bükülmüş masif ahşabın kurutulmasında kullanılıyor.
- **Seçilen model:** 60 kW RF çıkış, 90 kVA kurulu güç, 3 faz / 400 V / 50 Hz, hava ya da su soğutma.
- **Kontrol paneli:** Ürün fotoğrafındaki standart panel analog.
- **Ayrıntılı bilgi:** makine-bilgisi.md.

## 3. Analiz

### 3.1 Güçlü yönler (iç, yardımcı)

- **Çift çıkış:** Jeneratör iki prese sırayla enerji verdiği için bir pres yüklenirken diğeri ısıtılır. Pahalı olan RF kaynağı boş beklemez.
- **Yalnızca tutkal hattını ısıtma:** Üreticiye göre dielektrik ısıtmada lameller soğuk kalır ve panel düz çıkar. Sıcak preste bütün parça ısınır.
- **Kısa yapıştırma süresi:** Üretici, sıcak preste 10–15 dakika süren işin 1–1,5 dakikaya indiğini belirtiyor.
- **Kalın ve formlu parça:** Üreticiye göre 100–150 mm kalınlığa kadar formlu ya da düz kontrplak yapıştırılabiliyor.
- **Köklü yerli üretici:** Firma 1974'ten beri RF ısıtma, 1990'dan beri ahşap sektörü için makine yapıyor. Türkiye'deki kullanıcı için servis ve yedek parça yakın.
- **Sade panel:** Analog göstergeler ve ayrı koruma lambaları (anot, grid, triyot termostatı, fan termiği) arızanın yerini okumayı kolaylaştırıyor. Yazılım az olduğu için saldırı yüzeyi de küçük.
- **Açık uyarı işaretleri:** Panelde iyonlaştırmayan radyasyon uyarısı ve aktif implant taşıyanlar için yasak işareti var.

### 3.2 Zayıf yönler (iç, zararlı)

- **Lambalı osilatör:** Panel etiketleri triyot lambalı bir tasarımı düşündürüyor (çıkarım). Lamba eskir ve değişimi bakım maliyeti ile duruş demektir.
- **Reçete ve kayıt eksikliği:** Analog zaman ayarı ve elle anot ayarı, aynı ürünün her seferinde aynı ayarla yapıldığını kanıtlamayı zorlaştırıyor.
- **Uzaktan izleme yok:** Standart modelde veri çıkışı ya da uzak servis görünmüyor. Bir Endüstri 4.0 hattına bağlamak ek mühendislik gerektiriyor.
- **Eksik teknik veri:** Ağırlık, verim, kaçak alan değerleri ve ölçülerin modellere göre dağılımı kamuya açık belgelerde yok.
- **Emniyet bilgisi açık değil:** Emniyet fonksiyonlarının performans seviyeleri, safety PLC ya da ışık perdesi kullanımı belirtilmiyor. Alıcı bunları ayrıca sormak zorunda.
- **Sistem olarak emniyet:** Jeneratör tek başına çalışmıyor. Pres, kalıp ve elektrotla birlikte emniyetten kimin sorumlu olduğu her kurulumda ayrıca netleştirilmeli.

### 3.3 Fırsatlar (dış, yardımcı)

- **Masif ve lamine ahşap ürünleri:** CLT, masif panel ve kiriş gibi ürünlere olan ilgi YF yapıştırmaya talep yaratabilir (yorum).
- **Enerji maliyeti baskısı:** Yalnızca tutkal hattını ısıtan bir yöntem, enerji giderine duyarlı işletmelere cazip gelebilir (yorum).
- **Modernizasyon paketi:** Sahada çalışan eski analog makinelere PLC/HMI, reçete kaydı ve güvenli uzak servis paketi satılabilir (yorum).
- **AB Makine Yönetmeliği geçişi:** (AB) 2023/1230, 20 Ocak 2027'den itibaren uygulanacak. Ek III'teki bozulmaya karşı koruma (1.1.9) ve kontrol sistemlerinin güvenliği (1.2.1) gerekliliklerini baştan karşılayan bir tasarım AB'ye ihracatta avantaj sağlayabilir.
- **Uzak servisle ihracat desteği:** Uzaktan arıza tespiti, yurt dışındaki müşteriye teknisyen göndermeden destek verilmesini sağlar.
- **Fuar ağı:** Firma Hannover ve İstanbul fuarlarına katılıyor. Yeni bir sürümü tanıtmak için hazır bir kanal var.

### 3.4 Tehditler (dış, zararlı)

- **Katı hal jeneratörler:** Lambasız (katı hal) RF jeneratörü sunan yabancı üreticiler, bakım ve verim açısından lambalı tasarımı geride bırakabilir (yorum, rakip verisi kullanılmadı).
- **Bağlı makineye siber saldırı:** Uzak servis eklendiğinde modem ya da VPN üzerinden giriş, reçete değişikliği ve yangın gibi fiziksel sonuçlara yol açabilir (Hafta 3, R1).
- **CRA yükümlülükleri:** (AB) 2024/2847 genel olarak 11 Aralık 2027'de uygulanmaya başlıyor. Bildirim yükümlülükleri (madde 14) 11 Eylül 2026'dan beri geçerli. Uzak servis yazılımı içeren bir sürüm kapsama girerse güvenlik güncellemesi ve açık yönetimi yükü gelir. Kapsama girip girmediği yorum gerektiriyor.
- **RF maruziyeti mevzuatı:** 2013/35/AB Direktifi işverene elektromanyetik alan maruziyetini değerlendirme yükü getiriyor. Kaçak alan değerleri verilmeyen bir makine alıcıyı tereddüde düşürebilir.
- **Nitelikli personel:** RF ve yüksek gerilim bilen bakım personeli bulmak kullanıcı işletmeler için zor olabilir (yorum).
- **İthal parça bağımlılığı:** Triyot gibi özel parçaların ithal olması fiyat ve teslim süresi riskini artırabilir (yorum, parça menşei doğrulanmadı).

### 3.5 Özet matris

| | Yardımcı | Zararlı |
|---|---|---|
| **İç (makine)** | **S · Güçlü yönler**<br>Çift çıkış, iki pres sırayla<br>Yalnızca tutkal hattını ısıtma<br>Kısa yapıştırma süresi (1–1,5 dk)<br>Kalın ve formlu parça (100–150 mm)<br>Köklü yerli üretici (1974)<br>Sade analog panel, az yazılım<br>Açık uyarı işaretleri | **W · Zayıf yönler**<br>Lambalı osilatör (çıkarım)<br>Reçete ve kayıt eksikliği<br>Uzaktan izleme yok<br>Eksik teknik veri<br>Emniyet bilgisi açık değil<br>Emniyet sorumluluğu sistem düzeyinde |
| **Dış (çevre)** | **O · Fırsatlar**<br>Masif ve lamine ahşap ürünleri<br>Enerji maliyeti baskısı<br>Modernizasyon paketi<br>2023/1230 geçişi (20 Ocak 2027)<br>Uzak servisle ihracat desteği<br>Fuar ağı | **T · Tehditler**<br>Katı hal jeneratörler (rakipler)<br>Bağlı makineye siber saldırı<br>CRA yükümlülükleri (11 Aralık 2027)<br>RF maruziyeti mevzuatı (2013/35/AB)<br>Nitelikli personel<br>İthal parça bağımlılığı |

**Şekil 1.** SWOT özet matrisi: satırlar iç ve dış etkenler, sütunlar yardımcı ve zararlı etkenler.

### 3.6 TOWS strateji tablosu

**Tablo 1.** TOWS stratejileri

| | Fırsatlar (O) | Tehditler (T) |
|---|---|---|
| **Güçlü yönler (S)** | **SO:** Çift çıkışın ve kısa yapıştırma süresinin avantajını CLT ve masif panel üreticilerine "parça başına enerji" hesabıyla göstermek. Mevcut kullanıcı tabanına modernizasyon paketi sunmak. | **ST:** Sade panelin avantajını koruyarak bağlı sürümde emniyet fonksiyonlarını ağdan bağımsız tutmak (Hafta 4, GR-1–GR-5). Uyarı etiketlerine ek olarak kaçak alan ölçüm raporunu teslimata eklemek. |
| **Zayıf yönler (W)** | **WO:** Reçete, veri kaydı ve güvenli uzak servis içeren bağlı bir sürüm geliştirmek. Teknik veri sayfasını 2023/1230'a göre tamamlamak: ölçüler, ağırlık, kaçak alan, emniyet fonksiyonları ve PL değerleri. | **WT:** Uzak servisi varsayılan kapalı, MFA'lı ve kayıtlı kurmak, bir açık yönetimi süreci oluşturmak. Lamba ömrünü anot ve grid akımı eğrilerinden izleyip yedek lamba stoğunu buna göre planlamak. |

## 4. Değerlendirme

Makinenin güçlü yönleri süreçle ilgili: çift çıkış, kısa süre, yalnızca tutkalın ısınması. Zayıf yönleri ise bilgi ve dijital taraftan geliyor: reçete kaydı yok, uzaktan izleme yok, emniyet ve teknik veriler açık değil.

Fırsatlar ve tehditler tablosunda aynı konu iki kez görünüyor: bağlanabilirlik. Uzak servis ve veri kaydı makineyi modern hatlara uygun hâle getiriyor ve ihracatta servis maliyetini düşürüyor. Aynı özellik, laboratuvar föylerinde görüldüğü gibi yeni bir saldırı yüzeyi açıyor. Bu yüzey reçete üzerinden yangına kadar giden bir zincir kurabiliyor. 2023/1230 ve CRA ise bu ikisini birbirine bağlıyor. Bağlı bir makine artık bozulmaya karşı korumayı ve güvenlik güncellemesini belgelemek zorunda.

Bu analizden çıkan öneri WO ve ST stratejilerinin birlikte izlenmesi. Bağlı sürüm geliştirilmeli ama emniyet fonksiyonları ve aşırı ısınma koruması ağdan bağımsız kalmalı. Sade analog panelin "az yazılım, az saldırı yüzeyi" avantajı, emniyet tarafında bilerek korunmalı.

Sınırlılıklar: Pazar ve rakiplerle ilgili maddeler gözlem ve yorum düzeyinde. Sayısal veri kullanılmadı. Makinenin iç yapısına dair bazı maddeler ürün fotoğrafından çıkarıldı.

## 5. Kaynaklar

1. Ürün ilanı: twm.com.tr/tr/ilan/yuksek-frekans-jeneratoru (erişim 23.10.2026).
2. Sonar Elektronik, ürün ve firma sayfaları, sonar.com.tr (erişim 23.10.2026).
3. Regulation (EU) 2023/1230 on machinery, OJ L 165, 29.6.2023; Corrigendum, OJ L 169, 4.7.2023. eur-lex.europa.eu.
4. Regulation (EU) 2024/2847 (Cyber Resilience Act), OJ L, 20.11.2024, madde 71. eur-lex.europa.eu.
5. Directive 2013/35/EU, elektromanyetik alanlara maruz kalan çalışanlar için asgari sağlık ve güvenlik gereklilikleri.
6. Laboratuvar föyleri 1–4 (bu repoda) ve makine-bilgisi.md.
