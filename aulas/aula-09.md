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
# Aula 09

## §F1 — Escopo

Objetivos de Aprendizagem:
- O1: Reconhecer a anatomia de interruptores (single‑pole, 3‑way), identificar terminais (Hot, Neutral, Ground) e faceplates.
- O2: Executar substituição segura de um interruptor single‑pole em bancada desenergizada, seguindo o protocolo NCVT.
- O3: Realizar side‑wire loops e apertar corretamente os parafusos de terminal, organizando a fiação para manutenção futura.

Skills e Temas:
- Centrais: Substituição like‑for‑like de interruptores, protocolo NCVT de desenergização, conexão side‑wire, terra de segurança.
- Adjacentes: Noções de Smart Switches (necessidade de fio neutro), organização de cabos na caixa.
- Awareness: Fronteira legal clara entre troca direta de dispositivo existente e criação de novas linhas elétricas.

O que NÃO Ensinar:
- Conexão de circuitos energizados 120 V/240 V.
- Alteração de disjuntores no painel principal (breaker box).

Flags de Risco (Legal/Segurança):
- Regra de Ouro: Todo teste é precedido pelo protocolo de verificação de energia zero com NCVT.

## §F2 — Desenho

Modelo Mental:
"Trabalhar em elétrica de Handyman é 90% rigor de protocolo NCVT de Energia Zero e 10% mecânica de aperto de parafusos."

Blocos da Teoria:
1. A Regra de Ouro do NCVT: Testador de tensão sem contato (NCVT) — teste em fonte viva -> teste no circuito -> teste na fonte viva.
2. Anatomia do Interruptor Single-Pole: Terminais brass (fase/retorno), green screw (ground), strip gauge.
3. A Arte do Loop Side-Wire: Dobra no sentido horário a 3/4 de volta sob o parafuso de latão com aperto de 12-14 in-lbs.

Plano Detalhado da Prática (Lab Presencial - Bancada Desenergizada):
- Operador A (Protocolo NCVT): Executa o protocolo de verificação de energia zero com NCVT no circuito de bancada.
- Operador B (Conexão MEC): Descarca as pontas do cabo, cria loops no sentido horário e fixa nos terminais do interruptor.
- Operador C (Auditor): Confere torque dos parafusos, valida terminal de aterramento (ground), organiza cabos na caixa e registra no app.

Arco Emocional:
Respeito/Receio da eletricidade -> Segurança garantida pelo protocolo NCVT -> Orgulho da fiação organizada e profissional.

## §F3 — Conteúdo

Texto que Ensina:
A regra nº 1 ao trabalhar com elétrica residencial é: **Garantir Energia Zero**. Como Handyman, você fará substituições diretas (like-for-like) de interruptores e tomadas em circuitos desenergizados.

Protocolo NCVT de Segurança (Non-Contact Voltage Tester):
1. Teste a caneta NCVT em uma tomada comprovadamente energizada (validação da ferramenta).
2. Teste os fios na caixa onde você vai trabalhar (confirmação de energia zero).
3. Teste novamente na tomada energizada (confirmação de que a caneta continuou funcionando).

Anatomia do Interruptor Single-Pole e Conexão Side-Wire:
- **Latão (Brass Screws):** Onde entram o fio Fase (Hot - preto) e o Retorno da lâmpada.
- **Verde (Green Screw):** Onde conecta o fio de Aterramento (Ground - nu ou verde).
- **Side-Wire Loop:** Descarque 3/4" de fio, faça uma volta em forma de "C" usando alicate meia-cana e encaixe no parafuso **SEMPRE NO SENTIDO HORÁRIO**. Assim, ao apertar o parafuso, a rosca puxa e fecha o loop de fio em vez de expulsá-lo.

Quiz de Fixação:
1. Em qual sentido deve ser feito o loop do fio no parafuso do terminal? (a) Anti-horário (b) Horário (c) Tanto faz -> Resposta: (b)
2. Qual o primeiro passo do protocolo NCVT? (a) Cortar os fios (b) Testar o NCVT numa fonte sabidamente viva (c) Ligar o disjuntor -> Resposta: (b)

Erros Comuns:
- Fazer o loop no sentido anti-horário (o parafuso desfaz o loop ao ser apertado).
- Trabalhar sem testar o NCVT antes.

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
