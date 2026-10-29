# Projeto Clima

App de clima que consulta condições meteorológicas por cidade usando a API Open-Meteo. Roda só no navegador, sem backend nem persistência.

## Stack e comandos

- **Vite + TypeScript**, sem framework.
- Testes em `tests/*.test.mjs` com `node --test` (DOM simulado via jsdom): `npm test`.
- Checagem de tipos e build: `npm run build` (`tsc && vite build`).
- Deploy no GitHub Pages via `.github/workflows/deploy.yml` a cada push na `main`.

## Convenções

- Código, comentários, documentação e mensagens de commit em português do Brasil.
- Documentação do projeto fica em `.docs/`; PRDs de novas funcionalidades vão em `.docs/prd/`.
