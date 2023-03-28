<html>
<html lang="pt-br">
  <head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1.0">
    <meta name="robots" content="max-image-preview:large">
  	<link rel="icon" href="https://images.emojiterra.com/google/noto-emoji/v2.034/128px/1f468-1f3fb-1f4bb.png" sizes="32x32">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.7/css/all.css">
    <script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@200&family=Playfair+Display&display=swap" rel="stylesheet">
    <title></title>
    <!-- estilo integrado para github pages-->
    <style> 
     
   /*Formatação da página*/
   *{
      
      font-family: 'Playfair Display', serif;
      font-size: 16px;
      letter-spacing: 1px;
      box-sizing: border-box;
      outline: none;
      text-decoration: none;
      transition: all .2s linear;
      padding: 0;
      margin: 0;
      text-decoration: none;
      list-style: none;
   }
   
   html {
     font-size: 62.5%;
     overflow-x: hidden;
   }
   
   /* Estilizando corpo da página*/
   body {
     background-color: #159494;
     font-size: 13px;
   }
   /*Estilizando a barra de navegação no topo*/
   nav {
     height: 80px;
     width: 100%;
     background-color: #0B6170;
   }
   
   img {
     display: inline;
     height: 90px;
     width: 190px;
     margin: 5px;
     margin-top:-5px;
     
   }
   
   nav ul {
     float: right;
     margin-right: 40px;
   }
   
   nav li {
     display: inline-block;
     margin: 0 8px;
     line-height: 80px;
   }
   
   nav a {
     color: #fff;
     font-family: 'Playfair Display', serif;
     font-size: 20px;
     padding: 7px 10px;
     border-radius: 5px;
   }
   
   a.active, a:hover {
    
     border: 2px  solid #0B6170;
     transition: .5s;
     
   }
   
   nav #icon {
     color: white;
     font-size: 30px;
     line-height: 80px;
     float: right;
     margin-right: 40px;
     cursor: pointer;
     display: none;
   }
 
   section{
    padding: 5rem 10%;
    margin-top: 60px;    
   }
   
    .heading{
        text-align: center;
        margin-bottom: 3rem;
        font-size: 3.5rem;
        text-transform: capitalize;
        color: #444;
    }
    
    .blog .box-container{
        display: -ms-grid;
        display: grid;
        -ms-grid-columns: (minmax(30rem, 1fr))[auto-fit];
            grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
        gap: 2rem;    
    }
    
    .blog .box-container .box:hover .image img{
        transform: scale(1.1);
    }
    
    .blog .box-container .box.shadow{
       
        box-shadow: 0px 18px 39.1px 6.9px rgba(224, 241, 255, 0.34) !important;
    }
    
    .blog .box-container .box .image{
        height: 25rem;
        overflow: hidden;
        position: relative;
    }
    
    .blog .box-container .box .image img{
        height: 100%;
        width: 100%;
        -o-object-fit: cover;
           object-fit: cover; 
    }
    
    .blog .box-container .box .image h3{
        border-radius: 15px;
        background-color: #fff;
        color: #444;
        position: absolute;
        top: 2rem;
        left: 1rem;
        padding: .5rem 1.5rem;
        font-size: 1.5rem;
        
    }
    
    .blog .box-container .box .image h3 i{
        color: #bd18b4;
    }
    
    .blog .box-container .box .content{
        padding: 2rem;
        background-color: #fff;
    }
    
    .blog .box-container .box .content h3{
        font-size: 2rem;
    }
    
    .blog .box-container .box .content p{
        font-size: 1.6rem;
        padding: 1rem 0;
        line-height: 2;
        color: #222;
    }
    
    .btn{
        display: inline-block;
        margin-top: 1rem;
        padding: 0.8rem 2rem;
        font-size: 1.2rem;
        border: 0.1rem solid #0B6170;
        background: #159494;
        color: white;
        cursor: pointer;
        text-transform: capitalize;
        border-radius: 5px;
        box-shadow: 1px 1px 1px black;
        outline: none;
    }
    
    .btn:hover{
        background: #0B6170;
        color: #fff;
    }
    
    mark {
      border-radius: 5px;
      background-color: #159494;
      color: #fff;
    }
    
   /* media query para pc */
   @media (max-width: 1048px) {
       label.logo {
         font-size: 32px;
         padding-left: 60px;
       }
       
       nav ul {
         margin-right: 20px;
       }
       
       nav a {
         font-size: 17px;
       }
       #aqua {
         display: none;
       }
       
       h3 {
         display: none
       }
       
       h1 {
         display: none;
         font-family: 'Playfair Display', serif;
       }
  
   }
   /* media query para mobile */
   @media (max-width: 909px) {
       nav #icon {
         display: block;
         margin-top: 20px;
         -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
       }
       
       nav {
         position: fixed;
         z-index: 1000;
       }
       nav ul {
         position: fixed;
         width: 100%;
         height: 100vh;
         background: #159494;
         top: 80px;
         left: -100%;
         text-align: center;
         transition: all .5s;
         z-index: 1000;
       }
       
       label i {
        color: #fff;
        font-size: 40px;
        font-weight: bold;
     
       }

       nav li {
         display: block;
         margin: 50px 0;
         line-height: 30px;
       }
   
       nav a {
         font-size: 25px;
         -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
         text-decoration: none;
       }
       
       a.active,a:hover {
         border: none;
         color: #0B6170
         
       }
       
       nav ul.show {
         left: 0;
       }
       #aqua {
         display: inline-block;
       }
       
       footer {
         position: relative;
         bottom: 0;
         left: 0;
         right: 0;
         background: #0B6170;
         height: 50px;
         width: 100vw;
         font-family: "times";
         color: #fff;
         text-align: center;
      }
      
      h3 {
        display: inline-block;
        margin-top: 10px;
      }
      
      h1 {
        display: inline;
        font-family: 'Playfair Display', serif;
      }
      
   }
   /* Idéia principal da Barra nav e o menu mibile e desktop ( https://youtu.be/tEC4kqzNTnM)*/
    </style>
    <body>
      <nav>
        <img src="astro1.png">
          <ul>
            <li class="active"><a href="https://blogoficialvr.netlify.app/">Blog Home</a></li>
            <li><a href="https://vitordev01.netlify.app/">Sobre Min</a></li>
            <li><a href="https://www.instagram.com/vitorkw89/">Instagram </a></li>
            <li><a href="mailto:victorskw89@gmail.com">Feedback</a></li>
            <li><a href="https://astrologia-tarot.netlify.app/">Serviços</a></li>
            
            <img id="aqua" src="si1.png" style="height:210px; border-radius:10px 0px 10px 0px; width: 210px; background-color: #fff; box-shadow: 1px 1px 1px black;">
            <br>
            <br>
            <h1 style="color: #fff; font-size: 10px;">bem vindo(a) ao blog! boa leitura.
            Última Atualização em 28/03/23</h1>
          </ul>
          <label id="icon">
            <i class="fa fa-bars" aria-hidden="true"></i>
          </label>
      </nav>
      <br>
      <!-- seções de cada página do blog-->
      <section class="blog">

        <div class="box-container">
            <!-- Página 1-->
            <div class="box shadow">

                <div class="image">
                    <img src="blog_4.jpg" alt="">
                   
                </div>
                <div class="content">
                    <h3>Whitney Houston Análise Mapa Natal</h3>
                    <p>Interpretação da casa astrológica de saúde da cantora e seus desafios com as drogas... • 28/03/2023 <mark>#mapanatal #leão #peixes #WhitneyHouston #saúde</mark></p>
                    <a href="https://vitordev01.github.io/pagina-blog-4/" class="btn">Ler Mais</a>
                </div>
            </div>
            <!-- Página 2-->
            <div class="box shadow">

                <div class="image">
                    <img src="blog_1.jpg" alt="">
                    
                </div>
                <div class="content">
                    <h3>Astrologia E A Geração Z</h3>
                    <p>Uma geração tão tecnológica mas também a mais depressiva, veja as influências dos planetas geracionais na astrologia... 01/03/2023 • <mark>#1990 #2000 #netuno #urano #aquário</mark></p>
                    <a href="https://vitordev01.github.io/pagina-asteologia-saudemental/" class="btn">Ler Mais</a>
                </div>
            </div>
            
            <!-- Página 3-->
            <div class="box shadow">

                <div class="image">
                    <img src="blog_2.jpg" alt="">
                    
                </div>
                <div class="content">
                    <h3>Lutero E Seu Signo Escorpião ♏🦂</h3>
                    <p>A ligação de Matinho Lutero e seu signo e suas profundas características e mudanças na Reforma Protestante...  06/12/2022 • <mark>#escorpião #religião #séculoXVI</mark></p>
                    <a href="https://vitordev01.github.io/pagina-reforma-protestante/" class="btn">Ler Mais</a>
                </div>
            </div>
            <!-- Página 4-->
            <div class="box shadow">

                <div class="image">
                    <img src="blog_3.jpg" alt="">
                    
                </div>
                <div class="content">
                    <h3>Os 12 Signos Do Zodíaco </h3>
                    <p>As principais características dos signos e suas coligações com outros temas... • 01/12/2022 <mark>#astrologia #personalidade #individualidade #signos</mark></p>
                    <a href="https://vitordev01.github.io/pagina-signos-curso/" class="btn">Leia Mais</a>
                </div>
            </div>
            <!-- 
            <div class="box shadow">

                <div class="image">
                    <img src="blog_5.jpg" alt="">
                    <h3><i class="fas fa-heart"></i> 50</h3>
                </div>
                <div class="content">
                    <h3>Do You Want Your Blog To Stand Alone Or Support Another Site?</h3>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eaque, odit!</p>
                    <a href="#" class="btn">read more</a>
                </div>

            </div>

            <div class="box shadow">

                <div class="image">
                    <img src="blog_6.jpg" alt="">
                    <h3><i class="fas fa-heart"></i> 40</h3>
                </div>
                <div class="content">
                    <h3>Do You Want Your Blog To Stand Alone Or Support Another Site?</h3>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eaque, odit!</p>
                    <a href="#" class="btn">read more</a>
                </div>

            </div>
        </div> -->
    </section>
     <!-- roda pé da página -->
    <footer>
        <div class="footer-content">
          <h3>© Vitor Oliveira 2023</h3>
         
        </div>
      </footer>
      <!-- Script para Fazer o menu funcionar-->
      <script>
        $(document).ready(function(){
          $('#icon').click(function(){
            $('ul').toggleClass('show');
          });
        });
    </script>
    </body>
</html>
