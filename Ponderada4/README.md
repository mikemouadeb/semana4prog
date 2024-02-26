# semana4prog

# Relatório do Autoestudo ponderado: Formulários Dinâmicos

## Componentes do Projeto

### Componentes Angular (`*.component.*`)
- **app.component**: O componente que atua como o ponto de entrada para o aplicativo Angular.
  - `app.component.ts`: A lógica do componente.
  - `app.component.html`: HTML do componente.
  - `app.component.css`: CSS do componente.
  - `app.component.spec.ts`: Testes unitários para o componente.

### Módulos (`*.module.ts`)
- **app.module.ts**: Define o módulo raiz que declara todos os componentes e serviços usados na aplicação.

### Roteamento (`app-routing.module.ts`)
- Define as rotas para navegação na aplicação, permitindo a construção de SPAs (Single Page Applications).

### Serviços (`*.service.ts`)
- **question-control.service.ts** e **question.service.ts**: São os serviços para gerenciar a lógica de formação e operação dos formulários dinâmicos.

### Classes Base para Formulários (`*.ts`)
- **question-base.ts**, **question-dropdown.ts**, **question-textbox.ts**: Definem as classes base para diferentes tipos de perguntas, facilitando a criação de formulários dinâmicos.

### Componentes de Formulário Dinâmico
- Diretórios **dynamic-form-question** e **dynamic-form** contêm os componentes para construir e renderizar formulários dinâmicos.

## Conceitos Aprendidos

- **Formulários Dinâmicos**: Aprendi como criar formulários que podem ser dinamicamente alterados ou extendidos com base nas necessidades do usuário ou da lógica de negócios, utilizando classes base e serviços.
- **Injeção de Dependência**: A prática de fornecer componentes (como serviços) que um componente ou serviço requer, melhorando a modularidade e a reutilização de código.
- **Testes Unitários**: A importância de testar componentes e serviços individualmente para garantir que a lógica de negócios funcione conforme esperado.
- **Roteamento Angular**: Como gerenciar a navegação entre diferentes vistas e componentes em uma SPA.

## Resultado

![alt text](<Screen Shot 2024-02-26 at 09.23.01.png>)
