<head>
  <title>Minha Página</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #f1f1f1;
      padding: 10px;
    }
    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    nav ul li {
      display: inline;
      margin: 0 10px;
    }
    section {
      padding: 20px;
      text-align: center;
    }
    footer {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h1>Minha Página</h1>
  </header>
  
  <nav>
    <ul>
      <li><a href="#">Big</a></li>
      <li><a href="#">Jao</a></li>
    </ul>
  </nav>
  
  <section>
    <h1>PERGUNTA SUPER SERIA</h1>
    <p>se te chamar pra um rodizio de traveco, tu vai ??</p>
	
<form>
    
   <p>Sim ou Nao ??:</p>
  <input type="text" id="numero" autocomplete="off">
  <button onclick="verificarNumero()">Verificar</button>
  <p id="resultado"></p>

  <script>
    function verificarNumero() {
      var numero = document.getElementById("numero").value;
      var resultadoElement = document.getElementById("resultado");

      if (numero  === "sim") {
        resultadoElement.textContent = <h1> "Amigo" </h1>
      } 
       else if (numero  === "Sim") {
        resultadoElement.textContent = "Amigo"
      } 
	 else if (numero  === "s") {
        resultadoElement.textContent = "Amigo"
      } 
	 else if (numero  === "S") {
        resultadoElement.textContent = "Amigo"
      } 
      else {
        resultadoElement.textContent = "Inimigo"
      }
	     event.preventDefault();
    }
  </script>
  </form>
	
  </section>
  
  <style>
  
   .button-container {
      display: grid;
      grid-template-columns: auto auto;
      gap: 10px;
    }
  
  .meu-botao{
    background-color: #000;
    color: white;
    padding: 10px 20px;
    border: none;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    cursor: pointer;
	
	margin-bottom: 20px;
  }
   
</style>







 <div class="button-container">
<button   class="meu-botao">Sim</button>
<button   class="meu-botao">Não</button>
 </div>
 
  <footer>
    <p>Saporra tem dono e sou eu</p>
  </footer>
</body>

