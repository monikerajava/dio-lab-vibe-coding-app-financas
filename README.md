# 💬 Prosa - Organizador Financeiro por Conversa

## 📖 Sobre o Projeto

O **Prosa** é um aplicativo de organização financeira pessoal desenvolvido com foco em simplicidade, acessibilidade e experiência conversacional.

A proposta é permitir que qualquer pessoa organize sua vida financeira utilizando linguagem natural, sem a necessidade de planilhas complexas ou formulários extensos.

Ao invés de cadastrar manualmente cada transação, o usuário conversa com o sistema como se estivesse falando com um assistente financeiro pessoal:

> "Gastei R$ 45 no almoço."

> "Recebi R$ 3.500 de salário."

> "Quero guardar R$ 10.000 para viajar."

O sistema interpreta as informações, registra os lançamentos e gera análises financeiras automaticamente.

---

# 🎯 Conceito do App

O Prosa foi concebido para resolver um problema comum:

Muitas pessoas abandonam o controle financeiro por considerarem os aplicativos atuais complicados, burocráticos ou difíceis de manter.

A solução proposta foi criar uma experiência baseada em conversação, utilizando Inteligência Artificial para transformar linguagem natural em dados financeiros estruturados.

### Diferenciais

- Registro de gastos via conversa.
- Classificação automática de categorias.
- Metas financeiras inteligentes.
- Relatórios simplificados.
- Análise de faturas de cartão.
- Importação de recibos e documentos.
- Agente Financeiro com recomendações personalizadas.
- Interface acessível baseada em princípios de Design Universal.

---

# 🚀 Funcionalidades Implementadas

## 🗣️ Conversa Financeira

Permite registrar receitas e despesas utilizando linguagem natural.

Exemplos:

- "Gastei R$ 45 no almoço"
- "Recebi R$ 5.500 de salário"

O sistema identifica automaticamente:

- Valor
- Tipo da movimentação
- Categoria
- Data

---

## 📊 Dashboard Financeiro

Visão consolidada contendo:

- Saldo atual
- Total de receitas
- Total de despesas
- Comprometimentos futuros
- Distribuição dos gastos por categoria

---

## 🎯 Metas Financeiras

Permite criar objetivos financeiros como:

- Viagem
- Reserva de emergência
- Compra de veículo
- Quitação de dívidas

A aplicação acompanha automaticamente o progresso.

---

## 📈 Relatórios

Geração de relatórios financeiros contendo:

- Resumo mensal
- Gastos por categoria
- Evolução financeira
- Comparativos mensais

Exportação prevista para:

- Excel (.xlsx)
- CSV

---

## 💳 Análise de Cartão de Crédito

Funcionalidade planejada para:

- Importação de PDF de faturas
- Identificação automática dos lançamentos
- Classificação por categoria
- Identificação de assinaturas recorrentes
- Análise de parcelamentos
- Geração de plano de corte de gastos

---

## 📄 Importação de Documentos

Funcionalidade planejada para:

- Recebimento de recibos
- Comprovantes
- PDFs

Utilizando OCR para extração automática de informações.

---

## 🤖 Agente Financeiro

Assistente responsável por:

- Alertas financeiros
- Recomendações de economia
- Acompanhamento de metas
- Educação financeira contextual

Exemplo:

> "Você gastou 32% mais com alimentação este mês."

---

# 🧠 Prompt Final (PRD)

O desenvolvimento do aplicativo foi guiado por um Product Requirements Document (PRD) estruturado especificamente para utilização em plataformas de Vibe Coding como Lovable.

O PRD contemplou:

- Visão do produto
- Problema de negócio
- Público-alvo
- Funcionalidades
- Regras de negócio
- Fluxos do usuário
- Design Universal
- Prompts do Agente Financeiro
- Critérios de validação do MVP

## Principais Objetivos do MVP

- Registrar movimentações financeiras por conversa.
- Automatizar classificações financeiras.
- Criar metas financeiras.
- Oferecer insights financeiros personalizados.
- Gerar relatórios simples e acessíveis.

