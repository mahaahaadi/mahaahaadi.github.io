# mahaahaadi.github.io


<!DOCTYPE html>
<html>
<head>
<style>
input {
  display: none;
}

button {
	width:  100%;
    color:  #008CBA;
    border: 2px solid #fff;
}


button:hover {
  color:  #008CBA; 
  border: 2px solid #008CBA;
  padding: 10px;
}



</style>
</head>
<body>

<h1><input type="text" value="8660720750" id="myInput" disabled style=" background-color:#fff display:block "></h1>
<button onclick="myFunction()">Click to Copy my number</button>

<script>
function myFunction() {
  /* Get the text field */
  var copyText = document.getElementById("myInput");

  /* Select the text field */
  copyText.select();
  copyText.setSelectionRange(0, 99999); /* For mobile devices */

  /* Copy the text inside the text field */
  navigator.clipboard.writeText(copyText.value);
  
  /* Alert the copied text */
  alert("You have successfully copied my number : " + copyText.value);
}
</script>

</body>
</html>
