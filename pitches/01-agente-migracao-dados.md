# Pitch 01 — Agente de Migração de Dados Condominiais

> **Em uma frase:** um agente de IA que migra a base de uma administradora de qualquer sistema legado (Excel, PDF, ERP concorrente) para um ERP moderno em dias — não semanas —, validando o histórico financeiro automaticamente.

**Vertical:** Administradoras de condomínios · **Tier:** 1 · **Estágio:** ideia / conceito

---

## O problema

- Trocar de sistema de gestão condominial leva **semanas de digitação manual**. A uCondo descreve o medo de "migrar o histórico de centenas de famílias"; a BRCondomínio aponta o onboarding como a etapa "negligenciada pelos fornecedores".
- O custo de troca prende o cliente. A própria Group, na saída, **entrega só planilha Excel e recusa o formato `.bkp`** — avaliação no Google Play (mai/2024, marcada útil por 84 pessoas): *"Preciso dos arquivos em formato 'bkp' e os mesmos não fornecem... O descaso com o cliente é a marca desta empresa."*
- Resultado: administradoras insatisfeitas **não trocam** — não por falta de alternativa, mas pela dor da migração. O mercado fica congelado.

## A solução

Um agente de IA que lê bases legadas heterogêneas — exportações Excel, PDFs de balancete, `.bkp` de Superlógica/uCondo, ERPs antigos —, **interpreta** os dados (sem exigir mapa de-para rígido), reconcilia o histórico financeiro (saldos, inadimplência, acordos) e gera um relatório de migração para aprovação humana antes da virada de chave.

**Por que IA-first:** o trabalho é interpretar dados não-estruturados e inconsistentes entre dezenas de formatos e convenções. ETL roteirizado quebra a cada layout novo; um agente LLM generaliza. É o caso em que a IA não é enfeite — é o motor.

## Por que agora

Insatisfação documentada e crescente com os incumbentes (notas baixas de app, reclamações de instabilidade financeira) abre uma janela de churn. Quem remover o atrito de migração destrava esse movimento — e isso vale para todo fornecedor que queira crescer puxando cliente da concorrência.

## Mercado

Estimativa Brasil: ~70–100 mil condomínios formais de médio/grande porte sob administradora profissional; milhares de administradoras. SOM inicial: as administradoras que querem trocar de sistema mas estão presas — um **fluxo recorrente**, não um estoque único, porque migração acontece a cada renovação de contrato insatisfatória.

## Modelo de negócio

Cobrança por projeto de migração (por condomínio ou por base migrada) + licença para o ERP de destino que adota o agente como ferramenta de onboarding. Duas pontas pagantes: a administradora que migra e o fornecedor que quer reduzir seu custo de aquisição.

## Diferencial / moat

Conhecimento dos modelos de dados reais dos principais sistemas do mercado — incluindo o do Condomínio21 / Group Condomínios. Cada migração feita treina o agente em mais um formato; a biblioteca de layouts vira o moat.

## Encaixe no ecossistema Group

Ataca diretamente o gargalo comercial nº1 da Group: o custo e o atrito de implantação. Com migração barata, fica fácil "puxar" cliente de Superlógica/uCondo para o Group Condomínios. É infraestrutura que a Group usa internamente **e** pode revender — não compete com o ERP, alimenta ele.

## Por que este time

*Rascunho — personalizar.* Arquiteto que conhece o modelo de dados do Condomínio21 / Group Condomínios por dentro, com experiência em construir agentes de IA. O conhecimento insider da arquitetura de destino é o que ninguém de fora replica rápido.

## O ask

Acesso a 2–3 administradoras-piloto da base Group para a primeira leva de migrações; documentação do modelo de dados do Group Condomínios; investimento para a engenharia do agente. Parceria de go-to-market: o agente como ferramenta oficial de onboarding da Group.

## Fontes

- Reclame Aqui — Group Software Ltda (lock-in contratual, exportação só em Excel); avaliação Google Play, 27/05/2024
- uCondo Blog — "A migração e implantação de um sistema para gestão condominial"
- BRCondomínio — "Implementação de um sistema condominial: muito além de um manual de boas-vindas"
