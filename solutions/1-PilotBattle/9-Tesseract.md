# Battle #1 - Pilot Battle

## #9 - Tesseract

[Link to the problem](https://cssbattle.dev/play/9)

## Result
<img width="420" alt="Screenshot 2022-12-30 at 11 46 25 PM" src="https://user-images.githubusercontent.com/53368431/210101008-1c48c2a8-236e-4d4d-8a09-e515e2fb60fc.png">


## Code

```html
<!-- r-rectangle -->
<!-- s1-big square -->
<!-- s2-small square -->
<!-- c-circle -->

<div id="r"></div>
<div id="s1"></div>
<div id="s2"></div>
<div id="c"></div>
<style>
  * {
    margin: 0;
  }
  body {
    display: grid;
    place-items: center;
    background: #222730;
  }
  div {
    position: absolute;
  }
  #r {
    width: 100%;
    height: 150;
    background: #4caab3;
  }
  #s1 {
    background: #222730;
    width: 250;
    height: 250;
    transform: rotate(45deg);
  }
  #s2 {
    background: #4caab3;
    width: 150;
    height: 150;
    transform: rotate(45deg);
  }
  #c {
    background: #393e46;
    width: 50;
    height: 50;
    border-radius: 100%;
  }
</style>
```
