---
layout: doc
title: "Gizlilik Politikası ve KVKK Aydınlatma Metni"
description: "Formda'nın hangi kişisel verileri neden işlediği, kimlerle paylaştığı, ne kadar sakladığı ve KVKK kapsamındaki haklarınız."
permalink: /gizlilik/
eyebrow: Yasal · Gizlilik
---

# Gizlilik Politikası ve KVKK Aydınlatma Metni

<p class="meta">Yürürlük tarihi: <strong>24 Kasım 2026</strong> · Sürüm 1.1</p>

Formda ("uygulama"), beslenmeni ve antrenmanlarını takip etmeni sağlayan bir
mobil uygulamadır. Bu metin, 6698 sayılı Kişisel Verilerin Korunması Kanunu
("KVKK") kapsamında hangi verilerini neden işlediğimizi, nerede sakladığımızı
ve haklarını anlatır.

<nav class="toc" aria-label="İçindekiler" markdown="1">
<p>İçindekiler</p>

* TOC
{:toc}
</nav>

## 1. Veri sorumlusu

- **Ad soyad:** Eren Şimşek (bireysel geliştirici)
- **Adres:** Beykoz, İstanbul
- **E-posta (gizlilik ve veri başvuruları):** formda-gizlilik@smsekdev.com
- **E-posta (destek):** formda-destek@smsekdev.com

## 2. Hangi verileri işliyoruz?

| Veri | Örnek | Nerede |
|---|---|---|
| Hesap bilgisi | e-posta adresi, ad; Apple / Google ile girişte bu hizmetlerin verdiği e-posta ve ad | Bulut (hesabınla eşlenir) |
| Profil ve ölçümler | doğum tarihi, cinsiyet, boy, kilo, vücut ölçüleri, yağ oranı, hedefler, aktivite düzeyi | Bulut + telefon |
| Kayıtlar | öğünler, su, antrenmanlar, setler, günlük adım, gece uykusu (yatış ve kalkış saati, süre), takviye hatırlatıcıları, tercih ve alerjiler | Bulut + telefon |
| Kendi içeriğin | eklediğin yemekler, tarifler, katkı olarak gönderdiğin yemek / hareket bilgisi | Bulut |
| Uygulama kullanımı | hangi ekranın açıldığı, özelliklerin ne sıklıkla kullanıldığı (kimliğine bağlanmaz) | Google Firebase Analytics |
| Hata kaydı | çökme ve hata bilgisi, cihaz modeli, işletim sistemi sürümü; kullanıcı kimliği (ad / e-posta değil) | Sentry |

**Telefonundan çıkmayan veriler:**

- **Vücut fotoğrafları** yalnız telefonunda saklanır, hiçbir sunucuya gönderilmez.
- **Konum**, yalnız koşu / yürüyüş antrenmanı açıkken mesafe ölçmek için
  okunur; saklanmaz, gönderilmez. Arka planda konum alınmaz.
- **Menü / liste fotoğrafındaki yazı** telefonda okunur (Apple Vision /
  Google ML Kit); fotoğraf gönderilmez.
- **Sesli giriş:** mikrofon yalnız sen dokunduğunda açılır; ses kaydı
  saklanmaz. Telefonun destekliyorsa konuşma telefonda yazıya çevrilir;
  desteklemiyorsa ses, telefonunun işletim sistemi tarafından Apple ya da
  Google'ın konuşma tanıma hizmetine gönderilir. Formda bu sese erişmez.

**Apple Sağlık / Health Connect:** İzin verirsen (Profil → Sağlık ve saat)
Formda telefonundaki Apple Sağlık (iPhone) ya da Health Connect (Android)
uygulamasından **yalnız günlük adım sayını, dinlenme nabzını ve gece
uykunu okur** (üçü ayrı izindir); oraya hiçbir şey yazmaz. Okunan adım, diğer kayıtların gibi
hesabında saklanır ve günlük hareketini ve harcadığın enerjiyi tahmin etmek
için kullanılır. Dinlenme nabzının son 7 günlük ortancası profilindeki
dinlenme nabzı alanına yazılır ve antrenman nabız aralıklarını hesaplamakta
kullanılır. Son 7 gecenin uykusu (yatış, kalkış, süre) uyku kayıtlarına
yazılır; elle girdiğin gece ezilmez. Uyku raporda, uyum skorunda ve Profil →
Uyku'daki genel notlarda kullanılır; bu notlar tıbbi tavsiye değildir. Bu veri reklamda,
analitikte ya da pazarlamada kullanılmaz, kimseyle paylaşılmaz, iCloud'a
yazılmaz. Bağlantıyı aynı ekrandan ya da telefonunun Sağlık / Health Connect
ayarlarından istediğin an kapatabilirsin; daha önce okunan günler, sen
silene kadar kayıtlarında kalır.

Reklam göstermiyoruz, verini satmıyoruz, seni uygulamalar arasında
**takip etmiyoruz**.

### Verileri nasıl topluyoruz?

- **Doğrudan senden:** hesap açarken, profilini doldururken ve uygulamaya kayıt girerken yazdıkların.
- **İzin verirsen telefonundan:** Apple Sağlık / Health Connect (adım, dinlenme nabzı, uyku) ve bildirim izinleri; her biri telefonun kendi izin ekranından verilir.
- **Otomatik olarak:** uygulama kullanımı ve hata bilgisi (kimliğine bağlanmayan analitik ve hata kaydı).

