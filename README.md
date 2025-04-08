<!DOCTYPE html>
<html>
<body>
<h1>JavaScript Array Sort</h1>

<h2>Você pode usar o Math.min.apply para achar o menor número em um Array:</h2>

<p>O menor número é <span id="demo"></span>.</p>
<br>
<p>O menor número é <span id="demo2"></span>.</p>

<h2>Você pode usar o Math.max.aplly para achar o maior número de um array:</h2>

<p>O maior número é <span id="demo1"></span>.</p>
<br>
<p>O maior número é <span id="demo3"></span></p>
<br>

<h2>The sort() Method</h2>
<br>
<h3></h3>

<p>The sort() method sorts an array alphabetically:</p>

<p id="as1"></p>
<p id="as2"></p>


<script>
const points = [40, 100, 1, 5, 25, 10];
document.getElementById("demo").innerHTML = myArrayMin(points);

function myArrayMin(arr) {
  return Math.min.apply(null, arr);
}
const points2 = [2, 3, 4, 5, 6, 10];
document.getElementById("demo2").innerHTML = myArrayMin(points2);

function myArrayMin(arr) {
  return Math.min.apply(null, arr);
}
const points1 = [40, 100, 1, 5, 25, 10];
document.getElementById("demo1").innerHTML = myArrayMax(points1);

function myArrayMax(arr) {
  return Math.max.apply(null, arr);
}
const points3 = [400, 100, 10, 5, 25, 10];
document.getElementById("demo3").innerHTML = myArrayMax(points3);
function myArrayMax(arr) {
    return Math.max.apply(null, arr);
}
const fruits = ["Banana", "Orange", "Apple", "Mango"];
document.getElementById("as1").innerHTML = fruits;

fruits.sort();
document.getElementById("as2").innerHTML = fruits;

</script>

</body>
</html>
