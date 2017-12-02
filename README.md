# Matilda eating 🍫🍦

A [fun little page](https://matildapearce.com/eating-chocolate-ice-cream) I made for my daughter which includes a
picture of her eating chocolate ice cream whilst on holiday in
[Thailand](https://www.google.com.au/maps/place/The+Surin+Phuket/@7.981048,98.277681,15z/data=!4m2!3m1!1s0x0:0x4fca1f8fd01767e6?sa=X&ved=0ahUKEwii_6qp9aDXAhUGOJQKHTPpDGIQ_BIIdDAK)
with Dad (me) and my fiancé [Kate](http://kllevin.com/).

It includes a filters widget which lets you apply certain filters to Matilda and also change the background and link
color of the page.

## Geek stuff 🤓

* Used [CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) for layout.
* Used [CSS Custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/--*) including in the JavaScript to
  apply the filters (I first applied this technique whilst doing the [JavaScript30](https://javascript30.com/) **Playing
  with CSS variables and JS** challenge.
* The filters use the [Modal Dialog](http://w3c.github.io/aria-practices/#dialog_modal) design pattern on smaller
  screens.
* The image uses the [WebP](https://developers.google.com/speed/webp/) file format falling back to JPEG implemented like
  this:

  ```html
  <picture>
    <source srcset="matilda.webp" type="image/webp">
    <img src="matilda.jpg" alt="Picture of Matilda Pearce eating chocolate ice cream">
  </picture>
  ```
