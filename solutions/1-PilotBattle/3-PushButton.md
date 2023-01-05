# Battle #1 - Pilot Battle

## #3 - Push Button

[Link to the problem](https://cssbattle.dev/play/3)

## Result
<img width="420" alt="Screenshot 2023-01-05 at 11 28 35 PM" src="https://user-images.githubusercontent.com/53368431/210848509-ebbcb13c-84d1-4f90-9f70-54da10183dbf.png">


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
