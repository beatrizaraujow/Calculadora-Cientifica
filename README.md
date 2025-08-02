# Calculadora Científica

Este projeto é uma **Calculadora Científica** desenvolvida com **HTML, CSS e JavaScript puro**. A aplicação possui funções básicas (adição, subtração, multiplicação, divisão, porcentagem) e funções científicas como **seno, cosseno, tangente** e **raiz quadrada**.

## Funcionalidades

* Operações Aritméticas: `+`, `-`, `×`, `/`, `%`
* Funções Científicas:

  * Seno (`sin`)
  * Cosseno (`cos`)
  * Tangente (`tan`)
  * Raiz Quadrada (`√`)
* Botão **AC (All Clear)** para limpar tudo
* Botão **⌫ (Backspace)** para apagar o último dígito
* Exibição do histórico da operação em andamento
* Interface responsiva e estilizada com CSS moderno

## 🛠️ Tecnologias Utilizadas

* **HTML5**: Estruturação da calculadora e seus elementos.
* **CSS3**: Estilização com grid layout para os botões, responsividade e efeitos de hover/active.
* **JavaScript (Vanilla JS)**: Lógica funcional da calculadora, manipulação do DOM, cálculos matemáticos e funções científicas utilizando o objeto `Math`.

## Estrutura de Arquivos

```
📁 Calculadora-Cientifica
├── index.html
├── style.css
└── README.md
```

## ⚙️ Como Funciona?

### HTML:

* A calculadora é composta por um container `.calculator` que possui:

  * Um **display** para exibir os valores digitados e resultados.
  * Um **painel de botões**, organizado com **CSS Grid**, com categorias específicas (operadores, científicos, numéricos).

### CSS:

* Utilização de **Grid Layout** para organizar os botões em 5 colunas.
* Cores diferenciadas para botões de ação, operadores e funções científicas.
* Estilo responsivo e centralizado utilizando Flexbox para o corpo da página.

### JavaScript:

* Manipulação de variáveis globais para armazenar operandos e operadores.
* Funções principais:

  * `appendNumber()`: Adiciona números ou ponto decimal ao display.
  * `appendOperator()`: Armazena o operador selecionado e prepara a operação.
  * `calculate()`: Realiza o cálculo entre os operandos.
  * `calculateFunction()`: Executa funções científicas (`Math.sin`, `Math.cos`, `Math.tan`, `Math.sqrt`).
  * `clearAll()`: Reseta a calculadora.
  * `deleteLast()`: Remove o último caractere digitado.
* As funções atualizam dinamicamente os elementos do display.

## Melhorias Futuras

* Implementar suporte a parênteses.
* Adicionar mais funções científicas (logaritmos, exponenciais).
* Histórico de cálculos.
* Animações para interação com os botões.
