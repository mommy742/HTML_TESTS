<!DOCTYPE html>
<html>
<body>
    <div id="myDiv" style="background:red;height: 200px;width: 100px;">
    </div>
    <button onclick="changeCol()">Click me</button>

   <script>
     function changeCol() {
            var bgColor = "rgb(" + Math.floor(Math.random() * 256) + "," + Math.floor(Math.random() * 256) + "," + Math.floor(Math.random() * 256) + ")";
            document.body.style.background = bgColor; // https://www.w3resource.com/javascript-exercises/javascript-math-exercise-40.php
     }
    </script>
</body>
</html>
