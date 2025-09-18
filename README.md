# HTML_7
Anonymous function 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anonymous</title>
</head>
<body>
    <h2>Anonymous function</h2>
    <button id="btn">click Me</button>
    <p id="demo3" class="out"></p>
    <script>
        document.getElementById("btn").onclick=function(){
        document.getElementById("demo3").innerText="HTML stands for Hyper Text Markup Language";
    }

    </script>
    
</body>
</html>
