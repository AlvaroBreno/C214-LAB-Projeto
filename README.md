<h1 align="center"> Incrementador e Decrementador </h1>
<p align="center">
  <img src="https://github.com/AlvaroBreno/C214-LAB-Projeto/actions/workflows/node.js.yml/badge.svg">
</p>


## Menu
- [Sobre](#sobre)
- [React](#react)
- [Instalação e Execução](#instalação-e-Execução)
  - [Front-end](#front-end)
  - [Back-end](#back-end)
  - [IDE de desenvolvimento](#ide-de-desenvolvimento) 
- [Clonando o projeto](#clone-o-projeto-no-seu-computador)
  - [Possíveis erros](#possíveis-erros-após-a-execução-de-npm-start)
- [Desenvolvimento e Melhorias](#desenvolvimento-e-melhorias)
- [Autores](#autores)

## Sobre:

O projeto trata-se sobre um incrementador e decrementador unitário simples baseado em react, com dois botões para realizar o incrementador em verde e o decrementador em vermelho. Inicialmente em zero, quando incrementar um valor e o mesmo ser positivo, ficará verde o numero em exibição. O mesmo acontece para caso o decremento ocorra e seja negativo, ficará em vermelho o numero em exibição.


## React

React JS é uma biblioteca JavaScript para a criação de interfaces de usuário — ou UI de código aberto. React faz com que a criação de UIs interativas seja uma tarefa fácil. Crie views simples para cada estado na sua aplicação, e o React irá atualizar e renderizar de forma eficiente apenas os componentes necessários na medida em que os dados mudam.
Por ser uma ferramenta no qual não é da grade curricular do curso de graduação e, a fim de aprender sobre outras ferramentas que, possivelmente possamos usar no mercado de trabalho.

## Instalação e Execução

#### Front-end:

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
)](https://pt-br.reactjs.org/) 
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
)](https://developer.mozilla.org/en-US/docs/Learn/HTML) 
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white
)](https://developer.mozilla.org/en-US/docs/Learn/CSS) 
[![JavaScritp](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
)](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

#### Back-end:

[![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white
)](https://nodejs.org/en/)

#### IDE de Desenvolvimento 
[![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)

Verifique se tem instalado o NodeJS em sua máquina. Caso nao tenha instalado em sua máquina, use [esse link](https://nodejs.org/en/) para acessar o instalador e a documentação oficial do NodeJS.

Para verificar se foi instalado corretamente e o núnero da versão instalada, use:

```bash
node -v
```

## Clone o projeto no seu computador:

```bash
git clone https://github.com/AlvaroBreno/C214-LAB-Projeto.git
```

Com o projeto clonado em sua máquina
Instale as dependencias do projeto usando o npm (com o projeto aberto na IDE).

```bash
npm install
```

Para rodar o programa, execute o comando:

```bash
npm start
```

Note que após a inicialização, abrirá um localhost para execução do código.

```bash
http://localhost:3000
```

#### Possíveis erros após a execução de npm start

* Mensagem **Something is already running on port 3000**:

Execute o seguinte comando para corrigir o erro e liberar a porta 3000 e assim executar o projeto. 

```bash
npx kill-port 3000
```

* Mensagem **'React' must be in scope when using JSX**: 

Execute o seguinte comando para corrigir o erro, e rode **npm start** novamente.

```bash
npm update
```



## Desenvolvimento e Melhorias

Que melhorias você fez no seu código? Ex: refatorações, melhorias de performance, acessibilidade, etc

 - [x]  Criação do README.md
 - [x]  Criação do Projeto inicial
 - [X]  Desenvolvimento do Projeto
 - [X]  Realização dos Testes


## Autores

- **Alvaro Breno** - Link Github: [Alvaro Breno](https://www.github.com/AlvaroBreno)
- **André** - Link Github: [André](https://github.com/andrevrj)
- **Bruno Rabelo** - Link Github: [Bruno Rabelo](https://github.com/barabelo)
- **Vagner Silva** - Link Github: [Vagner Silva](https://github.com/silva-vagner)

