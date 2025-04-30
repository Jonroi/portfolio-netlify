---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: Colour
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >-
      ## Welcome to my portfolio!

      I am a dedicated software developer and entrepreneur with a strong background in full-stack development and a growing specialization in AI technologies. My journey into tech is driven by a lifelong ambition to master software development and create intelligent, scalable solutions that make a real-world impact.


      I thrive both as a freelancer and in leadership roles, having worked across industries to build custom web applications, cloud-integrated systems, and tailored software platforms. I currently lead a team of developers at Psyche's Royal Gaming, overseeing the development of a large-scale project and ensuring technical alignment with business goals.


      In my current role as a Prompt Engineer at Outlier, I design, test, and optimize JavaScript-based prompts for generative AI applications. My work focuses on building efficient, accurate, and adaptable AI systems for real-world use cases, with an emphasis on LLM performance and prompt architecture.


      Technically, I specialize in React, Next.js, TypeScript, Nest.js, and AWS. I’m also expanding my skills in Python, SQL, Docker, and cloud-native development. I actively study modern AI practices, especially those involving generative models and autonomous agents.


      I’m currently pursuing the IBM AI Engineering Professional Certificate to deepen my understanding of machine learning, deep learning, and AI deployment strategies. Alongside this, I study software development at Salo Region Vocational School, focusing on JavaScript-based frameworks and full-stack architecture.


      I’m particularly interested in generative AI and machine learning, as well as web and cloud development . I’m always open to innovative opportunities in these areas and enjoy collaborating with others who are passionate about building the future of software.


      Feel free to explore my portfolio to see the projects I’ve worked on, and don't hesitate to reach out if you are interested in collaborating or discussing potential opportunities!

    media:
      type: ImageBlock
      url: /images/about.png
      altText: Hero image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        display: flex
        flexDirection: row
        alignItems: flex-start
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: GitHub
            url: 'https://github.com/Jonroi'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/in/joni-roine/'
        styles:
          self:
            textAlign: left
    columns: 3
    spacingX: 120
    spacingY: 0
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    subtitle: 'You can find me here:'
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: React
      - type: Label
        label: Nest.js
      - type: Label
        label: Next.js
      - type: Label
        label: Directus CMS
      - type: Label
        label: AWS
      - type: Label
        label: Docker
      - type: Label
        label: Python
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [joni.roine@outlook.com](mailto:joni.roine@outlook.com)
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: |-
          **Current**  

             * Lead Website Developer @ Psyche’s Royal Gaming
                 *	Managing a team of 10+ web developers in a large-scale project with over 60 participants.
                 *	Overseeing project coordination, ensuring efficient workflows, and aligning development with business goals.
           


             * Prompt Engineering
                 *   LLM promting tasks via Outlier platform
        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
      - type: FeaturedItem
        subtitle: 'Education:'
        text: |-
          **On going**
          * Graduating as a Software Developer in December 2025 @ Salo Region Vocational School.



          **Completed**

          * AI Agents and Agentic AI in Python: Powered by Generative AI

          * Coursera AWS Fundamentals (Technical Essentials, Migration, and Architecting Solutions).

          * Coursera Nest.js Fundamentals.
        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
