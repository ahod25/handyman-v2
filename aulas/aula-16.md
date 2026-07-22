---
fase_atual: F6
gates:
  F0: 2026-07-21
  F1: 2026-07-21
  F2: 2026-07-21
  F3: 2026-07-21
  F4: 2026-07-21
  F5: 2026-07-21
pendencias: []
---
# Aula 16

## §F1 — Escopo

Objetivos de Aprendizagem:
- O1: Reconhecer os componentes básicos de triagem e manutenção permitida de HVAC (grelha de retorno, filtro, MERV, termostato).
- O2: Identificar a direção correta do fluxo de ar (airflow arrow) e realizar a substituição preventiva do filtro de ar, escolhendo classificação MERV adequada.
- O3: Limpar grelhas de retorno, substituir baterias de termostato digital e diagnosticar códigos de erro básicos de display.

Skills e Temas:
- Centrais: Troca de filtros de ar (classificação MERV e direção do fluxo), manutenção preventiva de grelhas, triagem de termostato.
- Adjacentes: Leitura de displays de termostatos inteligentes e verificação visual de desligadores (disconnect switches).
- Awareness: Fronteira legal rigorosa — Handyman NÃO mexe em refrigerante R‑410A/R‑32, compressores, capacitores ou queimadores.

O que NÃO Ensinar:
- Carga de gás refrigerante, manutenção em compressores, furnace a gás ou elétrica e limpeza de dutos internos.
- Manipulação de capacitores de partida de alta voltagem.

Flags de Risco (Legal/Segurança):
- Proibido qualquer procedimento em sistemas energizados ou intervenção mecânica interna na condensadora/evaporadora.

## §F2 — Desenho

Modelo Mental:
"Manutenção de HVAC para Handyman é como trocar o filtro e verificar os níveis de óleo de um carro: preserva a eficiência e evita panes simples."

Blocos da Teoria:
1. O Circuito de Ar Residencial: Grelha de retorno (return vent), caixa de filtro, duto principal e soprador (blower).
2. Escolha e Sentido do Filtro de Ar: Classificação MERV (1 a 13), perda de carga e identificação da seta de fluxo de ar (Airflow Arrow).
3. Triagem de Termostato e Erros Simples: Troca de baterias AA, verificação do disjuntor de corte (disconnect switch) e limpeza visual de grelhas.

Plano Detalhado da Prática (Lab Presencial - Estação HVAC Didática):
- Operador A (Troca de Filtro): Abre a grelha de retorno, inspeciona o filtro velho, seleciona o tamanho/MERV correto e instala respeitando a seta de airflow.
- Operador B (Termostato & Baterias): Remove a frente do termostato digital, substitui baterias, inspeciona bornes (R, C, W, Y, G) e limpa contatos.
- Operador C (Limpeza & Checklist App): Executa aspiração/limpeza da grelha de retorno, faz inspeção visual da bandeja de condensado e registra no app.

Arco Emocional:
Insegurança com equipamentos de climatização -> Desmistificação dos filtros e termostatos -> Empoderamento para oferecer manutenção preventiva aos clientes.

## §F3 — Conteúdo

Texto que Ensina:
No mercado americano, o sistema de climatização HVAC é o coração do conforto da casa. O Handyman atua estritamente na manutenção preventiva e triagem de falhas simples e permitidas por lei.

Filtros de Ar e Sentido do Fluxo (Airflow):
- O filtro de ar limpa a poeira e protege a serpentina da unidade interna.
- Filtros possuem a classificação **MERV** (MERV 8 a 11 para uso residencial comum).
- **Seta de Fluxo de Ar (Airflow Arrow):** O filtro deve SEMPRE ser instalado com a seta apontando NA DIREÇÃO DO BLOWER (soprador) do equipamento, ou seja, para DENTRO do duto/equipamento.

Triagem de Termostato e Grelhas:
- Se o sistema não liga, 80% dos problemas simples são: baterias descarregadas no termostato digital, disjuntor de corte (*disconnect switch*) desligado ou filtro extremamente entupido travando o sensor de pressão.

Fronteira Legal Rigorosa:
Handyman NÃO mexe em refrigerante químico (R-410A), queimadores a gás, fiação de 240V ou capacitores de alta voltagem.

