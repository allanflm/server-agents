# NLW Agents

Projeto de backend desenvolvido durante o evento **Next Level Week (NLW) Agents** da [Rocketseat](https://rocketseat.com.br).

## 🚀 Tecnologias Utilizadas

Este projeto foi construído com as seguintes tecnologias e bibliotecas principais:

- **Node.js**: Ambiente de execução para o JavaScript no servidor.
- **Fastify**: Um framework web de alta performance e baixo overhead, utilizado para construir a API.
- **@fastify/swagger**: Plugin para gerar documentação de API interativa (Swagger/OpenAPI) automaticamente a partir dos schemas das rotas.
- **Biome**: Ferramenta integrada para formatação e linting de código, garantindo consistência e qualidade no desenvolvimento.
- **esbuild**: Utilizado nos bastidores para transpilação e bundling de TypeScript/JavaScript com foco em velocidade.

## 🏛️ Padrões de Projeto

- **API First**: Com o uso do `@fastify/swagger`, o projeto segue uma abordagem onde o contrato da API é definido e documentado primeiro, facilitando a integração e o desenvolvimento do frontend.
- **Qualidade de Código**: A adoção do Biome como ferramenta única para lint e formatação assegura um padrão de código consistente em todo o projeto, com regras pré-definidas para evitar erros comuns.

## ⚙️ Setup e Configuração

Siga os passos abaixo para configurar e executar o projeto em seu ambiente local.

### Pré-requisitos

- Node.js (versão 20 ou superior)
- Um gerenciador de pacotes como `npm`, `yarn` ou `pnpm`.

### Instalação

1. Clone este repositório:
   ```sh
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DA_PASTA>
   ```

2. Instale as dependências do projeto:
   ```sh
   npm install
   ```

### Executando o Projeto

1. Para iniciar o servidor em modo de desenvolvimento, execute:
   ```sh
   npm run dev
   ```

2. O servidor estará rodando em `http://localhost:3333`.

3. A documentação da API estará disponível em `http://localhost:3333/docs`.

### Comandos Úteis (Biome)

- Para verificar a formatação e aplicar correções de lint seguras:
  ```sh
  npx biome check --write .
  ```