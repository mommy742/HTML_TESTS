<!DOCTYPE html>
<link rel="stylesheet" href="styles.css">
<html>
<body>
    <div id="myDiv" style="background:red;height: 200px;width: 100px;">
    </div>
	<img src="https://i.imgur.com/kDDFvUp.png" class="rotate" width="100" height="100" />
	<img src="https://i.imgur.com/kDDFvUp.png" class="rotate" width="100" height="100" />
	<img src="https://i.imgur.com/kDDFvUp.png" class="rotate" width="100" height="100" />
	<input type="checkbox" id="my-toggle">
		<label for="my-toggle">toggle me</label>
    <button onclick="changeCol()">Click me</button>
   <script>
     function changeCol() {
			if ( document.getElementById("my-toggle").checked == true ) {
				if ( document.getElementById("my-toggle").checked == true ) {
					var bgColor = "rgb(" + Math.floor(Math.random() * 256) + "," + Math.floor(Math.random() * 256) + "," + Math.floor(Math.random() * 256) + ")";
					document.body.style.background = bgColor;
				}
				setTimeout( changeCol, 100 );
			}
     };
    </script>
</body>
</html>
