# Battle #1 - Pilot Battle

## #11 - Eye of Sauron

[Link to the problem](https://cssbattle.dev/play/11)

## Result

## Code

```html
<div class="semi-circle left"></div>
<div class="semi-circle right"></div>
<div class="circle c1">
  <div class="circle c2">
    <div class="circle c3"></div>
  </div>
</div>

<style>
  * {
    margin: 0;
  }
  body {
    background: #191210;
    display: grid;
    place-items: center;
  }
  div {
    position: absolute;
  }
  .circle {
    border-radius: 100%;
    display: grid;
    place-items: center;
  }
  .c1 {
    width: 140;
    height: 140;
    background: #eca03d;
  }
  .c2 {
    width: 100;
    height: 100;
    background: #191210;
  }
  .c3 {
    width: 50;
    height: 50;
    background: #84271c;
  }
  .semi-circle {
    width: 60;
    height: 30;
    border: 20px solid #eca03d;
  }
  .left {
    top: 150;
    left: 50;
    border-radius: 0 0 80px 80px;
    border-top: 0;
  }
  .right {
    top: 100;
    right: 50;
    border-radius: 80px 80px 0 0;
    border-bottom: 0;
  }
</style>
```
