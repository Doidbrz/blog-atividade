
# Blog Simples

Este é um projeto simples de blog, desenvolvido com **React** no front-end e **Express** no back-end, utilizando **MongoDB** como banco de dados.

## Pré-requisitos

Verefique se ja possui instalado:

- **Node.js** (versão 16 ou superior)
- **npm** (gerenciador de pacotes do Node.js)
- **MongoDB** (executando localmente ou em uma nuvem)

## 1. Instalação

passo a passa para configurar o ambiente de desenvolvimento local:

### 1.1. Clone o Repositório

```bash
https://github.com/Doidbrz/blog-atividade.git
cd blog-atividade
```

### 1.2. Instale as Dependências do Front-end

No diretório raiz do projeto, execute o seguinte comando para instalar as dependências do front-end:

```bash
cd blog-front
npm install
```

### 1.3. Instale as Dependências do Back-end

Navegue até o diretório do back-end e instale as dependências:

```bash
cd blog-back
npm install
```

## 2. Executando a Aplicação

### 2.1. Front-end (React)

Para iniciar o front-end em modo de desenvolvimento, execute o seguinte comando no diretório raiz:

```bash
npm start
```

O front-end será iniciado automaticamente em [http://localhost:3000](http://localhost:3000).

### 2.2. Back-end (Express)

No diretório do back-end, execute o servidor Express:

```bash
npm run start
```

O back-end estará em execução em [http://localhost:8000](http://localhost:8000).

## 3. Scripts Disponíveis

### Front-end

- `npm start`: Inicia o servidor de desenvolvimento.
- `npm run build`: Cria uma versão otimizada da aplicação para produção.
- `npm test`: Executa os testes da aplicação.

### Back-end

- `npm run start`: Inicia o servidor Express com **nodemon**, que recarrega automaticamente o servidor ao detectar mudanças no código.

## 4. Configuração do Banco de Dados

Certifique-se de que o **MongoDB** está configurado e rodando corretamente. Por padrão, a aplicação tenta se conectar ao MongoDB na porta **27017** localmente. Se estiver utilizando uma instância de MongoDB em nuvem ou uma URL diferente, você pode ajustar a conexão nas variáveis de ambiente.

## 5. Variáveis de Ambiente

No back-end, você pode configurar as seguintes variáveis de ambiente:

- `MONGODB_URI`: URL de conexão com o banco de dados MongoDB.
- `PORT`: Porta na qual o servidor back-end será executado (padrão: 8000).
