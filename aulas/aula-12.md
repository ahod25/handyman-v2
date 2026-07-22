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
# Aula 12

## §F1 — Escopo

Objetivos de Aprendizagem:
- O1: Identificar a anatomia de fixtures de teto e ventiladores (bracket, canopy, motor, pás, kit de luz, pull‑chains).
- O2: Ler o manual do fabricante, conferir o suporte da caixa (fan‑rated) e montar a sequência mecânica com segurança.
- O3: Instalar o conjunto no suporte de teto de treino em altura confortável, realizar balanceamento mecânico inicial e testar operação.

Skills e Temas:
- Centrais: Montagem e fixação de ventiladores de teto/luminárias, leitura de manuais, verificação de caixa fan‑rated.
- Adjacentes: Montagem do kit de luz, conexão de hastes (downrod), acoplamento de pás e controle remoto.
- Awareness: Identificação de caixas de teto inadequadas que exigem retrofitting ou recusa por risco de queda.

O que NÃO Ensinar:
- Fixação em caixas de teto plásticas simples (não fan‑rated) para ventiladores pesados.
- Passagem de novos cabos de teto em sótão (attic).

Flags de Risco (Legal/Segurança):
- Risco de queda do equipamento se o suporte mecânico e trava de segurança não forem instalados corretamente.

## §F2 — Desenho

Modelo Mental:
"Ventilador de teto é massa em rotação sobre cabeças humanas; segurança mecânica vem antes de qualquer conexão elétrica."

Blocos da Teoria:
1. Suporte e Estrutura: Diferença entre caixa de luz comum e caixa FAN-RATED (capacidade de carga dinâmica de até 50-70 lbs).
2. Sequência de Montagem Mecânica: Bracket de teto, downrod, canopy, acoplamento de pás e kit de iluminação.
3. Balanceamento e Segurança: Trava de pino de retenção (clevis pin/cotter pin) e uso de pesos de balanceamento.

Plano Detalhado da Prática (Lab Presencial - Suporte de Teto Didático):
- Operador A (Suporte & Mastro): Insere o pino de trava (clevis pin) no downrod, passa a fiação e prepara o motor.
- Operador B (Montagem de Pás): Fixa os suportes e as pás no motor mantendo torque uniforme em todos os parafusos.
- Operador C (Ancoragem & Auditoria): Encaixa a esfera do ventilador no bracket de teto, trava o kit de iluminação, afere nivelamento das pás e valida checklist no app.

Arco Emocional:
Intimidação com o volume de peças do ventilador -> Trabalho em equipe fluido -> Alívio e orgulho ao ver o ventilador perfeitamente alinhado.

## §F3 — Conteúdo

Texto que Ensina:
Ventiladores de teto e fixtures de iluminação são equipamentos pesados e dinâmicos. A prioridade absoluta do Handyman é a segurança de fixação física antes da conexão elétrica desenergizada.

Suporte FAN-RATED vs. Caixas Comuns:
- Jamais instale um ventilador de teto em uma caixa octogonal plástica ou metálica comum. Ela não foi projetada para suportar a vibração dinâmica do motor e cairá com o tempo.
- Use exclusivamente caixas classificadas como **FAN-RATED** (suportam até 50-70 lbs em movimento) fixadas diretamente no stud do teto ou com suporte expansível metálico (*Fan Brace*).

Sequência de Montagem e Travas de Segurança:
1. Monte o mastro (downrod) e certifique-se de inserir e travar o pino de retenção (*Clevis Pin* e *Cotter Pin*).
2. Encaixe a esfera do downrod no bracket de teto.
3. Monte as pás com torque uniforme nos parafusos.
4. Faça a conexão elétrica desenergizada e instale o kit de iluminação e canopy.

Quiz de Fixação:
1. Qual tipo de caixa de teto deve ser usada para ventiladores? (a) Caixa plástica comum (b) Caixa Fan-Rated (c) Nenhuma -> Resposta: (b)
2. Para que serve o pino de trava (clevis/cotter pin) no mastro do ventilador? (a) Enfeite (b) Trava mecânica de segurança contra queda do motor (c) Aterramento -> Resposta: (b)

Erros Comuns:
- Instalar ventilador em caixa de teto simples.
- Esquecer de colocar o cotter pin de trava no mastro.

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
