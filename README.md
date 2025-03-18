<!DOCTYPE html>
<html>
<body>
    <div id="myDiv" style="background:red;height: 200px;width: 100px;">
    </div>
    <button onclick="changeCol()">Click me</button>

   <script>
     function changeCol() {
         document.getElementById("myDiv").style.background = Math.floor(Math.random()*16777215).toString(16); // https://stackoverflow.com/a/74280677/10256442
     }
    </script>
</body>
</html>
