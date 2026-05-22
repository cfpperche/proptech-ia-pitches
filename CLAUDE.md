# CLAUDE.md — PropTech IA Pitches

Repositório que hospeda pitches **IA-first** para o setor de gestão de propriedades no Brasil, preparados para o programa **Startup Academy da Group Software**.

## Visão geral

A Group Software (CEO: Rodrigo Monteiro) abriu, em maio de 2026, uma rodada do Startup Academy — investimento de até R$ 1 milhão (até R$ 200 mil sem contrapartida de equity) para founders construindo soluções IA-first em gestão de propriedades. Este repo reúne pitches candidatos a esse programa.

Cada pitch parte de uma **dor real e evidenciada** (Reclame Aqui, avaliações de apps, fontes setoriais) e propõe uma solução que **pluga no ecossistema da Group em vez de competir com o ERP dela**.

## Stack

Nenhuma — repositório só de documentos. Markdown puro, sem build, sem dependências.

## Estrutura

```
pitches/              # pitches de startup p/ o Startup Academy (01–08); founder → Group
expansao-portfolio/   # propostas p/ a Group construir (09–11); análise competitiva
docs/                 # contexto de mercado, boas práticas de pitch, análise competitiva
README.md             # índice navegável de tudo
```

Dois tipos de pitch coexistem no repo:

- **`pitches/`** — um founder externo pitcha; a Group investe. Parte de dor de mercado. Segue `pitches/_template.md`.
- **`expansao-portfolio/`** — a própria Group constrói; expansão de portfólio. Parte de espaço em branco competitivo. Segue `expansao-portfolio/_template.md`.

## Convenções

- **Idioma:** português do Brasil. O público-alvo é o Rodrigo (CEO brasileiro); pitch em inglês seria funcionalmente errado.
- **Formato:** todo pitch é um one-pager e segue `pitches/_template.md`. One-pagers concisos têm ~2,5× mais taxa de resposta que decks longos — concisão é requisito, não estilo.
- **Lidere com o problema de negócio**, não com a tecnologia. Quantifique a dor. Cite a fonte de cada número.
- **Não reconstruir o ERP da Group.** Toda ideia pluga por cima ou pelas bordas (morador, síndico, migração, auditoria). Ver `docs/contexto-group-software.md` § Filtros estratégicos.
- Numeração de arquivo é estável e global: `NN-slug.md`. Pitch-herói = 00, Tier 1 = 01–05, Tier 2 = 06–08, expansão de portfólio = 09–11.
- `pitches/00-administradora-ia-nativa.md` é o **pitch-herói** — a tese-mãe IA-first. É mais longo que os one-pagers (~2–2,5 páginas) e os pitches 01–08 dobram como módulos da escada de autonomia dele. Ao editar 01–08, manter a coerência com a escada do 00.

## Gotchas

- Os números de inadimplência, notas de Reclame Aqui e citações foram coletados em maio/2026 — re-verificar antes de usar publicamente, pois envelhecem.
- A seção "Por que este time" de cada pitch é um rascunho a personalizar antes de apresentar.
