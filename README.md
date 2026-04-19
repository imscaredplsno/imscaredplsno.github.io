<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
    <style>
        * {
            padding: 0;
            margin: 0;
        }

        body {
            background: rgb(0, 0, 0);
        }

        .name {
            color: rgb(255, 255, 255);
            font-size: 50px;
            padding: 30px;
            text-align: center;
            font-family: serif;
        }

        .pogi {
            margin: 100px 0 0 200px;
            width: 70%;
            height: 450px;
            display: flex;
            justify-content: center;
            gap: 10px;
        }

        .pogi img {
            width: 10%;
            height: 100%;
            object-fit: cover;
            border-radius: 10px;
            border: 2px solid rgba(255, 255, 255, 255);
            transition: all ease-in-out 0.5s;
        }

        .pogi img:hover {
            width: 25%;
        }
    </style>
</head>
<body>
    <div class="name">
        <p>愛してます</p>
    </div>
   <div class="pogi">
        <img src="C:\Users\DIRK\Downloads\th (1).jpg">
        <img src="C:\Users\DIRK\Downloads\5bbc7f11-5644-4524-8b7d-f6a285a5a0db.jpg">
        <img src="C:\Users\DIRK\Downloads\e503df9c-4822-4265-b9b1-da9db8348fd3.jpg">
        <img src="C:\Users\DIRK\Downloads\d35ee6ce-18c6-449d-aa22-ea5b9d3bf4d3.jpg">
        <img src="C:\Users\DIRK\Downloads\b8e12153-0b2c-4ef4-a759-d812455419df (1).jpg">
    </div>
</body>
</html>