PRD REFINADO NO COPILOT WEB
```markdowon
============================================================
PRD - ORGANIZADOR FINANCEIRO POR CONVERSA
VERSÃO MVP 1.0
============================================================

1. VISÃO DO PRODUTO

Criar um aplicativo de finanças pessoais baseado em conversação,
permitindo que usuários registrem receitas e despesas utilizando
linguagem natural.

O sistema deve transformar conversas em lançamentos financeiros,
gerar análises automáticas e oferecer recomendações personalizadas
para ajudar o usuário a tomar melhores decisões financeiras.

Proposta de Valor:

"Converse com seu dinheiro da mesma forma que conversa com uma pessoa."

Exemplos:

"Gastei R$ 45 no almoço."
"Recebi R$ 3.500 de salário."
"Quero economizar R$ 500 por mês."
"Como posso reduzir meus gastos?"


============================================================
2. PROBLEMA
============================================================

Muitas pessoas abandonam o controle financeiro porque:

- Os aplicativos exigem lançamentos manuais.
- As interfaces são complexas.
- Os gráficos são difíceis de entender.
- Falta orientação personalizada.
- O processo consome muito tempo.

O produto busca eliminar essas barreiras utilizando IA e conversação.


============================================================
3. PÚBLICO-ALVO
============================================================

Primário:

- Pessoas iniciando sua organização financeira.
- Usuários sem conhecimento financeiro.

Secundário:

- Jovens adultos.
- Trabalhadores autônomos.
- Profissionais CLT.
- Pessoas que já tentaram usar planilhas e desistiram.


============================================================
4. OBJETIVOS DO MVP
============================================================

Validar se os usuários conseguem:

1. Registrar gastos por conversa.
2. Entender para onde seu dinheiro está indo.
3. Criar metas financeiras.
4. Receber recomendações relevantes.
5. Utilizar o aplicativo sem necessidade de treinamento.


============================================================
5. FUNCIONALIDADES DO MVP
============================================================

5.1 CHAT FINANCEIRO

Registrar:

- Despesas
- Receitas
- Transferências
- Metas

Exemplos:

"Gastei R$ 89 no mercado."
"Recebi R$ 4.500 de salário."
"Paguei a fatura do cartão."


------------------------------------------------------------
5.2 CLASSIFICAÇÃO AUTOMÁTICA
------------------------------------------------------------

Categorias padrão:

- Alimentação
- Transporte
- Saúde
- Educação
- Moradia
- Compras
- Assinaturas
- Lazer
- Salário
- Investimentos
- Outros

O sistema deve aprender categorias frequentes.


------------------------------------------------------------
5.3 METAS FINANCEIRAS
------------------------------------------------------------

Permitir:

- Criar metas
- Editar metas
- Remover metas
- Acompanhar progresso

Tipos:

- Reserva de emergência
- Viagem
- Compra de veículo
- Compra de imóvel
- Quitação de dívidas


------------------------------------------------------------
5.4 AGENTE FINANCEIRO
------------------------------------------------------------

Responsável por:

- Dar dicas de economia
- Identificar desperdícios
- Explicar hábitos financeiros
- Ajudar na criação de metas

Exemplos:

"Você gastou 32% mais com delivery este mês."

"Você possui 5 assinaturas recorrentes."


------------------------------------------------------------
5.5 RELATÓRIOS
------------------------------------------------------------

Relatórios disponíveis:

- Resumo mensal
- Evolução financeira
- Gastos por categoria
- Comparativo mensal
- Metas financeiras

Exportação:

- Excel (.xlsx)
- CSV


------------------------------------------------------------
5.6 ANÁLISE DE FATURA DE CARTÃO
------------------------------------------------------------

Upload:

- PDF de fatura

Extração:

- Data
- Estabelecimento
- Valor
- Parcelamento
- Categoria

Relatórios:

- Resumo
- Parcelamentos
- Assinaturas
- Plano de corte
- Gastos recorrentes

Exportação:

- Excel
- CSV


------------------------------------------------------------
5.7 IMPORTAÇÃO DE DOCUMENTOS
------------------------------------------------------------

Tipos suportados:

- Fotos de recibos
- PDF
- Comprovantes

OCR deve identificar:

- Data
- Valor
- Estabelecimento

Sistema cria sugestão automática de lançamento.


============================================================
6. REGRAS DE NEGÓCIO
============================================================

RN001

Toda movimentação deve possuir:

- Tipo
- Valor
- Data
- Categoria

RN002

Despesas reduzem saldo disponível.

RN003

Receitas aumentam saldo disponível.

RN004

Quando a IA não identificar uma categoria com confiança suficiente,
deve solicitar confirmação ao usuário.

Exemplo:

"Você deseja classificar essa compra como Alimentação?"

RN005

Parcelamentos devem gerar:

- Quantidade total de parcelas
- Parcela atual
- Parcelas restantes
- Valor comprometido futuro

RN006

Assinaturas recorrentes com mesmo valor por mais de 2 meses
devem ser sinalizadas.

RN007

Metas financeiras devem recalcular automaticamente o progresso.

RN008

Relatórios devem considerar filtros:

- Período
- Categoria
- Tipo de movimentação

RN009

Ao importar uma fatura, não devem ser criados lançamentos duplicados.

RN010

Receitas e despesas futuras devem ser marcadas como planejadas.

RN011

Toda recomendação financeira deve ser explicável.

Exemplo:

"Estou sugerindo reduzir gastos em Delivery porque o valor aumentou
40% nos últimos dois meses."

RN012

Nenhuma alteração automática pode excluir informações financeiras
sem confirmação explícita do usuário.

RN013

O sistema deve manter histórico completo de alterações.

RN014

Toda exportação deve respeitar os filtros aplicados.


============================================================
7. FLUXOS DO USUÁRIO
============================================================

FLUXO 1 - ONBOARDING

1. Usuário cria conta.
2. Define renda aproximada.
3. Define objetivos financeiros.
4. Configura preferências.
5. Acessa Dashboard.


------------------------------------------------------------
FLUXO 2 - REGISTRAR DESPESA
------------------------------------------------------------

Usuário:

"Gastei R$ 50 em combustível."

Sistema:

1. Detecta valor.
2. Detecta categoria.
3. Cria lançamento.
4. Atualiza Dashboard.


------------------------------------------------------------
FLUXO 3 - REGISTRAR RECEITA
------------------------------------------------------------

Usuário:

"Recebi R$ 4.500."

Sistema:

1. Registra receita.
2. Atualiza saldo.
3. Atualiza relatórios.


------------------------------------------------------------
FLUXO 4 - CRIAR META
------------------------------------------------------------

Usuário:

"Quero guardar R$ 10.000 para viajar."

Sistema:

1. Solicita prazo.
2. Calcula contribuição mensal.
3. Cria meta.


------------------------------------------------------------
FLUXO 5 - IMPORTAR FATURA
------------------------------------------------------------

1. Upload PDF.
2. Processamento.
3. Extração de lançamentos.
4. Classificação automática.
5. Emissão de relatório.


------------------------------------------------------------
FLUXO 6 - EXPORTAR RELATÓRIOS
------------------------------------------------------------

1. Selecionar período.
2. Escolher formato.
3. Gerar Excel.
4. Download.


============================================================
8. PROMPT BASE DO AGENTE FINANCEIRO
============================================================

PERSONA

Você é um Educador Financeiro Digital.

Seu objetivo é ajudar o usuário a compreender seus hábitos
financeiros sem julgamentos.

Tom:

- Educativo
- Motivador
- Claro
- Positivo
- Objetivo

Nunca utilize linguagem técnica sem explicação.


============================================================
PROMPT 1 - ANÁLISE GERAL
============================================================

Analise os dados financeiros do usuário.

Identifique:

- Principais categorias de gastos.
- Tendências de consumo.
- Possíveis excessos.
- Oportunidades de economia.

Explique em linguagem simples.

Forneça até 3 recomendações acionáveis.


============================================================
PROMPT 2 - RESUMO MENSAL
============================================================

Com base nas movimentações do mês, gere:

- Receita total.
- Despesa total.
- Saldo final.
- Maior categoria de gasto.
- Principal insight financeiro.

Use linguagem amigável e objetiva.


============================================================
PROMPT 3 - PLANO DE CORTE
============================================================

Analise as despesas.

Identifique:

- Gastos recorrentes.
- Assinaturas.
- Despesas não essenciais.

Monte um plano de redução contendo:

- Categoria
- Economia potencial
- Impacto estimado


============================================================
PROMPT 4 - META FINANCEIRA
============================================================

Ajude o usuário a alcançar sua meta.

Calcule:

- Valor restante.
- Tempo restante.
- Contribuição mensal necessária.

Forneça sugestões realistas.


============================================================
PROMPT 5 - DETECÇÃO DE ALERTAS
============================================================

Monitore movimentações.

Dispare alertas quando:

- Categoria crescer acima de 20%.
- Gasto único ultrapassar média histórica.
- Meta estiver atrasada.

Explique claramente o motivo do alerta.


============================================================
PROMPT 6 - EDUCAÇÃO FINANCEIRA
============================================================

Sempre que relevante:

- Explique conceitos financeiros.
- Utilize exemplos simples.
- Evite jargões.
- Incentive boas práticas.

Objetivo:

Ensinar o usuário enquanto ele utiliza o produto.


============================================================
9. PRINCIPAIS TELAS
============================================================

1. Onboarding
2. Dashboard
3. Chat Financeiro
4. Metas
5. Relatórios
6. Cartão de Crédito
7. Importação de Documentos
8. Configurações


============================================================
10. DESIGN UNIVERSAL E ACESSIBILIDADE
============================================================

O sistema deve possuir:

- Alto contraste.
- Compatibilidade com leitores de tela.
- Navegação por teclado.
- Texto simples.
- Layout responsivo.
- Fontes ajustáveis.
- Feedback visual e textual.
- Ícones com legendas.
- Não depender exclusivamente de cores.


============================================================
11. MÉTRICAS DE VALIDAÇÃO DO MVP
============================================================

Hipótese Principal:

Usuários preferem registrar gastos por conversa
em vez de formulários.

Indicadores:

- 70% dos lançamentos realizados via chat.
- Retenção superior a 60%.
- Satisfação média acima de 8/10.
- NPS superior a 50.
- Tempo médio de registro inferior a 30 segundos.
- Pelo menos 1 insight útil gerado por semana.

============================================================
FIM DO PRD
============================================================

```

