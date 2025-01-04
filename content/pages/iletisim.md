---
type: PageLayout
title: İletişim
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Projelerinize kurumsal çözüm için buradayız
      color: text-dark
    subtitle: 15 yılı aşan deneyim ile hizmetinizdeyiz
    text: >
      Seo alt yapısına uygun, işlevsel ve modern web siteleri geliştiriyoruz.
      Yaptığımız web sitelerin yüksek hızla daha geniş bir hedef kitleye
      ulaşmasını sağlıyoruz.
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: SubmitGönder
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: 'MESAJ ATIN, ARAYIN GÖRÜŞELİM'
      color: text-primary
    colors: bg-light-fg-dark
slug: iletisim
isDraft: false
seo:
  type: Seo
  metaTitle: Landing Page
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
