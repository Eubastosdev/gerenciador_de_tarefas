# Gerenciador de Tarefas — React

Aplicação web de gerenciamento de tarefas desenvolvida com **React, JavaScript e Tailwind CSS**, com o objetivo de praticar conceitos fundamentais do desenvolvimento Front-End.

O projeto foi desenvolvido como parte dos meus estudos em React, acompanhando as aulas do **Felipe Rocha**, com foco na construção de componentes reutilizáveis, gerenciamento de estados, manipulação de eventos e persistência de dados.

## Funcionalidades

- Adicionar tarefas com título e descrição.
- Marcar e desmarcar tarefas como concluídas.
- Excluir tarefas.
- Visualizar os detalhes de cada tarefa.
- Navegar entre páginas utilizando React Router.
- Armazenar tarefas no `localStorage`.
- Preservar os dados após atualizar a página.
- Interface estilizada com Tailwind CSS.

## Tecnologias utilizadas

| Tecnologia       | Finalidade                        |
| ---------------- | --------------------------------- |
| React            | Construção da interface           |
| JavaScript       | Lógica da aplicação               |
| Vite             | Ambiente de desenvolvimento       |
| Tailwind CSS     | Estilização                       |
| React Router DOM | Navegação entre páginas           |
| Lucide React     | Biblioteca de ícones              |
| UUID             | Geração de identificadores únicos |
| LocalStorage     | Persistência local das tarefas    |

## Estrutura do projeto

```text
curso-de-react/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── AddTask.jsx
│   │   ├── Button.jsx
│   │   ├── Input.jsx
│   │   ├── Tasks.jsx
│   │   └── Title.jsx
│   ├── pages/
│   │   └── TaskPage.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── vite.config.js
└── README.md
```

## Como executar o projeto

**Pré-requisitos:** Node.js e npm instalados.

### 1. Clone o repositório

```bash
git clone https://github.com/Eubastosdev/gerenciador_de_tarefas.git
```

### 2. Acesse a pasta

```bash
cd curso-de-react
```

### 3. Instale as dependências

```bash
npm install
```

### 4. Inicie o servidor de desenvolvimento

```bash
npm run dev
```

Abra o endereço exibido no terminal, normalmente:

```text
http://localhost:5173/
```

## Conceitos praticados

Durante o desenvolvimento, foram aplicados os seguintes conceitos:

- Componentização e reutilização de componentes.
- Passagem de propriedades (`props`).
- Gerenciamento de estado com `useState`.
- Efeitos colaterais com `useEffect`.
- Renderização de listas com `map()`.
- Manipulação de arrays com `filter()`.
- Renderização condicional.
- Eventos `onClick` e `onChange`.
- Desestruturação de objetos.
- Spread operator (`...`).
- Navegação com React Router.
- Armazenamento de dados com `localStorage`.

## Armazenamento de dados

O projeto utiliza a API `localStorage` do navegador para armazenar as tarefas localmente.

As informações são convertidas para JSON antes do armazenamento e recuperadas quando a aplicação é iniciada.

Não é necessário configurar um banco de dados ou uma API externa.

## Objetivo do projeto

Este projeto foi desenvolvido com finalidade educacional, buscando consolidar conhecimentos de React e JavaScript por meio de uma aplicação prática.

O desenvolvimento contribui para o aprendizado de organização de componentes, gerenciamento de estados, navegação e persistência de informações.

## Créditos e agradecimentos

**Felipe Rocha — Professor e criador do conteúdo educacional**

Este projeto foi desenvolvido acompanhando uma aula/tutorial ministrado por **Felipe Rocha**, que apresentou a implementação do gerenciador de tarefas e os conceitos utilizados durante o desenvolvimento.

Os créditos pela proposta didática, pela estrutura original e pelos ensinamentos apresentados pertencem ao autor do conteúdo.

Agradeço ao Felipe Rocha por compartilhar seus conhecimentos e contribuir para a formação de novos desenvolvedores.

## Autor

**Luiz Bastos**

Estudante de Análise e Desenvolvimento de Sistemas, com foco em desenvolvimento Full Stack.

GitHub: [Eubastosdev](https://github.com/Eubastosdev)

---

**Nota:** Projeto desenvolvido para fins de estudo e aprendizado, baseado no conteúdo educacional de Felipe Rocha.s
