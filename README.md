# StardewValley

Stardew Valley Wiki
Este é um projeto de uma Wiki interativa de Stardew Valley, desenvolvida em React. O objetivo é oferecer informações detalhadas sobre personagens, itens, tarefas e easter eggs do jogo Stardew Valley. Esse projeto é uma excelente adição ao portfólio, demonstrando habilidades em desenvolvimento front-end com React, gerenciamento de dados locais e design de interface.

📋 Índice
#-Funcionalidades
#-Pré-requisitos
#-Instalação e Configuração
#-Estrutura do Projeto
#-Uso
#-Estrutura de Dados
#-Contribuições
#-Licença
✨ Funcionalidades
Listagem de Personagens: Exibe uma lista de personagens com suas preferências de presentes, localização e aniversário.
Itens de Stardew Valley: Mostra informações sobre itens do jogo, como cultivos, peixes e minerais.
Tarefas e Missões: Lista de tarefas e requisitos para completá-las.
Easter Eggs: Detalhes sobre easter eggs e como encontrá-los no jogo.
Busca e Filtros: Permite buscar ou filtrar informações específicas (planejado como aprimoramento futuro).
🛠 Pré-requisitos
Certifique-se de ter instalado:

Node.js (versão 14 ou superior)
npm ou yarn
🚀 Instalação e Configuração
Siga as etapas abaixo para configurar o projeto localmente:

Clone o repositório:

bash
Copiar código
git clone https://github.com/seu-usuario/stardew-valley-wiki.git
cd stardew-valley-wiki
Instale as dependências:

bash
Copiar código
npm install
# ou, se preferir o yarn
yarn install
Inicie o servidor de desenvolvimento:

bash
Copiar código
npm start
# ou
yarn start
Abra o navegador e acesse http://localhost:3000.

📂 Estrutura do Projeto
csharp
Copiar código
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
💻 Uso
Home Page: Página de boas-vindas com links para cada categoria.
Página de Personagens: Exibe todos os personagens, incluindo suas preferências de presentes, localização e aniversário.
Página de Itens: Lista de todos os itens, organizados por tipo e estação.
Página de Tarefas: Tarefas e missões, com requisitos e recompensas.
Página de Easter Eggs: Mostra os easter eggs e como eles podem ser encontrados no jogo.
Para navegar entre as páginas, clique nos links do menu principal.

📊 Estrutura de Dados
Os dados estão em um arquivo JSON (stardewData.json) localizado na pasta src/data. A estrutura JSON inclui quatro categorias principais: characters, items, tasks, e easter_eggs.

Exemplo de estrutura para cada seção:

Personagens
json
Copiar código
{
  "id": 1,
  "name": "Abigail",
  "image": "abigail.png",
  "birthday": "Fall 13",
  "location": "Pierre's General Store",
  "description": "Abigail is the daughter of Pierre and Caroline...",
  "likes": ["Amethyst", "Pumpkin", "Spicy Eel"],
  "dislikes": ["Clay", "Holly"],
  "gifts": {
    "loved": ["Amethyst", "Pumpkin", "Spicy Eel"],
    "liked": ["Quartz", "Chocolate Cake"],
    "disliked": ["Mayonnaise"],
    "hated": ["Clay"]
  }
}
Itens
json
Copiar código
{
  "id": 1,
  "name": "Parsnip",
  "type": "Vegetable",
  "seasons": ["Spring"],
  "value": 35,
  "growth_time": 4,
  "description": "A tasty root vegetable with a hint of sweetness."
}
Tarefas
json
Copiar código
{
  "id": 1,
  "name": "Build a Coop",
  "description": "Build a coop to raise chickens on your farm.",
  "requirements": ["300 Wood", "100 Stone"],
  "reward": "Allows raising chickens",
  "difficulty": "Easy"
}
Easter Eggs
json
Copiar código
{
  "id": 1,
  "name": "Alien Capsule",
  "trigger": "Randomly spawns on farm after Year 2",
  "description": "An alien capsule may randomly appear on your farm..."
}
📢 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir Issues para sugestões ou bugs encontrados, e para enviar Pull Requests para melhorias no projeto.

Para contribuir:

Fork o projeto.
Crie uma branch para sua feature (git checkout -b minha-feature).
Commite suas mudanças (git commit -m 'Adiciona minha feature').
Faça o push para a branch (git push origin minha-feature).
Abra um Pull Request.
📜 Licença
Este projeto é licenciado sob a MIT License.
