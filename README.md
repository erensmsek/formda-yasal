<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/img/formda-logo-light.svg">
    <img src="assets/img/formda-logo.svg" alt="FormDa" height="96">
  </picture>
</p>

<h1 align="center">FormDa — Yasal Metinler</h1>

<p align="center">
  FormDa mobil uygulamasının gizlilik politikası, kullanım şartları, hesap silme ve destek sayfaları.
</p>

<p align="center">
  <a href="https://erensmsek.github.io/formda-yasal/">Siteyi aç</a> ·
  <a href="https://erensmsek.github.io/formda-yasal/gizlilik/">Gizlilik</a> ·
  <a href="https://erensmsek.github.io/formda-yasal/kullanim-sartlari/">Kullanım şartları</a> ·
  <a href="https://erensmsek.github.io/formda-yasal/hesap-silme/">Hesap silme</a> ·
  <a href="https://erensmsek.github.io/formda-yasal/destek/">Destek</a>
</p>

---

## Bu depo nedir?

FormDa; beslenmeyi ve antrenmanı sakin bir arayüzle takip etmeyi sağlayan bir mobil uygulamadır. Bu **herkese açık** depo, uygulamanın mağaza girişlerinde ve uygulama içinde bağlantı verilen yasal belgeleri [GitHub Pages](https://pages.github.com/) ile yayınlar. Uygulamanın kaynak kodu bu depoda **yer almaz**.

| Sayfa | Adres | Kullanıldığı yer |
|---|---|---|
| Gizlilik Politikası ve KVKK Aydınlatma Metni | [`/gizlilik/`](https://erensmsek.github.io/formda-yasal/gizlilik/) | Uygulama, App Store ve Google Play gizlilik bağlantısı, Android Health Connect |
| Kullanım Şartları | [`/kullanim-sartlari/`](https://erensmsek.github.io/formda-yasal/kullanim-sartlari/) | Uygulama |
| Hesap ve Veri Silme | [`/hesap-silme/`](https://erensmsek.github.io/formda-yasal/hesap-silme/) | Google Play veri güvenliği formu |
| Destek | [`/destek/`](https://erensmsek.github.io/formda-yasal/destek/) | App Store destek bağlantısı |

## İletişim

- Destek: [formda-destek@smsekdev.com](mailto:formda-destek@smsekdev.com)
- Kişisel veri başvuruları (KVKK): [formda-gizlilik@smsekdev.com](mailto:formda-gizlilik@smsekdev.com)
- Veri sorumlusu: Eren Şimşek, Beykoz / İstanbul

## Site yapısı

Site, GitHub Pages'in Jekyll'iyle özel bir temayla (`_layouts/`, `assets/`) derlenir; harici paket, izleyici ya da çerez kullanmaz. Yazı tipi (Rubik, SIL Open Font License) siteden sunulur, Google Fonts'a istek gitmez.

```
├── _config.yml          site ayarları, gezinme, iletişim bilgileri
├── _layouts/            sayfa şablonları (default, doc)
├── assets/              stil, yazı tipi, logo
├── index.md             ana sayfa
├── gizlilik-politikasi.md
├── kullanim-sartlari.md
├── hesap-silme.md
└── destek.md
```

## Metinler değişirse

Belge değişince sayfadaki **Yürürlük tarihi** güncellenir. Önemli değişiklikler uygulama içinde de duyurulur. Bu depodaki geçmiş (`git log`) belgelerin önceki sürümlerini gösterir.

## Lisans ve haklar

Metinler ve FormDa adı/logosu © 2026 Eren Şimşek, tüm hakları saklıdır. Rubik yazı tipi [SIL Open Font License 1.1](https://openfontlicense.org/) ile lisanslıdır.
