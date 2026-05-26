# Regras para desenvolvimento do PromoCar Growth Panel

Este projeto deve permanecer simples, visual e operacional. O objetivo e ser um painel de gestao do funil, nao uma landing page.

## Direcao do produto

- O painel deve ajudar a operar o grupo de promocoes automotivas no dia a dia.
- A estrutura principal deve ser faseada: Base, Organico, Pre-pago, Teste pago, Otimizacao e Escala leve.
- O mapa mental do funil e uma parte central da experiencia e deve mostrar claramente a operacao completa.
- Trafego pago so pode aparecer como alavanca de escala, nunca como estrategia principal.

## Regras visuais

- Estilo premium, minimalista, escuro, com inspiracao Apple/fintech.
- Manter hierarquia limpa, bastante respiro visual e poucos elementos concorrendo.
- Evitar tela poluida com muitos cards pequenos sem relacao clara.
- O mapa mental precisa ser mais visual que textual.
- Em mobile, tudo deve empilhar sem corte horizontal.

## Regras tecnicas

- `funil.html` deve continuar funcionando como arquivo unico, com CSS e JavaScript internos.
- Nao adicionar framework sem necessidade real.
- Persistencia local deve usar `localStorage`.
- Nao quebrar dados salvos sem criar migracao simples ou trocar a chave de armazenamento.
- Toda mudanca visual deve ser validada no navegador em desktop e mobile.

## Regras de negocio

- Trafego pago bloqueado antes de 07/07/2026.
- Orcamento inicial de teste: R$10 a R$15 por dia.
- CPE saudavel: ate R$1,50.
- CPE em atencao: acima de R$1,50.
- CPE alto: acima de R$2,00.
- Escala somente com CPE saudavel, retencao acima de 75% e rotina sendo preenchida.
