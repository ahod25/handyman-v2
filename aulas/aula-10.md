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
# Aula 10

## §F1 — Escopo

Objetivos de Aprendizagem:
- O1: Identificar a anatomia de tomadas residenciais (duplex, 15 A/20 A) e a diferença vital entre GFCI e tomadas convencionais.
- O2: Executar substituição like‑for‑like de tomadas e identificar corretamente os terminais LINE e LOAD em GFCIs.
- O3: Conectar condutores usando side‑wiring com torque adequado e alinhar o yoke com nível e parede para acabamento profissional.

Skills e Temas:
- Centrais: Substituição de tomadas, instalação de GFCI (LINE vs LOAD), polaridade (fase/neutro/terra), alinhamento de yoke.
- Adjacentes: Teste mecânico de retenção de plugues, uso de conectores tipo porca (wire nuts).
- Awareness: Normas de obrigatoriedade de GFCI em áreas molhadas (cozinhas, banheiros, garagem, externo).

O que NÃO Ensinar:
- Instalação de tomadas 240 V de alta potência (secadoras, RVs, carros elétricos).
- Reparo interno de placas eletrônicas de tomadas GFCI.

Flags de Risco (Legal/Segurança):
- Inversão de polaridade (Hot/Neutral) ou inversão LINE/LOAD em GFCI — verificado com rigor na bancada.

## §F2 — Desenho

Modelo Mental:
"Tomada duplex é o ponto de entrega de força; GFCI é o anjo da guarda que interrompe a energia em milissegundos para salvar vidas."

Blocos da Teoria:
1. Anatomia de Tomada Duplex vs. GFCI: Diferença visual, botões TEST/RESET e terminais LINE vs. LOAD.
2. Polaridade Correta: Fios pretos (Hot) nos parafusos de latão (fenda menor); Fios brancos (Neutral) nos parafusos prateados (fenda maior).
3. Proteção em Áreas Molhadas: Como a tomada GFCI protege a si própria e o circuito downstream conectado ao LOAD.

Plano Detalhado da Prática (Lab Presencial - Instalação de Duplex e GFCI):
- Operador A: Conecta tomada Duplex convencional garantindo a polaridade correta e enrolando a fita isolante no corpo (se caixa metálica).
- Operador B: Conecta tomada GFCI identificando corretamente os terminais LINE (entrada) e isolando terminais LOAD não usados.
- Operador C (Auditor & Torque): Confere alinhamento do yoke na caixa, torque dos parafusos, alinhamento da placa decorativa e inspeciona no app.

Arco Emocional:
Clareza na distinção entre fiação neutra e fase -> Compreensão da lógica do GFCI -> Sensação de domínio de instalações seguras.

## §F3 — Conteúdo

Texto que Ensina:
Tomadas residenciais (Receptacles) fornecem energia para os aparelhos da casa. Tomadas **GFCI** (Ground Fault Circuit Interrupter) monitoram o equilíbrio entre Fase e Neutro e cortam a energia em milissegundos se detectarem fuga de corrente, salvando vidas em áreas úmidas.

Convenção de Polaridade e Fiação:
- **Parafuso de Latão (Brass Screw / Fenda Curta):** Fio Hot (Preto).
- **Parafuso Prateado (Silver Screw / Fenda Longa):** Fio Neutro (Branco).
- **Parafuso Verde (Green Screw):** Fio Ground (Aterramento / Nu ou Verde).

Instalação de Tomadas GFCI (LINE vs. LOAD):
As tomadas GFCI possuem dois pares de terminais:
- **LINE:** Onde entra a fiação vinda do painel elétrico.
- **LOAD:** Onde sai a fiação para proteger tomadas convencionais a montante (downstream). Se você estiver apenas trocando uma GFCI avulsa, use apenas os terminais LINE e mantenha o adesivo cobrindo os terminais LOAD.

Quiz de Fixação:
1. Em qual parafuso deve ser conectado o fio branco (Neutro)? (a) Verde (b) Latão (c) Prateado -> Resposta: (c)
2. Qual a função dos terminais LINE em uma tomada GFCI? (a) Receber a energia vinda do painel (b) Conectar a lâmpada (c) Aterrar o circuito -> Resposta: (a)

Erros Comuns:
- Inverter polaridade (conectar Hot no parafuso prateado e Neutro no latão).
- Conectar a entrada de energia nos terminais LOAD do GFCI, inutilizando a proteção contra choque.

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
