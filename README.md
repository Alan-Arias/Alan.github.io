<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/CSS CODE/estilos.css">

    <script>
     function cambiarFoto(input) {
  if (input.files && input.files[0]) {
    var reader = new FileReader();

    reader.onload = function(e) {
      document.querySelector(".profile img").src = e.target.result;
    }

    reader.readAsDataURL(input.files[0]);
  }
}
    </script>
    <script>
      function playVideo() {
  var videoIframe = document.getElementById("video-iframe");
  videoIframe.src = "https://sbbrisk.com/e/jrgstfhfq7t6.html";
}

    </script>

    <title>Document</title>
</head>    
<body>
    <header>
        <nav>
            <div class="logo">
              <img src="https://cdn-icons-png.flaticon.com/512/2471/2471573.png" alt="Logo">
            </div>
            <ul>
              <li><a href="#">Inicio</a></li>
              <li><a href="#">Productos</a></li>
              <li><a href="#">Mi Carrito</a></li>
              <li><a href="#">Descarga</a></li>
            </ul>
            <div class="profile">
              <img src="/collei.jpg" alt="Foto de perfil" id="imagen" onclick="ampliarImagen()">
              <input type="file" id="input-file" style="display:none;" accept="image/*" onchange="cambiarFoto(this)">
              <button onclick="document.querySelector('#input-file').click()">Cambiar foto</button>
            </div>
          </nav>
          
    </header>
    <section class="video-ssth1">
      <h3 class="titulo">Saint Seiya Hades Capitulo 1</h3>
      <IFRAME id="video-iframe" SRC="https://sbbrisk.com/e/jrgstfhfq7t6.html" FRAMEBORDER=0 
      MARGINWIDTH=0 MARGINHEIGHT=0 SCROLLING=NO WIDTH=640 HEIGHT=360 allowfullscreen>
      </IFRAME>
    </section>
      

</body>
</html>
