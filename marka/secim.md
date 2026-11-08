# Günay Studio — Kurumsal Kimlik ve Yön Seçimi

## Üretilen Üç Yön ve Özeleştiri

| Yön | Dosyalar | Kavram ve Mimari | Sert Özeleştiri (Üst Lig Gözüyle) |
| :--- | :--- | :--- | :--- |
| **Yön 1 (Seçilen)**<br>*Tutulma ve Zenit Küresi* | `1-logo.svg`<br>`1-logo-mono.svg`<br>`1-wordmark.svg`<br>`1-wordmark-mono.svg` | **Gün** (tam küre) ve **Ay** (hilal kundağı) kavramlarının tek bir eksenel geometri içinde soyutlanması. Palantir, Vercel ve Dieter Rams (Braun) çizgisinde; zamansız, sakin ve anıtsal bir sembol. Tipografide optik olarak sıkılaştırılmış (`-0.018em`), yüksek okunaklılığa sahip neo-grotesk yapı. | En güçlü ve zamansız çözüm. İsimle kurduğu kavramsal bağ zorlama değil, saf geometriye dayanıyor. 29px LinkedIn yorum boyutunda dahi iç küre ve alt hilal birbirine yapışmadan anında seçiliyor. |
| **Yön 2**<br>*Brütalist Monolit* | `2-logo.svg`<br>`2-logo-mono.svg`<br>`2-wordmark.svg`<br>`2-wordmark-mono.svg` | Anduril ve klasik İsviçre (Chermayeff & Geismar) ekolünde, tek bir dikey/yatay poligondan oluşan ağır mimari `G` kasası. Boğaz açıklığı ile iç hazne yüksekliği milimetrik olarak eşit (`26` birim). Yazı markasında **GÜNAY** (600) ve **STUDIO** (420) ağırlık kontrastı. | Mühendislik ve savunma/altyapı ağırlığı çok yüksek; 29px'te keskin bir piksel netliği veriyor. Ancak oyun ve tüketiciye dönük masaüstü/mobil ürünlerde Yön 1 kadar sıcak ve evrensel bir şemsiye hissi vermiyor; fazla sert ve endüstriyel kalıyor. |
| **Yön 3**<br>*Klasik Editoryal Otorite* | `3-logo.svg`<br>`3-logo-mono.svg`<br>`3-wordmark.svg`<br>`3-wordmark-mono.svg` | Kökleri 16. yüzyıl matbaa geleneğine uzanan yüksek kontrastlı serif (`Cormorant Garamond`) yazı markası ve dört köşeli usturlap yıldızıyla dengelenmiş `G` mührü. | Prestij, entelektüel ağırlık ve "eski para" (old-money) hissi en yüksek alternatif. Buna karşın, geliştirici araçları (CLI/SDK) ve yapay zeka yazılımları üreten bir teknoloji evi için fazla editoryal/yayın evi karakterinde kalıyor; ayrıca serif incelikleri 29px boyutunda geometrik bir sembol kadar tok durmuyor. |

---

## Seçim ve Gerekçe: Yön 1 (`1-*`)

**Seçilen Yön:** **Yön 1** (`1-logo.svg`, `1-wordmark.svg` ve `-mono` sürümleri).

1. **İsimden Doğan Saf Geometri:** "Günay" kelimesini oluşturan iki kozmik unsuru (*Gün* ve *Ay*) illüstrasyona kaçmadan, tek bir dış çember (`R=84`) içinden eksantrik olarak oyulmuş hilal (`r=56`) ve merkezdeki zenit küresi (`r=27.5`) ile tek bir matematiksel formda birleştirir. Palantir'in küre-kaide soyutlaması veya Vercel'in saf üçgeni gibi, ilk bakışta akılda kalan ve 50 yıl sonra da eskimeyecek bir ağırlığa sahiptir.
2. **Çoklu Disiplin Şemsiyesi:** Günay Studio hem geliştirici araçları ve yapay zeka yazılımları, hem de masaüstü/mobil uygulamalar ve oyunlar üretmektedir. Yön 1; bir terminal aracının yanında duracak kadar ciddi ve keskin, bir oyunun açılış ekranında (splash screen) belirecek kadar ikonik, kurumsal bir sözleşmenin antetinde yer alacak kadar ağırbaşlıdır.
3. **Teknik Kusursuzluk ve Ölçeklenebilirlik:**
   - **LinkedIn Dairesel Kırpma (`r=200`):** 512×512 tuvalde amblem yarıçapı `159.6px` olarak ayarlanmış, dairesel profil kırpmasında etrafında dengeli bir karanlık/aydınlık nefes alanı bırakılmıştır.
   - **29px Mikro Okunabilirlik:** Küre ile hilal arasındaki negatif boşluk kanalı (`28.5` birim), logo 29×29 piksele küçüldüğünde dahi kapanmaz; leke dağılımı bozulmadan okunur.
   - **Sıfır Font Bağımlılığı ve Kusursuz Diyakritik:** Tüm harfler ve `ü` harfinin noktaları doğrudan kapalı bezier eğrilerine (`<path>`) dönüştürülmüş, harf çiftleri (`Gü`, `ay`, `St`) optik olarak elle dengelenmiştir.
   - **Tek Renk Disiplini:** Ana sürümler derin obsidyen (`#09090B`) üzerinde kırık tebeşir beyazı (`#F4F4F5`) kullanır; `-mono` sürümleri ise şeffaf zemin üzerinde saf tek renk `<path>` yapısıyla her yüzeye doğrudan uygulanabilir.

nihai karar: yon 3 (editoryal serif) secildi; yon 1 ve 2 elendi.
g'nin yanindaki dort koseli yildiz tamamen kaldirilarak yalnizca tek basina anitsal 'G' harfi birakildi; 'ü' noktalari 'i' harfinin noktasiyla ayni optik agirlik ve yukseklik eksenine hizalandi.
final-logo.svg, final-logo-ters.svg, final-wordmark.svg, final-wordmark-ters.svg, final-logo-300.png ve final-kapak-1128x191.png yalnizca siyah (#0D0C0A) ve fildisi (#F5F2EB) paletiyle uretildi.
