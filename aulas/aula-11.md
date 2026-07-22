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
# Aula 11

## §F1 — Escopo

Objetivos de Aprendizagem:
- O1: Integrar caixas, interruptor, tomada e luminária em um módulo de parede didático desenergizado, simulando um circuito residencial.
- O2: Executar testes de integridade e segurança usando multímetro nas escalas de continuidade e resistência, garantindo ausência de curtos.
- O3: Validar a eficácia do caminho de aterramento antes da entrega ao cliente, documentando resultados no app.

Skills e Temas:
- Centrais: Montagem de circuito didático completo, uso de multímetro (continuidade/resistência), validação de switch loop.
- Adjacentes: Trabalho em equipe integrada com papéis definidos (Montador, Conector, Auditor).
- Awareness: Comunicação clara com o cliente sobre relatórios de integridade de circuito simples.

O que NÃO Ensinar:
- Energização direta na rede 120 V sem supervisão e sem aprovação prévia do checklist de continuidade.
- Alterações em painéis de distribuição elétrica.

Flags de Risco (Legal/Segurança):
- 100 % dos testes realizados em circuito estritamente desenergizado, eliminando risco elétrico.

## §F2 — Desenho

Modelo Mental:
"Um circuito elétrico residencial é um caminho contínuo de ida e volta; antes de dar energia, provamos a integridade com multímetro."

Blocos da Teoria:
1. Diagnóstico por Multímetro: Escala de Continuidade (Beep) e Medição de Resistência (Ohms) em circuitos desenergizados.
2. Verificação de Curto-Circuito: Como detectar pontes acidentais entre Hot-Neutral, Hot-Ground ou Neutral-Ground.
3. Validação Lógica de Switch Loop: Testar o fechamento e abertura de contato do interruptor alimentando o ponto de luz via multímetro.

Plano Detalhado da Prática (Lab Presencial - Módulo Completo em Trio):
- Operador A (Montador): Conecta fisicamente o cabo entre caixa de alimentação didática, interruptor, tomada duplex e luminária.
- Operador B (Conector & Wire Nuts): Realiza as emendas com wire nuts (torque e teste de tração "pull test" em cada condutor).
- Operador C (Auditor de Multímetro): Aplica as pontas de prova do multímetro nos bornes para testar continuidade com switch aberto/fechado, zera risco de curto e valida no app.

Arco Emocional:
Expectativa com a integração de vários dispositivos -> Concentração durante o teste de multímetro -> Vibração com o 'BEEP' de continuidade correta.

## §F3 — Conteúdo

Texto que Ensina:
Antes de conectar qualquer circuito à energia real, o Handyman profissional realiza o **Teste de Integridade e Continuidade com Multímetro** no circuito desenergizado. Isso garante que não existem curtos-circuitos ou falhas de isolamento.

Diagnóstico com Multímetro (Escala de Continuidade / Ohms):
1. **Teste de Curto-Circuito (Hot para Neutral):** Coloque uma ponta de prova no fio Hot e outra no Neutral. O multímetro DEVE marcar resistência infinita (sem beep). Se der beep, há um curto-circuito!
2. **Teste de Curto para Terra (Hot/Neutral para Ground):** Deve dar resistência infinita.
3. **Teste do Switch Loop:** Coloque as pontas no Hot de entrada e no Retorno da lâmpada. Com o interruptor LIGADO, deve dar BEEP (continuidade = 0 Ohms). Com o interruptor DESLIGADO, deve dar resistência infinita.

Trabalho em Equipe e Organização:
No lab presencial, o circuito é montado em trio com verificação cruzada. Todos os conectores plásticos (*wire nuts*) devem passar pelo **Pull Test** (puxar cada fio individualmente para garantir que ficou firme dentro do conector).

Quiz de Fixação:
1. Qual deve ser o resultado do teste de continuidade entre Fase e Neutro em um circuito normal desenergizado? (a) Beep contínuo (b) Sem beep / Resistência infinita (c) 120 Volts -> Resposta: (b)
2. O que é o 'Pull Test' em wire nuts? (a) Puxar o disjuntor (b) Puxar individualmente cada fio para testar se ficou preso no conector (c) Medir a tensão -> Resposta: (b)

Erros Comuns:
- Energizar o circuito sem realizar o teste prévio de continuidade com multímetro.
- Deixar pontas de cobre expostas fora do wire nut.

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
