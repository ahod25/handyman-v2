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
# Aula 01

## §F1 — Escopo

Objetivos de Aprendizagem:
- O1: Ler e interpretar a estrutura física de uma parede (top/bottom plate, studs a 16" OC, drywall 1/2").
- O2: Utilizar trena, esquadro e parafusadeira para construir um módulo de parede 24"x24" com precisão, aplicando boas práticas de corte e fixação.
- O3: Fixar a placa de drywall assegurando paralelismo e torque adequado dos parafusos, evitando rasgos.

Skills e Temas:
- Centrais: Montagem de frame de madeira 2x4, esquadro, corte e parafusamento de drywall 1/2".
- Adjacentes: Medição 16" OC, uso de prumo, segurança ao manusear parafusadeira.
- Awareness: Diferenças entre drywall padrão, moisture-resistant e fire-rated.

O que NÃO Ensinar:
- Instalação em paredes reais de clientes ou corte de madeira com serra circular sem bancada supervisionada.
- Tratamento de juntas/massa (assunto das Aulas 03 e 04).

Flags de Risco (Legal/Segurança):
- Obrigatório uso de óculos de proteção e luvas ao manusear madeira e parafusadeira; risco de perfuração acidental de conduítes internos em cenários reais.

## §F2 — Desenho

Modelo Mental:
"A parede de drywall americana é um esqueleto de madeira revestido; entender o esqueleto é o segredo para qualquer instalação perfeita."

Blocos da Teoria:
1. Anatomia do Frame 2x4: Top plate, bottom plate, studs e o padrão 16" On Center (OC).
2. Leitura e Preparação do Material: Cut list, seleção de madeira, verificação de empenamento.
3. Fixação de Drywall 1/2": Parafusos para drywall, profundidade do dimple e preservação do papel.

Plano Detalhado da Prática (Lab Presencial - Módulo 24"x24"):
- Operador A (Executor): Mede e corta as peças de madeira conforme cut list de bancada.
- Operador B (Suporte): Segura no esquadro e posiciona o frame 2x4 enquanto A parafusar os studs.
- Operador C (Auditor/App): Valida alinhamento, marca o espaçamento 16" OC no app, autoriza fixação do drywall e verifica se os parafusos fizeram o dimple sem rasgar o papel.

Arco Emocional:
Receio inicial com ferramentas -> Empolgação ao ver o frame 24"x24" rígido e esquadrejado -> Orgulho da primeira parede construída.

## §F3 — Conteúdo

Texto que Ensina:
A parede de drywall americana é um esqueleto de madeira 2x4 revestido com gesso. Para instalar, reparar ou ancorar qualquer coisa com segurança, você precisa entender como essa estrutura é montada.

Montagem do Frame (2x4 Studs):
1. **Cut List:** Cortar a madeira com precisão. O bottom plate e top plate delimitam o comprimento da parede.
2. **Esquadro e Prumo:** Garantir que o retângulo do frame tenha ângulos exatos de 90° e esteja alinhado verticalmente.
3. **Marcação 16" OC:** Medir a partir do centro do primeiro stud para que as bordas do drywall de 48" de largura sempre coincidam com o centro de um stud.

Fixação Perfeita do Drywall:
O segredo da fixação do drywall está na profundidade do parafuso. O parafuso de drywall (1-1/4" bugle head) deve criar um afundamento suave na superfície do gesso — conhecido como **Dimple**. 
- Se o parafuso ficar saliente, ele rasga a espátula de massa.
- Se o parafuso afundar demais e romper o papel protetor do drywall, o poder de fixação cai em 80%.

Exemplos e Cenários Reais:
- *Cenário:* Você está parafusando a placa de gesso e a cabeça do parafuso rasga o papel superficial.
- *Solução:* Deixe aquele parafuso ali (não remova), insira um novo parafuso a 2" de distância criando o dimple correto.

Quiz de Fixação:
1. O que acontece se o parafuso rasgar o papel do drywall? (a) Fica mais forte (b) Perde a capacidade de retenção (c) Nada -> Resposta: (b)
2. O que é o 'dimple'? (a) Um furo no gesso (b) O afundamento suave do parafuso sem rasgar o papel (c) Uma marca de mofo -> Resposta: (b)

Erros Comuns:
- Parafusar nas bordas do drywall sem dar a margem de segurança de 3/8" (causa quebra da quina).
- Montar o frame fora do esquadro, fazendo a placa de gesso ficar desalinhada.

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
