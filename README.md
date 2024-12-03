<!DOCTYPE html>

<htmllang="pt-BR">
<head>
 <meta charset="UTF-8">
 <meta name="viewport"
 content="width=device-width,initial-scale=1.0">
  <title> Página com Menu, Carrossel e 
  Rodapé</title>
 <link rel="stylesheet" hrf="style.css">
</head>
<body>
<!--Menu Superior-->
<header class="menu">
 <nav>
 <ul>
  <li><a hrf="#home">Home</a></li>
  <li><a hrf="#galeria">Galeria</a></li>
  <li><a hrf="#contato"></a></li>
    </ul>
   </nav>
  </header>

 <!--Carrossel de imagens-->
 <section id="galeria"
class="carousel-section">
 <h2>Galeria de Imagens</h2>
 <div class="carousel">
  <div class="carousel-item"><img src="https://via.placeholder.com/800x400"
 alt="Imagem 1"><div>
  <div class="carousel-item"><img src="https://via.placeholder.com/800x400"
 alt="imagem 2"><div>
  <div class="=carousel-item"><img src="https://via.placeholder.com/800x400"
 alt="imagem 3"></div>
  </div>
 </section>
<!--Rodapé-->
<footer id="contato" class="footer"> 
 <p>Conecte-se comigo:</p>
 <div class="social-icons">
   <a href="https://github.com"
target="_blank">GitHub</a>
   <a href="https://linkedin.com"
target="_blank">Linkedin</a>
   <a href="https://twitter.com'
target="blank'>Twitter</a>
  </div>
 </footer>
</body>
</html>

/*Reset Básico*/
. {
 margin: 0;
 padding: 0;
 box-sizing:border-box;
 }
body{
 font-family:Arial, sans-serif;
 line-height: 1.6;
 background-color: #f4f4f9;
 color:#333;
 }
/*Menu Superior*/
.menu {
 background-color:#6200ea;
 padding: 1rem 0;
 }
 .menu nav ul {
 list-style: none;
 display: flex;
 justify-content: center;
 gap: 2rem;
 }
 .menu nav ul li a {
  color: white;
  
  text-decoration: none;
  font-size: 1.2rem;
  }
  .menu nav ul li a:hover {
    text-decoration:underline;
    }
   /*Carrossel*/
   .carousel-section {
     padding: 2rem;
     text-aling: center;
     }
     .carousel {
      display: flex;
      overflow-x: auto;
      scroll-snap-type:x mandatory;
      gap: 1rem;
      }
      .carousel-item {
        flex: 0 0 auto;
        width: 80%;
        scroll-snap-aling: center;
        }
       .carousel-item img {
         width: 100%;
         border-radius: 10px;
         box-shadow:0 4px 6px rgba(0, 0, 0,0.1);
         }
       /*Rodapé*/
      .footer {
       background-color:#333;
       color:white;
       text-aling: center;
       padding: 1rem 0;
       }
      .footer .social-icons a {
         color: white;
         text-decoration: none;
         margin 0 1rem:
         }
      .footer .social-icons a:hover {
       text-decoration: underline;
       }
       
         

 























