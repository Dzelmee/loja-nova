# NOVA STUDIO — Loja demonstrativa

Desenvolvi esta loja demonstrativa para trabalhar a experiência de navegação em um e-commerce, combinando uma interface visual com operações de cadastro e consulta de registros.

## O que implementei

- Aplicação de domínio com cadastro, edição, exclusão, pesquisa, filtro e exportação CSV.
- API REST em Node.js e persistência demonstrativa em `data/records.json`.
- Layout de múltiplas seções, responsivo, imagens remotas sob licença Unsplash, dark mode persistido no navegador, microinterações e animações scroll-driven com fallback.
- Navegação por teclado, foco visível, link para pular conteúdo e respeito a `prefers-reduced-motion`.

## Execução

```bash
npm test
npm start
```

Acesse http://localhost:3000. Para mudar a porta: `PORT=3001 npm start` (Linux/macOS) ou `$env:PORT=3001; npm start` (PowerShell).

## Limitações

Projeto demonstrativo sem autenticação, banco de dados de produção ou autorização por usuário. A loja possui checkout simulado sem pagamentos reais. Fotos externas dependem de internet. Dados e estatísticas do painel são derivados dos registros da aplicação; não representam clientes reais.

## Imagens

Veja `CREDITOS-IMAGENS.md`.