## 3. Verilerini neden işliyoruz?

1. Hesabını açmak ve verilerini cihazların arasında eşlemek
2. Kalori ve makro hedeflerini, öneri ve raporları hesaplamak
3. Hatırlatıcı bildirimleri göndermek
4. Uygulamanın hatalarını bulup düzeltmek ve hangi özelliklerin işe yaradığını
   anlamak (analitik ve hata kaydı)
5. Hesap silme gibi yasal yükümlülükleri yerine getirmek

## 4. Hukuki sebepler

- **Sözleşmenin kurulması ve ifası** (KVKK m.5/2-c): hesap, kayıtlar,
  hesaplamalar, eşleme.
- **Meşru menfaat** (KVKK m.5/2-f): kimliğe bağlanmayan kullanım analitiği ve
  hata kaydı. Bunları istediğin an **Profil → Veri ve gizlilik → Anonim kullanım istatistikleri**'nden kapatabilirsin.
- **Açık rıza** (KVKK m.6): kilo, vücut ölçüleri, yağ oranı, alerji ve
  Apple Sağlık / Health Connect'ten okunan adım, dinlenme nabzı ve uyku gibi
  bilgiler **sağlık verisi** (özel nitelikli kişisel veri) sayılabilir. Bunları
  ilk kurulumdaki, diğer onaylardan ayrı olan "Sağlık verilerimin işlenmesine açık rıza veriyorum" onayınla; Apple Sağlık / Health Connect verilerini ayrıca, bağlantıyı kendin açtığında telefonun izin ekranında verdiğin izinle işleriz. Rızanı
  istediğin an geri alabilirsin; bu durumda hesabını silmen gerekir, çünkü
  uygulama bu veriler olmadan hesap yapamaz.

## 5. Kimlerle paylaşıyoruz?

Verilerini yalnız uygulamayı çalıştırmak için kullandığımız hizmet
sağlayıcılarla, yalnız gereken kadar paylaşırız:

| Sağlayıcı | Ne için | Konum |
|---|---|---|
| Supabase | Veritabanı, kimlik doğrulama | Almanya (Frankfurt, AB) |
| Google Firebase Analytics | Kimliğe bağlanmayan kullanım analitiği | ABD ve diğer ülkeler |
| Sentry | Hata kaydı | ABD |
| Apple, Google | "Apple ile giriş" / "Google ile giriş" | ABD |

Yasal zorunluluk olursa yetkili kamu kurumlarıyla da paylaşabiliriz.

## 6. Yurt dışına aktarım

Yukarıdaki sağlayıcıların sunucuları Türkiye dışındadır (Almanya/AB, ABD). KVKK
m.9/6-a uyarınca bu aktarımı **açık rızana** dayanarak yaparız; rızanı ilk
kurulumdaki onay adımında verirsin ve istediğin an geri alabilirsin (bkz. §4).

## 7. Ne kadar saklıyoruz?

- Hesabın açık olduğu sürece.
- **Hesabını silersen** (Profil → Veri ve gizlilik → Hesabımı sil; uygulamayı kurmadan silme isteği için
  [Hesap silme sayfası](../hesap-silme/)): hesabın hemen
  kapanır ve giriş yapılamaz; verilerin **90 gün** içinde geri alınabilsin
  diye bekletilir, sonra **kalıcı olarak silinir**.
- Hata kayıtları ve analitik verileri, sağlayıcıların saklama süreleriyle
  sınırlıdır: Firebase Analytics olay verileri **2 ay**, Sentry hata kayıtları
**30 gün** sonra silinir.

## 8. Çocuklar

Formda 13 yaşından küçükler için tasarlanmadı. 18 yaşından küçüksen
uygulamayı velinin bilgisiyle kullan.

## 9. Hakların (KVKK m.11)

Veri sorumlusuna başvurarak:

- verinin işlenip işlenmediğini öğrenme, işlenmişse bilgi isteme,
- amacını ve amacına uygun kullanılıp kullanılmadığını öğrenme,
- aktarıldığı kişileri bilme,
- eksik ya da yanlışsa düzeltilmesini, silinmesini isteme,
- otomatik sistemlerle analiz sonucu aleyhine bir sonuç çıkmasına itiraz etme,
- kanuna aykırı işleme nedeniyle zararının giderilmesini isteme

haklarına sahipsin. Başvurunu **formda-gizlilik@smsekdev.com** adresine yazabilirsin; en geç
**30 gün** içinde ücretsiz yanıtlanır. Uygulama içinden de verilerini
düzeltebilir ve hesabını silebilirsin.

## 10. Sağlık uyarısı

Formda'nın hesapladığı değerler genel nüfus için bilimsel formüllere dayalı
tahminlerdir; **tıbbi tavsiye değildir**. Kendi sağlık durumun için bir
hekime ya da diyetisyene danış.

## 11. Değişiklikler

Bu metni güncellediğimizde yürürlük tarihini değiştirir, önemli
değişiklikleri uygulama içinde bildiririz.
