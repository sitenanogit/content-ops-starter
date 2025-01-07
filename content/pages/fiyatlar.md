---
title: Fiyatlar
slug: fiyatlar
sections:
  - title:
      text: Farklı hizmetler aynı anda tek yerde
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: >-
      Her bütçeye göre web site, sipariş sistemi, e-ticaret çözümleri bir arada
      uygun fiyatlarla hizmetinizdeyiz.
    plans:
      - title: Kurumsal Web Sayfası
        price: Teklif al
        details: Örnek sayfa ve içeriklerinize göre belirlenir
        description: >
          Kurumsal web siteleri, mobil uyumluluk, kullanıcı dostu arayüzler,
          hızlı yükleme süreleri ve arama motoru optimizasyonu (SEO) gibi teknik
          detaylara dikkat edilerek tasarlanır.
        features:
          - firmanıza özel tasarım
          - seo anahtar kelime çalışmaları
          - mobil sayfa & hız testleri
          - 'alan adı, sunucu bakım, güncellemeler'
        image:
          url: /images/cmsnano-logo_yesil.png
          altText: Web Tasarım Fiyatları
          type: ImageBlock
        actions:
          - type: Button
            label: İncele
            altText: ''
            url: /
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
          - label: Teklif al
            url: /contact
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: Yerli Üretim Sipariş Sistemi
        price: 4.900₺
        details: yıllık alımlarda geçerli başlangıç fiyatıdır
        description: |
          Trenyol, Yemeksepeti entegrasyonları
        features:
          - özel alan adınız ile çalışır
          - kurulum desteği ücretsizdir
          - siparişlerinizde ekstra komisyon alınmaz
          - üyelere özel indirim yapılabilir
          - 1 şube için geçerli fiyattır
          - kampanya ve duyurular sunulabilir
          - entegrasyonlar ücretlidir
        image:
          url: /images/komisyonsuz-logo-red-white_250 (1).png
          altText: Sipariş Alma Sistemi Fiyatları
          type: ImageBlock
        actions:
          - label: Kur & Dene
            url: 'https://admin.komisyonsuz.com/admin/register.html'
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
            altText: komisyonsuz sipariş sistemi kur ve dene
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: Yerli Üretim Profesyonel E-ticaret
        price: 9.900₺
        details: yıllık alımlarda geçerli başlangıç fiyatıdır
        description: |
          Trendyol, Hepsiburada, Amazon ve Etsy Entegrasyonları
        features:
          - 'e-ihracat, çoklu dil, çoklu stok ve lokasyon'
          - 'amazon, trendyol, hepsiburada, n11, pazarama entegrasyonları'
          - 'sepet hatırlatmaları, teklifli satış, dropshipping'
          - 'bölge bazlı ve saat bazlı teslimat, kargo entegrasyonları'
          - ürün yorumları ve cevaplama
          - 'AI ürün liste planları, AI ürün fiyatlama'
        image:
          url: /images/footer-logo.png
          altText: E-ticaret Sitesi Fiyatları
          type: ImageBlock
        actions:
          - label: Kur & Dene
            url: 'https://eticaret.sitenano.com/account/register/?next=/'
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
            altText: Profesyonel e-ticaret sitesi
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: PricingSection
  - type: FeaturedPostsSection
    posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    actions: []
    variant: three-col-grid
    colors: bg-light-fg-dark
    hoverEffect: shadow-plus-move-up
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic section with a video
      color: text-dark
      styles:
        self:
          textAlign: left
    subtitle: Section with a video subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
      type: VideoBlock
      title: Title of the video
      url: /images/placeholder-video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-3
          - pl-3
          - pb-3
          - pr-3
seo:
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