# 🖼️ Evidências do Processo

## Tela Inicial

A landing page apresenta a proposta principal:

> "Converse com seu dinheiro como conversa com uma pessoa."

Demonstra a experiência conversacional como principal forma de interação.

### Funcionalidades evidenciadas:

- Proposta de valor
- Simulação de conversa
- Call-to-action para cadastro

---

## Onboarding

Fluxo de entrada responsável por coletar:

- Nome
- Renda aproximada
- Objetivos financeiros
- Preferências do usuário

Esse processo permite personalizar recomendações futuras.

---

## Dashboard

Painel principal contendo:

- Saldo do mês
- Receitas
- Despesas
- Gastos por categoria
- Dicas financeiras

O dashboard foi projetado para apresentar apenas informações essenciais, reduzindo a sobrecarga cognitiva.

---

# 🎨 Aplicação dos Conceitos de Design Universal

Durante a construção do produto foram considerados princípios de Design Universal:

✅ Linguagem simples

✅ Navegação intuitiva

✅ Poucos passos para executar tarefas

✅ Alto contraste visual

✅ Interface limpa

✅ Responsividade

✅ Feedback claro para ações do usuário

✅ Redução de termos técnicos

O objetivo foi construir uma experiência acessível ao maior número possível de usuários.

---

# 🧩 Tecnologias e Abordagem

