# Projeto GTech Front-end — Loja Drip

## Descrição

Este projeto é uma aplicação front-end desenvolvida com foco em uma loja virtual (e-commerce), denominada **Loja Drip**. A aplicação oferece funcionalidades típicas de um sistema de vendas online, como listagem de produtos, navegação por categorias, carrinho de compras e fluxo de cadastro de usuários.

O projeto foi construído utilizando tecnologias modernas do ecossistema JavaScript, com ênfase em performance, organização de componentes e escalabilidade.

---

## Tecnologias Utilizadas

- **React** — Biblioteca principal para construção da interface
- **Vite** — Ferramenta de build e desenvolvimento rápido
- **React Router DOM** — Gerenciamento de rotas
- **Axios** — Requisições HTTP
- **Tailwind CSS** — Estilização com utilitários
- **ESLint** — Padronização e qualidade de código

---

## Instalação e Setup

### Pré-requisitos

- Node.js (versão 18 ou superior recomendada)
- Gerenciador de pacotes (npm ou yarn)

### Passos para instalação

```bash
# Clone o repositório
git clone <url-do-repositorio>
# Acesse a pasta do projeto
cd projetoGTech-front/PROJETO-FRONT/loja-drip
```
# Instale as dependências
```bash
npm install
```
Execução do Projeto
Ambiente de desenvolvimento
npm run dev

A aplicação estará disponível em:
```bash
http://localhost:5173
```
Build para produção
```bash
npm run build
```
Visualizar build
```bash
npm run preview
```
Estrutura do Projeto:
```
A organização do projeto segue uma arquitetura baseada em componentes e separação de responsabilidades:

src/
│
├── assets/            # Imagens e arquivos estáticos
├── components/        # Componentes reutilizáveis
│   ├── HomePage/
│   ├── AbaProdutos/
│   └── ...
│
├── contexts/          # Context API (ex: carrinho)
├── data/              # Dados mockados (produtos)
├── pages/             # Páginas principais da aplicação
│   ├── homePage.jsx
│   ├── categoriasPage.jsx
│   ├── cadastro.jsx
│   └── ...
│
├── services/          # Integração com APIs (Axios)
├── App.jsx            # Componente raiz
├── main.jsx           # Ponto de entrada da aplicação
└── index.css          # Estilos globais
```
Funcionalidades Principais
Listagem de produtos
Navegação por categorias
Visualização de detalhes de produtos
Carrinho de compras com estado global
Cadastro e fluxo de usuário
Integração com API (estrutura preparada)
Dependências Principais
```
"dependencies": {
  "react": "^19.2.0",
  "react-dom": "^19.2.0",
  "react-router-dom": "^7.13.1",
  "axios": "^1.13.6",
  "react-icons": "^5.6.0"
}
```


Boas Práticas Adotadas:
```
Componentização para reutilização de código
Separação entre lógica, apresentação e dados
Uso de Context API para gerenciamento de estado global (carrinho)
Estrutura modular para facilitar manutenção e escalabilidade
Contribuição
```
Contribuições são bem-vindas. Para colaborar:

Faça um fork do projeto

Crie uma branch para sua feature:

git checkout -b minha-feature

Commit suas alterações:
```bash
git commit -m "feat: minha nova feature"
```
Envie para o repositório:
```bash
git push origin minha-feature
```
Abra um Pull Request
Possíveis Melhorias
Integração completa com backend real
Sistema de autenticação robusto
Persistência do carrinho (localStorage ou API)
Testes automatizados (unitários e integração)
Otimização de performance e SEO
Licença

Este projeto não possui licença definida no momento. Recomenda-se adicionar uma licença (MIT, Apache, etc.) para uso aberto.