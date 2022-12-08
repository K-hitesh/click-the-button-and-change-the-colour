# click-the-button-and-change-the-colour<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>JavaScript change background color</title>
    <script>
     
      function changeBackgroundgreen() {
        document.body.style.background = "green";}
	  function changeBackgroundred() {
        document.body.style.background = "red";}
	  function changeBackgroundblue() {
        document.body.style.background = "blue";}
	  function changeBackgroundgray() {
        document.body.style.background = "gray";}
      function changeBackgroundyellow() {
        document.body.style.background = "yellow";}		
	  function myFunc(){
	     document.getElementByI('demo').innerHTML="Hello i am para being inserted by javascript";}
                                                                
    </script>
  </head>
  <body>
    <h1>Click the button to change the background:</h1>
    <button onclick="changeBackgroundgreen();">green</button>
	<button onclick="changeBackgroundred();">red</button>
	<button onclick="changeBackgroundblue();">blue</button>
	<button onclick="changeBackgroundgray();">gray</button>
	<button onclick="changeBackgroundyellow();">yellow</button>
	<p id="demo">Hey I am para from html</p>


<button type="button"onclick ="document.getElementById('Date').innerHTML=Date()">show current Date</button>

  </body>
</html>
