<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gradient Text Example</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #111;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
    }

    .gradient-text {
        font-size: 4rem;
        font-weight: bold;
        background: linear-gradient(90deg, #ff7e5f, #feb47b);
        -webkit-background-clip: text; /* For Safari/Chrome */
        -webkit-text-fill-color: transparent;
        background-clip: text; /* For Firefox */
        text-fill-color: transparent;
    }
</style>
</head>
<body>

<h1 class="gradient-text">Gradient Text</h1>

</body>
</html>
