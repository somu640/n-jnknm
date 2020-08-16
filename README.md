<!DOCTYPE html>

<head>
    <meta charset="utf-8">
</head>
<title>619 Assignment</title>

<body style="background-color: steelblue;">
    <script src="" async defer></script>
    <h1 style="text-align: center;"> Welcome to my webpage 619</h1>

    <br>
    <br>
    <br>
    <br>
    <script>
        var name = prompt("enter your name");
        document.write("<h2>" + "Hi  " + name + "<br>" + "</h2>");
    </script>
    <p id="k"></p>
    <a id="demo" style="color: red;"></a>
    <script style="text-align: end;">
        document.getElementById("k").innerHTML = "click on button to generate a link" + " Mention your profession as Teacher or IAS or doctor or Student ";
        var prof = prompt("enter your profession");
        if (prof == "student" || prof == "Student") {
            document.getElementById("demo").innerHTML = "Student";
            document.getElementById("demo").href = "https://www.w3schools.com";

        } else if (prof == "Doctor" || prof == "doctor") {
            document.getElementById("demo").innerHTML = "MBBS";
            document.getElementById("demo").href = "https://www.mciindia.org";

        } else if (prof == "Teacher" || prof == "teacher") {
            document.getElementById("demo").innerHTML = "Teacher";
            document.getElementById("demo").href = "https://www.englishclub.com/webguide/Teaching_Jobs/";

        } else if (prof == "IAS" || prof == "Ias") {
        } else {
            document.getElementById("demo").innerHTML = "Unidentified";
            document.getElementById("demo").href = "myweb.html";
        }
    </script>

</body>

</html>


