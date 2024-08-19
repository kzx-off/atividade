<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tela de login</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="telaLogin">
        <h1>Login</h1>
        <input type="text" placeholder="Nome">
        <br><br>
        <input type="password" placeholder="Senha">
        <br>
        <h2>Esqueceu sua senha?</h2>
        <br>
        <button>Enviar</button>
    </div>
</body>
</html>

        body{
            font-family: Arial, Helvetica, sans-serif;
            background-image: linear-gradient(45deg, rgb(64, 224, 252), rgb(0, 26, 255));
        }
        .telaLogin{
            background-color: rgba(0, 0, 0, 0.9);
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            padding: 80px;
            border-radius: 15px;
            color: #fff;
            box-shadow: 0px 0px 70px 7px white;
        }
        .telaLogin input{
            padding: 15px;
            border: none;
            outline: none;
            font-size: 15px;
        }
        .telaLogin button{
            background-color: dodgerblue;
            border: none;
            padding: 15px;
            width: 100%;
            border-radius: 10px;
            color: white;
            font-size: 15px;
            
        }
        .telaLogin button:hover{
            background-color: deepskyblue;
            cursor: pointer;
        }
        .telaLogin h2{
            font-size: 0.9rem;
            font-weight: 100;
            padding-top: 5px;
        }
