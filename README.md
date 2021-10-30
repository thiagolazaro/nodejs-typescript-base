## Configuração Base para NodeJS e Typescript

## Recursos utilizados na configuração:

- Typescript;
- NodeJS
- Express
- DontEnv
- ESLint;
- Prettier


## Começando... 😁

Para começar, você deve simplesmente clonar o repositório do projeto na sua máquina e instalar as dependências.

### Pre-Requisitos 😅

Antes de instalar as dependências no projeto, você precisa já ter instalado na sua máquina:

* **Node.Js**: Caso não tenha, basta realizar o download [Aqui](https://nodejs.org/en/)
 
 Estou utilizando o Yarn para instalar execute:
 ```
npm install -g yarn
```

* **Git**: Caso não tenha instalado, [clicando aqui podera seguir esse artigo da propria pagina do git para instalar em seu sistema operacional seja ele Mac, Windows, Linux etc.](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git)

### Criando um projeto

Abre terminal ou cmd (caso esteja utilizando o Windows) e digite

```
git clone https://github.com/thiagolazaro/nodejs-typescript-base  nome-seu-projeto
```

### Instalando as Dependências

Depois de realizar o clone do projeto base, com o terminal aberto entra no seu projeto com o comando
```
cd nome-seu-projeto
```
Para instalar as dependência execute o comando :

```
yarn
```

Ao digitar a instrução acima, automaticamente ele irá baixar todas as dependências listadas no arquivo package.json:

* `node_modules` - que contêm os packages do npm que precisará para o projeto.

👉 Na sequencia você renomeia o arquivo * `.env.example`  para  * `.env`   e coloca o nome do seu projeto!

### Executando a Aplicação 👍

Bom, agora na mesma tela do terminal ou cmd, basta iniciar o server para o projeto ser executado localmente.

```
yarn dev
```

Agora você vai ver a mensagem no terminal ou cmd

![Solid](https://github.com/thiagolazaro/nodejs-typescript-base/blob/main/projeto-funcionando.jpg)

Parabéns seu projeto está funcinando!

Agora é so continuar e desenvolver seus projetos 😁😁😁