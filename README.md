# 🚀 React Boilerplate

Boilerplate moderno para projetos React com Vite, TypeScript, Tailwind CSS, MUI, SWC e ferramentas de lint/testes.

## 🚀 Tecnologias e ferramentas

- ![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
- ![Vite](https://img.shields.io/badge/Vite-6-646CFF?logo=vite&logoColor=white) – Build ultra-rápido
- ![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)
- ![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-4-06B6D4?logo=tailwindcss&logoColor=white)
- ![MUI](https://img.shields.io/badge/MUI-5-007FFF?logo=mui&logoColor=white) – Componentes de UI
- ![SWC](https://img.shields.io/badge/SWC-transpile-F5DE19?logo=esbuild&logoColor=black) – Transpilação rápida via `@vitejs/plugin-react-swc`
- ![Vitest](https://img.shields.io/badge/Vitest-3-6E4AFF?logo=vitest&logoColor=white) – Testes unitários
- ![ESLint](https://img.shields.io/badge/ESLint-9-4B32C3?logo=eslint&logoColor=white) + ![Prettier](https://img.shields.io/badge/Prettier-3-F7B93E?logo=prettier&logoColor=black) – Linting e formatação
- ![React Hook Form](https://img.shields.io/badge/React_Hook_Form-7-EC5990?logo=reacthookform&logoColor=white) – Forms com validação usando Yup
- ![Faker.js](https://img.shields.io/badge/faker.js-8-yellowgreen) – Geração de dados fake
- ![Lodash](https://img.shields.io/badge/Lodash-4-3492FF?logo=lodash&logoColor=white)
- ![Moment.js](https://img.shields.io/badge/Moment.js-2-EF5B53?logo=moment&logoColor=white)
- ![UUID](https://img.shields.io/badge/UUID-9-blue)
- ![React Router](https://img.shields.io/badge/React_Router_6-CA4245?logo=reactrouter&logoColor=white)

## 🚧 Scripts disponíveis

| Comando                 | Descrição                            |
| ----------------------- | ------------------------------------ |
| `npm run dev`           | Inicia o servidor de desenvolvimento |
| `npm run build`         | Gera build de produção               |
| `npm run preview`       | Visualiza o build localmente         |
| `npm run test`          | Executa testes com Vitest            |
| `npm run test:watch`    | Roda testes em modo observador       |
| `npm run test:coverage` | Gera relatório de cobertura          |
| `npm run lint`          | Verifica problemas de lint           |
| `npm run lint:fix`      | Corrige automaticamente os problemas |
| `npm run format`        | Formata o código com Prettier        |

## ✅ Requisitos

Node.js 20 ou 22+

## 🧰 Lint e formatação

Lint com ESLint + plugins (React, JSX A11y, Import)
Formatação com Prettier + plugin de ordenação de imports

```bash
npm run lint
npm run format
```

## 🧪 Testes

O projeto utiliza Vitest com suporte ao Testing Library para testes unitários e de componentes.

```bash
npm test
```

## 📦 Instalação

```bash
git clone git@github.com:kawanofer/react19-boilerplate.git
cd react19-boilerplate
npm install
npm start
```
