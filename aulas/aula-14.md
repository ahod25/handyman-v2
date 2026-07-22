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
# Aula 14

## §F1 — Escopo

Objetivos de Aprendizagem:
- O1: Compreender a anatomia completa de um vaso sanitário (tanque, bowl, fill valve, flush valve, flapper, supply line, wax ring).
- O2: Diagnosticar problemas comuns (gotejamento, descarga fraca, vazamento na base) e substituir mecanismos internos do tanque de forma segura.
- O3: Simular a instalação de vaso sanitário em bancada seca (alinhamento de flange, closet bolts, anel de cera seco e nivelamento), preparando para montagem real.

Skills e Temas:
- Centrais: Troca de fill valve, flapper e assento, substituição de supply line, assentamento sobre flange e anel de cera.
- Adjacentes: Ajuste da corrente do flapper e boia, controle de aperto dos parafusos do tanque para evitar trincas.
- Awareness: Identificação de vazamentos ocultos na estrutura de madeira do piso (subfloor rot).

O que NÃO Ensinar:
- Desentupimento de esgoto com roto‑rooter comercial ou substituição de tubulação de esgoto abaixo do piso.
- Reparo de louças sanitárias trincadas (devem ser substituídas por segurança).

Flags de Risco (Legal/Segurança):
- Risco de vazamento de água e trinca da louça por aperto excessivo dos closet bolts, exigindo torque adequado.

## §F2 — Desenho

Modelo Mental:
"O vaso sanitário depende da gravidade e de uma vedação hermética com a tubulação; a precisão do assentamento previne desastres ecológicos e estruturais."

Blocos da Teoria:
1. Anatomia e Funcionamento: Tanque, bowl, mecanismo de descarga (flush valve), válvula de enchimento (fill valve), flapper e boia.
2. O Anel de Cera (Wax Ring): Como funciona a vedação deformável por compressão entre o vaso e a flange do piso.
3. Mecânica do Assoalho: Flange de esgoto, closet bolts, nivelamento com calços plásticos (shims) e silicone sanitário na base.

Plano Detalhado da Prática (Lab Presencial - Simulação Seca de Vaso Sanitário):
- Operador A (Mecanismo do Tanque): Substitui fill valve e flapper dentro do tanque, ajustando a corrente e o nível de água didático.
- Operador B (Flange & Anel Seco): Posiciona closet bolts na flange, coloca anel de vedação de teste (elastômero/cera seca) e alinha o vaso.
- Operador C (Assentamento & Nível): Comprime o vaso sobre a flange, ajusta as porcas alternadamente sem trincar a louça, checa nível e valida no app.

Arco Emocional:
Aversão inicial à manutenção de sanitários -> Desmistificação dos componentes internos -> Confiança para instalar ou reparar qualquer vaso sanitário.

## §F3 — Conteúdo

Texto que Ensina:
O vaso sanitário residencial funciona por gravidade e vedação deformável. Problemas comuns incluem vazamentos internos no tanque e falhas de vedação na base.

Anatomia e Mecanismos do Tanque:
- **Fill Valve (Válvula de Enchimento):** Controla a entrada e o nível de água do tanque.
- **Flush Valve & Flapper:** A tampa emborrachada (flapper) que abre na descarga. Se estiver ressecada, a água vaza continuamente para o bowl (gotejamento/corrida de água).

Instalação da Base e Anel de Cera (Wax Ring):
- O vaso sanitário se conecta à tubulação através da **Flange de Esgoto**.
- O **Anel de Cera (Wax Ring)** fica espremido entre a flange e a base do vaso, criando uma vedação hermética contra água e gases.
- Posicione o vaso reto sobre os closet bolts e pressione com o peso do corpo. Nivele com calços plásticos (*shims*) e aperte os parafusos alternadamente **sem força bruta** para não trincar a louça de porcelana.

Quiz de Fixação:
1. Qual componente faz a vedação contra gases e água entre o vaso e o piso? (a) Fita isolante (b) Anel de Cera (Wax Ring) (c) Cola de cano -> Resposta: (b)
2. O que causa a perda contínua de água do tanque para o bowl? (a) Flapper ressecado ou mal ajustado (b) Assento quebrado (c) Suporte de papel -> Resposta: (a)

Erros Comuns:
- Aperto excessivo das porcas de fixação da louça, trincando o vaso.
- Mover ou girar o vaso sanitário após ter comprimido o anel de cera (destrói a vedação).

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
