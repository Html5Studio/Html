<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>O que é HTML?</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      color: #333;
      margin: 20px;
      padding: 20px;
      line-height: 1.6;
    }

    header, footer {
      background-color: #dcdcdc;
      padding: 10px;
      border-radius: 8px;
    }

    h1, h2 {
      color: #2c3e50;
    }

    footer {
      margin-top: 40px;
      font-size: 0.9em;
      text-align: center;
    }

    a {
      color: #2980b9;
    }

    .exemplo-box {
      margin-top: 10px;
      padding: 10px;
      border: 2px dashed #888;
      background-color: #f9f9f9;
      display: none;
    }

    .botao-exemplo {
      background-color: #444;
      color: white;
      border: none;
      padding: 8px 12px;
      cursor: pointer;
      border-radius: 5px;
      margin-top: 10px;
    }

    .botao-exemplo:hover {
      background-color: #666;
    }

    code {
      background-color: #eee;
      padding: 2px 4px;
      border-radius: 4px;
      display: inline-block;
      margin: 2px 0;
    }
  </style>
</head>
<body>

  <header>
    <h1>O que é HTML?</h1>
    <p>HTML (HyperText Markup Language) é a linguagem padrão usada para criar e estruturar páginas na web. Ele permite organizar textos, imagens, links e outros conteúdos de forma que possam ser visualizados em navegadores.</p>
  </header>

  <section>
    <h2>Breve história do criador do HTML</h2>
    <p>O HTML foi criado por Tim Berners-Lee, um cientista da computação britânico. Em 1989, enquanto trabalhava no CERN, ele propôs um sistema de gerenciamento de informações que se tornaria a World Wide Web. Em 1991, ele desenvolveu o primeiro site e publicou a primeira versão do HTML, permitindo a criação de páginas conectadas por hiperlinks. Seu trabalho revolucionou a forma como acessamos e compartilhamos informações.</p>
  </section>

  <section>
    <h2>Estrutura básica de um documento HTML</h2>
    <p>Um documento HTML é composto por elementos que definem a estrutura da página. A estrutura básica inclui as tags <code>&lt;!DOCTYPE html&gt;</code>, <code>&lt;html&gt;</code>, <code>&lt;head&gt;</code> e <code>&lt;body&gt;</code>. Dentro do <code>&lt;head&gt;</code>, podemos incluir metadados, o título da página e links para estilos. O conteúdo visível fica dentro do <code>&lt;body&gt;</code>.</p>
  </section>

  <section>
    <h2>Principais tags HTML</h2>
    <ul>
      <li><code>&lt;h1&gt; a &lt;h6&gt;</code>: Títulos</li>
      <li><code>&lt;p&gt;</code>: Parágrafos</li>
      <li><code>&lt;a&gt;</code>: Links</li>
      <li><code>&lt;img&gt;</code>: Imagens</li>
      <li><code>&lt;ul&gt;</code>, <code>&lt;ol&gt;</code> e <code>&lt;li&gt;</code>: Listas</li>
      <li><code>&lt;div&gt;</code> e <code>&lt;span&gt;</code>: Elementos genéricos de contêiner</li>
    </ul>

    <h2>Curiosidade</h2>
    <p>Existe uma variedade de tipos de <code>&lt;input&gt;</code> em HTML. Clique abaixo para ver os exemplos:</p>

    <button class="botao-exemplo" onclick="mostrarExemplo()">📂 Mostrar exemplos de &lt;input&gt;</button>

    <div id="exemplo" class="exemplo-box">
      <strong>Exemplos de <code>&lt;input type=""&gt;</code>:</strong><br><br>
      <code>&lt;input type="text"&gt;</code><br>
      <code>&lt;input type="password"&gt;</code><br>
      <code>&lt;input type="email"&gt;</code><br>
      <code>&lt;input type="number"&gt;</code><br>
      <code>&lt;input type="tel"&gt;</code><br>
      <code>&lt;input type="url"&gt;</code><br>
      <code>&lt;input type="search"&gt;</code><br>
      <code>&lt;input type="date"&gt;</code><br>
      <code>&lt;input type="time"&gt;</code><br>
      <code>&lt;input type="datetime-local"&gt;</code><br>
      <code>&lt;input type="month"&gt;</code><br>
      <code>&lt;input type="week"&gt;</code><br>
      <code>&lt;input type="checkbox"&gt;</code><br>
      <code>&lt;input type="radio"&gt;</code><br>
      <code>&lt;input type="range"&gt;</code><br>
      <code>&lt;input type="color"&gt;</code><br>
      <code>&lt;input type="file"&gt;</code><br>
      <code>&lt;input type="submit"&gt;</code><br>
      <code>&lt;input type="reset"&gt;</code><br>
      <code>&lt;input type="button"&gt;</code><br>
      <code>&lt;input type="hidden"&gt;</code>
    </div>
  </section>

  <section>
    <h2>Referências</h2>
    <ul>
      <li><a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML" target="_blank">MDN Web Docs</a></li>
      <li><a href="https://www.w3schools.com/html/" target="_blank">W3Schools</a></li>
    </ul>
  </section>

  <footer>
    <p>Copyright © 2025 Marcos Vinícius [test studios] - Todos os direitos reservados.</p>
    <p>Suporte: <a href="mailto:vnicusmrcs@gmail.com">vnicusmrcs@gmail.com</a></p>

  <script>
    function mostrarExemplo() {
      const div = document.getElementById('exemplo');
      div.style.display = (div.style.display === 'none' || div.style.display === '') ? 'block' : 'none';
    }
  </script>
   <h1>bora botar em pratica?</h1>
   <p>sobre as input types, vejamos na pratica.</p>
   <p>receba mais informação!,mais antes insira seu e-mail</p>
   --------------------------------------------------------------------
   <p>e-mail:</p><input type="email"> 
   <p>senha:</p><input type="password">
  <p><button>confirmar</button></p>
  </footer>
  <p>voçe ainda esta aqui?, que bom!,bem,esse e meu primeiro site,eu quero decora-lo ainda mais,lembrando que essa  versão esta em Demo, ou seja, pode aver modificação ou algo do tipo,mas uma coisa que eu digo... e que nunca desista do seu sonho,mesmo que seja dificil,continue pois no final vai valer a pena!</p>
  <h1>Obrigado por visitar meu site!:)</h1>  
  ---------------------------------------------------------------------
</body>
</html>

