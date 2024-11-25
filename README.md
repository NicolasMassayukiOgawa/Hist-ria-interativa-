<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aventura dos Cinco Amigos</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<div id="content">
  <h1>Aventura dos Cinco Amigos</h1>
  <p id="story"></p>
  <div id="choices"></div>
  <img id="storyImage" src="" alt="Imagem da história" />
</div>

<script src="script.js"></script>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  background-color: #f0f8ff;
  margin: 0;
  padding: 0;
}

#content {
  padding: 20px;
  text-align: center;
}

button {
  margin-top: 20px;
  padding: 10px 20px;
  background-color: #28a745;
  color: white;
  font-size: 18px;
  border: none;
  cursor: pointer;
}

button:hover {
  background-color: #218838;
}

img {
  width: 300px;
  height: auto;
  margin-top: 20px;
}