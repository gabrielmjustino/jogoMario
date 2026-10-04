# Jogo Mario

## Descrição

Projeto de um jogo inspirado no universo do Mario, desenvolvido como atividade acadêmica para colocar em prática conceitos de desenvolvimento Front-End, Git e GitHub.

O jogo possui uma interface interativa desenvolvida com HTML, CSS e JavaScript, permitindo ao jogador controlar o personagem e interagir com os elementos presentes no cenário.

## Objetivo do Projeto

O objetivo do projeto é desenvolver um jogo Front-End utilizando tecnologias web e, ao mesmo tempo, aplicar conceitos de controle de versão e trabalho colaborativo utilizando Git e GitHub.

Durante o desenvolvimento, o projeto utiliza branches, commits e merge para organizar e controlar a evolução do código.

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- Vite
- Git
- GitHub

## Estrutura do Projeto

```text
jogoMario/
│
├── backend/
│   └── .gitkeep
│
├── docs/
│   ├── branding/
│   │   └── .gitkeep
│   ├── mer/
│   │   └── .gitkeep
│   ├── mockups/
│   │   └── .gitkeep
│   ├── models/
│   │   └── uml/
│   │       └── .gitkeep
│   └── requirements/
│       └── .gitkeep
│
├── frontend/
│   ├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── script.js
│   ├── index.html
│   ├── package.json
│   └── package-lock.json
│
├── .gitignore
├── LICENSE
└── README.md
```

## Instalação

Para executar o projeto, é necessário possuir o [Node.js](https://nodejs.org/) instalado.

Primeiro, entre no diretório do Front-End:

```bash
cd frontend
```

Depois, instale as dependências do projeto:

```bash
npm install
```

## Execução

Após instalar as dependências, execute o projeto com:

```bash
npm run dev
```

O Vite irá iniciar um servidor local para execução do jogo.

Acesse o endereço informado pelo terminal, normalmente:

```
http://localhost:5173/
```

## Git e GitHub

O projeto utiliza duas branches principais:

- **main** — versão principal e integrada do projeto.
- **dev** — branch utilizada para o desenvolvimento.

O desenvolvimento deve ser realizado inicialmente na branch `dev`. Após a conclusão das alterações e realização dos commits necessários, a branch `dev` deverá ser integrada à `main` por meio de merge.

### Commits

Os commits são utilizados para registrar as etapas de desenvolvimento do projeto.

Alguns exemplos:

```
chore: cria estrutura inicial do projeto
docs: adiciona README
chore: configura npm no frontend
feat: cria tela inicial do jogo
feat: implementa interface do jogador
feat: adiciona componentes do jogo
style: ajusta layout da interface
fix: corrige problema na tela inicial
```

## Integrantes

| Nome                   | Matrícula       | Papel         |
|------------------------|-----------------|---------------|
| João Ferreira          | SUA_MATRÍCULA   | Scrum Master  |
| NOME DO INTEGRANTE     | MATRÍCULA       | Desenvolvedor |
| NOME DO INTEGRANTE     | MATRÍCULA       | Desenvolvedor |
| NOME DO INTEGRANTE     | MATRÍCULA       | Documentador  |
| NOME DO INTEGRANTE     | MATRÍCULA       | Testador      |

## Licença

Este projeto está licenciado sob a licença [MIT](LICENSE).