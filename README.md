# Typography2

<!DOCTYPE html>
<html>
<head>
<style>
.grid-container {
  display: grid;
  grid-gap: 50px;
  grid-template-columns: auto auto auto;
  background-color: #2196F3;
  padding: 10px;
}
  __
._3 {
  background-image: url("3.png");
  position: absolute;
  left: 214px;
  top: 831px;
  width: 435px;
  height: 546px;
  z-index: 7;
}_

.grid-item {
  background-color: rgba(255, 255, 255, 0.8);
  border: 1px solid rgba(0, 0, 0, 0.8);
  padding: 20px;
  font-size: 30px;
  text-align: center;
}
</style>
</head>
<body>

<h1>The grid-gap Property:</h1>

<p>Use the <em>grid-gap</em> shorthand property to adjust the space between the columns and rows:</p>

<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>  
  <div class="grid-item">4</div>
  <div class="grid-item">5</div>
  <div class="grid-item">6</div>  
  <div class="grid-item">7</div>
  <div class="grid-item">8</div>
  <div class="grid-item">9</div>  
</div>

</body>
</html>
