# PromoCar Growth Panel

Dashboard em HTML para organizar o funil de crescimento do grupo PromoCar.

## Arquivos principais

- `index.html`: painel principal com visao geral, mapa mental do funil, fases, diario, metricas e conexao GitHub.
- `funil.html`: redirecionamento de compatibilidade para `index.html`.
- `package.json`, `vite.config.js` e `vercel.json`: configuracao minima para deploy na Vercel.
- `AGENTS.md`: regras para evoluir o projeto com consistencia.
- `docs/`: documentacao de produto, funil, roadmap, regras, metricas, QA e backlog.

## Documentacao

Comece pelo [indice da documentacao](docs/00-indice.md).

## Estrategia

- Trabalhar organico, landing page, criativos e rastreamento antes de investir.
- Liberar trafego pago somente a partir de 07/07/2026.
- Comecar com R$10 a R$15 por dia.
- Escalar apenas com CPE saudavel, retencao forte e registros consistentes.

## Funil central

```text
Conteudo -> Captura -> Grupo -> Ofertas -> Retencao -> Escala
```

O mapa mental visual no painel mostra esse fluxo conectado ao grupo PromoCar.

## Estrutura da interface

- `Painel`: visao geral executiva.
- `Funil`: mapa mental visual da operacao.
- `Fases`: plano faseado e checklist.
- `Metricas`: leitura objetiva de decisao.
- `Registros`: area isolada para uso futuro.
- `GitHub`: referencia do repositorio.

## Dados locais

O painel usa `localStorage` do navegador para salvar:

- fase selecionada;
- checklist das fases;
- notas;
- registros diarios.
