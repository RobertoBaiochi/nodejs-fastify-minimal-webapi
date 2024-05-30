<div align="center">

  <h1 align="center"><strong>Fórmula 1 Minimal API</strong></h1>
  <p align="center">
	  Estudo do conceito de Minimal API utilizando o framework Fastify 
  </p>

</div>

<br />

# 🚀 Tecnologias

Este código-fonte foi desenvolvido com os seguintes itens

### 📦 Dependências

### Dependências de Produção

-   [`@fastify/cors`](https://www.npmjs.com/package/@fastify/cors) : Middleware para habilitar CORS (Cross-Origin Resource Sharing) em aplicações Fastify.
-   [`fastify`](https://www.npmjs.com/package/fastify): Framework web rápido e de baixo overhead para Node.js, otimizado para performance.

### Dependências de Desenvolvimento

-   [`@types/node`](https://www.npmjs.com/package/@types/node): Tipos TypeScript para Node.js, permitindo o uso de tipagem estática e autocompletar.

-   [`tsup`](https://www.npmjs.com/package/tsup): Empacotador TypeScript que gera bundles otimizados para produção.

-   [`tsx`](https://www.npmjs.com/package/tsx): Ferramenta para execução de arquivos TypeScript diretamente, sem necessidade de compilação prévia.

-   [`typescript`](https://www.npmjs.com/package/typescript): Superset de JavaScript que adiciona tipagem estática opcional, ideal para desenvolvimento de grandes aplicações.

# 👨‍💻 Executando o Projeto

Primeiro, faça o download das dependências:

```sh
npm install
```

**Iniciando o Servidor:**
Agora inicie o servidor de desenvolvimento:

```sh
npm run start:dev
```

Para monitoramento automático de alterações durante o desenvolvimento, use:

```sh
npm run start:watch
```

### ⚡ Scripts

-   **Compilar o projeto:**
    `sh
npm run dist
`
    Este comando compila os arquivos TypeScript na pasta `src` para JavaScript utilizando o `tsup`.
    <br>

-   **Iniciar o servidor em ambiente de desenvolvimento:**

    ```sh
    npm run start:dev
    ```

    Este comando inicia o servidor utilizando o `tsx` e carrega as variáveis de ambiente do arquivo `.env`.
    <br>

-   **Iniciar o servidor em ambiente de desenvolvimento com monitoramento de alterações:**

    ```sh
    npm run start:watch
    ```

    Este comando inicia o servidor em modo watch, reiniciando automaticamente ao detectar alterações nos arquivos, utilizando o `tsx` e carregando as variáveis de ambiente do arquivo `.env`.
    <br>

-   **Compilar e iniciar o servidor a partir dos arquivos compilados:**
    ```sh
    npm run start:dist
    ```
    Este comando compila os arquivos TypeScript e em seguida inicia o servidor a partir dos arquivos compilados na pasta `dist`.
