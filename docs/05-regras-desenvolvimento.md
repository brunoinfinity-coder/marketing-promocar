# Regras de desenvolvimento

## Arquitetura

- O produto principal e `index.html`.
- `funil.html` existe apenas como redirecionamento de compatibilidade.
- O painel deve continuar abrindo diretamente no navegador.
- O projeto tambem deve compilar com `vite build` para deploy na Vercel.
- A Vercel deve usar `dist` como diretorio de saida.
- CSS e JavaScript permanecem internos enquanto o projeto for simples.
- Se o painel crescer muito, separar em `src/` deve ser uma decisao planejada.

## Persistencia

- Usar `localStorage`.
- Dados principais:
  - fase selecionada;
  - checklist das fases;
  - notas por fase;
  - registros diarios.
- Mudancas que quebrem dados salvos devem trocar a chave de armazenamento ou fazer migracao.

## Qualidade visual

- Aparencia premium, escura, minimalista e profissional.
- Evitar poluicao visual.
- Cada secao deve ter uma funcao clara.
- O mapa mental do funil deve ficar sempre facil de entender.

## Responsividade

- Validar desktop e mobile.
- Nao permitir scroll horizontal em mobile.
- Textos grandes devem quebrar corretamente.
- Botoes devem continuar tocaveis em tela pequena.

## Validacao antes de commit

- Abrir o HTML no navegador.
- Conferir console do navegador quando possivel.
- Validar que o mapa mental renderiza.
- Validar que `localStorage` salva tarefas e registros.
- Conferir `git status` antes de commitar.
