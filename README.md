# 🏠 Imobigest - CRM para Imobiliárias

[![Laravel](https://img.shields.io/badge/Laravel-10.x-red)](https://laravel.com)
[![Vue.js](https://img.shields.io/badge/Vue.js-3.x-green)](https://vuejs.org)
[![Inertia.js](https://img.shields.io/badge/Inertia.js-Laravel%20Adapter-purple)](https://inertiajs.com)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

O **Imobigest** é um CRM desenvolvido para **imobiliárias**, com objetivo de gerenciar imóveis, contratos e inquilinos de forma simples e organizada.  
Construído com **Laravel**, **Inertia.js** e **Vue.js** para oferecer alta performance e experiência fluida.

---

## 📑 Índice
- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias](#-tecnologias)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação](#-instalação)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Como Usar](#-como-usar)
- [Roadmap](#-roadmap)
- [Contribuição](#-contribuição)
- [Licença](#-licença)
- [Autor](#-autor)

---

## 📌 Sobre o Projeto
O **Imobigest** é uma plataforma para gestão completa de processos de imobiliárias.  
Permite centralizar informações de imóveis, contratos e clientes, além de disponibilizar relatórios financeiros para facilitar a tomada de decisão.

---

## ✅ Funcionalidades
- Cadastro de **imóveis**
- Cadastro de **inquilinos**
- Cadastro de **imobiliárias**
- Criação e gerenciamento de **contratos**
- Geração de **relatórios financeiros**
- Painel administrativo com **filtros e paginação dinâmica**
- Interface **reativa e responsiva**

---

## 🛠 Tecnologias
- **Backend:** Laravel 10
- **Frontend:** Vue.js 3 + Inertia.js
- **Banco de Dados:** MySQL
- **Estilização:** Tailwind CSS
- **Build Tool:** Vite

---

## ✅ Pré-requisitos
Antes de começar, você precisa ter instalado:
- [PHP 8.1+](https://www.php.net/)
- [Composer](https://getcomposer.org/)
- [Node.js 18+ e NPM](https://nodejs.org/)
- [MySQL](https://www.mysql.com/)

---

## ⚙️ Instalação
```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/imobigest.git

# Acessar o diretório do projeto
cd imobigest

# Instalar dependências do Laravel
composer install

# Instalar dependências do Frontend
npm install

# Criar arquivo .env
cp .env.example .env

# Gerar chave da aplicação
php artisan key:generate

# Rodar migrations
php artisan migrate --seed

# Rodar servidor backend
php artisan serve

# Rodar servidor frontend
npm run dev
```

---

📂 Estrutura do Projeto
```bash
markdown
Copiar
Editar
imobigest/
├── app/
│   ├── Http/
│   ├── Models/
│   └── Services/
├── resources/
│   ├── js/
│   │   ├── Pages/
│   │   ├── Components/
│   └── views/
├── routes/
│   └── web.php
└── database/
    ├── migrations/
    └── seeders/
```

---

▶️ Como Usar
Acesse http://localhost:8000 no navegador.

Crie sua primeira imobiliária, depois cadastre imóveis e inquilinos.

Gere contratos e visualize relatórios financeiros no painel.

(Adicione prints de tela ou GIFs aqui para demonstrar a aplicação.)

---

📌 Roadmap
 Implementar autenticação com roles (Admin, Corretor)

 Relatórios gráficos interativos

 Integração com gateway de pagamento

 API pública para integrações externas

---

🤝 Contribuição
Faça um fork do projeto

Crie uma branch para sua feature:
git checkout -b minha-feature

Faça o commit das alterações:
git commit -m 'Adiciona minha feature'

Envie para a branch principal:
git push origin minha-feature

Abra um Pull Request

---

📜 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

---

👤 Autor
Desenvolvido por Seu Nome.
📧 Contato: seuemail@exemplo.com
💼 LinkedIn: linkedin.com/in/seuusuario

yaml
Copiar
Editar

---

Esse arquivo está **pronto para ser salvo como README.md**.  
Quer que eu **adicione uma seção com comandos Docker para rodar a aplicação**?  
Ou prefere que eu também **inclua imagens (placeholders) mostrando telas, com Markdown padrão**?
