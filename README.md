# first_project
my first html css project

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            margin: 0;
            padding: 0;

        }

        body {
            background-color: hsl(0, 4%, 80%);
        }

        .container {
            width: 344px;
            display: inline-block;
            margin: 50px;
            border-radius: 25px;
            padding: 30px;
            align-items: center;
            background-color: rgb(253, 253, 250);
            box-shadow: 3px 5px 13px 4px;
            height: 600px;
        }

        .img {
            display: block;
            margin: auto;
            margin-left: -6px;
            border-radius: 25px;
            padding: 5px;
            width: 344px;
        }

        h2 {
            margin-top: 20px;
            margin-bottom: 20px;
        }

        p {
            padding-top: 20px;
            padding-bottom: 20px;
            font-size: 20px;
            color: rgb(80, 82, 83);
        }

        .link1 {
            text-decoration: none;
            margin: 10px;
            padding: 10px;
            padding-left: 20px;
            padding-right: 20px;
            display: inline-block;
            background-color: #ddd;
            border-radius: 20px;
            color: rgb(80, 82, 83);
        }

        .link2 {
            text-decoration: none;
            padding: 15px;
            padding-left: 25px;
            padding-right: 25px;
            margin: 10px;
            display: inline-block;
            border-radius: 50px;
            margin-left: 110px;
            background-color: rgb(215, 241, 250);
        }
    </style>
</head>

<body>
    <div class="container">
        <img src="https://images.unsplash.com/photo-1575936123452-b67c3203c357?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            alt="profile" class="img">
        <div class=" container1">
            <a href="" class="link1">Student</a>
            <a href="" class="link1">photography</a>
            <h2>HARSHIT MISHRA</h2>
            <p> |B.Sc.IT(1st Year)|Diploma in Computer Applications|
                |Learning Web Development,C Programming & E-Commerce|
                Aspiring Full-Stack Developer Passionate About
                Building Scalable Web Solutions</p>
        </div>
        <div class=" container2">
            <a href="https://www.linkedin.com/in/harshit-mishra-46a46527b/" class="link2">Read more</a>
        </div>
    </div>
</body>

</html>
