
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>POLLO ARA 🐔</title>

<style>
body {
  background: #fff5b8;
  font-family: Arial, sans-serif;
  text-align: center;
  padding-top: 100px;
}

h1 {
  color: #d71920;
  font-size: 38px;
}

button {
  background: #ffdf00;
  color: #d71920;
  border: 6px solid #d71920;
  border-radius: 30px;
  padding: 45px 25px;
  font-size: 32px;
  font-weight: bold;
  cursor: pointer;
  box-shadow: 0 10px 0 #b9a000;
}

button:active {
  transform: translateY(7px);
  box-shadow: 0 3px 0 #b9a000;
}
</style>
</head>

<body>
<h1>🐔 POLLO ARA 🐔</h1>

<button onclick="document.getElementById('sonido').currentTime=0;
document.getElementById('sonido').play();">
¡POLLO ARA!
</button>

<audio id="sonido" src="pollo-ara.mp3" preload="auto"></audio>
</body>
</html>
