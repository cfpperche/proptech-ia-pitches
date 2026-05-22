# Pitch 04 — Camada de Auditoria e Governança Financeira

> **Em uma frase:** uma camada de IA sobre o ERP que audita cada despesa do condomínio em tempo real — detecta superfaturamento, nota fiscal ausente e concentração de fornecedor — e mantém uma trilha auditável imutável.

**Vertical:** Condomínios / associações de moradores · **Tier:** 1 · **Estágio:** ideia / conceito

---

## O problema

- Superfaturamento e fraude na contratação de fornecedores são padrão documentado: notas fiscais infladas, empresas de fachada, síndico recebendo comissão (MB7 Auditoria; caso real de ex-síndico condenado a ressarcir o condomínio).
- Despesas misturam ordinário com extraordinário; fornecedor único é contratado sem cotação; há pagamento a pessoa física no lugar de CNPJ.
- Em casos reais, cobranças e transferências foram feitas **sem aprovação prévia do síndico** (reclamação Lello no Reclame Aqui); e dados financeiros **somem do sistema sem log de auditoria** (caso Condomínio21: "Previsão Orçamentária 'some' e a empresa não resolve").
- Decisões judiciais LGPD no setor condominial cresceram 81% entre 2022 e 2023 — a falta de trilha auditável é passivo jurídico.

## A solução

Uma camada de IA que observa os lançamentos do ERP e: classifica cada despesa (ordinária / extraordinária / obra); detecta padrões anômalos (concentração de fornecedor, valor fora da mediana de mercado para o serviço, nota fiscal ausente, pagamento sem contrapartida); exige fluxo de aprovação acima de um limite configurável; e registra tudo numa **trilha auditável imutável** que o conselho e a próxima gestão podem inspecionar.

**Por que IA-first:** detecção de anomalia e classificação contínua sobre lançamentos heterogêneos é estatística e contextual — não cabe em regra fixa. O agente aprende o padrão normal de cada condomínio e sinaliza o desvio.

## Por que agora

Pressão regulatória (LGPD) e social por governança, somada a síndicos cada vez mais responsabilizados pessoalmente. A trilha auditável deixou de ser luxo: é defesa jurídica.

## Mercado

~70–100 mil condomínios de médio/grande porte. O comprador é o condomínio (síndico/conselho), não a administradora — o que abre um canal de venda distinto. SOM: condomínios com histórico de conflito de gestão ou troca recente de síndico/administradora.

## Modelo de negócio

Assinatura por condomínio, vendida ao síndico/conselho como apólice de governança. Módulo premium possível: auditoria sob demanda (parecer para assembleia).

## Diferencial / moat

A base de preços de serviços por região e tipo — construída a cada condomínio auditado — é o benchmark que torna a detecção de superfaturamento precisa. Quanto mais condomínios, melhor o benchmark.

## Encaixe no ecossistema Group

Produto de **confiança e governança**, vendido para o lado do condomínio e não da administradora — complementa o ERP da Group em vez de competir. Para a Group, é um diferencial que torna a plataforma dela a "escolha de quem quer transparência".

## Por que este time

*Rascunho — personalizar.* Esta ideia transfere uma tese já em construção — governança de engenharia com IA, trilha de auditoria, contrato verificável — para um vertical com dor concreta e disposição a pagar.

## O ask

Acesso de leitura aos lançamentos do Group Condomínios; condomínios-piloto com conselho ativo; investimento para a engenharia do motor de detecção e do benchmark de preços.

## Fontes

- MB7 Auditoria — "Superfaturamento e Fraudes em Contratos do Condomínio"; Blog Robotton — ex-síndico condenado a ressarcir condomínio
- Reclame Aqui — Lello Condomínios (cobranças sem aprovação do síndico); Group Software (Condomínio21: previsão orçamentária some sem log)
- Conjur / Jusbrasil — crescimento de 81% nas decisões LGPD do setor condominial
