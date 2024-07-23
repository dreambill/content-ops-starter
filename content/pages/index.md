---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: ΑΝΑΣΤΑΣΙΑ ΓΟΔΕΒΕΝΟΥ
      color: text-dark
      type: TitleBlock
      styles:
        self:
          fontWeight: 400
          textAlign: left
    subtitle: INTERIOR DESIGNER
    text: >

      Είμαι η Αναστασία, interior designer με πάθος για τη δημιουργία μοναδικών
      και λειτουργικών χώρων που αντανακλούν την προσωπικότητά σας. Στόχος μου
      είναι να μετατρέψω κάθε σπίτι, γραφείο ή επαγγελματικό χώρο σε ένα μέρος
      όπου θα αισθάνεστε άνετα, ευχάριστα και δημιουργικά.


      Με έμφαση στη λεπτομέρεια και τη χρήση ποιοτικών υλικών, δουλεύω στενά με
      τους πελάτες μου για να κατανοήσω τις ανάγκες και τα όνειρά τους. Από τον
      αρχικό σχεδιασμό μέχρι την τελική υλοποίηση, είμαι εδώ για να σας
      καθοδηγήσω και να εξασφαλίσω ένα αποτέλεσμα που θα σας ενθουσιάσει.


      Ανακαλύψτε πώς μπορούμε να μεταμορφώσουμε το χώρο σας μαζί. Επικοινωνήστε
      μαζί μου για να συζητήσουμε τις ιδέες και τις επιθυμίες σας.
    actions: []
    media:
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
      text:
        textAlign: left
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
