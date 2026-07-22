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
# Aula 08

## §F1 — Escopo

Objetivos de Aprendizagem:
- O1: Selecionar e posicionar caixas elétricas tipo "old work" (retrofit) na altura padrão americana, respeitando códigos de instalação.
- O2: Varredura com scanner de parede para verificar ausência de obstruções internas (studs, tubulação, fiação) antes do corte.
- O3: Executar corte preciso no drywall com jab saw e fixar a caixa old work firme pelas abas de travamento, garantindo alinhamento.

Skills e Temas:
- Centrais: Varredura com scanner, marcação de caixas, corte com jab saw, fixação de caixa old work.
- Adjacentes: Nivelamento da caixa com nível de bolso, limpeza de bordas de gesso.
- Awareness: Distinção entre instalação física da caixa (permitida) e fiação energizada (não permitida nesta fase).

O que NÃO Ensinar:
- Passagem de fios elétricos energizados dentro da caixa (foco é 100 % corte mecânico).
- Abertura de rasgos extensos em estrutura ou conduítes comerciais.

Flags de Risco (Legal/Segurança):
- Risco de perfuração acidental de fiação/tubulação oculta — exige varredura rigorosa com scanner antes de cortar.

## §F2 — Desenho

Modelo Mental:
"Instalar uma caixa elétrica old work é como cirurgia vascular: recorta-se a pele (drywall) com precisão cirúrgica sem tocar em nervos e vasos (fios e canos)."

Blocos da Teoria:
1. Anatomia da Caixa Old Work: Abas de travamento (crows feet/swing ears), volume em polegadas cúbicas e knockout plugs.
2. Padrões de Altura e Posição: 12" do piso para tomadas, 48" para switches, posicionamento em relação aos studs.
3. Mapeamento Cego de Parede: Scanner de parede (stud/metal/AC wire) e uso tátil da jab saw.

Plano Detalhado da Prática (Lab Presencial - Corte e Fixação de Caixa):
- Operador A (Mapeamento): Escaneia a área do módulo, localiza studs e fiação virtual e traça o contorno do gabarito da caixa.
- Operador B (Corte): Insere a jab saw no drywall e realiza o corte preciso nos 4 lados com bordas limpas.
- Operador C (Fixação & App): Passa o cabo didático pela caixa, insere a caixa old work no furo, aperta os parafusos de travamento até fixar e verifica alinhamento com nível de bolso.

Arco Emocional:
Tensão antes de dar o primeiro golpe de jab saw no drywall -> Alívio com o corte limpo -> Empolgação ao ver a caixa travada perfeitamente.

## §F3 — Conteúdo

Texto que Ensina:
A instalação de uma caixa elétrica tipo **Old Work** (ou retrofit) é necessária ao adicionar novos pontos de interruptor ou tomada em uma parede de drywall já existente. 

Regras de Varredura e Marcação:
1. **Varredura de Segurança com Scanner:** Antes de furar, escaneie a área para garantir que não há fiação viva, tubos de água ou studs de madeira no local exato do corte.
2. **Posicionamento e Nível:** Utilize o nível de bolso para traçar o contorno do gabarito da caixa a 12" do piso (tomada) ou 48" (interruptor).

Corte e Trava Mecânica:
Faça o corte preciso utilizando a **Jab Saw** (serra manual para drywall). Encaixe a caixa no furo. As caixas Old Work possuem travas plásticas ou metálicas (*swing ears / flip clamps*) que giram e pressionam o verso do drywall conforme você aperta os parafusos frontais, fixando a caixa firmemente.

Quiz de Fixação:
1. Qual ferramenta é usada para cortar o retalho exato da caixa old work no drywall? (a) Serra miter (b) Jab saw (c) Alicate -> Resposta: (b)
2. Como a caixa old work se fixa na parede sem stud? (a) Com cola (b) Com abas de travamento (swing ears) que prensam o drywall (c) Pregos longos -> Resposta: (b)

Erros Comuns:
- Cortar o drywall maior que o gabarito, fazendo a caixa afundar.
- Cortar sem escanear a parede antes, arriscando atingir fiação oculta.

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
