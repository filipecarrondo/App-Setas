# Gestor de Setas

Aplicação desktop para gerir torneios de setas, com fase de grupos, classificação automática e eliminatórias.

## Executável Windows

O GitHub Actions gera automaticamente um executável portátil. Abra **Actions → Build Windows EXE**, escolha a execução mais recente e transfira o artefacto `Gestor-de-Setas-Windows`.

## Desenvolvimento

```bash
npm install
npm start
```

## Gerar localmente

```bash
npm install
npm run dist:win
```

O executável será criado na pasta `dist`.
