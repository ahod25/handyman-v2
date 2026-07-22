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
# Aula 06

## §F1 — Escopo

Objetivos de Aprendizagem:
- O1: Identificar a anatomia completa de uma porta e fechadura residencial (jamb, latch, strike plate, backset, deadbolt).
- O2: Montar, alinhar e testar fechaduras tipo knob/lever e deadbolt em estações de bancada, replicando condições reais.
- O3: Diagnosticar problemas de travamento e executar ajustes mecânicos de folga no strike plate e nas dobradiças.

Skills e Temas:
- Centrais: Substituição like‑for‑like de fechaduras, alinhamento de latch e strike plate, ajuste de dobradiças.
- Adjacentes: Uso de parafusos longos na dobradiça, shims de ajuste fino.
- Awareness: Privacidade do cliente, segurança residencial e limites legais de chaveiro (locksmithing) amador.

O que NÃO Ensinar:
- Abertura de portas trancadas sem chave (lock‑picking) ou códigos avançados.
- Instalação de fechaduras em portas blindadas ou comerciais pesadas.

Flags de Risco (Legal/Segurança):
- Cuidado com o alinhamento das peças para não travar o mecanismo interno, evitando desgaste desnecessário.

## §F2 — Desenho

Modelo Mental:
"Uma fechadura é um relógio mecânico de segurança: milímetros de desalinhamento causam emperramento e frustração no cliente."

Blocos da Teoria:
1. Anatomia do Lockset: Knob/Lever, Latch bolt, Deadbolt, Strike plate, Backset (2-3/8" vs 2-3/4").
2. Mecânica do Encaixe: Por que a porta raspa no strike e como o latch se comporta sob pressão.
3. Correção de Sag e Trava: Ajuste de parafusos de dobradiça, limagem de strike plate e lubrificação.

Plano Detalhado da Prática (Lab Presencial - Bancada de Portas):
- Operador A: Desmonta e reinstala fechadura knob e deadbolt na bancada respeitando o backset.
- Operador B: Ajusta o folga do strike plate usando grosa/lima e instala parafusos de 3" na dobradiça para alinhar o sag.
- Operador C (Auditor): Testa ciclo mecânico de tranca (10x sem enganchar), confere recolhimento do latch e valida no app.

Arco Emocional:
Irritação com portas que emperram -> Entendimento do motivo mecânico -> Empoderamento ao resolver o emperramento em minutos.

## §F3 — Conteúdo

Texto que Ensina:
Uma fechadura residencial é um mecanismo de precisão. Quando uma porta não tranca direito ou raspa no batente (sagging door), o cliente sente frustração imediata. O Handyman resolve isso identificando se o problema é alinhamento da porta ou mecanismo interno do lockset.

Anatomia e Padrões de Fechaduras (Locksets & Deadbolts):
- **Backset:** Distância do centro do furo da fechadura até a borda da porta. Padrões americanos: 2-3/8" ou 2-3/4".
- **Latch Bolt (Lingueta):** Biselado que recolhe ao girar a maçaneta.
- **Deadbolt (Tranca de Segurança):** Lingueta maciça retangular acionada por chave.
- **Strike Plate (Testa da Fechadura):** Placa metálica parafusada no jamb (batente) de madeira.

Técnicas de Ajuste e Correção de Sag:
1. Se a porta estiver caída (sagging) e raspando na parte superior/inferior do strike, substitua um dos parafusos curtos da dobradiça superior por um parafuso de 3" que alcance o stud da parede puxando o frame.
2. Se o latch não entrar no furo do strike plate, use uma lima metálica ou grosa para ajustar a abertura em milímetros.

Quiz de Fixação:
1. Quais são as duas medidas padrão de backset nos EUA? (a) 1" e 2" (b) 2-3/8" e 2-3/4" (c) 3" e 4" -> Resposta: (b)
2. Como corrigir uma porta caindo que raspa no strike plate? (a) Serrar a porta (b) Trocar parafuso da dobradiça por um de 3" (c) Colar fita adesiva -> Resposta: (b)

Erros Comuns:
- Forçar o parafuso do deadbolt desalinhado, travando o cilindro.
- Tentar abrir portas trancadas sem chave (atuação de chaveiro não autorizada).

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
