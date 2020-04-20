# Custom Grid SASS
## Sizes

Label | Size | $Var |
--- | --- | --- |
xxs | 0px | $xxs |
xs | 300px | $xs |
sm | 480px | $s |
md | 769px | $m |
lg | 1024px | $l |
xl | 1200px | $xl |
xxl | 1440px | $xxl |
## Grid

To build a grid you need .row and a child of that can be a .col

 ``` 
 <div class="row">
  <div class="col col-xxs-6"></div>
  <div class="col col-xxs-6"></div>
 </div>
 
 ``` 


## Gutters

We are using xs as the default here

```
.gutter-tb-xs-#{$label}-up 
.gutter-margin-xs-#{$label} 
.gutter-margin-xs-#{$label}-up
.gutter-none-xs-#{$label} 
.gutter-margin-tb-xs-#{$label}
```

## Text align

The text align works on the same basis as those above.

```
.text-#{$label}-center 
.text-#{$label}-right
.text-#{$label}-left
```


E.G


```
<div class="col col-xxs-6 text-xxs-left"></div>
```
