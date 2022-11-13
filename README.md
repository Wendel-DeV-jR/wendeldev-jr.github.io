# wendeldev-jr.github.io
esta é a pagina do meu site.
<!DOCTYPE html>
<html lang="en-br">
<head>

   <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site profissional- wendel reis</title>
    <link rel="stylesheet" href="STYLES.CSS">

<body>
    <header class="cabeçalho">
        <img class="cabeçalho-imagem" src="vai site.jpg" alt="logo">
        <nav class="babeçalho-menu">
            <a class="cabeçalho-menu-item" href="google.com ou o meu site">Meu Site Profissional</a>
            <a class="cabeçalho-menu-item">Tutorial</a>
            <a class="cabeçalho-menu-item">Open source</a>
            <a class="cabeçalho-menu-item">Comandos</a>
        </nav>

    </header>
    <main class="conteudo">
        <section class="conteudo-principal">
            <div class="conteudo-principal-escrito">
                <h1 clas="conteudo-prncipal-escrito-titulo">Paixão por Desenvolvimento JavaScript,PHP,Html e Css.</h1>
                <h2 class="conteudo principal-escrito-subtitulo">Venha conhecer meus serviços,habilidades e técnicas.</h2>
                <button class="conteudo-principal-escrito">Me adicione</button>
            </div>
            <img class="conteudo-principal-imagem" src="minha logo.jpg" alt="=logo">
        </section>
        <section class="conteudo-secundario">
            <h3 class="conteudo-secundario-titulo">O que posso fazer por voçê?</h3>
            <p class="conteudo-secundario-paragrafo">1. <strong> Me chame para uma entrevista ou projeto. </strong></p>
            <p class="conteudo-secundario-paragrafo">2. <strong>Mostro minhas Habilidades,voçê me avalia,estou a disposição.</strong></p>
            <p class="conteudo-secundario-paragrafo"> <strong></strong></p>
        </section>
   
    </main>
     <footer class="rodape">
        <img class="rodape-imagem" src="MINHA LT.gif" alt="logo">
     </footer>    
 </body>
 </head>
</html>

.css{
    url @import("https://fonts.googleapis.com/css2?family=Righteous&family=sarala:wght@400;700&display=swap");

    margem=0;
    preenchimento=0;
    box-sizing: border-box;
    decoração de texto:nenhuma;
}

corpo{ 
    tamanho da fonte: 100%;
    plano de fundo: gradiente linear (68,15 graus,#0a789916,62%,#6e914b 85,61%);
}
. cabeçalho{
   exibição: flex;
   flex-direção: linha;
   itens de alinhamento:centro;
   justificar-conteúdo:espaço-ao redor;
   preenchimento: 14px;
   lacuna: 70px;
}
. cabe çalho-imagem {
    altura:80px;
   exibição: flexbox;
 }

. cabeçalho-menu-item {
      família de fontes:'sarala',sans-serif;
      cor:#08070a;
      fonte-peso: 300;
      tamanho da fonte: 13px;
      lacuna:20px;
   }
. conteudo | {
    margem-fundo: 80px;
    borda - topo: 0.04pxsólido#f6eee7;
   }
. conteudo-principal {
      exibição: flex;
      flex-direção: linha;
      itens de alinhamento:centro;
      justificar-conteúdo:espaço-ao redor;
   } 
. conteudo-principal-imagem {
         altura: 210px;
        exibição: flexbox;
   }
. conteudo-principal-escrito {
      fonte-família: 'Justo', cursivo;
      fonte-peso: 300;
      tamanho da fonte: 15px;
      cor:#281e16;
     }

. conteudo-principal-escrito-subtitulo {
        família de fontes:'sarala',sans-serif;
        fonte-peso: 300;
        tamanho da fonte: 9px;
        cor: #ecd6c4;

     }
     
. conteudo-principal-escrito-botão:hover {
      cor de fundo: rgba (236,214,196,0.53);
      largura: 180px;
      altura:60px;
      borda:nenhuma;
      itens de alinhamento:centro;
      caixa-sombra: 4 px 5 px 4pxrgba (0,0,0,0,0.25);

   }
. conteudo-secundario {
      exibição: flex;
      flex-direção: coluna;
      itens de alinhamento:centro;
      lacuna: 12px;
      margem-topo: 28px;

   }
. conteudo-secundario-paragrafo {
    família de fontes:'sarala',sans-serif;
    fonte-peso: 200;
    tamanho da fonte: 14px;
   }
. rodape {  
    preenchimento: 12px;
    borda - topo: 0.4pxsólido#FFF2E7;
  }
. rodape-imagem {
    altura:70px;
    exibição:bloco;
    margem: 0automático;

   }

}
