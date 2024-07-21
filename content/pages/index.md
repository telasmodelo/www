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
  - subtitle: Award winning enterprises trust us
    images:
      - url: /images/empathy-logo.svg
        altText: Empathy logo
        type: ImageBlock
      - url: /images/wellster-logo.svg
        altText: Wellster logo
        type: ImageBlock
      - url: /images/vise-logo.svg
        altText: Vise logo
        type: ImageBlock
      - url: /images/telus-logo.svg
        altText: Telus logo
        type: ImageBlock
      - url: /images/contenful-logo.svg
        altText: Contentful logo
        type: ImageBlock
      - url: /images/sanity-logo.svg
        altText: Sanity logo
        type: ImageBlock
      - url: /images/rangle-logo.svg
        altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
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
  - title:
      text: Grow your business 10x faster
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: This is a subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    media:
      title: Title of the video
      url: /images/placeholder-video.mp4
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
      type: VideoBlock
      autoplay: true
      loop: true
      muted: true
    badge:
      label: Key Benefits
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection
  - type: GenericSection
    title:
      text: Generic section with a video
      color: text-dark
      styles:
        self:
          textAlign: left
      type: TitleBlock
    subtitle: Section with a video subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
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
      type: VideoBlock
    elementId: null
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - title:
      text: Social Media Management
      color: text-dark
      type: TitleBlock
    subtitle: Increase your reach
    text: >
      A service that helps businesses to manage their social media accounts and
      posts.
    actions:
      - label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/hero2.svg
      altText: Fun feature preview
      type: ImageBlock
    badge:
      label: This is a badge
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
    type: GenericSection
  - title:
      text: Business Consulting
      color: text-dark
      type: TitleBlock
    subtitle: Be in good company
    text: >
      A service that provides advice and guidance to startups and small
      businesses.
    actions:
      - label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/hero3.svg
      altText: Dope design preview
      type: ImageBlock
    badge:
      label: This is a badge
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
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
  - type: CarouselSection
    title: null
    subtitle: What our customers say about us
    items:
      - title: >-
          “A designer knows he has achieved perfection not when there is nothing
          left to add, but when there is nothing left to take away.”
        tagline: Testimonial 1
        subtitle: 'Maria Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Design is a plan for arranging elements in such a way as best to
          accomplish a particular purpose."
        tagline: Testimonial 2
        subtitle: 'John Doe, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: John Doe
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Design is how it works, how it functions. Good design doesn't just
          make a product aesthetically pleasing, it makes it a pleasure to use."
        tagline: Testimonial 3
        subtitle: 'Maria Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          “A designer knows he has achieved perfection not when there is nothing
          left to add, but when there is nothing left to take away.”
        tagline: Testimonial 4
        subtitle: 'Maria Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Design can be art. Design can be aesthetics. Design is so simple,
          that's why it is so complicated."
        tagline: Testimonial 5
        subtitle: 'Jane Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          “Quote from some important person goes right here. I love using
          Netlify Create.”
        tagline: Testimonial 6
        subtitle: 'Jane Doe, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/img-placeholder-dark.png
          altText: Jane Doe
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
    elementId: null
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: List of features here
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Featured items section subtitle
    items:
      - title: Feature Item One
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first Netlify Create site.
        image:
          url: /images/abstract-feature1.svg
          altText: Placeholder Image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Feature Item Two
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first awesome Netlify Create site.
        image:
          url: /images/abstract-feature2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Feature Item Three
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: >
          Learn from the tutorial and build your first awesome Netlify Create
          site.
        image:
          url: /images/abstract-feature1.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
  - title:
      text: Generic Section With A Form
      color: text-dark
      type: TitleBlock
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
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
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
