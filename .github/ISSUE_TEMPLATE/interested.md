name: A bit about you
description: Just a few questions to set the playing field - use your full name as the title.
body:
  - type: dropdown
    id: notification
    attributes:
      label: Notifications in GitHub setup
      description: |
        We assume that you have setup [notifications on your GitHub account](https://github.com/notifications) in such a a way, that we can communicate with you through _mentions_ and _assignments_ on issues - is that a fair assumption?
      options:
        - Yep - that's right, hit me!
        - No - I don't know how to set that up
      default: 0
    validations:
      required: true

  - type: dropdown
    id: markdown
    attributes:
      label: Confident in MarkDown
      description: |
        We assume that you are familiar with [GitHub flavoured MarkDown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) to an extend that you are confident to do this exercise and document your progress and replies here in GitHub Issues. Is that a fair assumption?
      options:
        - Yep - that's right!
        - No - Wait ...eeeh! MarkDown?
      default: 0
    validations:
      required: true
      

  - type: textarea
    id: in-your-own-words
    attributes:
      label: Bread crumbs...
      description: |
        If you have any relevant material or links publicly available on the internet that you would would like to draw our attention to. Please list them here.
      placeholder: |
        Linkedin posts, blog posts, articles, videos, podcasts, slide decks etc.
    validations:
      required: false

  - type: markdown
    attributes:
      value: |
        🤷‍♂️ Maybe you had more information you wanted to get off your chest?
        
        > [!TIP]
        > When you have submitted this issue, you can go back and find and open it and then chose to _edit_ the description.
        > It will open up as raw MarkDown - and you can take it in any direction you want - knock yourself out!