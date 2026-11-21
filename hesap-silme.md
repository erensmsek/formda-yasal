---
layout: doc
title: "Hesap ve Veri Silme"
description: "Formda hesabını ve hesabına bağlı verilerini uygulamadan ya da e-postayla nasıl sildirebileceğin, neler silindiği ve ne kadar süre saklandığı."
permalink: /hesap-silme/
eyebrow: Yasal · Veri silme
---

# Hesap ve Veri Silme

<p class="meta">Yürürlük tarihi: <strong>21 Kasım 2026</strong> · Uygulama: Formda · Geliştirici: Eren Şimşek</p>

**Formda** uygulamasındaki hesabını ve hesabına bağlı verilerini istediğin an sildirebilirsin.
Uygulama telefonunda kurulu değilse ya da erişimin yoksa e-postayla da
isteyebilirsin.

## 1. Uygulamadan silme

1. Formda'yı aç ve giriş yap.
2. **Profil → Veri ve gizlilik → Hesabımı sil**'e dokun.
3. Onayla.

Hesabın hemen kapanır, bu hesapla giriş yapılamaz.

## 2. E-postayla silme isteği

Uygulamayı kurmadan ya da giriş yapamadan silme isteği için **formda-gizlilik@smsekdev.com**
adresine, hesabını açarken kullandığın e-posta adresinden yaz. Konu:
"Hesap silme isteği". Kimliğini doğrulamak için hesapla aynı adresten yazman
gerekir. İsteğin en geç **30 gün** içinde ücretsiz yanıtlanır.

## 3. Neler silinir, ne kadar süreyle saklanır?

| Veri | Ne olur |
|---|---|
| Hesap bilgisi (e-posta, ad) | Silinir |
| Profil ve ölçümler (boy, kilo, hedefler vb.) | Silinir |
| Kayıtların (öğünler, su, antrenmanlar, adım, uyku, takviye hatırlatıcıları) | Silinir |
| Kendi eklediğin yemekler ve tarifler | Silinir |
| Telefonundaki vücut fotoğrafları | Hiçbir zaman sunucuya gönderilmedi; uygulamayı silince telefondan da gider |

**Süre:** Hesabın kapandıktan sonra verilerin yanlışlıkla silinme ihtimaline
karşı **90 gün** boyunca geri alınabilir şekilde bekletilir, bu süre dolunca
**kalıcı olarak silinir**.

**Kimliğine bağlanmayan veriler:** Hata kayıtları (Sentry, 30 gün) ve kullanım
istatistikleri (Firebase Analytics, 2 ay) hesabınla eşleşmez ve sağlayıcıların
saklama süreleri sonunda kendiliğinden silinir.

**Katkı olarak gönderdiğin yemek / hareket bilgisi:** Herkesin kullandığı
veritabanına eklenmişse kişisel bilgin içermez ve besin değeri bilgisi olarak
kalabilir (bkz. [Kullanım Şartları](../kullanim-sartlari/) §4).

Daha fazla bilgi: [Gizlilik Politikası](../gizlilik/).