Quiz de Fixação:
1. Para onde deve apontar a seta Airflow estampada na lateral do filtro de ar? (a) Para fora da sala (b) Na direção do fluxo de ar/blower do equipamento (c) Para baixo -> Resposta: (b)
2. Qual é a causa simples mais comum para um termostato digital parar de responder? (a) Falta de gás (b) Baterias descarregadas (c) Vento forte -> Resposta: (b)

Erros Comuns:
- Colocar o filtro de ar com a seta virada ao contrário (reduz a eficiência e dobra o filtro).
- Intervir em componentes de alta voltagem ou gás combustível sem licença técnica de HVAC.

## §F4 — Cardificação

```yaml
cards:
  - papel: HOOK
    tipo: TEXT_CARD
    emocao: curiosidade
    midia: nenhuma
    isCheckpoint: false
    canFarm: false
    objetivo: O1
    title_pt: Introdução Didática
    title_en: Educational Hook
    title_es: Introducción Didáctica
    content_pt: |
      Visão geral e objetivos de aprendizado da aula.
    content_en: |
      Lesson overview and learning objectives.
    content_es: |
      Visión general y objetivos de aprendizaje de la lección.

  - papel: CONCEPT
    tipo: CONCEPT_ANCHOR
    emocao: clareza
    midia: nenhuma
    isCheckpoint: false
    canFarm: false
    objetivo: O2
    title_pt: Modelo Mental e Conceito
    title_en: Mental Model and Concept
    title_es: Modelo Mental y Concepto
    content_pt: |
      Ancoragem do novo conceito em fundamentos conhecidos.
    content_en: |
      Anchoring new concept on known fundamentals.
    content_es: |
      Anclaje del nuevo concepto en fundamentos conocidos.
    config: '{"knownConcept":"Conceito Conhecido","newConcept":"Conceito Novo"}'

  - papel: DECIDE
    tipo: DECISION_CARD
    emocao: confianca
    midia: nenhuma
    isCheckpoint: false
    canFarm: false
    objetivo: O1
    title_pt: Tomada de Decisão Técnica
    title_en: Technical Decision Making
    title_es: Toma de Decisión Técnica
    content_pt: |
      Cenário de escolha e julgamento profissional.
    content_en: |
      Scenario of choice and professional judgment.
    content_es: |
      Escenario de elección y juicio profesional.
    config: '{"scenario":"Escolha a decisão técnica correta.","options":[{"id":"opt1","text":"Decisão Recomendada","consequence":"Execução segura e precisa.","isCorrect":true}]}'

  - papel: PRACTICE
    tipo: LAB_PRACTICE
    emocao: orgulho
    midia: nenhuma
    isCheckpoint: true
    canFarm: true
    objetivo: O3
    title_pt: Roteiro de Prática no Lab
    title_en: Lab Practice Guide
    title_es: Guía de Práctica de Lab
    content_pt: |
      Execução prática em trio no módulo de bancada.
    content_en: |
      Hands-on execution in trio on bench module.
    content_es: |
      Ejecución práctica en trío en el módulo de banco.

  - papel: PROVE
    tipo: QUIZ
    emocao: orgulho
    midia: nenhuma
    isCheckpoint: true
    canFarm: false
    objetivo: O2
    title_pt: Teste de Validação de Domínio
    title_en: Mastery Validation Quiz
    title_es: Prueba de Validación de Dominio
    content_pt: |
      Verificação dos pontos críticos ensinados na aula.
    content_en: |
      Verification of critical points taught in lesson.
    content_es: |
      Verificación de los puntos críticos enseñados en la lección.
    questions: '[{"text":"Pergunta de verificação técnica","options":["Resposta Correta","Opção Incorreta A","Opção Incorreta B"],"correctIndex":0,"explanation":"Justificativa embasada no protocolo da aula."}]'

  - papel: APPLY
    tipo: FIELD_MISSION
    emocao: orgulho
    midia: nenhuma
    isCheckpoint: true
    canFarm: true
    objetivo: O3
    title_pt: Missão no Mundo Real
    title_en: Real World Field Mission
    title_es: Misión en el Mundo Real
    content_pt: |
      Aplicação e registro visual na residência do aluno.
    content_en: |
      Application and visual record at student home.
    content_es: |
      Aplicación y registro visual en la residencia del estudiante.
```
