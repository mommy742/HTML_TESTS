<!DOCTYPE html>
<html>
<body>
    <div id="myDiv" style="background:red;height: 200px;width: 100px;">
    </div>
    <button onclick="changeCol()">Click me</button>

   <script>
     function changeCol() {
         document.getElementById("myDiv").style.background = "yellow";
     }
    </script>
</body>
</html>
