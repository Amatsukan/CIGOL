CIGOL - Colorful Interactive Game of Life 🌈👾

CIGOL é uma versão infinita e interativa do Jogo da Vida de Conway. Desenvolvido por Amatsukan, o projeto traz herança de cores (HSL), ferramentas de desenho e parametrização em tempo real. Explore a "Borda do Caos" e crie padrões hipnotizantes numa simulação didática direto no navegador!

✨ Funcionalidades Principais

🌌 Plano Infinito (Virtualização): Navegue por uma matriz sem limites. Graças à utilização de uma Sparse Matrix (Matriz Esparsa) e renderização inteligente via HTML5 Canvas, a simulação apenas consome memória para as células vivas, garantindo alta performance mesmo com ecrãs repletos de vida.

🧬 Herança Genética Colorida: As células "filhas" não nascem apenas pretas ou brancas. Elas herdam as cores dos seus "pais" (células vizinhas) através de cálculos matemáticos cíclicos (Matiz HSL). Existe ainda um sistema de mutação genética que, quando ativo, desvia ligeiramente a cor a cada geração, criando rastos arco-íris deslumbrantes.

🎨 Ferramentas de Criação Avançadas: Uma interface ao estilo Paint integrada na simulação:

🖌️ Pincel: Com algoritmo de Bresenham para traços contínuos.

🔲 / ⭕ Formas Geométricas: Retângulos e círculos (ocos ou sólidos).

🪣 Balde de Tinta: Preenchimento de área seguro (com limite de segurança para planos infinitos).

💦 Spray: Perfeito para espalhar caos e poeira estelar.

🧪 Laboratório em Tempo Real: Altere as Leis da Física do universo enquanto a simulação corre! Modifique as constantes de Subpopulação, Sobrevivência, Superpopulação e Nascimento para observar o colapso ou a explosão da vida instantaneamente.

🚀 Como Usar

Este projeto é 100% Client-Side (Front-end) e não necessita de qualquer servidor, dependências externas ou processos de build.

Faça o clone deste repositório ou descarregue o ficheiro.

Abra o ficheiro matriz_infinita.html em qualquer navegador web moderno (Chrome, Firefox, Edge, Safari).

Comece a desenhar e clique em "▶️ Iniciar Simulação".

🎮 Controlos

Botão Esquerdo do Rato: Desenhar / Interagir com a ferramenta selecionada.

Botão Direito do Rato: Clicar e arrastar move a câmara pelo plano infinito (funciona a qualquer momento, independentemente da ferramenta selecionada).

Scroll (Roda do Rato): Aumentar ou reduzir o zoom (centrado na posição do rato).

🧠 A Matemática por trás (Conway)

O "Jogo da Vida" original de John Conway utiliza as regras [2, 2, 3, 4, 3]:

Subpopulação (< 2): Morre de solidão.

Sobrevivência (2 a 3): Permanece viva.

Superpopulação (>= 4): Morre por falta de recursos.

Nascimento (Exatamente 3): Uma nova célula nasce.

O CIGOL permite alterar estes valores para que possa explorar as razões pelas quais Conway escolheu exatamente estes números para alcançar a chamada "Borda do Caos" — o equilíbrio perfeito entre um universo morto e um universo caótico estático.

👨‍💻 Autor

Desenvolvido por Amatsukan.

Criado com o objetivo de tornar conceitos matemáticos e de autómato celular mais acessíveis, interativos e visualmente estimulantes para aulas e demonstrações.

Sinta-se livre para explorar, fazer fork e contribuir para o código!
