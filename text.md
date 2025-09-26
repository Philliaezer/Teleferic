Perguntar para o Otavio script de atendimento voz para o cliente para colocar em aba especial Scripts/Templates da equipe Time Bradesco no Microsoft Teams

Tabelas (dica: fazer html)
- Redumo de informações dos principais casos (contestação, anuidade, evolução de dívidas, etc.)
- Prazos SLA (também coloque descrição FORA da tabela sobre como deve ser feito o contato ex: após feito contato com sucesso, podem ser feitos quantos contatos quiser/precisar)
- Do que precisa de PID, só que não precisa contato com o cliente, do que é feito no plástico e do que é feito na consolidada 
- Ver formulario bradesco e colocar fixado no email e teams pessoal

Entulho -> colocar informações importantes de cada um dos três principais sistemas 

NÃO SE ESQUECA DOS EMAILS - MAS FOQUE NOS PRINCIPAIS/DISNEY/MAIS RECENTES

Estudar mais sobre limites

Service view
- conta consolidada (titular): número completo
- conta plástico - número truncado/com asteriscos 
SACL
- Ir na aba """"histórico """ para ver histórico do cliente


<!-- Using iframe -->
    <iframe src="another_page.html" width="100%" height="400px" frameborder="0"></iframe>

    
    <!-- <embed src="another_page.html" type="text/html" width="100%" height="400px"> -->
    

https://github.com/Philliaezer/operation/blob/main/info.md
https://github.com/Philliaezer/operation/tree/main base64.html editor.html youtube.html TABELA VENDORS.xlsx https://cdn.jsdelivr.net/gh/philliaezer/teleferic@main

https://tpbradesco.beedoo.io/wiki/467260/rotativo-devolucao-de-pagamento

https://tpbradesco.beedoo.io/wiki/465881/registro-informativo

Atenção! Para 100% das tratativas, siga com o registro informativo!

Para todas a situações que exija Registro informativo siga com o registro no sistema Service View em Tarefa RC000 - Informacoes Gerais  reclamacoes, conforme passo a passo abaixo:

https://tpbradesco.beedoo.io/wiki/474173/reativacao-do-cartao

A manutenção é realizada online e caso o sistema apresente erro é necessário abrir tarefa na fila RC042 - SOLICITAÇÃO DE REATIVAÇÃO DE CARTÃO/PF. 

BM002 - SOLICITACAO DE ROTATIVO NORMAL

BM003 - ANTECIPACAO DE PAGAMENTO

BM004 - ACERTO/CANCELAMENTO DE ROTATIVO

BM005 – DEVOLUÇÃO DE PAGAMENTO – EXCEÇÃO

https://tpbradesco.beedoo.io/wiki/470246/transferencia-de-pagamento

BM006 - TRANSFERENCIA DE PAGAMENTO

https://tpbradesco.beedoo.io/wiki/470793/antecipacao-de-compras-parceladas

BM007 - ANTECIPACAO TOTAL PARCELADO

https://tpbradesco.beedoo.io/wiki/469378/anuidade

BM008 - ISENCAO TOTAL/PARCIAL TAXA DE ANUIDADE

https://tpbradesco.beedoo.io/wiki/470793/antecipacao-de-compras-parceladas

BM009 – REPROCESSAMENTO DE PARCELAS

https://tpbradesco.beedoo.io/wiki/469637/estorno-de-encargos-juros-multa-e-iof

BM010 – ESTORNO TAXAS / TARIFAS

https://tpbradesco.beedoo.io/wiki/470719/devolucao-saldo-credor

BM011 - TRANSFERENCIA DE SALDO CREDOR - ENTRE CARTOES

BM012 - TRANSF SALDO CREDOR - CONTA CORRENTE

https://tpbradesco.beedoo.io/wiki/467355/parcelamento-de-fatura-parcelado-comum-parcelado-facil

BM013 - PARCELAMENTO DE FATURA

https://tpbradesco.beedoo.io/wiki/476562/seguros-cartao-de-credito

BM015 - SOLICITACAO DE ESTORNO DO SEGURO

https://tpbradesco.beedoo.io/wiki/476562/seguros-cartao-de-credito

BM020- ESTORNO DO BRADESCO DENTAL

https://tpbradesco.beedoo.io/wiki/469378/anuidade

BM025 - Isenção Anuidade - Func Folha de Pagamento

https://tpbradesco.beedoo.io/wiki/469637/estorno-de-encargos-juros-multa-e-iof

BM029 – AJUSTES DE ENCARGOS - CHEQUE ESPECIAL

https://tpbradesco.beedoo.io/wiki/470211/pagamento-nao-processado

