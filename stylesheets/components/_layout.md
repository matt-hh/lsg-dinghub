Layout
======

```
@full-width
@haml
.layout
  .layout-header
    %a.layout-header-logo(href='#') Dinghub
    .layout-header-container
      .layout-header-dingos
        3000 Dingos
      %nav.layout-header-nav
        Nav goes here
      %form.layout-header-searchform
        %label.layout-header-searchform-label
          %i.ion-icon.ion-search
        %input.layout-header-searchform-input(placeholder='Search')
  .layout-container
    .layout-main
      Content
    .layout-sidebar-right
      Control navigation
```

First element with class .layout should be the body-element.
