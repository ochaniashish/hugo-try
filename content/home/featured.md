---
# An instance of the Featured widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: featured

active: false

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 25

title: Research
subtitle: ''

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: publication
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Financial Media
      tag: Financial Media
    - name: Cryptocurrency
      tag: Cryptocurrency
    - name: Earnings
      tag: Earnings
    - name: Capital Markets
      tag: Capital Markets
    - name: Institutional Investors
      tag: Institutional Investors
    - name: Retail Investors
      tag: Retail Investors
      

  # Filter on criteria
#  filters:
#    author: ''
#    category: ''
#    publication_type: ''
#    tag: ''
  # Page order: descending (desc) or ascending (asc) date.
  order: desc

design:
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  columns: '1'
  view: 5

---
