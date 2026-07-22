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
# Aula 15

## §F1 — Escopo

Objetivos de Aprendizagem:
- O1: Identificar os componentes do sistema de pia (torneira, supply lines, shutoff valves, ralo, P‑trap, slip nuts).
- O2: Montar o P‑trap com arruelas novas, aplicar Plumber's Putty no ralo/basket strainer e efetuar aperto manual correto.
- O3: Diagnosticar pontos de vazamento visual em pias e realizar substituição de aeradores e linhas de suprimento flexíveis.

Skills e Temas:
- Centrais: Montagem de P‑trap, vedação com Plumber's Putty, troca de supply lines flexíveis, limpeza de aeradores.
- Adjacentes: Inspeção seca de anéis de vedação (washers) e alinhamento de tubos de escoamento (tailpiece).
- Awareness: Limites de atuação entre pequenos reparos sob a pia e intervenções em encanamento predial.

O que NÃO Ensinar:
- Instalação de trituradores de lixo (garbage disposals) com alteração elétrica ou tubulação hidráulica em ferro galvanizado.
- Soldagem de tubos de cobre ou prensagem de tubos PEX em parede.

Flags de Risco (Legal/Segurança):
- Cuidado para não apertar porcas plásticas de P‑trap com chave pesada, evitando espanar ou rachar a conexão.

## §F2 — Desenho

Modelo Mental:
"Abaixo da pia existe um sifão que retém gases e resíduos (P-trap); cada junta rosqueada precisa de alinhamento perfeito sem força bruta."

Blocos da Teoria:
1. O Sistema de Escoamento sob a Pia: Tailpiece, ralo (basket strainer), P-trap (curva e braço de parede) e slip nuts com arruelas cônicas.
2. Vedação da Torneira e Ralo: Plumber's Putty (massa de encanador) sob a borda do ralo vs. vedações de silicone/borracha.
3. Linhas de Suprimento Flexíveis (Supply Lines): Tramas de inox, conexões de 3/8" compression e torque de vedação manual + 1/4 volta.

Plano Detalhado da Prática (Lab Presencial - Bancada de Pia):
- Operador A (Ralo & Putty): Aplica cordão de Plumber's Putty no ralo, insere na pia e aperta a porca inferior recolhendo o excesso de massa.
- Operador B (Montagem P-Trap): Encaixa o tailpiece, o P-trap e as arruelas cônicas posicionadas no sentido correto, apertando as slip nuts à mão.
- Operador C (Supply Lines & Auditoria): Conecta as linhas de suprimento de inox às válvulas de corte (shutoff), afere alinhamento mecânico e inspeciona no app.

Arco Emocional:
Confusão com o emaranhado de tubos -> Clareza na montagem do P-trap e utilidade da massa de encanador -> Satisfação ao ver o sistema vedado.

## §F3 — Conteúdo

Texto que Ensina:
Abaixo de pias de cozinha e banheiro existe o sistema de drenagem e hidráulica acessível. Cada junta precisa estar alinhada e vedada sem exigir ferramentas pesadas.

Anatomia do Sistema sob a Pia:
- **Basket Strainer / Ralo:** Peça metálica do ralo vedada com **Plumber's Putty** (massa flexível de encanador).
- **Tailpiece & P-Trap (Sifão em P):** Retém um fecho hídrico de água para impedir o retorno de maus odores do esgoto. Conectado por porcas plásticas (*slip nuts*) e arruelas cônicas de borracha.
- **Supply Lines (Linhas de Suprimento Flexíveis):** Cabos trançados de inox ligando a válvula de corte (*shutoff valve*) à torneira.

Técnica de Vedação e Montagem:
1. As arruelas cônicas do P-Trap devem ter o lado mais fino apontado na direção da corrente de fluxo.
2. Aperte as porcas *slip nuts* com a mão. Se necessário, dê no máximo 1/4 de volta com alicate ajustável.

Quiz de Fixação:
1. Para que serve o fecho hídrico de água retido dentro do P-Trap? (a) Filtrar água (b) Bloquear o retorno de gases e maus odores do esgoto (c) Esfriar a pia -> Resposta: (b)
2. Qual massa é usada para vedar a borda metálica do ralo na pia? (a) Silicone de alta temperatura (b) Plumber's Putty (massa de encanador) (c) Massa de drywall -> Resposta: (b)

Erros Comuns:
- Colocar a arruela cônica do P-Trap invertida, causando vazamento imediato.
- Apertar porcas plásticas com chave pesada até espanar ou rachar o tubo.

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
