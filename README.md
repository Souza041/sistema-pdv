# 🧾 Sistema PDV (Ponto de Venda)

Sistema PDV (Ponto de Venda) desenvolvido com fins didáticos. A aplicação permite listar produtos, adicionar ao carrinho e registrar vendas em um banco de dados local. O projeto utiliza Node.js no back-end, SQLite como banco de dados e HTML/CSS/JavaScript puro no front-end.

---

## 🧱 Tecnologias Utilizadas

- 🔧 **Back-end**: Node.js + Express
- 💾 **Banco de dados**: SQLite3
- 🎨 **Front-end**: HTML5, CSS3, JavaScript Vanilla

---

## 📁 Estrutura de Pastas

pdv-system/ ├── backend/ │ ├── controllers/ # Lógica da API │ ├── database/ # Conexão e seed do banco │ ├── routes/ # Rotas da aplicação │ ├── app.js # Configuração do Express │ └── server.js # Inicializa o servidor │ ├── frontend/ │ ├── index.html # Página principal │ ├── style.css # Estilos │ └── script.js # Funções do carrinho │ ├── package.json └── README.md

---

## 🚀 Como Rodar Localmente

### 1. Clone o projeto

```bash
git clone https://github.com/seu-usuario/pdv-system.git
cd pdv-system
2. Instale as dependências
bash
npm install

3. Crie o banco de dados
bash
node backend/database/seed.js

4. Inicie o servidor
bash

node backend/server.js
O servidor estará disponível em: http://localhost:3000

5. Acesse o Front-end
Opção 1 — Manual
Abra o arquivo frontend/index.html no navegador.

Opção 2 — Via Express
Caso esteja servindo via Express, acesse http://localhost:3000

📡 Endpoints da API
GET /produtos — Lista todos os produtos

POST /venda — Registra uma nova venda

💡 Melhorias Futuras
Autenticação de operadores

Relatórios de vendas

Conexão com banco de dados online (PostgreSQL/MySQL)

Impressão de recibos

👨‍💻 Autor
Desenvolvido com fins de estudo por [Dhionatas Souza].

📄 Licença
Este projeto está sob a licença MIT — fique à vontade para usar, estudar e adaptar!
