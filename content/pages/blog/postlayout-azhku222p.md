---
title: Post Title
date: '2021-10-24'
excerpt: >-
  This is the excerpt of your blog post visible in the post feed or featured
  posts.
featuredImage:
  type: ImageBlock
  url: /images/post-1.jpeg
  altText: Post thumbnail image
bottomSections:
  - elementId: contact-form
    colors: colors-a
    width: wide
    height: tall
    contentWidth: large
    contentAlignHoriz: center
    contentAlignVert: middle
    topGap: none
    bottomGap: none
    variant: variant-b
    title: Contact us
    text: We look forward to hearing from you.
    form:
      type: FormBlock
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: true
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: true
          width: 1/2
        - type: TextFormControl
          name: home-address
          label: Home address
          placeholder: Your home address
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
      submitLabel: Send Message
    feature:
      type: ImageBlock
      url: /images/contact.png
      altText: Contact form image
    action: /.netlify/functions/submission_created
    type: ContactSection
layout: PostLayout
author: content/data/team/desmond-eagle.json
---
## Lorem ipsum

Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

- Lorem ipsum
- dolor sit amet