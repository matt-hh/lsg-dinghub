Control navigation
==================

```
@haml
%ul.controlnav
  %li.controlnav-item
    %button.controlnav-button.is-active
      %span Active
  %li.controlnav-item
    %button.controlnav-button.is-disabled
      %span Disabled
  %li.controlnav-item
    %button.controlnav-button(disabled='')
      %span Disabled
  %li.controlnav-item
    %button.controlnav-button
      %span Default
```
