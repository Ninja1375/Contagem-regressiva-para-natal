# Contagem Regressiva para o Natal

Este projeto é uma contagem regressiva visual e animada para o Natal, utilizando HTML, CSS e JavaScript. A interface exibe os dias, horas, minutos e segundos restantes até o Natal de 2024.

## Tecnologias Utilizadas

- **HTML**: Estrutura do layout.
- **CSS**: Estilização e animações.
- **JavaScript**: Lógica de cálculo do tempo restante.

## Como Usar

1. Faça o download dos arquivos do projeto: `index.html`, `style.css` e `script.js`.
2. Certifique-se de que os três arquivos estão na mesma pasta.
3. Abra o arquivo `index.html` em um navegador para visualizar a contagem regressiva.

## Estrutura do Projeto

- **index.html**: 
  - Estrutura principal com elementos de contagem e texto introdutório.
  - Inclui referência aos arquivos CSS e JavaScript.

- **style.css**:
  - Estiliza os círculos e o texto exibido na contagem.
  - Define animações de "bounce" para os elementos.

- **script.js**:
  - Calcula a diferença de tempo entre a data atual e o Natal de 2024.
  - Atualiza os elementos da contagem em tempo real.

## Pré-visualização

A interface apresenta quatro círculos coloridos, cada um mostrando:
- Dias restantes.
- Horas restantes.
- Minutos restantes.
- Segundos restantes.

Além disso, há uma mensagem de "Feliz Natal!" e um botão fictício para "Compre Agora".

## Personalização

- Para alterar a data da contagem regressiva, modifique a seguinte linha no arquivo `script.js`:
  ```javascript
  var dest = new Date("dec 25, 2024 12:00:00").getTime();

Substitua "dec 25, 2024 12:00:00" pela data desejada.

Licença

Este projeto é de livre uso para fins educacionais ou pessoais.

## Apoie-me:

<a href="https://buymeacoffee.com/antonio13" target="_blank"><img loading="lazy" src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&emoji=&slug=seu_nome_de_usuario&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff" width="130" height="30"></a>

<a href="https://www.paypal.com/donate/?hosted_button_id=DN574F28FYUNG" target="_blank"><img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/b/b5/PayPal.svg" width="130" height="30"></a>

<a href="https://github.com/sponsors/Ninja1375" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-Sponsor-ea4aaa?style=for-the-badge&logo=github&logoColor=white" width="130" height="30"></a>

