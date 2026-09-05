# Angular Essentials

> Aplicação de estudo em Angular 11 que lista livros por situação de leitura, cobrindo componentes, data binding, eventos e injeção de dependência.

![status](https://img.shields.io/badge/status-concluído-success) ![angular](https://img.shields.io/badge/Angular-11-red) ![ts](https://img.shields.io/badge/TypeScript-4-blue)

## Sobre
Exercícios de um curso de fundamentos de Angular (fevereiro de 2021). Cada commit corresponde a uma aula: criação do primeiro app, passagem de dados por *event binding*, injeção de dependência e injeção de serviço em serviço. O app mostra abas com livros lidos, em leitura e não lidos, alimentados por `LivrosService`, que registra ações via `LogService`.

## Estrutura de pastas
```text
angular-essential/src/app/
├── app.component.*        raiz
├── tabs/                  abas de situação
├── list/                  lista de livros da aba
├── item/                  card de livro com ação de mudar situação
├── livros-service.ts      dados e regras de filtragem
└── log.service.ts         serviço injetado em LivrosService
```

## Como executar
```bash
cd angular-essential && npm install && npm start   # http://localhost:4200
```

## Status
Concluído. Material de estudo; não recebe manutenção.

## Autor
Ronildo Silva · ronildo.comp@gmail.com
