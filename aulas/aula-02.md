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
# Aula 02

## §F1 — Escopo

Objetivos de Aprendizagem:
- O1: Determinar o tipo correto de ancoragem em função da carga, tipo de substrato e direção do esforço.
- O2: Localizar studs através de métodos físicos e de stud finder eletrônico no módulo de teste.
- O3: Instalar buchas expansivas, toggle bolts (Snaptoggle) e lag screws garantindo torque adequado e segurança.

Skills e Temas:
- Centrais: Deteção de studs, ancoragem em drywall oco vs. fixação direta em stud, controle de torque.
- Adjacentes: Interpretação de capacidade de carga de buchas (shear vs. pull‑out), uso de nível de bolha.
- Awareness: Comunicação clara ao cliente sobre limites de peso suportado por suportes de TV ou prateleiras.

O que NÃO Ensinar:
- Instalação de suportes de TV em paredes de alvenaria ou concreto; foco permanece em drywall e studs de madeira.
- Instalação de cargas muito pesadas (>200 lb) que exigem reforço interno (blocking).

Flags de Risco (Legal/Segurança):
- Atenção ao torque para não espanar o gesso; risco de perfuração acidental de tubulação ou fiação oculta em paredes reais.

## §F2 — Desenho

Modelo Mental:
"Drywall é gesso prensado; para pendurar algo pesado, ou você acha a madeira sólida (stud) ou usa a ancoragem correta para o gesso."

Blocos da Teoria:
1. A Física da Ancoragem: Esforço de Cizalhamento (Shear) vs. Tração (Pull-out).
2. Como Encontrar Studs: Stud finder eletrônico, padrão 16" OC, batida tátil e localização por tomadas.
3. O Arsenal de Buchas: Plastic anchors, Conkey/Self-drilling, Snaptoggle (Toggle Bolt) e Lag Screws.

Plano Detalhado da Prática (Lab Presencial - Ancoragem no Módulo):
- Operador A (Scanner & Marcação): Varre o painel com stud finder, marca a borda/centro do stud e fura com broca guia.
- Operador B (Fixação): Instala 1 bucha expansiva em drywall oco, 1 Snaptoggle e 1 Lag Screw direto no stud.
- Operador C (Teste & Checklist App): Aplica carga de teste (suporte de TV didático), afere nível e registra parâmetros de torque e carga suportada no app.

Arco Emocional:
Insegurança de pendurar objetos pesados -> Descoberta da força surpreendente do Snaptoggle -> Confiança total em ancoragem.

## §F3 — Conteúdo

Texto que Ensina:
Pendurar objetos em paredes americanas exige entender a física da ancoragem. O drywall de 1/2" é gesso prensado; ele suporta pouca carga direta sem o acessório correto.

Tipos de Esforço Mecânico:
- **Cizalhamento (Shear Force):** Força para baixo (ex: quadros, prateleiras rasas). O drywall resiste bem a cizalhamento.
- **Tração (Pull-out Force):** Força para fora puxando o fixador (ex: suporte de TV articulado, cabideiro pesado). Exige fixação direta no stud ou Snaptoggle.

Arsenal de Ancoragem:
1. **Buchas Plásticas Expansivas (Plastic Anchors):** Cargas leves até 10-15 lbs em cizalhamento (quadros pequenos).
2. **Buchas Rosqueáveis (Self-Drilling / Conkey Anchors):** Cargas médias até 30-50 lbs (espelhos, quadros médios).
3. **Snaptoggle (Toggle Bolts de Aço):** Cargas pesadas até 80-100 lbs em drywall oco (suportes de TV fixos, prateleiras).
4. **Lag Screw (Parafuso de Madeira 1/4" ou 5/16"):** Fixação direta no stud de madeira. Suporta +150 lbs com segurança total.

Como Encontrar o Stud:
Use o **Stud Finder Eletrônico** deslizando suavemente na horizontal. Confirme o centro batendo levemente na parede (som sólido vs. som oco) e buscando a presença de tomadas (que são pregadas na lateral de um stud).

Exemplos e Cenários Reais:
- *Cenário:* Cliente quer instalar uma TV de 65" com braço articulado em drywall oco.
- *Decisão de Handyman:* Braço articulado gera alta força de tração (pull-out). É obrigatório fixar pelo menos um lado do suporte no Stud de madeira com Lag Screws e o outro lado com Snaptoggles.

Quiz de Fixação:
1. Qual bucha é ideal para pendurar um suporte pesado em drywall oco sem stud? (a) Bucha plástica comum (b) Snaptoggle (c) Prego de aço -> Resposta: (b)
2. Qual força atua puxando o parafuso para fora da parede? (a) Cizalhamento (b) Tração (Pull-out) (c) Torção -> Resposta: (b)

Erros Comuns:
- Usar buchas plásticas comuns para suportes articulados de TV.
- Apertar o Lag Screw no stud com parafusadeira em alto torque até espanar a madeira.

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
