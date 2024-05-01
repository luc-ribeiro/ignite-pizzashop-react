<h1 align="center">
🍕 Ignite Pizzashop 
</h1>

![image](https://github.com/luc-ribeiro/pizzashop-web-react/assets/69688077/527c1ae8-1e94-45d6-b0c9-d9763c3d2fad)

![image](https://github.com/luc-ribeiro/pizzashop-web-react/assets/69688077/62b2e21d-4977-4683-86ca-6c55f9119fc1)

![image](https://github.com/luc-ribeiro/pizzashop-web-react/assets/69688077/0a0a8d89-7e82-43f7-b498-bececf5afdfa)

## 📄 Projeto
Projeto de um dashboard de administrador para gerenciamento de vendas, acompanhemento de pedidos, atualização de status e controle de vendas com gráficos de uma pizzaria.
O foco de sua criação consiste em aplicar conceitos de comunicação com APIs via requisições HTTP, testes de aplicações front-end (Testes E2E, unitários e mocks) e a utilização de componentes do Shadcn/ui.

## 💻 Tecnologias

- **ReactJS**
- **TypeScript**
- **React Router DOM**
- **TailwindCSS**
- **Shadcn/ui**
- **TanStack Query**
- **React Hook Form**
- **Zod**
- **Recharts**
- **Axios**
- **date-fns**
- **React Helmet**
- **Sonner**
- **Skeleton**
- **Vitest**
- **Playwright**
- **Happy DOM**
- **Mocking Service Worker**

## 🚀 Executando o projeto

```bash
1. Clone este repositório em sua máquina
$ git clone https://github.com/luc-ribeiro/ignite-pizzashop-react.git

2. Instale as dependencias
$ npm i

3. Rode o projeto através do comando:
$ npm run dev

4. Para utilizar a API do projeto, é necessário clonar o repositório abaixo.
$ git clone https://github.com/rocketseat-education/pizzashop-api.git

5. Altere no arquivo "src/db/seed.ts" a linha 58 para o seu e-mail.

6. Instale o Bun.
$ https://bun.sh/

6. Após clonar o repositório da API e instalar o Bun, baixe e instale o Docker.
$ https://www.docker.com/get-started/

7. Após a instalação e execução do Docker, execute os seguintes comandos:
$ docker compose up -d (executa a imagem do docker na maquina)
$ bun i (instalar as dependencias)
$ bun migrate (gerar as migrations do banco de dados)
$ bun seed (popular o banco de dados com algumas informações)
$ bun dev (executa a aplicação)

- A aplicação estará disponível no endereço `http://localhost:5173`
