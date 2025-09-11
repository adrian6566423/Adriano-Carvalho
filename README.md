
body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f9;
      color: #333;
    }
    header {
      background: #0077cc;
      color: white;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }
    pre {
      background: #272822;
      color: #f8f8f2;
      padding: 15px;
      border-radius: 10px;
      overflow-x: auto;
    }
    h2 {
      color: #0077cc;
    }
    canvas {
      display: block;
      margin: 20px auto;
      border: 2px solid #0077cc;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Portfólio de Programação</h1>
    <p><strong>Adriano - 2º A</strong> | Escola João Evangelista</p>
  </header>

  <section>
    <h2>Minhas Qualidades</h2>
    <ul>
      <li>Programador dedicado e curioso.</li>
      <li>Experiência em Java, JavaScript e p5.js.</li>
      <li>Capacidade de resolver problemas e criar projetos criativos.</li>
    </ul>
  </section>

  <section>
    <h2>Exemplo em Java</h2>
    <pre><code>public class HelloWorld {
  public static void main(String[] args) {
    System.out.println("Olá, eu sou Adriano do 2º A!");
    int soma = 5 + 10;
    System.out.println("A soma de 5 + 10 é: " + soma);
  }
}</code></pre>
  </section>

  <section>
    <h2>Exemplo em JavaScript</h2>
    <pre><code>// Função para calcular fatorial
function fatorial(n) {
  if (n === 0) return 1;
  return n * fatorial(n - 1);
}

console.log("Fatorial de 5 é:", fatorial(5));</code></pre>
  </section>

  <section>
    <h2>Exemplo em p5.js</h2>
    <p>Um círculo interativo que segue o mouse:</p>
    <pre><code>function setup() {
  createCanvas(400, 300);
  background(220);
}

function draw() {
  background(220);
  fill(0, 150, 255);
  ellipse(mouseX, mouseY, 50, 50);
}</code></pre>
  </section>

  <section>
    <h2>Resultado do p5.js</h2>
    <div id="sketch"></div>
  </section>

  <script>
    function setup() {
      let canvas = createCanvas(400, 300);
      canvas.parent("sketch");
    }

    function draw() {
      background(240);
      fill(0, 150, 255);
      ellipse(mouseX, mouseY, 50, 50);
    }
  </script>
</body>
</html>
