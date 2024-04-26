<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Abel&family=Dosis:wght@200..800&family=Libre+Baskerville&display=swap" rel="stylesheet">
</head>
<link rel="stylesheet" href="style.css">
<body>
   
    <header class="cabecalho"> 
        <img class= "cabecalho-imagem" src="download.jpg" alt="estudos">
        <ul class="cabecalho-lista">
           <li class="cabecalho-lista-item">Escola</li>
           <li class="cabecalho-lista-item">Estudante</li>
        </ul>
    </header>
    <section class="turma">
        <div class="div-turma-conteudo">
            <h2 class="turma-titulo">Sobre mim</h2>
            <p class="turma-texto"> Meu nome e Beatriz, finalmente consegui fazer meu site, depois de muito e irritar, eu aprendi, tive a ajuda da plataforma Alura e dos meus amigos que me explicaram um pouco melhor como funciona a parte de programacao, porem nao compreendi completamente! .</p>
            <h2 class="turma-titulo-2">Apresento aqui meu site!</h2>
        </div>

        
        <img class="turma-imagem" src="andras-arato-ficou-conhecido-como-hide-pain-harold-por-causa-de-seu-sorriso-nervoso-1573231062755_v2_3x4.jpg" alt="imagem">
    </section>

    </section>

</body>
</html>

    
*{
    margin: 0;
    padding: 0;
}
.cabeçalho{
    background-color: #E90D1D;
    color: white;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 24px 0;
}
body {
        font-family: "Abel", sans-serif;
        font-weight: 400;
        font-style: normal;
          
}


.cabeçalho-imagem{
width: 17%;

}
.cabeçalho-lista-item{

    display: inline-block;
    margin: 20px;
    font-size: 20px;
}
.turma-imagem{
    width: 25%;
}
.turma{
    background-image: linear-gradient(#E90D1D,#e218c0) ;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 50px 0;
}

.turma-titulo{
    padding: 24px 0;
}
.turma-titulo-2{
    padding: 24px 0;
}
.div-turma-conteudo{
width: 35%;
}
<css/>
