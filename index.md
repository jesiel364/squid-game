<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>Squid Game</title>
  
  <!-- HTML -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@300&display=swap" rel="stylesheet">

<link href="https://fonts.googleapis.com/icon?family=Material+Icons"rel="stylesheet">

  <!-- Custom Styles -->
<link rel="stylesheet" href="style.css">

<style>
body{
  background-repeat: no-repeat;
  background-position: top;
  background-size: 100%;

  background:
        /* top, transparent black, faked with gradient */ 
        linear-gradient(
          rgba(0, 0, 0, 0.7), 
          rgba(1, 0, 0, 0.7)
        ),
        /* bottom, image */
        url(bg.jpg);
    }
}
</style>
</head>

<body>
  <div id="container">

    <div id="logo"><a href='https://jesiel364.github.io/squid-game/'>
   <span class="material-icons">radio_button_unchecked</span>
   <span class="material-icons">change_history</span>
   <span class="material-icons">crop_square</span></a>
    </div>

    <div id="main" style="background-color: rgba(.2, .2, .2, .3);">
    <h1>Bem vindo aos Jogos da Lula</h1>
    <p>Aqui quem fala é o lider da competição.</p>
    <p>Preparado para jogar os jogos?</p>
   
   <div id="form">
    <form action="page2.html" method="GET">
      <input id="nome" placeholder="Seu nome?" type="text" name="name"/>
      <input id="button" type="submit" name="submit" value="Confirmar"/>
    </form>
    </div>
</div>
    
  </div>
  <!-- Project -->
  
</body>
</html>