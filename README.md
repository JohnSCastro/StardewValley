# Stardew Valley Wiki

Este é um projeto de uma Wiki interativa de *Stardew Valley*, desenvolvida em **React**. O objetivo é oferecer informações detalhadas sobre personagens, itens, tarefas e easter eggs do jogo *Stardew Valley*. Esse projeto é para adição ao portfólio, demonstrando minhas habilidades em desenvolvimento front-end com React, gerenciamento de dados locais e design de interface.

## 📋 Índice
- [Funcionalidades](#-funcionalidades)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação e Configuração](#-instalação-e-configuração)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Uso](#-uso)
- [Contribuições](#-contribuições)

---

## ✨ Funcionalidades
- **Listagem de Personagens**: Exibe uma lista de personagens com suas preferências de presentes, localização e aniversário.
- **Itens de Stardew Valley**: Mostra informações sobre itens do jogo, como cultivos, peixes e minerais.
- **Tarefas e Missões**: Lista de tarefas e requisitos para completá-las.
- **Easter Eggs**: Detalhes sobre easter eggs e como encontrá-los no jogo.
- **Busca e Filtros**: Permite buscar ou filtrar informações específicas (planejado como aprimoramento futuro).
  
## 🛠 Pré-requisitos

Certifique-se de ter instalado:
- **Node.js** (versão 14 ou superior)
- **npm** ou **yarn**

## 🚀 Instalação e Configuração

Siga as etapas abaixo para configurar o projeto localmente:

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/stardew-valley-wiki.git
   cd stardew-valley-wiki

  ```bash
    npm install
    # ou, se preferir o yarn
    yarn install
  ```

2. Inicie o servidor de desenvolvimento:

  ```bash
  npm start
  # ou
  yarn start
  ```

3. Abra o navegador e acesse http://localhost:3000.

## 📂 Estrutura do Projeto
```
stardew-valley-wiki/
├── public/                     # Arquivos públicos
│   └── images/                 # Imagens de personagens e itens
├── src/                        
│   ├── components/             # Componentes reutilizáveis
│   ├── data/                   # Dados JSON para personagens, itens, tarefas e easter eggs
│   ├── pages/                  # Páginas principais do projeto (Characters, Items, etc.)
│   ├── services/               # Arquivos de API simulada (dados carregados localmente)
│   ├── App.js                  # Configuração das rotas principais
│   └── index.js                # Arquivo de entrada do React
├── README.md                   # Documentação do projeto
└── package.json                # Configuração do projeto e dependências
```

## 💻 Uso
- Home Page: Página de boas-vindas com links para cada categoria.
- Página de Personagens: Exibe todos os personagens, incluindo suas preferências de presentes, localização e aniversário.
- Página de Itens: Lista de todos os itens, organizados por tipo e estação.
- Página de Tarefas: Tarefas e missões, com requisitos e recompensas.
- Página de Easter Eggs: Mostra os easter eggs e como eles podem ser encontrados no jogo.
- Para navegar entre as páginas, clique nos links do menu principal.

## 📢 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir Issues para sugestões ou bugs encontrados e para enviar Pull Requests para melhorias no projeto.

Para contribuir:

1. Fork o projeto.
2. Crie uma branch para sua feature (git checkout -b minha-feature).
3. Commite suas mudanças (git commit -m 'Adiciona minha feature').
4. Faça o push para a branch (git push origin minha-feature).
5. Abra um Pull Request.