BM049 – VERIFICAR BAIXA DE PAGAMENTO – PF 

https://tpbradesco.beedoo.io/wiki/470615/alteracao-de-vencimento

BM065 - MANIFESTACAO ALTERACAO DE VENCIMENTO EXCECAO - BACK OFFICE. 

https://tpbradesco.beedoo.io/wiki/470719/devolucao-saldo-credor

BM547 DEVOLUCAO SALDO CREDOR - CARTÃO ATIVO CANC SRV 

Tabulator
<!DOCTYPE html>
<html lang="pt-BR">

<head>
  <meta charset="UTF-8">
  <title>Selects dinâmicos</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background-color: #24d6cd;
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 90vh;
    }

    select {
      margin: 5px;
      padding: 5px;
      background-color: #24d6cd;
      color: #fff;
      border: 1px solid #fff;
      border-radius: 5px;
      font-size: 16px;
      width: 200px;
    }

    #select-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
  </style>
</head>

<body>
  <h1>Tabulator</h1>
  <h2>Selecione:</h2>
  <div id="select-container"></div>

  <script>
    const data = {
      "Cartao Top": {
        "Solicitacao": {
          "Primeira Via": "primeira_via",
          "Segunda Via": {
            "Puro": "segunda_puro", 
            "Hibrido": "segunda_hibrido"
          }
        },
        "Reclamacao": {
          "Erro de Leitura": "erro_leitura"
        }
      },
      "Cartão City": {
        "Informação": {
          "Como obter 1a via": "obter_primeira",
          "Como obter 2a via": {
              "Comum": "city_segunda_comum",
              "VT": "city_segunda_vt",
              "Especial": "city_segunda_especial",
              "Escolar": "city_segunda_escolar",
              /*
              "Comum":"Olá CLIENTE, segue link para saber como obter a segunda via do seu cartão: LINK",
              "VT": "Olá CLIENTE, segue link para saber como obter a segunda via do seu cartão VT: LINK"*/
            }
        }
      }
    };

    const templates = {
      "primeira_via": "Olá CLIENTE, segue link para obter a primeira via do seu cartão: LINK",
      "segunda_puro": "Olá CLIENTE, segue link para obter a segunda via do seu cartão: LINK",
      "segunda_hibrido": "Olá CLIENTE, segue link para obter a segunda via do seu cartão híbrido: LINK",
      "erro_leitura": "Olá CLIENTE, segue link para saber como resolver o erro de leitura do seu cartão: LINK",
      "obter_primeira": "Olá CLIENTE, segue link para saber como obter a primeira via do seu cartão: LINK",
      "city_segunda_comum": "Olá CLIENTE, segue link para saber como obter a segunda via do seu cartão: LINK",
      "city_segunda_vt": "Olá CLIENTE, segue link para saber como obter a segunda via do seu cartão VT: LINK",
      "city_segunda_especial": "Olá CLIENTE, segue link para saber como obter a segunda via do seu cartão especial: LINK",
    }
    
    const container = document.getElementById("select-container");

    // Função para criar um select a partir de um objeto/array
    function createSelect(options, nextCallback) {
      const select = document.createElement("select");

      const defaultOpt = document.createElement("option");
      defaultOpt.textContent = "Selecione...";
      defaultOpt.disabled = true;
      defaultOpt.selected = true;
      select.appendChild(defaultOpt);

      for (let key in options) {
        let opt = document.createElement("option");
        opt.value = key;
        opt.textContent = key;
        select.appendChild(opt);
      }

      select.addEventListener("change", () => {
        // Remove selects que vierem depois
        while (select.nextSibling) {
          container.removeChild(select.nextSibling);
        }

        const selected = options[select.value];

        if (typeof selected === "object") {
          if (Array.isArray(selected)) {
            // Caso seja array -> cria select com os valores
            const subSelect = document.createElement("select");
            selected.forEach(v => {
              let opt = document.createElement("option");
              opt.value = v;
              opt.textContent = v;
              subSelect.appendChild(opt);
            });
            container.appendChild(subSelect);
          } else {
            // Caso seja outro objeto -> cria novo select recursivo
            const subSelect = createSelect(selected);
            container.appendChild(subSelect);
          }
        } else if (typeof selected === "string"){
          // Caso seja número -> cria texto
          const input = document.createElement("p");
          input.textContent = templates[selected];
          container.appendChild(input);
        }
        // Se for 0 -> para
      });

      return select;
    }

    // Inicializa com o objeto raiz
    container.appendChild(createSelect(data));

  </script>
</body>

</html>


