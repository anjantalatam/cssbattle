# Battle #1 - Pilot Battle

## #3 - Push Button

[Link to the problem](https://cssbattle.dev/play/3)

## Result

## Code

```html
<div class="left"></div>
<div class="right"></div>
<div class="outer circle"></div>
<div class="inner circle"></div>
<div class="center circle"></div>

<style>
  body {
    margin: 0;
    background: #6592cf;
    display: grid;
    place-items: center;
  }

  .circle {
    border-radius: 50%;
  }

  .center {
    background: #eeb850;
    width: 50px;
    height: 50px;
  }

  .inner {
    width: 150px;
    height: 150px;
  }

  .outer {
    background: #6592cf;
    width: 250px;
    height: 250px;
  }

  .left {
    left: 50px;
  }

  .right {
    right: 50px;
  }

  div {
    position: absolute;
    background: #243d83;
    width: 50px;
    height: 150px;
  }
</style>
```
