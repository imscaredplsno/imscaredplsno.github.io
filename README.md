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
        <p>Hi, Mr. Richard</p>
    </div>
   <div class="pogi">
        <img src="C:\Users\DIRK\Downloads\th (1).jpg">
        <img src="C:\Users\DIRK\Desktop\Github Portfolio\457422784_1182391752876584_4146896408851820312_n.jpg">
        <img src="C:\Users\DIRK\Desktop\Github Portfolio\458464154_530315806036760_4271058015887137538_n.jpg">
        <img src="C:\Users\DIRK\Desktop\Github Portfolio\458498428_1475435146307420_1095839169639995395_n.jpg">
        <img src="C:\Users\DIRK\Desktop\Github Portfolio\457727021_1653521728552859_6117808892471563202_n.jpg">
    </div>
</body>
</html>
