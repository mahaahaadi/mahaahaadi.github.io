# mahaahaadi.github.io


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
    background-color:#fff;
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
   text = 8660720750;
   const elem = document.createElement('textarea');
   elem.value = text;
   document.body.appendChild(elem);
   elem.select();
   document.execCommand('copy');
   document.body.removeChild(elem);
   
   alert("You have successfully copied my number " + text + ", save it else I can't see your status 😂");
}
</script>

</body>
</html>


