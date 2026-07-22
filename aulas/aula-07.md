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
# Aula 07

## §F1 — Escopo

Objetivos de Aprendizagem:
- O1: Compreender os 3 eixos de ajuste em dobradiças europeias ocultas (altura, lateralidade e profundidade).
- O2: Regular portas de armários desalinhadas e utilizar gabaritos (jigs) para furação e instalação de puxadores de forma consistente.
- O3: Remover, alinhar e reinstalar gavetas com corrediças metálicas (drawer slides) garantindo operação suave.

Skills e Temas:
- Centrais: Ajuste fino de dobradiças europeias, furação com gabarito, instalação de puxadores e alinhamento de corrediças.
- Adjacentes: Reparo de furos espanados em aglomerado/MDF com cavilhas e cola de madeira.
- Awareness: Percepção de qualidade do cliente referente ao alinhamento visual de cozinhas e banheiros.

O que NÃO Ensinar:
- Fabricação sob medida de gabinetes de cozinha ou restauração de marcenaria antiga.
- Corte de superfícies de granito ou pedra para gabinetes.

Flags de Risco (Legal/Segurança):
- Cuidado com aperto excessivo de parafusos em painéis de MDP/MDF para não espanar a rosca, evitando rachaduras precoces.

## §F2 — Desenho

Modelo Mental:
"Dobradiças europeias são o volante tridimensional do marceneiro: alguns giros de parafuso alinham qualquer porta de armário."

Blocos da Teoria:
1. A Geometria das 3 Dimensoes (3D Hinges): Parafuso de altura (Y), lateralidade (X) e profundidade/folga (Z).
2. Instalação de Hardware: Uso de gabaritos (jigs) para furação precisa de puxadores sem desvio.
3. Reparo de MDF Espanado: Técnica de cavilha de madeira + cola PVA para refazer furos espanados.

Plano Detalhado da Prática (Lab Presencial - Bancada de Armários):
- Operador A: Executa o alinhamento 3D de 2 portas de armário desalinhadas na bancada até zerar a fresta.
- Operador B: Prepara e repara um furo espanado usando cavilha e cola, reinstalando a dobradiça.
- Operador C (Auditor/Gabarito): Posiciona gabarito de puxadores, realiza furação com broca de 3/16", fixa puxadores e inspeciona no app.

Arco Emocional:
Sensação de caos ao ver portas tortas -> Fascinamento com a precisão dos parafusos 3D -> Confiança para alinhar qualquer cozinha.

## §F3 — Conteúdo

Texto que Ensina:
Armários de cozinha e banheiro desalinhados passam impressão de desleixo. Com a dobradiça europeia oculta (3D Hinge), você ajusta os 3 eixos espaciais com apenas uma chave chave Philips.

Os 3 Eixos de Ajuste 3D:
1. **Eixo Y (Altura / Vertical):** Sobe e desce a porta alinhando com as portas vizinhas.
2. **Eixo X (Lateral / Esquerda-Direita):** Ajusta a fresta central entre duas portas.
3. **Eixo Z (Profundidade / Dentro-Fora):** Ajusta a folga entre a porta e o corpo do gabinete para não raspar na moldura.

Reparo de MDF Espanado e Gabaritos de Puxador:
- Quando o parafuso da dobradiça espanar no MDF/aglomerado, insira uma cavilha de madeira besuntada em cola PVA (Titebond), deixe secar, corte rente e refaça o furo.
- Para instalar puxadores (knobs e pulls), utilize sempre um **Gabarito Plastico Ajustável (Jig)**. Furar a olho humano resulta em puxadores tortos e perda da porta.

Quiz de Fixação:
1. Quantos eixos de ajuste possui uma dobradiça europeia oculta? (a) 1 (b) 2 (c) 3 -> Resposta: (c)
2. Como reparar um furo espanado em gabinete de MDF? (a) Usar prego (b) Cavilha de madeira com cola PVA (c) Fita isolante -> Resposta: (b)

Erros Comuns:
- Furar a porta do armário para colocar puxador sem usar gabarito.
- Apertar excessivamente parafusos em MDF causando espanamento.

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
