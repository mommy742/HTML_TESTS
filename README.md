<!DOCTYPE html>
<link rel="stylesheet" href="styles.css">
<html>
<body>
    <div id="myDiv" style="background:red;height: 200px;width: 100px;">
    </div>
	<img src="https://i.imgur.com/kDDFvUp.png" class="rotate" width="100" height="100" />
	<img src="https://i.imgur.com/kDDFvUp.png" class="rotate" width="100" height="100" />
	<img src="https://i.imgur.com/kDDFvUp.png" class="rotate" width="100" height="100" />
    <button onclick="changeCol()">Click me</button>
   <script>
     function changeCol() {
		for (var i = 0; i < 10; i++) {
			(function(i){
				setTimeout(function(){
					var bgColor = "rgb(" + Math.floor(Math.random() * 256) + "," + Math.floor(Math.random() * 256) + "," + Math.floor(Math.random() * 256) + ")";
					document.body.style.background = bgColor;
				}, 1000 * i);
			}(i));
		}
     }
    </script>
</body>
</html>
