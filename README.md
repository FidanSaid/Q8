# Q8
<!DOCTYPE html>
<html>
<body>

<form action="demo_form.asp">
<textarea rows="4" cols="20" name="usrtxt" wrap="hard">
At W3Schools you will find free Web-building tutorials.
</textarea>
<input type="submit">
</form>
<h3>A demonstration of how to access a TEXTAREA element</h3>

Address:<br>
<textarea id="myTextarea">
2950 W Arthur Ave
chicago,IL,60645
</textarea>

<p>Click the button to get the content of the text area.</p>

<button type="button" onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() {
    var x = document.getElementById("myTextarea").value;
    document.getElementById("demo").innerHTML = x;
}
</script>

</body>
</html>
