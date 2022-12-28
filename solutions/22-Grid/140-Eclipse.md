# Battle #22 - Grid

## #140 - Eclipse

[Link to the problem](https://cssbattle.dev/play/140)

## Result
<img width="412" alt="Screenshot 2022-12-28 at 10 36 58 PM" src="https://user-images.githubusercontent.com/53368431/209847522-acfbee32-ec79-4038-b84f-446402e96b6c.png">


## Code

```html
<div id="c1"></div>
<div id="c2"></div>
<div id="t"></div>

<style>
  body {
    margin: 0;
    background: #4f77ff;
  }
  div {
    position: absolute;
    width: 80px;
    height: 80px;
    background: #dd6b4d;
  }
  #c1 {
    background: #ffffff;
    border-radius: 50%;
    top: 50px;
    left: 160px;
  }
  #c2 {
    background: #4f77ff;
    border-radius: 50%;
    top: 90px;
    left: 160px;
  }
  #t {
    background: transparent;
    width: 0;
    height: 0;
    border-left: 175px solid transparent;
    border-right: 175px solid transparent;
    border-bottom: 175px solid #1038bf;
    left: 25px;
    top: 138px;
  }
</style>
```
