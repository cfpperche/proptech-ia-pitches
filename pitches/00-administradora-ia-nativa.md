# Pitch 00 — Administradora IA-nativa: o operador agêntico do condomínio

> **Em uma frase:** uma administradora de condomínios construída como software — agentes de IA executam a operação (financeiro, cobrança, comunicação, fornecedores, compliance) e a equipe humana só supervisiona —, fazendo o mesmo time gerir 10× mais condomínios.

**Categoria:** Services-as-software / operação condominial agêntica · **Estágio:** tese + v1 definível · **Tipo:** pitch-herói

---

*Este é o pitch-herói do repositório. Os pitches [01–08](.) não competem com ele — são os **módulos** dele (ver § A escada de autonomia). Leia este primeiro; os outros são a prova de que o roadmap é executável.*

## A tese — a inversão

Hoje o condomínio é operado por **pessoas** (síndico + administradora) e o software é uma ferramenta que essas pessoas usam. Toda a indústria — Group, Superlógica, uCondo — vende a ferramenta.

A revolução é a inversão: **os agentes de IA operam o condomínio; as pessoas supervisionam.** O software deixa de ser a ferramenta e passa a ser o operador. Não se vende mais o ERP — vende-se o *trabalho* que o ERP hoje só ajuda a fazer.

Isso não é "IA na gestão condominial". É a administradora reconstruída como software.

## Por que agora

Em março de 2026 a Sequoia publicou a tese "Services: The New Software": a próxima empresa de US$ 1 trilhão não venderá uma ferramenta — venderá o *serviço*, executado por IA e cobrado por resultado. A lógica: para cada US$ 1 gasto em software, gastam-se US$ 6 em serviços. O prêmio não é o software de gestão condominial — é o **serviço de administração** que ele apenas apoia.

Dois fatos tornam a janela urgente:

- **A IA do setor condominial brasileiro parou na camada de assistência.** A Móra (uCondo), o SíndicoNet PRO, o atendimento com IA da Group — todos são *assistentes*: rascunham texto, classificam conta, respondem dúvida. Nenhum *executa*. O mercado global de proptech (US$ 16,7 bi captados em 2025, +68%) já migrou de "assistência" para "execução" — e o Brasil ainda não tem o operador agêntico.
- **O agente que executa já amadureceu.** O que faltava — agentes que planejam, agem, verificam o próprio resultado e se corrigem — virou realidade técnica em 2025–26.

Quem construir o operador agêntico do condomínio brasileiro agora ocupa uma categoria que ainda não tem dono.

## O mercado — a matemática do colapso

A administradora de condomínios é, estruturalmente, um **negócio de mão de obra**:

- ~1.000 administradoras ativas no Brasil; ~80% têm até 10 funcionários — uma cauda longa de empresas micro e intensivas em pessoas.
- A folha de pagamento é o maior custo fixo da administradora; a margem do negócio é magra — da ordem de 10% sobre o faturamento.
- A produtividade é refém de gente: hoje um gerente de contas cuida de ~20–30 condomínios — e a qualidade despenca quando passa disso (é a origem do "atendimento que só responde dois dias depois").

É exatamente o alvo da tese services-as-software: um negócio onde o custo é trabalho humano repetitivo e a margem é refém da folha. Um operador agêntico quebra o teto de 20–30 condomínios por gerente. O mesmo time passa a gerir 100, 200 — e a margem de 10% expande, ou o preço cai e a administradora toma o mercado. **A receita endereçável não é a licença de software; é a folha inteira da administração condominial brasileira.**

## A escada de autonomia — e onde os 11 pitches entram

"A IA opera o condomínio" não é v1 — é o destino. O caminho é uma escada, e cada degrau só sobe quando o anterior é confiável:

