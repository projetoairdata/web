
🌐 Projeto AirData — Documentação Oficial
=========================================

Este repositório contém a **documentação do Projeto AirData**, estruturada com o gerador estático MkDocs e publicada automaticamente via **GitHub Pages**.

📌 Objetivo
-----------
O objetivo deste site é **centralizar a descrição do projeto e registrar a participação dos pesquisadores** envolvidos na iniciativa. Cada pesquisador possui uma página individual em `.md` onde pode registrar contribuições, estudos, dados e observações relevantes.

🧑‍🔬 Contribuições dos Pesquisadores
-------------------------------------
Cada pesquisador possui um arquivo `.md` localizado na pasta `docs/pesquisadores/`.

Exemplo:
- docs/pesquisadores/marcelo_guterres.md
- docs/pesquisadores/flavio_mendes_neto.md
- docs/pesquisadores/joao_szenczuk.md
- etc.

Como atualizar:
1. Edite diretamente o seu arquivo `.md`, usando Markdown padrão.
2. Faça um commit e um push:
   git add docs/pesquisadores/seu_nome.md
   git commit -m "Atualização da minha página"
   git push
3. Um dos responsáveis deve rodar o comando de publicação:
   mkdocs gh-deploy
4. A alteração estará visível em:
   https://projetoairdata.github.io/web/

🚀 Como rodar o site localmente
-------------------------------
1. Clone o repositório:
   git clone git@github.com:projetoairdata/web.git
   cd web

2. Instale o MkDocs com o tema Material:
   pip install mkdocs mkdocs-material

3. Rode o servidor local:
   mkdocs serve

4. Acesse no navegador:
   http://localhost:8000

🌍 Como publicar atualizações online
------------------------------------
Apenas os responsáveis com acesso podem publicar o site com:

   mkdocs gh-deploy

Esse comando gera os arquivos HTML e envia para o GitHub Pages.

📁 Estrutura de diretórios
---------------------------

```text
web/
├── docs/
│   ├── index.md
│   └── pesquisadores/
│       ├── marcelo_guterres.md
│       ├── flavio_mendes_neto.md
│       └── ...
├── mkdocs.yml
└── README.md

✨ Sobre o Projeto AirData
--------------------------
O AirData é uma iniciativa do ITA, ANAC, SAC e DECEA para construir uma base de dados integrada da aviação civil brasileira, apoiada por **inteligência artificial**, para análise, monitoramento e tomada de decisão no setor aéreo.

