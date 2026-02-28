# TecBoard

Aplicação React para criação e listagem de eventos de tecnologia, desenvolvida durante os estudos na Alura.

## 💻 Sobre o projeto

O TecBoard permite cadastrar eventos de tecnologia informando nome, capa, data e tema. Os eventos são exibidos agrupados por tema em cards visuais.

## ⚙️ Funcionalidades

- Cadastro de eventos via formulário
- Agrupamento de eventos por tema
- Exibição de cards com capa, data e título do evento
- Temas disponíveis: Front-end, Back-end, DevOps, Inteligência Artificial, Data Science e Cloud

## 🧱 Componentes

| Componente           | Descrição                                  |
| -------------------- | ------------------------------------------ |
| `Banner`             | Imagem de destaque no topo da página       |
| `FormularioDeEvento` | Formulário para criação de novos eventos   |
| `CardEvento`         | Card com informações do evento             |
| `Tema`               | Título de seção agrupando eventos por tema |
| `Botao`              | Botão reutilizável                         |
| `CampoDeEntrada`     | Input estilizado                           |
| `CampoDeFormulario`  | Fieldset para agrupar campos               |
| `Label`              | Label estilizada para os campos            |
| `ListaSuspensa`      | Select estilizado para seleção de tema     |
| `TituloFormulario`   | Título do formulário                       |

## 🚀 Como executar

```bash
# Instalar dependências
npm install

# Rodar em desenvolvimento
npm start

# Gerar build de produção
npm run build
```

## 🛠️ Tecnologias

- [React](https://react.dev/)
- CSS Modules
- [ViaCEP API](https://viacep.com.br/) _(utilizada em exercícios anteriores)_

## 📚 Contexto

Projeto desenvolvido como exercício do curso de React da [Alura](https://www.alura.com.br/), com foco no uso do hook `useState` para gerenciamento de estado.
