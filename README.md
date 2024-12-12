# Desafio Frontend Mission Brasil
Primeiramente, muito obrigado pelo interesse em trabalhar na maior plataforma de serviços recompensados do Brasil!

## Avisos antes de começar
- Crie um repositório no Github sem citar nada relacionado ao Mission Brasil.
- Faça pelo menos 2 commits.
- Envie o link do seu repositório para o e-mail do recrutador responsável.
- Fique a vontade para perguntar qualquer dúvida aos recrutadores.

## Caso você seja aprovado para etapa da entrevista técnica
Na data agendada vamos falar um pouquinho sobre o seu código, como se fosse um code review analisando alguns detalhes, nada muito profundo, apenas para nos conhecermos melhor e você entender um pouco mais sobre fit cultural da empresa.

## Ambiente
- Utilizar Next >= 14
- App Router
- Tailwind
- Next Auth (Para Autenticação, Utilizar Google)
- Utilizar componentes com [shad](https://ui.shadcn.com/)
- Deploy Vercel

## Desafio: Construção de um Dashboard Interativo para Gerenciamento de Projetos

## Objetivo

Criar um dashboard interativo utilizando Next.js, shadcn (Radix UI com TailwindCSS), e TailwindCSS, com foco em responsividade, acessibilidade e boas práticas de desenvolvimento frontend.

## Especificações do Desafio

### Funcionalidades Básicas

- Página Inicial (Home)
  - Um resumo dos projetos ativos e concluídos.
  - Gráficos simples mostrando progresso (por exemplo, usando uma biblioteca de gráficos como recharts ou chart.js).
  - Links para acessar páginas detalhadas.
- Página de Projetos
  - Lista de projetos com:
  - Nome do projeto.
  - Status (ativo, atrasado, concluído).
  - Barra de progresso (usando componentes estilizados do shadcn).
	- Um botão para criar um novo projeto (abre um modal).
    - Modal de Criação de Projetos
      - Campos obrigatórios:
      - Nome do projeto.
      - Data de início e fim.
      - Descrição.
      - Responsável (pode ser um dropdown com opções pré-definidas).
	•	Validação de formulários (ex.: usar react-hook-form com feedback visual).
- Página de Detalhes do Projeto
  - Exibir detalhes do projeto, como:
    - Tarefas associadas (componente de lista).
    - Comentários (usando caixas de texto e um botão para adicionar).
    - Opção para marcar tarefas como concluídas (feedback visual imediato).


## Extra (Desafios Avançados)
- Autenticação: Implementar autenticação simples com next-auth (Google ou GitHub).
- Persistência de Dados: Usar um banco de dados simples, como SQLite ou MongoDB, com Prisma ou outra ferramenta ORM.
- Dark Mode: Adicionar suporte ao modo escuro com Tailwind.

## Avaliação

- Documentação (ex.: README.md com instruções de execução).
- Apresentar soluções que domina
- Tratamento de erros
- Cuidado com itens de segurança
- Arquitetura
- Design e Responsividade
- Desacoplamento e reutilização de componentes (Composition, Providers...)

## Tem um prazo de entrega?

Normalmente em 5 dias, tente focar em qualidade de entrega, caso demore um pouco mais, não tem problema, faça no seu tempo, isso não é o mais importante pra nós.
