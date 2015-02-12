Button
======

## Default

```
@haml
%button.btn
  %span Default
%button.btn.is-disabled
  %span Disabled
%button.btn(disabled='')
  %span Disabled
```

## Primary

```
@haml
%button.btn-primary
  %span Primary
%button.btn-primary.is-disabled
  %span Primary disabled
```

## Default for icons

```
@haml
%button.btn-icon
  %span.ion-icon.ion-close-round
%button.btn-icon
  %span.ion-icon.ion-minus-round
%button.btn-icon
  %span.ion-icon.ion-navicon-round
%button.btn-icon
  %span.ion-icon.ion-chevron-down
%button.btn-icon.btn-primary
  %span.ion-icon.ion-chevron-left
%button.btn-icon
  %span.ion-icon.ion-chevron-right
%button.btn-icon.btn-primary
  %span.ion-icon.ion-chevron-up
```

## Link as button

```
@haml
%a.btn(href='#')
  %span Default
@haml
%a.btn.is-disabled(href='#')
  %span Disabled
```



