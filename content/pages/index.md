---
title: Home
slug: /
sections:
  - type: FeaturedItemsSection
    title:
      text: Desarrollando textiles de vanguardia desde 1967
      color: text-light
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items: []
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/gradient.svg
  - title:
      text: Cartas de colores
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      Descubrí la amplia variedad de colores que disponemos para nuestros
      artículos
    actions:
      - label: Explorar
        url: /cartas
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
    media:
      url: /images/carta-colores.png
      altText: Fun feature preview
      type: ImageBlock
    badge:
      label: Productos
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
    type: GenericSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
