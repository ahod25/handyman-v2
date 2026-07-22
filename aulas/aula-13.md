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
# Aula 13

## §F1 — Escopo

Objetivos de Aprendizagem:
- O1: Identificar a anatomia de um chuveiro americano (shower arm, showerhead, filtro, handheld, diverter, escutcheon).
- O2: Executar remoção e instalação de showerheads usando fita PTFE no sentido correto e gaskets de vedação, garantindo estanqueidade.
- O3: Remover caulk/silicone antigo em áreas úmidas e aplicar novo silicone 100 % à prova d'água com acabamento limpo.

Skills e Temas:
- Centrais: Substituição de showerheads/handhelds, aplicação de fita PTFE, vedação com silicone sanitário.
- Adjacentes: Limpeza de depósitos minerais, uso de ferramentas com proteção para não riscar o acabamento.
- Awareness: Distinção entre troca de acessórios de rosca exposta e manutenção em válvulas/misturadores internos.

O que NÃO Ensinar:
- Substituição de válvulas de chuveiro (shower valves) de trás da parede ou soldagem de tubos de cobre.
- Troca de bases de chuveiro (shower pans) ou azulejamento completo.

Flags de Risco (Legal/Segurança):
- Cuidado com aperto excessivo no braço do chuveiro (shower arm) para não quebrar a conexão de latão dentro da parede.

## §F2 — Desenho

Modelo Mental:
"Água é implacável: ela encontra qualquer falha de rosca ou vedação; fita PTFE e silicone de qualidade são seus melhores escudos."

Blocos da Teoria:
1. Anatomia do Shower Arm & Head: Rosca NPT de 1/2", gaxetas de borracha, restrictores de fluxo e aeradores.
2. A Regra da Fita PTFE (Teflon): Aplicação em sentido horário (3 a 5 voltas) sem cobrir o primeiro fio de rosca.
3. Recaulking em Áreas Úmidas: Remoção total de silicone estragado com estilete/raspador, limpeza com álcool e cordão de silicone 100%.

Plano Detalhado da Prática (Lab Presencial - Bancada de Chuveiro):
- Operador A (Showerhead): Aplica fita PTFE no shower arm, rosqueia o showerhead manualmente e dá o aperto final com chave protegida por pano.
- Operador B (Raspagem): Raspa o silicone antigo da junta da bancada usando raspador e limpa a superfície com álcool isopropílico.
- Operador C (Silicone & App): Aplica cordão contínuo de silicone 100% à prova d'água, alisa a junta com ferramenta de acabamento e registra checkpoint no app.

Arco Emocional:
Receio de deixar vazamentos -> Satisfação com a aplicação perfeita da fita PTFE -> Sensação de limpeza com o novo cordão de silicone.

## §F3 — Conteúdo

Texto que Ensina:
Infiltrações em banheiros causam danos estruturais graves à madeira da casa (subfloor rot). O Handyman protege o imóvel substituindo acessórios de rosca exposta e refazendo vedações sanitárias.

Instalação de Showerhead e Fita PTFE:
1. Limpe a rosca do braço de chuveiro (shower arm).
2. Aplique a **Fita PTFE (Teflon)** no sentido horário (3 a 5 voltas), mantendo o primeiro fio de rosca livre.
3. Rosqueie o novo showerhead à mão e finalize com alicate protegido por pano para não arranhar o acabamento metálico.

Recaulking (Vedação com Silicone 100%):
1. Raspe todo o silicone antigo, mofado ou ressecado usando raspador de silicone e estilete.
2. Limpe a junta com álcool isopropílico para remover gorduras e resíduos de sabão.
3. Aplique um cordão contínuo de **Silicone 100% Sanitário** (à prova d'água e mofo). Alise com ferramenta de silicone ou dedo úmido.

Quiz de Fixação:
1. Em qual sentido se deve enrolar a fita PTFE na rosca metálica? (a) Anti-horário (b) Horário (c) Transversal -> Resposta: (b)
2. Qual tipo de selante deve ser aplicado em juntas de box e chuveiros? (a) Caulk acrílico simples (b) Silicone 100% sanitário à prova d'água (c) Gesso -> Resposta: (b)

Erros Comuns:
- Aplicar silicone novo por cima do mofo/silicone antigo sem raspar.
- Usar alicate direto no chuveiro cromado, riscando a peça do cliente.

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
