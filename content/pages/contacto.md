---
type: PageLayout
title: Contactanos
sections:
  - type: GenericSection
    subtitle: ''
    text: ''
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Tu nombre
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Tu email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Tu mensaje
          width: full
          isRequired: true
      submitButton:
        type: SubmitButtonFormControl
        label: Enviar
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
      label: EMPRESA
      color: text-primary
    colors: bg-light-fg-dark
    title:
      type: TitleBlock
      text: Contactanos
      color: text-dark
slug: contacto
isDraft: false
seo:
  type: Seo
  metaTitle: Landing Page
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
