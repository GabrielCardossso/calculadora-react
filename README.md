<img src="./.github/readme/header.svg" width="100%" alt="calculadora-react: Projeto de estudo" />

<img src="./.github/readme/sobre.svg" width="100%" alt="Sobre o projeto: Calculadora feita em React, com foco em lógica de programação, componentização e manipulação de estados. Faz contas encadeadas como uma calculadora de verdade." />

<img src="./.github/readme/stack.svg" width="100%" alt="Stack: React, JavaScript, CSS3, HTML5, Create React App, Node.js / npm" />

<img src="./.github/readme/funcionalidades.svg" width="100%" alt="Funcionalidades: Operações básicas (Soma, subtração, multiplicação e divisão, com números decimais; divisão por zero não quebra a conta.); Operações encadeadas (Em 10 + 10 + 5, a operação anterior é calculada sozinha e o fluxo da conta continua.); Suporte ao teclado (Números, operadores, Enter para o resultado e Esc para limpar, sem precisar do mouse.); Display dinâmico (Atualiza em tempo real; ao apertar = mostra só o resultado e limpa sozinho no próximo número.); Componentes (Button, Display e Calculator separados, cada um com seu próprio CSS.); Interface responsiva (Layout moderno em grade, com fonte Roboto Mono e link para o GitHub no rodapé.)" />

<img src="./.github/readme/estrutura.svg" width="100%" alt="Estrutura de pastas: src/ (código da aplicação), main/ (Calculator: lógica principal), components/ (Button e Display), fonts/ (fonte Roboto Mono), App.js (componente raiz), public/ (index.html e ícones), assets/ (prévia em GIF e imagem), package.json (dependências e scripts)" />

<img src="./.github/readme/secao-01-como-rodar.svg" width="100%" alt="Como rodar" />

```bash
git clone https://github.com/GabrielCardossso/calculadora-react
cd calculadora-react
npm install
npm start          # abre em http://localhost:3000
```

Para gerar a versão de produção: `npm run build`.

<img src="./.github/readme/secao-02-como-usar.svg" width="100%" alt="Como usar" />

A calculadora tem um sistema de operações encadeadas parecido com o de calculadoras reais. Em `10 + 10 + 5`, ela:

- calcula automaticamente a operação anterior ao escolher o próximo operador;
- mantém o fluxo da conta e atualiza o display em tempo real;
- ao pressionar `=`, mostra apenas o resultado; ao começar uma nova operação, o cálculo continua normalmente.

### Atalhos do teclado

| Tecla | Ação |
| --- | --- |
| `0`–`9` | Digita o número |
| `.` ou `,` | Ponto decimal |
| `+` `-` `*` `/` | Escolhe a operação |
| `Enter` ou `=` | Mostra o resultado |
| `Esc` ou `Delete` | Limpa tudo (AC) |

<img src="./.github/readme/secao-03-aprendizados.svg" width="100%" alt="Aprendizados" />

- Componentização e props.
- Estados e eventos (cliques e teclado).
- Manipulação do DOM com React.
- Organização de projeto e CSS separado por componente.
- Lógica de programação e operações matemáticas.

<img src="./.github/readme/secao-04-previa.svg" width="100%" alt="Prévia" />

<div align="center">
  <img src="./assets/VideoPreview.gif" width="700" alt="Calculadora em React em uso" />
</div>

<a href="https://github.com/GabrielCardossso"><img src="./.github/readme/rodape.svg" width="100%" alt="Obrigado! Feito por Gabriel Cardoso" /></a>