Editor

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>VS Pobre</title>
<style>
  body, html { display: flex; flex-direction: column; margin:0; height:100%; max-width:100vw; background-color: #343131; color: white; font-family: Verdana, Geneva, Tahoma, sans-serif; padding: 15px; }
  
  #editor { position: relative; width:100%; height:90vh; border:0; height:70vh!important;}
  .editor-container { width:100%; height:10vh!important; padding-bottom: 15px; box-sizing: border-box !important; }
  
  header { box-sizing: border-box !important; display: flex; justify-content: space-between; align-items: center; width: 100%; padding: 10px; background-color: #222; color: white; margin-bottom: 20px; position: relative;box-sizing: border-box !important;}
  
  .fa { font-size: 24px; cursor: pointer; } 
  #settingsIcon { display: inline-block; padding: 25px;}
  
  .settings {
    display: none; margin-top: 40px;
    background-color: #222; padding: 10px; border-radius: 5px; 
  position: absolute; top: 100px; right: 15px; z-index: 10;  transform: translateX(0px); }
  .settings-list { list-style: none; padding: 0; margin: 0; }
  
  .changeVisibility { display: block !important; }
  .shortcuts-container { position: fixed; top: 0; left: 0; width: 100%; height: 100%; display: none; align-items: center; justify-content: center; z-index: 10; }
  .shortcuts-background { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 13; }
  .shortcuts { position: fixed; display: none; background-color: #222; padding: 10px; border-radius: 5px; z-index: 15; top: 50%; left: 50%; transform: translate(-50%, -50%);}
  .logo { display: flex; min-width: 225px; align-items: center; justify-content: space-between; }
  .console { display: none; position: fixed; bottom: 0; left: 0; width: 100%; height: 40%; background-color: #222; color: white; padding: 10px; box-sizing: border-box; z-index: 20; overflow-y: scroll; }
  
  @media (max-width: 475px) { .title { display: none; } .logo { min-width: 50px; } } 
</style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <script src="https://cdn.jsdelivr.net/pyodide/v0.23.4/full/pyodide.js"></script>

  <!-- cdn jsdelvr do pyodide -->
  <!--script src="https://cdn.jsdelivr.net/pyodide/v0.21.3/full/pyodide.js"></script-->
  <script src="https://cdn.jsdelivr.net/npm/php-wasm@0.0.8/php-web.min.js"></script>
  <!-- https://www.jsdelivr.com/package/npm/@webwriter/code -->
</head>
<body>
    <header>
      <div class="logo">
        <img src="./vscode.webp" alt="VS Pobre" width="50" height="50">
        <h1 class="title">VS Pobre</h1>
      </div>
      <div class="icons">
        <i class="fa fa-cog" id="settingsIcon"></i>
        <i class="fa fa-play" id="settingsIcon" onclick="runCode()"></i>
      </div>
    </header>
    <div class="settings">
      <ul class="settings-list">
        <li>
          <label for="fontSizeSlider">Font Size:</label>
          <input type="range" id="fontSizeSlider" min="10" max="30" value="16" oninput="updateFontSize(this.value)">
        </li>
        <li>
          <label for="themeSelect">Theme:</label>
          <select id="themeSelect" onchange="updateTheme(this.value)">
            <option value="vs-dark">Dark</option>
            <option value="vs-light">Light</option>
          </select>
        </li>
        <li>
          <label for="languageSelect">Language:</label>
          <select id="languageSelect" onchange="updateLanguage(this.value)">
            <option value="javascript">JavaScript</option>
            <option value="html">HTML</option>
            <option value="css">CSS</option>
            <option value="java">Java</option>
            <option value="php">PHP</option>
            <option value="python">Python</option>
          </select>
        </li>
        <li>
          <label for="saveCode">Save Code:</label>
          <button onclick="promptSaveCode()">Save Code</button>
        </li>
        <li>
          <label for="shortcuts">Shortcuts:</label>
          <button onclick="openShortcuts()">Open Shortcuts</button>
        </li>
    </div>


    <div class="shortcuts-container">
      <div class="shortcuts-background"></div>
      <div class="shortcuts">
        <ul class="shortcuts-list">
          <li><strong>Ctrl + S</strong> - Salvar Código</li>
          <li><strong>Ctrl + O</strong> - Abrir Código</li>
          <li><strong>Ctrl + P</strong> - Abrir Paleta de Comandos</li>
          <li><strong>Alt + Shift + Seta para baixo</strong> - Duplicar Linha</li>
          <li><strong>Alt + Shift + Seta para cima</strong> - Mover Linha para cima</li>
        </ul>
      </div>
    </div>
    
    <div class="editor-container">
      <div id="editor"></div>
    </div>
  </div>

  <div class="console">
    <p>Console</p>
  </div>

<!-- Loader AMD necessário -->
<script src="https://cdn.jsdelivr.net/npm/monaco-editor@0.52.2/min/vs/loader.js"></script>
<script>
  require.config({ paths: { 'vs': 'https://cdn.jsdelivr.net/npm/monaco-editor@0.52.2/min/vs' }});
  require(['vs/editor/editor.main'], function() {
    monaco.editor.create(document.getElementById('editor'), {
      value: `function exemploDeFuncao() {\n\tconsole.log("Este é um exemplo de função em JS");\n}`,
      language: 'javascript',
      theme: 'vs-dark',
      fontSize: 16,
      padding: { top: 30, bottom: 10 },
      automaticLayout: true
    });
  });
  function updateFontSize(value) {
    const editor = monaco.editor.getEditors()[0];
    editor.updateOptions({ fontSize: parseInt(value) });
  }
  document.getElementById('settingsIcon').addEventListener('click', function(){
    const settings = document.querySelector('.settings');
    settings.classList.toggle('changeVisibility');
  });
  function updateTheme(value) {
    const editor = monaco.editor.getEditors()[0];
    editor.updateOptions({ theme: value });
  }
  function updateLanguage(value) {
    const editor = monaco.editor.getEditors()[0];
    monaco.editor.setModelLanguage(editor.getModel(), value);
  }
  function promptSaveCode(){
    const filename = prompt('Enter filename:');
    if(filename){
      saveCode(filename);
    } else {
      alert('Filename is required');
    }
  }
  function saveCode(filename){
    const editor = monaco.editor.getEditors()[0];
    const code = editor.getValue();
    const blob = new Blob([code], { type: 'text/plain' });
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = filename;
    a.click();
  }


  const shortcuts = document.querySelector('.shortcuts');
  const shortcutsContainer = document.querySelector('.shortcuts-container')
  const shortcutsBackground = document.querySelector('.shortcuts-background');
  
  function openShortcuts() {
    for (change of [shortcuts, shortcutsBackground, shortcutsContainer]){
      change.classList.toggle('changeVisibility');
    }
  }
  
  document.querySelector('.shortcuts-background').addEventListener('click', function() {
    for (change of [shortcuts, shortcutsBackground, shortcutsContainer]){
      change.classList.remove('changeVisibility');
    }
  });

  async function runCode(){
    const editor = monaco.editor.getEditors()[0];
    const code = editor.getValue();
    const language = editor.getModel().getLanguageId();
    const consoler = document.querySelector('.console');
    // console.innerHTML = `<p>Console</p>`;
    if(language === 'python') {
      runPythonCode(code)
    } else if (language === `javascript`) {
      runJavaScriptCode(code);
    } else if (language === 'php') {
      runPHPCode(code);
    } else {
      consoler.innerHTML = `${language} não implementado ainda!`
    }

    function runJavaScriptCode(code){
      try {
        consoler.innerHTML = eval(code);
      } catch (err) {
        consoler.innerHTML = `<p style='color: red'>Erro: </p><p>${err}</p>`
      }
    }

    async function runPythonCode(code) {
      consoler.innerHTML = `<p>Só um momento...</p>`;

      try {
        const pyodide = await loadPyodide({
          indexURL: "https://cdn.jsdelivr.net/pyodide/v0.23.4/full/"
        });

        // Redirect stdout and stderr
        pyodide.setStdout({
          batched: (output) => consoler.innerText = output
        });
        pyodide.setStderr({
          batched: (error) => consoler.innerText = error
        });

        await pyodide.runPythonAsync(code);
      } catch (err) {
        consoler.innerText = `Erro do Javascript: ${err}`;
      }
    }

    function runPHPCode(code){
      (async () => {
        // Carrega a instância do PHP compilado em WASM
        const php = await window.PHP.load();

        // Executa um código PHP simples
        const result = await php.run(code /*`<?php echo "Olá do PHP! " . (2+2); ?>`*/);

        // Pega a saída e coloca no HTML
        consoler.textContent = result.stdout;
      })();
    }
    consoler.classList.toggle('changeVisibility');
    };
</script>
</body>
</html>

Base64

<!-- Base64 Encoder/Decoder -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Base64 Encoder/Decoder</title>
    <style>
      body {
        font-family: Verdana, sans-serif;
        margin: 20px;
        background-color: #f4f4f4;
      }
      textarea {
        width: 85vw;
        height: 100px;
        margin-bottom: 10px;
        border: 3px solid #ccc;
        border-radius: 5px;
        padding: 10px;
      }
      button {
        margin-right: 10px;
      }
      #result {
        margin-top: 20px;
        background-color: #f9f9f9;
        padding: 10px;
        border: 1px solid #ccc;
        border-radius: 5px;
      }
      #result pre {
        white-space: pre-wrap;
        word-wrap: break-word;
      }
      #result h3 {
        margin-top: 0;
      }
      #result p {
        margin: 0;
      }
      #result .copy-button {
        margin-top: 10px;
      }
      .copy-button {
        background-color: #4285f4;
        border: none;
        border-radius: 3px;
        color: #fff;
        cursor: pointer;
        font-size: 14px;
        padding: 10px;
        width: 100%;
      }
      .copy-button:hover {
        background-color: #357ae8;
      }
      .copy-button:active {
        background-color: #285bac;
      }
      .copy-button:focus {
        outline: none;
      }  
      .copy-button:disabled {
        background-color: #ccc;
        cursor: not-allowed;
      }
      .copy-button:disabled:hover {
        background-color: #ccc;
      }
      .copy-button:disabled:active {
        background-color: #ccc;
      }
      .copy-button:disabled:focus {
        outline: none;
      }
      .code{
        border: none;
        border-radius: 3px;
        color: #fff;
        cursor: pointer;
        font-size: 14px;
        padding: 10px;
      }
      .code:first-of-type{
        background-color: green;
      }
      .code{
        background-color: blue;
      }
    </style>
    </head>
    <body>
      <h2>Base64 Encoder/Decoder</h2>
      <textarea id="inputText" placeholder="Enter text to encode or decode"></textarea>
      <button class="code" onclick="encode()">Encode</button>
      <button class="code" onclick="decode()">Decode</button>
      <div id="result"></div>
      <script>
        function encode() {
          const inputText = document.getElementById('inputText').value;
          const encodedText = btoa(inputText);
          displayResult(encodedText, 'Encoded Text');
        }

        function escapeHtml(text) {
  var map = {
    '&': '&amp;',
    '<': '&lt;',
    '>': '&gt;',
    '"': '&quot;',
    "'": '&#039;'
  };
  return text.replace(/[&<>"']/g, function(m) { return map[m]; });
            }
        
        function decode() {
          const inputText = document.getElementById('inputText').value;
          const decodedText = atob(inputText);
          displayResult(decodedText, 'Decodeed Text');
        }
        function displayResult(text, title) {
          const resultDiv = document.getElementById('result');
          resultDiv.innerHTML = `
            <h3>${title}</h3>
            <code>${escapeHtml(text)}</code>
            <button class="copy-button" onclick="copyToClipboard('${text}')">Copy to Clipboard</button>
          `;
        }
        function copyToClipboard(text) {
          navigator.clipboard.writeText(text).then(() => {
            alert('Copied to clipboard!');
          });
        }
        </script>
        </body>
        </html>


        https://tpbradesco.beedoo.io/wiki/470986/nao-recebimento-de-fatura-envio-de-fatura

RC000 - Envio de SMS/Whatsapp Linha Digitável 

https://tpbradesco.beedoo.io/wiki/470615/alteracao-de-vencimento

RC010 – SOLIC ALTERAÇÃO DE VENCIMENTO – PESSOA FISIC. 

https://tpbradesco.beedoo.io/wiki/467080/fraude

 - RC016 – Contestação Despesa Nacional: Despesa Nacional; 

https://tpbradesco.beedoo.io/wiki/470254/moeda-estrangeira

RC028 

RECLAMACAO DA TAXA DE CONVERSAO DO DOLAR 

https://tpbradesco.beedoo.io/wiki/471555/cancelamento-reemissao-cartao-nao-recebido

RC032 - RECLAMAÇÃO - REEMISSÃO DE CARTÃO – PF

 - RC056 – Contestação Despesa Internacional: Despesa Internacional. 

https://tpbradesco.beedoo.io/wiki/474173/reativacao-do-cartao

 RC042 - SOLICITAÇÃO DE REATIVAÇÃO DE CARTÃO/PF. 

https://tpbradesco.beedoo.io/wiki/467355/parcelamento-de-fatura-parcelado-comum-parcelado-facil

RC055 ANTECIPAÇÃO TOTAL PARCELADO -RCP 

https://tpbradesco.beedoo.io/wiki/472669/programas-fidelidade-livelo

RC072 - RETROACAO DE PONTOS - BACKOFFICE.

RC095 – Estorno de Despesa Segura – Exceção

RC172 – ENVIO DE 2º VIA DE FATURA
