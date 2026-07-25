===============================================================================
VETERAN KAYNAK-ERİŞİLEBİLİR LİSANS (VSAL)
Sürüm 1.2 - Genel Kaynak-Erişilebilir ve Denetlenebilir Yazılım Lisansı
===============================================================================

Telif Hakkı (c) [2026] [Berkay Kesgin / VoidOaz]. Tüm Hakları Saklıdır.

-------------------------------------------------------------------------------
ÖNSÖZ VE AMAÇ
-------------------------------------------------------------------------------
Bu Lisans Sözleşmesi ("Lisans"), Yazar (VoidOaz) ile
Yazılıma erişen, inceleyen, derleyen veya değerlendiren herhangi bir gerçek
kişi, tüzel kişi veya kuruluş ("Berkay Kesgin" veya "VoidOaz") arasında akdedilen
yasal bir sözleşmedir.

Yazar, sunucu yöneticileri, geliştiriciler ve güvenlik araştırmacıları için tam
kaynak kodu şeffaflığı, statik güvenlik denetimi ve operasyonel doğrulama
sağlamak amacıyla Yazılımı oluşturmuş ve geliştirmiştir.

Yazar, Yazılım üzerindeki tüm fikri mülkiyet haklarını, telif haklarını ve
mülkiyet haklarını saklı tutar. Kaynak Koduna erişim, yalnızca bu Lisans'ta
tanımlanan açık hüküm, koşul ve sınırlamalara tabi olarak sağlanır.

BU YAZILIM "KAYNAK-ERİŞİLEBİLİR" BİR MODEL ALTINDA SUNULMAKTADIR. AÇIK KAYNAK
GİRİŞİMİ (OSI) TARAFINDAN TANIMLANDIĞI ŞEKİLDE AÇIK KAYNAK KODLU YAZILIM,
ÖZGÜR YAZILIM VEYA KAMU MALI DEĞİLDİR. KAYNAK KODUNA ERİŞİM, YALNIZCA BURADA
BELİRTİLEN DENETİM, İNCELEME VE TİCARİ OLMAYAN TEST AMAÇLARI İÇİN VERİLİR.


===============================================================================
BÖLÜM 1 - TANIMLAR
===============================================================================

1.1 "Yazar", [VoidOaz]'nı, Yazılımın tek yaratıcısı ve
telif hakkı sahibini ifade eder.

1.2 "Yazılım", bu paket kapsamında sağlanan kaynak kod dosyaları, derlenmiş
bytecode (.jar, .class), derleme yapılandırmaları, varlık dosyaları,
dokümantasyon ve algoritmaların tümünü ifade eder.

1.3 "Kaynak Kodu", Yazılımı oluşturan insan tarafından okunabilir programlama
dili dosyalarını (Java, XML ve derleme betikleri dahil) ifade eder.

1.4 "İkili Dosya" veya "Derlenmiş Çalıştırılabilir", Kaynak Kodundan üretilen
bilgisayar tarafından okunabilir bytecode arşivlerini (.jar) veya
çalıştırılabilir dosyaları ifade eder.

1.5 "Denetim" veya "İnceleme", güvenliği, performansı ve zararlı kod
bulunmadığını doğrulamak amacıyla yürütülen tahribatsız, salt okunur
inceleme veya statik analizi ifade eder.

