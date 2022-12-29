# Battle #1 - Pilot Battle

## #8 - Forking Crazy

[Link to the problem](https://cssbattle.dev/play/8)

## Result

## Code

```html
<!-- f -> fork body -->
<!-- c -> crest ⋂-->
<!-- t-> trough U-->
<!-- f-> fork handle -->
<div id="f"></div>
<div id="c1" class="c"></div>
<div id="c2" class="c"></div>
<div id="c3" class="c"></div>
<div id="c4" class="c"></div>
<div id="t1" class="t"></div>
<div id="t2" class="t"></div>
<div id="t3" class="t"></div>
<div id="h"></div>
<style>
  * {
    margin: 0;
  }
  body {
    background: #6592cf;
  }
  div {
    width: 20;
    height: 110;
    background: #060f55;
    position: absolute;
  }
  #f {
    top: 150;
    left: 130;
    height: 100;
    width: 140;
    border-radius: 0px 0px 70px 70px;
  }

  .c {
    border-radius: 10px 10px 0px 0px;
    top: 50;
  }
  #c1 {
    left: 130;
  }
  #c2 {
    left: 170;
  }
  #c3 {
    left: 210;
  }
  #c4 {
    left: 250;
  }

  .t {
    background: #6592cf;
    top: 50;
    border-radius: 0px 0px 10px 10px;
  }
  #t1 {
    left: 150;
  }
  #t2 {
    left: 190;
  }
  #t3 {
    left: 230;
  }

  #h {
    bottom: 0;
    width: 20;
    height: 60;
    left: 190;
  }
</style>
```