O projeto foi desenvolvido seguindo conceitos de:

### Vibe Coding

Abordagem onde os requisitos do produto são descritos em linguagem natural e utilizados por ferramentas de IA para acelerar o desenvolvimento.

No processo foram utilizados:

- Lovable
- Engenharia de Prompt
- Product Requirements Document (PRD)
- Iteração baseada em feedback

---

# 📚 O que Aprendi no Processo

Este projeto permitiu compreender na prática a importância de um PRD bem estruturado para o sucesso de ferramentas de Vibe Coding.

Principais aprendizados:

### 1. A qualidade do prompt influencia diretamente a qualidade da aplicação

Quanto mais claro o contexto fornecido para a IA, melhores são as interfaces, fluxos e regras de negócio geradas.

### 2. Fluxos são tão importantes quanto funcionalidades

Descrever como o usuário interage com o sistema ajuda a IA a entender o comportamento esperado da aplicação.

### 3. Regras de negócio reduzem ambiguidades

Ao definir regras claras, a IA produz resultados mais consistentes e próximos de um produto real.

### 4. Design Universal melhora a experiência para todos

Criar interfaces acessíveis não beneficia apenas usuários com necessidades específicas, mas melhora a experiência geral do produto.

### 5. Vibe Coding não elimina a necessidade de análise

Mesmo utilizando IA, continua sendo fundamental pensar em requisitos, experiência do usuário, validações e objetivos do negócio.

---

# ✅ Conclusão

O Prosa demonstra como Inteligência Artificial e interfaces conversacionais podem tornar a educação financeira e o controle de gastos mais acessíveis para usuários iniciantes.

A experiência reforçou a importância do planejamento de produto, da escrita de bons requisitos e do uso estratégico de ferramentas de IA para acelerar o desenvolvimento de soluções digitais.

---

## 📷 Capturas de Tela

### Landing Page
![Landing Page](./docs/landing-page.png)

### Onboarding
![Onboarding](./docs/onboarding.png)

### Dashboard
![Dashboard](./docs/dashboard.png)
