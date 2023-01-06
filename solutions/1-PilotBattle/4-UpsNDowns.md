# Battle #1 - Pilot Battle

## #4 - Ups n Downs

[Link to the problem](https://cssbattle.dev/play/4)

## Result
<img width="420" alt="Screenshot 2023-01-06 at 11 44 20 PM" src="https://user-images.githubusercontent.com/53368431/211073823-b0092bdc-54f1-4fa4-b671-4027460cd941.png">


## Code

```html
<main>
  <div id="d1"></div>
  <div id="d2"></div>
  <div id="d3"></div>
</main>

<style>
  body {
    margin: 0;
    background: #62306d;
    display: grid;
    place-items: center;
  }
  main {
    display: grid;
    grid-template-rows: repeat(2, 1fr);
    grid-template-columns: repeat(3, 1fr);
  }
  div {
    width: 100px;
    height: 100px;
    background: #f7ec7d;
    border-radius: 0px 0px 60px 60px;
  }
  #d1 {
    grid-row: 2;
    grid-column: 1;
  }

  #d2 {
    grid-row: 1;
    grid-column: 2;
    border-radius: 60px 60px 0px 0px;
  }
  #d3 {
    grid-row: 2;
    grid-column: 3;
  }
</style>
```
