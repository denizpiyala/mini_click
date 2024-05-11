<!DOCTYPE html>
<html>
    <head>
        <title>just click</title>
    </head>
    <body>
        <center>
        <button onclick="clickbutton()" style="background-color: rgb(244, 12, 58);
        color: azure; border-radius: 100px;"
        >click the button</button>
        <h1 id="script">click!</h1>
        <script>
            function clickbutton()
            {
                document.getElementById("script").innerHTML="you're great programmer ;)"
            }
        </script>
        </center>
    </body>
</html>
