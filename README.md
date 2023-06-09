<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script type="text/javascript" src="unit.js"></script>
</head>
<body>
    <form>
        <input type="text" id="miles" placeholder="miles">
        <input type="text" id="km"  placeholder="km">
        <input type="button" value="convert" onclick="convert()">
    </form>
</body>
</html>

js code

convert= () =>{
    x = document.getElementById('miles');
    y = document.getElementById('km');
    m = x.value;
    y.value = m*1.609;
}
