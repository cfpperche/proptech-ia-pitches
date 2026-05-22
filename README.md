# PropTech IA — Pitches

Coletânea de pitches **IA-first** para o setor de gestão de propriedades no Brasil, preparados para o programa **Startup Academy da Group Software** — rodada de investimento anunciada em maio/2026 por Rodrigo Monteiro, CEO da Group (até R$ 1 milhão; até R$ 200 mil sem contrapartida de equity).

Cada pitch parte de uma **dor real e evidenciada** — mapeada em sites de reclamação (Reclame Aqui), avaliações de apps e fontes do setor — e propõe uma solução que **pluga no ecossistema da Group em vez de competir com o ERP dela**.

## Índice dos pitches

### Tier 1 — prioritárias

| # | Pitch | Vertical | Dor central |
|---|---|---|---|
| 01 | [Agente de Migração de Dados](pitches/01-agente-migracao-dados.md) | Administradoras | Migrar de sistema leva semanas; lock-in prende o cliente |
| 02 | [Cobrança Conversacional com IA](pitches/02-cobranca-conversacional-ia.md) | Cobrança / inadimplência | Inadimplência recorde (~13%); acordo informal não volta ao ERP |
| 03 | [Prestação de Contas Explicável](pitches/03-prestacao-contas-explicavel.md) | Condomínios / moradores | 21% das reclamações em assembleia são sobre falta de clareza |
| 04 | [Auditoria e Governança Financeira](pitches/04-auditoria-governanca-financeira.md) | Condomínios / conselho | Superfaturamento e fraude sem trilha auditável |
| 05 | [Manutenção Preventiva e Cotação](pitches/05-manutencao-preventiva-fornecedores.md) | Condomínios (todos os tipos) | Manutenção em planilha; cotação manual = superfaturamento |

### Tier 2 — secundárias (verticais nichadas ou com sobreposição parcial ao portfólio Group)

| # | Pitch | Vertical | Dor central |
|---|---|---|---|
| 06 | [Agente de CCT, eSocial e Folha](pitches/06-agente-cct-esocial-folha.md) | RHTec / contadores | CCT recalculada à mão; multas de eSocial por atraso |
| 07 | [Rateio de Energia por Consumo Real](pitches/07-rateio-energia-consumo-real.md) | Energia / utilities | Rateio por fração ideal, não por consumo real |
| 08 | [Transparência de Encargos no Shopping](pitches/08-transparencia-crd-shopping.md) | Shopping centers | Encargo comum maior que o aluguel; CRD opaco |

## Como os pitches foram construídos

1. **Pesquisa de dores** — varredura de Reclame Aqui, avaliações de apps (Google Play / App Store), fontes setoriais (SindicoNet, AABIC, ABRASCE) e do site da Group, em quatro frentes: condomínios residenciais, propriedades comerciais, back-office (RH/contábil/cobrança/atendimento) e clientes da própria Group.
2. **Filtros estratégicos** — três filtros decidiram quais ideias entram. Detalhe em [`docs/contexto-group-software.md`](docs/contexto-group-software.md).
3. **Formato** — one-pager, seguindo as boas práticas em [`docs/boas-praticas-pitch.md`](docs/boas-praticas-pitch.md). Molde em [`pitches/_template.md`](pitches/_template.md).

## A tese, em uma frase

O ERP-núcleo da Group atende ~100 mil condomínios mas carrega problemas de confiabilidade (instabilidade financeira, suporte sobrecarregado, app instável). Os pitches fortes **não competem com o núcleo** — agregam valor nas bordas (morador, síndico, migração, auditoria), onde geram resultado mesmo enquanto o core é estabilizado.

## Estrutura do repositório

```
pitches/        # um one-pager por ideia (01–08) + _template.md
docs/           # contexto de mercado (contexto-group-software.md)
                # e boas práticas de pitch (boas-praticas-pitch.md)
CLAUDE.md       # orientação para o Claude Code trabalhar neste repo
```

## Aviso

Números de inadimplência, notas de Reclame Aqui e citações foram coletados em **maio/2026** e envelhecem — re-verificar antes de uso público. A seção *Por que este time* de cada pitch é rascunho a personalizar.
