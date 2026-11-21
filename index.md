---
layout: default
title: "Formda"
description: "Formda mobil uygulamasının gizlilik politikası, kullanım şartları, hesap silme ve destek bilgileri."
---

<section class="hero">
  <p class="eyebrow">Yasal metinler ve destek</p>
  <h1><strong>Formda</strong> ile ilgili<br>bilmen gereken her şey, açık ve sade.</h1>
  <p class="lead">Formda; beslenmeni ve antrenmanlarını sakin bir arayüzle takip etmeni sağlayan bir mobil uygulamadır. Bu sayfada uygulamanın yasal belgeleri ve destek bilgileri yer alır.</p>
</section>

<div class="cards">
  <a class="card" href="{{ '/gizlilik/' | relative_url }}">
    <h2>Gizlilik Politikası</h2>
    <p>Hangi verileri neden işliyoruz, kimlerle paylaşıyoruz, ne kadar saklıyoruz? KVKK aydınlatma metni dahil.</p>
    <span class="go">Oku →</span>
  </a>
  <a class="card" href="{{ '/kullanim-sartlari/' | relative_url }}">
    <h2>Kullanım Şartları</h2>
    <p>Hizmetin kapsamı, tıbbi tavsiye olmadığı, hesap ve içerikle ilgili kurallar.</p>
    <span class="go">Oku →</span>
  </a>
  <a class="card" href="{{ '/hesap-silme/' | relative_url }}">
    <h2>Hesap ve Veri Silme</h2>
    <p>Hesabını uygulamadan ya da e-postayla nasıl sildirirsin, neler silinir?</p>
    <span class="go">Nasıl yapılır →</span>
  </a>
  <a class="card" href="{{ '/destek/' | relative_url }}">
    <h2>Destek</h2>
    <p>Bir sorun mu yaşıyorsun, bir şey mi soracaksın? Bize nasıl ulaşırsın?</p>
    <span class="go">İletişim →</span>
  </a>
</div>

<div class="contact-box">
  <strong>Veri sorumlusu:</strong> {{ site.owner }}, {{ site.address }}<br>
  <strong>Gizlilik ve veri başvuruları:</strong> <a href="mailto:{{ site.privacy_email }}">{{ site.privacy_email }}</a><br>
  <strong>Destek:</strong> <a href="mailto:{{ site.support_email }}">{{ site.support_email }}</a>
</div>
