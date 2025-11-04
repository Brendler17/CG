🧩 WebGL – Transformações 2D (Translação, Rotação e Escala)

Este projeto demonstra transformações 2D em WebGL, permitindo mover, rotacionar e escalar objetos (no caso, a letra F) diretamente em um canvas HTML.
O código utiliza shaders escritos em GLSL e JavaScript para aplicar as transformações por meio de matrizes 3x3.

📁 Estrutura do Projeto
/
├── index.html
├── script.js
└── styles.css

🚀 Como Executar

Baixe ou clone este repositório:

git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git


Abra a pasta do projeto:

cd NOME_DO_REPOSITORIO


Abra o arquivo index.html diretamente no navegador.

Você pode simplesmente dar duplo clique em index.html, ou

Abrir com o botão direito → Abrir com → Navegador (Chrome, Edge, Firefox, etc.)

💡 Dica:
Se o navegador bloquear a execução local de scripts, rode um servidor simples com Python:

python -m http.server 8080


Depois acesse http://localhost:8080
 no navegador.

🕹️ Como Usar

O programa renderiza uma letra F no canvas.

Você pode controlar as transformações (posição, rotação e escala) por meio dos sliders exibidos na interface.

É possível ajustar os parâmetros em tempo real e observar o resultado imediato na tela.

🧠 Conceitos Envolvidos

Vertex e Fragment Shaders (GLSL)

Matrizes de transformação (translação, rotação, escala)

Projeção 2D com WebGL

Ligação de variáveis da CPU (JavaScript) com a GPU (Shader)

Uso de VAOs (Vertex Array Objects) e Buffers

🖥️ Requisitos

Navegador com suporte a WebGL2 (Chrome, Edge, Firefox, Opera, etc.)

Conexão com a internet (para carregar as dependências externas da biblioteca webgl-utils.js)

📜 Créditos

Baseado nas lições de WebGL Fundamentals
.