# didactic-winner
Java scripts and html 
<!DOCTYPE html>
<html>
<body>

<h1 onclick="changeText(this)">Click on this text!</h1>

<p>Click the button to display the date.</p>
<button onclick="displayDate()">The time is?</button>

<script>
function changeText(id) {
id.innerHTML= "Ooops!";
}
function displayDate(){
document.getElementById("demo").innerHTML = Date();
}
</script>
<p id="demo"></p>
</body>
</html>
