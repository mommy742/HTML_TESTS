<!DOCTYPE html>
<link rel="stylesheet" href="styles.css">
<html>
<body>
    <div id="myDiv" style="background:red;height: 200px;width: 100px;">
    </div>
	<img src="https://i.imgur.com/kDDFvUp.png" class="rotate" width="100" height="100" /> <!-- https://flaviocopes.com/rotate-image/ -->
	<img src="https://i.imgur.com/kDDFvUp.png" class="rotate" width="100" height="100" /> <!-- https://flaviocopes.com/rotate-image/ -->
	<img src="https://i.imgur.com/kDDFvUp.png" class="rotate" width="100" height="100" /> <!-- https://flaviocopes.com/rotate-image/ -->
    <button onclick="changeCol()">Click me</button>
   <script>
     function changeCol() {
            var bgColor = "rgb(" + Math.floor(Math.random() * 256) + "," + Math.floor(Math.random() * 256) + "," + Math.floor(Math.random() * 256) + ")";
            document.body.style.background = bgColor; // https://www.w3resource.com/javascript-exercises/javascript-math-exercise-40.phps
     }
    </script>
</body>
</html>
