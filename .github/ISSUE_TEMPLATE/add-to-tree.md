name: Add myself or my branch to the family tree
description: Add yourself or your direct line to the global interactive tree
title: "[Tree] Add: FIRST LAST (YYYY–YYYY)"
labels: ["tree", "new person"]
body:
  - type: markdown
    attributes:
      value: |
        Fill in as much as you know. The more dates/places, the better we can connect you!
  - type: input
    attributes:
      label: Your full name
      placeholder: "John William Cockerham"
    validations:
      required: true
  - type: input
    attributes:
      label: Birth year & place
      placeholder: "1985, Charlotte, North Carolina, USA"
  - type: input
    attributes:
      label: Father's full name (if known)
      placeholder: "Robert James Cockerham (1955–2020)"
  - type: input
    attributes:
      label: Grandfather's full name (if known)
      placeholder: "William Henry Cockerham (1920–1998)"
  - type: textarea
    attributes:
      label: Anything else? (DNA haplogroup, migration story, etc.)