<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Web Page with CSS Hover Effect</title>
    <style>
        /* CSS styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: navy;
            color: white;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .box {
            width: 200px;
            height: 200px;
            background-color: rgba(255, 255, 255, 0.5);
            margin: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            transition: transform 0.3s ease;
        }
        .box:hover {
            transform: translateY(-10px);
        }
        .box:hover .content {
            transform: translateY(10px);
        }
        .content {
            transition: transform 0.3s ease;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="box">
            <div class="content">
                Box 1
            </div>
        </div>
        <div class="box">
            <div class="content">
                Box 2
            </div>
        </div>
        <div class="box">
            <div class="content">
                Box 3
            </div>
        </div>
        <div class="box">
            <div class="content">
                Box 4
            </div>
        </div>
        <div class="box">
            <div class="content">
                Box 5
            </div>
        </div>
        <div class="box">
            <div class="content">
                Box 6
            </div>
        </div>
        <div class="box">
            <div class="content">
                Box 7
            </div>
        </div>
        <div class="box">
            <div class="content">
                Box 8
            </div>
        </div>
    </div>

</body>
</html>