| Degrau | O que a IA faz | O humano | Módulos (deste repo) |
|---|---|---|---|
| **v1 — Copiloto supervisionado** | Executa o trabalho de alto volume e baixo julgamento; humano aprova cada ação | Aprova tudo | Cobrança ([02](02-cobranca-conversacional-ia.md)), prestação de contas ([03](03-prestacao-contas-explicavel.md)), folha/CCT/eSocial ([06](06-agente-cct-esocial-folha.md)), onboarding/migração ([01](01-agente-migracao-dados.md)) |
| **v2 — Autonomia supervisionada** | Age sozinha dentro de limites; humano revisa por exceção | Revisa exceções | Manutenção ([05](05-manutencao-preventiva-fornecedores.md)), energia ([07](07-rateio-energia-consumo-real.md)); a auditoria/governança ([04](04-auditoria-governanca-financeira.md)) deixa de ser módulo e vira o **plano de controle** |
| **v3 — Operador autônomo** | Opera o condomínio; humano cuida de relação e exceção | Supervisiona e escala | Todos, sob o plano de controle |

O degrau que falta a todo concorrente é o **plano de controle**: não se supervisiona 100 condomínios sem um sistema que *prove* o que cada agente fez. A camada de verificação e trilha auditável é o que transforma "chatbot que às vezes erra" em "operador em que se confia" — e é ela que destrava cada degrau da escada.

## Empodera a administradora — não a substitui

Ponto estratégico, não cosmético. A administradora é a **cliente pagante** da Group. Um produto que promete "IA substitui a administradora" é o que a Group menos pode bancar — destrói a base de receita dela.

O enquadramento certo: o operador agêntico é um **superpoder para a administradora**. A mesma equipe opera 10× mais condomínios; a administradora pequena (aquelas ~800 com ≤10 pessoas) passa a competir com a Lello; a margem magra vira folga para crescer. A Group vende, ao cliente que já tem, a ferramenta que multiplica a capacidade dele — não a que o aposenta.

## Por que com a Group — e por que este time

**Por que a Group.** O operador agêntico precisa de duas coisas que a Group já tem: o ERP onde as ações de fato acontecem (sem ele, o agente não tem onde executar) e a base de ~100 mil condomínios para treinar e validar os agentes. Construir isso fora da Group é ter de construir o ERP primeiro. Com a Group, começa-se no degrau certo.

**Por que este time.** *Rascunho — personalizar.* O risco do produto não é "fazer um chatbot" — é construir a camada de verificação e governança que torna a autonomia confiável. É o que eu construo: sistemas de governança e verificação para agentes de IA — contrato verificável, trilha de auditoria, supervisão por exceção. Somo a isso conhecer a arquitetura da Group por dentro (fui arquiteto de software dela) e ter operado um negócio B2B real por cinco anos. O herói não precisa de quem faça IA vistosa; precisa de quem faça IA em que se confia.

## Riscos honestos

- **Confiança é tudo, e se ganha devagar.** Errar uma cobrança ou um lançamento contábil em escala é grave. Por isso a escada — e por isso o v1 é supervisionado, não autônomo. Quem promete v3 no primeiro ano está mentindo.
- **Responsabilidade legal.** Quando o agente erra, quem responde? O desenho do v1 mantém o humano no loop de aprovação justamente para que a responsabilidade fique clara enquanto a confiança se constrói.
- **Concorrente capitalizado.** A Superlógica tem capital e escala para tentar o mesmo. A defesa é velocidade e foco no plano de controle — não a corrida de features.

## O ask

Não financiar o v3 — financiar o **v1 verificável**. Concretamente, ao Startup Academy:

- Acesso a 2–3 administradoras-piloto da base Group para rodar o copiloto supervisionado em produção.
- Integração com o ERP Group Condomínios (onde os agentes executam) e leitura da base para treinar e validar.
- Investimento na engenharia do plano de controle — a camada de verificação e trilha auditável.
- **DONE do v1:** uma administradora-piloto operando o dobro de condomínios por gerente de contas, com cada ação de agente registrada e auditável.

## Fontes

- [`../docs/analise-concorrentes.md`](../docs/analise-concorrentes.md) — mapa competitivo (a IA do setor está presa na camada de assistência)
- Sequoia Capital — "Services: The New Software" (Julien Bek, mar/2026); kategos.ai — "Service as Software: The $4.6 Trillion AI Inversion (2026)"
- Econodata — ~1.000 administradoras de condomínio ativas no Brasil; ~815 com até 10 funcionários
- Group Software / TownSq (blogs) — estrutura de custo da administradora: folha como maior custo fixo, margem ~10%
- Relatórios de proptech 2025 — US$ 16,7 bi captados (+68%); capital migrando de "assistência" para "execução"
