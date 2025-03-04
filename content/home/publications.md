---
active: true
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Publications
# TODO
subtitle: 'See also my [Google Scholar](https://scholar.google.com/) profile'

content:
  # Filter on criteria
  filters:
    folders:
      - publications
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 5
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
  filter_default: 0
  filter_button:
    - name: All
      tag: '*'
    - name: Conference
      tag: paper-conference
    - name: Journal
      tag: article-journal
    - name: Preprint
      tag: preprint
design:
  # Choose a view for the listings:
  view: citation
  columns: '2'
---
