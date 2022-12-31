# Battle #1 - Pilot Battle

## #10 - Cloaked Spirits

[Link to the problem](https://cssbattle.dev/play/10)

## Result
<img width="420" alt="Screenshot 2022-12-31 at 11 28 11 AM" src="https://user-images.githubusercontent.com/53368431/210126871-0c089198-79bc-4264-a2ff-115cf85bd304.png">


## Code

```html
<div class="bg b1"></div>
<div class="bg b2"></div>
<div class="bg b3"></div>
<div class="circle outer o1">
  <div class="circle inner i1"></div>
</div>
<div class="circle outer o2">
  <div class="circle inner i2"></div>
</div>
<div class="circle outer o3">
  <div class="circle inner i3"></div>
</div>

<style>
  * {
    margin: 0;
  }
  body {
    background: #62306d;
  }
  div {
    width: 100px;
    height: 100px;
    position: absolute;
  }
  .bg {
    border-radius: 50px 50px 0 0;
    background: #f7ec7d;
  }
  .b1 {
    height: 150;
    top: 150;
    left: 50;
  }
  .b2 {
    height: 250;
    top: 50;
    left: 150;
  }
  .b3 {
    height: 150;
    top: 150;
    left: 250;
  }
  .circle {
    border-radius: 50%;
  }
  .outer {
    position: absolute;
    display: grid;
    place-items: center;
  }
  .inner {
    width: 60;
    height: 60;
  }
  .o1 {
    background: #aa445f;
    top: 150;
    left: 50;
  }
  .i1 {
    background: #e38f66;
  }
  .o2 {
    background: #e38f66;
    top: 50;
    left: 150;
  }
  .i2 {
    background: #aa445f;
  }
  .o3 {
    background: #aa445f;
    top: 150;
    left: 250;
  }
  .i3 {
    background: #e38f66;
  }
</style>
```
