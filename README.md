# NOVA STUDIO — Experimento de e-commerce

Criei a NOVA STUDIO para trabalhar a experiência de uma loja virtual: navegação, apresentação dos produtos e organização das informações em uma interface com várias seções.

Além do visual, quis ter operações reais de cadastro e consulta para não ficar apenas em uma landing page.

## O que tem no projeto

- Cadastro, edição, exclusão, pesquisa e filtros de registros.
- Exportação em CSV e API REST feita com Node.js.
- Armazenamento demonstrativo em `data/records.json`.
- Layout responsivo, tema escuro persistido no navegador e animações ligadas à rolagem.
- Navegação por teclado, foco visível, link para pular conteúdo e suporte a `prefers-reduced-motion`.

## Como executar

```bash
npm test
npm start
```

Acesse `http://localhost:3000`. Para alterar a porta no PowerShell, use `$env:PORT=3001; npm start`.

## O que é simulado

O checkout não processa pagamentos reais. O projeto não tem autenticação nem banco de produção, e os dados do painel são demonstrativos. As imagens externas precisam de conexão com a internet.

Créditos das fotografias em [CREDITOS-IMAGENS.md](CREDITOS-IMAGENS.md).
