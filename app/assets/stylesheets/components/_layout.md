Layout
======

```
@full-width
@haml
.layout
  .layout-header
    .layout-header-container
      %a.layout-header-logo(href='#') Dinghub
      .layout-header-dingos
        3000 Dingos
      %nav.layout-header-nav
        Nav goes here

      %form.layout-header-searchform
        %label.layout-header-searchform-label
          %i.icon.icon-search
        %input.layout-header-searchform-input(placeholder='Search')

  .layout-container
    Content goes here
```
