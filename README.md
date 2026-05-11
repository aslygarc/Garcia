<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Presentación GitHub</title>

 <style>
        body{
            margin:0;
            padding:0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #ffd6e7, #ffeef5);
            display:flex;
            justify-content:center;
            align-items:center;
            height:100vh;
        }

        .card{
            background:white;
            width:350px;
            padding:30px;
            border-radius:25px;
            text-align:center;
            box-shadow:0 10px 25px rgba(0,0,0,0.1);
            transition:0.3s;
        }

        .card:hover{
            transform:translateY(-5px);
        }

        .profile{
            width:120px;
            height:120px;
            border-radius:50%;
            object-fit:cover;
            border:5px solid #ff8fb1;
        }

        h1{
            color:#ff4f87;
            margin-top:15px;
        }

        p{
            color:#666;
            font-size:15px;
        }

        .btn{
            display:inline-block;
            margin-top:20px;
            padding:12px 25px;
            background:#ff4f87;
            color:white;
            text-decoration:none;
            border-radius:30px;
            transition:0.3s;
        }

        .btn:hover{
            background:#ff2f70;
        }
    </style>
</head>

<body>

    <div class="card">
        <img src="https://i.imgur.com/2DhmtJ4.png" alt="Foto perfil" class="profile">

        <h1>Asly García ✨</h1>

        <p>
            Estudiante de Desarrollo de Software 💻  
            Apasionada por la tecnología, el diseño y crear cosas bonitas.
        </p>

        <a href="https://github.com/" class="btn">
            Mi GitHub ❤️
        </a>
    </div>

</body>
</html>