1.6 "Üretim Ortamı", son kullanıcılar veya oyuncular tarafından erişilebilen,
canlı, genel, ağa bağlı veya ticari herhangi bir sunucu örneğini (Minecraft
sunucu ağları, proxy'ler veya konteynerler dahil) ifade eder.

1.7 "Ticari Olmayan Yerel Test", herhangi bir finansal ödeme, bağış veya ticari
menfaat kabul etmeksizin, Yazılımı yalnızca özel, çevrimdışı, genel olmayan
bir makinede veya yerel ortamda (localhost) çalıştırmayı ifade eder.

1.8 "Yetkili Dağıtım Kanalı", Yazar tarafından resmi olarak işletilen veya
yazılı olarak açıkça yetkilendirilmiş platformları, web sitelerini veya
depoları ifade eder.

1.9 "Türev Çalışma", Yazılımın Kaynak Kodunun önemli bölümlerini doğrudan
içeren, kopyalayan veya yeniden kullanan herhangi bir yazılım veya modülü
ifade eder. Yazılımın Kaynak Kodundan kopyalama yapmayan benzer işlevselliğe
sahip bağımsız uygulamalar Türev Çalışma olarak kabul edilmez.

1.10 "Lisans Anahtarı" veya "Doğrulama Protokolü", üretim ortamında
çalıştırmayı yetkilendirmek için Yazar tarafından sağlanan bir belirteç,
anahtar veya çevrimiçi doğrulama protokolünü ifade eder.


===============================================================================
BÖLÜM 2 - İZİN VERİLEN KULLANIMLAR (ŞEFFAFLIK VE DENETİM)
===============================================================================

2.1 Kaynak Kodu İnceleme
Bu Lisans'a uyulması koşuluyla Yazar, Kaynak Kodunu görüntüleme, okuma ve
inceleme için Size münhasır olmayan, devredilemez, sınırlı bir hak verir.
Bu hak, Bölüm 4'e aykırı olarak daha fazla dağıtmamanız koşuluyla, Lisans
başka nedenlerle feshedilse dahi, eriştiğiniz Kaynak Kodunun belirli sürümü
için kalıcıdır.

2.2 Güvenlik Denetimi ve Statik Analiz
Performansı ve güvenlik bütünlüğünü doğrulamak amacıyla Kaynak Kodu üzerinde
statik kod analiz araçları, güvenlik tarayıcıları ve yerel profil oluşturma
yazılımları çalıştırmaya tamamen izin verilir.

2.3 Denetim Raporlarının Yayınlanması
Aşağıdaki koşullara uymak kaydıyla bağımsız teknik incelemeler veya güvenlik
denetim raporları yayınlayabilirsiniz:
(a) Raporlar teknik ve objektif olmalıdır;
(b) Güvenlik açıkları bu Lisansın 8. Bölümüne uygun olarak ele alınmalıdır;
(c) Rapor, bulguları göstermek için gerekli olan adil kullanım kod
    alıntılarının ötesinde tüm kaynak dosyaları çoğaltmamalıdır.

2.4 Geri Bildirim ve Topluluk Katkıları
Yazar'a hata raporları, güvenlik bildirimleri veya kod katkıları
göndermeniz halinde, Yazar'a bu geri bildirimleri Yazılım içerisinde
kullanma ve ticarileştirme hakkı için sürekli, dünya çapında, münhasır
olmayan bir hak vermiş olursunuz. Karşılığında Yazar, katkıda bulunan kişiyi,
projenin dokümantasyonu, CREDITS dosyası veya Yazılımın resmi deposunda
tutulan eşdeğer bir kamusal atıf mekanizması içinde kamuya açık olarak
tanımayı ve atıf yapmayı taahhüt eder. Bu atıf, dahil edilen katkı Yazılımın
bir parçası olarak kaldığı sürece muhafaza edilir.


===============================================================================
BÖLÜM 3 - ÜRETİM ORTAMINDA ÇALIŞTIRMA VE TİCARİ KULLANIM
===============================================================================

3.1 Ticari Lisans Zorunluluğu
Derlenmiş İkili Dosyayı (.jar) herhangi bir Üretim Ortamında çalıştırmak,
barındırmak veya yürütmek, doğrudan Yazar'dan veya Yetkili Dağıtım
Kanalından alınmış geçerli bir Ticari Lisans veya açık yetkilendirme
gerektirir.

3.2 Ticari Olmayan Yerel Değerlendirme
Yazılımı yalnızca Ticari Olmayan Yerel Test amacıyla çalıştırmanız için
size sınırlı bir ayrıcalık tanınmıştır. Bu ayrıcalık, sunucunun genel
erişime açık hale gelmesi veya ticari gelir/bağış elde etmeye başlaması
halinde derhal sona erer.


===============================================================================
BÖLÜM 4 - KOD YENİDEN DAĞITIMI VE DERLEME KISITLAMALARI
===============================================================================

4.1 Kaynak Kodun Aynen Kullanımı ve Çıkarma
Yazılımın Kaynak Kodunu veya sınıf dosyalarını, Yazar'dan yazılı izin
almaksızın diğer genel veya ticari projelere kopyalayamaz, çıkaramaz,
çoğaltamaz veya yeniden dağıtamazsınız.

4.2 Yeniden Dağıtım Kısıtlamaları
Kaynak Kodunu veya derlenmiş İkili Dosyaları, üçüncü taraf dosya paylaşım
platformlarında veya yetkisiz genel depolarda barındıramaz, yeniden
satamaz, yeniden lisanslayamaz veya dağıtamazsınız.

4.3 Kendi Kendine Derleme
Kaynak Kodunu çalıştırılabilir ikili dosyalara (.jar) kendi kendine
derlemeye, yalnızca yerel hata ayıklama, eğitim ve resmi İkili Dosyanın
genel Kaynak Koduyla eşleştiğini doğrulama (örneğin, tekrarlanabilir derleme
karşılaştırması yoluyla) amacıyla kesinlikle izin verilir. Kendi derlediğiniz
ikili dosyaları geçerli bir ticari anlaşma olmadan herhangi bir Üretim
Ortamına dağıtmak yasaktır.


===============================================================================
BÖLÜM 5 - FİKRİ MÜLKİYET HAKLARI
===============================================================================

5.1 Sahiplik
Kaynak kodu, marka ve orijinal varlıklar dahil olmak üzere Yazılım
üzerindeki tüm haklar, unvanlar ve menfaatler münhasıran Yazar'a aittir.

5.2 Bildirimlerin Korunması
Kaynak Kodu dosyalarının içine gömülmüş herhangi bir telif hakkı bildirimi,
yazar kredisi veya atıf başlığını kaldıramaz, gizleyemez veya
değiştiremezsiniz. Bu yükümlülük, sunucu yönetim araçları tarafından
gerçekleştirilen sıradan sunucu günlüğü filtreleme veya konsol çıktısı
bastırma işlemlerini kapsamaz; yeter ki altta yatan kaynak başlıkları
bozulmadan kalsın.


===============================================================================
BÖLÜM 6 - ÜÇÜNCÜ TARAF KÜTÜPHANELER VE BAĞIMLILIKLAR
===============================================================================

6.1 Kapsam
Bu Lisans yalnızca Yazar tarafından yazılmış orijinal kod için geçerlidir.
Yazılım tarafından referans verilen üçüncü taraf kütüphaneler veya açık
kaynak API'ler (Spigot, Paper, Velocity, Jackson, Guava vb.) kendi ilgili
açık kaynak lisanslarına tabi olmaya devam eder.


===============================================================================
BÖLÜM 7 - YAZILIM BÜTÜNLÜĞÜ VE LİSANS DOĞRULAMASI
===============================================================================

7.1 Bütünlük Garantisi
Yazar, Yetkili Kanallar'dan yapılan resmi sürümlerin gizli keylogger'lar,
yıkıcı fidye yazılımları veya zararlı veri silme kodları içermediğini
taahhüt eder.

7.2 Asenkron Lisans Doğrulaması
Yazılım, aktif üretim lisans anahtarlarını doğrulamak için hafif, asenkron
bir ağ protokolü içerebilir. Bu işlem yalnızca temel operasyonel meta
verileri iletir: lisans anahtarı, sunucunun genel IP adresinin tuzlanmış
kriptografik karması (SHA-256) (düz IP'yi ifşa etmez), yazılım sürümü ve
çalışma zamanı Java sürümü. Hiçbir son kullanıcı kişisel verisi, sohbet
günlüğü, oyuncu verisi veya veritabanı içeriği toplanmaz, saklanmaz veya
iletilmez.


===============================================================================
BÖLÜM 8 - SORUMLU GÜVENLİK AÇIĞI BİLDİRİMİ
===============================================================================

8.1 Gizli Bildirim
Kaynak incelemesi sırasında bir güvenlik açığı keşfetmeniz halinde, kamuya
açıklama yapmadan önce bu açığı özel olarak Yazar'a bildirmeyi kabul
edersiniz.

8.2 Çözüm Süresi ve Sorumlu İfşa
Yazar'a, bildirilen sorunu incelemesi ve düzeltmesi için 30 günlük bir süre
tanınır. Güvenlik açığı sahada aktif olarak istismar ediliyorsa ("zero-day"),
kamu güvenliği için teknik uyarılar yayınlanmadan önce 7 günlük kısaltılmış
bir bildirim süresi uygulanır. Tüm durumlarda ifşa, teknik detaylar geniş
çapta yayınlanmadan önce kullanıcıların bir yamaya erişebilmesini sağlamak
amacıyla koordineli olarak yapılmalıdır.


===============================================================================
BÖLÜM 9 - FESİH VE YAPTIRIMLAR
===============================================================================

9.1 Otomatik Fesih
Yazılımı çalıştırma, dağıtım için derleme veya başka şekilde kullanma
haklarınız (Bölüm 2.1'de verilen kalıcı kaynak inceleme hakkı hariç),
bu Lisansın herhangi bir maddi hükmüne uymamanız halinde otomatik olarak
sona erer.

9.2 Feshin Sonuçları
Fesih üzerine, Yazılımın tüm üretim ve yerel çalıştırmasını durdurmalı,
ihlalde kullanılan tüm derlenmiş ikili dosyaları kaldırmalı ve izin verilen
inceleme kanalı dışında elde edilen yetkisiz Kaynak Kodu kopyalarını imha
etmelisiniz. Kamuya açık Kaynak Kodunu tarihsel/denetim amacıyla saklama ve
inceleme hakkı kalıcı olup, daha fazla dağıtmamanız koşuluyla fesihten
sonra da devam eder.

9.3 Yasal Yaptırımlar
Yetkisiz ticari kullanım, yetkisiz yeniden lisanslama veya kasıtlı kod
hırsızlığı, sözleşmenin ihlali ve telif hakkı ihlali teşkil eder. Yazar,
yürürlükteki yasalar uyarınca yasal yollara başvurma, ihtiyati tedbir ve
telif hakkı kaldırma bildirimleri dahil tüm haklarını saklı tutar.


===============================================================================
BÖLÜM 10 - GEÇERLİ HUKUK VE YARGI YETKİSİ
===============================================================================

10.1 Geçerli Hukuk
Bu Lisans, kanunlar ihtilafı hükümleri dikkate alınmaksızın,
[YARGI YETKİSİ / ÜLKE] yasalarına göre yönetilecek ve yorumlanacaktır.


===============================================================================
BÖLÜM 11 - GARANTİ REDDİ VE SORUMLULUĞUN SINIRLANDIRILMASI
===============================================================================

11.1 Garanti Reddi
YAZILIM "OLDUĞU GİBİ" SUNULMAKTA OLUP, AÇIK VEYA ZIMNİ HİÇBİR GARANTİ
VERİLMEMEKTEDİR. YAZAR, YAZILIMIN KULLANIMINDAN VEYA İŞLENMESİNDEN
KAYNAKLANAN HİÇBİR TALEP, HASAR, VERİ KAYBI VEYA DİĞER SORUMLULUKLARDAN
HİÇBİR ŞEKİLDE SORUMLU TUTULAMAZ.

11.2 Sorumluluğun Sınırlandırılması
GEÇERLİ YASANIN İZİN VERDİĞİ AZAMİ ÖLÇÜDE, YAZAR, BU TÜR HASARLARIN
OLASILIĞI KONUSUNDA BİLGİLENDİRİLMİŞ OLSA DAHİ, DOLAYLI, ARIZİ, ÖZEL VEYA
SONUÇ OLARAK ORTAYA ÇIKAN HİÇBİR HASARDAN (KAR KAYBI, İŞ KESİNTİSİ VEYA
VERİ KAYBI DAHİL) SORUMLU OLMAYACAKTIR.


===============================================================================
BÖLÜM 12 - AYRILABİLİRLİK
===============================================================================

12.1 Bu Lisansın herhangi bir hükmü, yetkili bir mahkeme tarafından geçersiz
veya uygulanamaz bulunursa, söz konusu hüküm, tarafların amacını
gerçekleştirecek şekilde izin verilen azami ölçüde uygulanacak ve Lisansın
geri kalan hükümleri tam olarak yürürlükte kalmaya devam edecektir.


===============================================================================
LİSANS METNİNİN SONU - VSAL v1.2
===============================================================================
