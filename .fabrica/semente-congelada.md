# SEMENTE — handyman-v2

Status: RASCUNHO — congela no GATE-0 | Criado: 2026-07-08

## Identidade do curso

| Campo | Valor |
|---|---|
| Nome | Handyman v2 |
| Público-alvo | Adultos que querem aprender serviços residenciais de handyman para atuar com segurança, acabamento profissional e clareza de escopo no mercado americano. |
| Promessa (1 frase: o que o aluno vira/consegue ao final) | Ao final, o aluno consegue executar e documentar serviços residenciais básicos de handyman com método, segurança, qualidade visível e limites profissionais claros. |
| Nº de aulas | 17 |
| Idiomas | Fonte autoral em PT-BR; entrega final em PT-BR, espanhol e inglês US. |
| Formato de prática (presencial/Lab, projeto em casa, só digital…) | Lab presencial de 120 min por aula, usando módulos de parede, bancada, fixtures residenciais e checklists de segurança, acabamento e documentação. |
| Restrições duras (legais, físicas, de plataforma) | Não ensinar execução elétrica 120V, plumbing regulado, HVAC técnico/licenciado ou qualquer procedimento fora do escopo legal/seguro de handyman; teoria sempre antes do Lab; prática precisa caber em Lab físico de 120 min. |
| Arquivo de diretrizes do curso | `CHECKS.md` |

## Aulas

> **Como preencher cada aula:** 
> Propositalmente simples (1 parágrafo para Teoria e 1 para Prática por aula). 
> Profundidade prematura nesta fase é a principal fonte de retrabalho. 
> O aprofundamento de escopo, objetivos e componentes é feito depois nas fases F1 e F2 dentro de `aulas/aula-NN.md`.

### Aula 00
- **Teoria:** Como o curso funciona: app, Guilda, ranks, loop teoria → Lab → missão, ética profissional. Estratégia pedagógica para o sistema imperial: internalização sem conversão (associação de medidas a referências físicas e proporções de componentes padrão da construção americana, como espessura de drywall e largura de studs, sem tradução para o sistema métrico) e anatomia básica da parede americana. Instala a identidade central: o aluno está entrando num ofício, não fazendo bicos soltos.
- **Prática:** Missão em casa, totalmente guiada pelo app e sem intervenção na estrutura: o aluno usa fita métrica e celular para medir portas, janelas, rodapés, altura de tomadas/switches, largura de trims e trechos simples de parede em polegadas, seguindo prompts passo a passo. Também observa e fotografa detalhes estruturais visíveis, como drywall, baseboard, casing, quinas, juntas, possíveis studs sugeridos por tomadas/switches, diferenças entre paredes internas e externas, sinais de reparo antigo, textura e pintura. O registro acontece dentro do app, com campos guiados, fotos e checkpoints de observação; não há entrega física ou material externo.
- Depende de:

### Aula 01
- **Teoria:** Anatomia do frame residencial americano e leitura de uma parede antes do acabamento: top/bottom plate, studs, espaçamento comum, esquadro, prumo, cut list, drywall 1/2", parafuso correto, dimple e diferença entre montar um mock e intervir em estrutura real. A aula também apresenta segurança básica de corte/parafusadeira, sequência de montagem e critérios visuais de uma base pronta para receber serviços futuros.
- **Prática:** Construção de um módulo de parede 24" x 24": conferir cut list, medir e cortar madeira, esquadrejar o frame, parafusar as peças, marcar posição dos studs e fixar uma placa de drywall. A prática termina com inspeção de alinhamento, firmeza, parafusos corretamente assentados e identificação das partes da parede.
- Depende de: Aula 00

### Aula 02
- **Teoria:** Fixação em parede como decisão de carga, substrato e risco: passo a passo das técnicas de ancoragem (seleção do tipo de bucha conforme peso e material da parede, pré-furo correto, controle de torque e alinhamento). Como localizar studs (estratégias físicas e eletrônicas), fixação direta em studs (lag screws) vs. drywall oco usando buchas expansivas e toggle bolts (como Snaptoggle para suportes de TV e cargas pesadas). Limites de peso, alavanca, carga dinâmica e comunicação ética com o cliente.
- **Prática:** Uso de stud finder, fita, nível e marcação para instalar um suporte de TV articulado ou prateleira no módulo: um lado fixado diretamente em stud e o outro com drywall anchor adequado (inclusive buchas de alta carga/toggle bolts). O aluno compara tipos comuns de anchors, faz pré-furo, aperta sem esmagar o drywall, verifica nivelamento e aprende a explicar limite de carga ao cliente.
- Depende de: Aula 01

### Aula 03
- **Teoria:** Drywall repair como leitura do dano antes da massa: tipos de furo, rasgo, amassado, dano por anchor, dano por impacto, quando usar spackle, joint compound, mesh patch ou patch com suporte, e por que camadas finas, feathering, lixamento e luz rasante definem o resultado. Também apresenta limites como umidade ativa, mofo, parede mole, pintura com chumbo e danos que pedem outro profissional.
- **Prática:** Reparos de drywall no mesmo módulo: remover o suporte/prateleira da Aula 02, corrigir rasgos dos anchors, reparar amassados, cobrir furo pequeno e tratar um dano maior provocado no painel. O aluno aplica patch quando necessário, usa joint compound em camadas finas, feathering, lixamento controlado e checagem com luz lateral para acabamento.
- Depende de: Aula 02

### Aula 04
- **Teoria:** Acabamento de parede como controle de superfície, textura e pintura: preparação, limpeza de pó, primer, diferença entre touch-up e repintura maior, textura Orange Peel/Knockdown em nível introdutório, sheen, corte com pincel, rolo, wet edge e limites de color match. A aula mostra que um reparo tecnicamente correto ainda pode falhar visualmente se textura, brilho e transição não forem tratados.
- **Prática:** Preparação final da parede reparada em dinâmica de trio com divisão do painel em zonas e rodízio de papéis (Executor, Suporte/Soprador Térmico e Auditor de Acabamento): revisão dos pontos altos/baixos, limpeza de pó, primer localizado, reprodução de textura simples compatível e pintura de acabamento. O trio treina proteção de área, corte com pincel, rolo, tempo de secagem acelerado no lab, retoques e comparação visual entre reparo e parede existente.
- Depende de: Aula 03

### Aula 05
- **Teoria:** Finish carpentry básica aplicada a trim: função estética e funcional de baseboard, casing e quarter round, leitura de cantos, medição, miter simples, fixação com prego, escolha de filler, diferença entre caulk pintável e silicone, controle de linha, sombra e excesso. Também cobre sinais de parada, como umidade ativa, mofo, drywall podre, piso solto ou necessidade de reparo estrutural.
- **Prática:** Instalação de baseboard/trim no módulo: medir, cortar, testar encaixe, fixar com nail gun ou método manual equivalente, afundar pregos, aplicar wood filler, caulk nas juntas e linha superior, lixar leve e pintar. O foco é acabamento limpo em cantos, controle de excesso de caulk e entrega com aparência profissional.
- Depende de: Aula 04

### Aula 06
- **Teoria:** Porta como sistema mecânico e fechadura como componente: partes da porta, jamb, latch, strike plate, backset, bore, lockset, knob/lever, deadbolt. Diagnóstico e passo a passo detalhado para ajuste de portas desalinhadas ou raspando (uso de parafusos longos na dobradiça para puxar o frame, shims de papelão/madeira atrás da folha da dobradiça, e ajuste mecânico do strike plate). Diagnóstico de folgas e sintomas comuns de problema, segurança, privacidade e limites de escopo.
- **Prática:** Prática focada apenas em fechadura/lockset: identificar as peças do conjunto, montar a fechadura na bancada, instalar em uma porta ou mock-up preparado, alinhar latch e strike plate, testar abertura/fechamento, corrigir folgas simples e desmontar o conjunto com organização das peças. A prática não executa ajustes estruturais de porta; esses assuntos ficam na teoria para diagnóstico e limite de escopo.
- Depende de: Aula 00

### Aula 07
- **Teoria:** Cabinet hardware como ajuste mecânico fino: anatomia de gabinete, porta, face frame, dobradiça europeia, eixos de ajuste, gaps visuais, alinhamento, drawer slides, parafusos frouxos, furo espanado e diferença entre ajuste, troca de ferragem e marcenaria pesada. A aula conecta percepção do cliente com pequenos desalinhamentos do dia a dia em cozinhas, banheiros e lavanderias.
- **Prática:** Estação mock seca de cabinet hardware, com rotação "um executa, outro inspeciona pelo app, depois troca": cada aluno ajusta uma porta de armário com dobradiça europeia nos eixos de altura, lateralidade e profundidade, corrige gaps visuais, testa abertura/fechamento. Utiliza gabaritos (jigs) para marcação e furação de novos puxadores, e depois remove, alinha e reinstala uma gaveta em trilhos/corrediças de treino. A estação simula problemas reais como porta caída, gap desigual e drawer slide desalinhado. O foco é diagnóstico mecânico e pequenos ajustes sem marcenaria pesada.
- Depende de: Aula 00

### Aula 08
- **Teoria:** Caixas elétricas como interface física entre parede e dispositivo: tipos de electrical box, old work/new work, faceplate, altura, alinhamento, recorte limpo em drywall, blind cut. Técnicas de detecção de obstruções internas (studs, tubos, fiação) usando scanners eletrônicos de parede antes de efetuar cortes. Risco de infraestrutura escondida e diferença entre instalação mecânica de uma caixa em mock e trabalho elétrico real. A teoria também reforça que abrir parede para caixa não autoriza tocar fiação fixa residencial.
- **Prática:** Instalação mecânica de caixa no módulo de parede construído pelo aluno: varrer com scanner de parede, marcar a posição no drywall, conferir medidas e alinhamento, abrir o recorte com cuidado usando serra de gesso (jab saw), encaixar a caixa "old work" no drywall, fixar corretamente e revisar acabamento ao redor da abertura. A aula não instala fiação ou energização; o foco é furo no drywall e caixa bem posicionada.
- Depende de: Aula 05

### Aula 09
- **Teoria:** Switches residenciais como peças, linguagem e lógica visual: single-pole, 3-way, faceplate, strap, screws, ground, line/load em nível de vocabulário. Processo de substituição segura (like-for-like replacement) e identificação da fiação (Hot, Neutral, Ground). Noções de interruptores inteligentes (Smart Switches) e exigência do fio Neutro. Orientação física e erros comuns de montagem. A aula ensina a reconhecer e organizar componentes, entender a diferença entre aparência do dispositivo e circuito real, e manter a fronteira entre bancada didática desenergizada e serviço elétrico licenciado.
- **Prática:** Prática focada em switches em bancada de teste mock, preparada para montagem e desmontagem sem energização: identificar os condutores, desmontar e remontar switch single-pole (como substituição direta), posicionar fios cenográficos ou de treino nos terminais corretos usando loops nos parafusos (side wiring) ou conectores, organizar parafusos e faceplates, e repetir a sequência até ganhar fluidez manual. Uso de testador de tensão sem contato (NCVT) para simular o protocolo de desligamento e checagem de energia. O app guia os checkpoints; a atividade não energiza componentes e não usa o frame da Aula 08.
- Depende de: Aula 00

### Aula 10
- **Teoria:** Tomadas/receptacles como componentes de uso cotidiano e ponto de risco: faceplate, yoke/strap, terminal screws, ground, orientação. Identificação de tomadas GFCI (Ground Fault Circuit Interrupter) e diferenciação dos terminais LINE e LOAD. Substituição segura like-for-like, identificação dos fios e importância de conexões firmes (side-wire vs. push-in) e alinhamento do yoke. A teoria amplia para triagem e comunicação de escopo, mas a prática permanece em bancada mock desenergizada.
- **Prática:** Prática focada em tomadas/receptacles em bancada de teste mock, preparada para montagem e desmontagem sem energização: identificar faceplate, caixa, terminais, screws, ground e orientação correta; realizar a substituição segura simulada de uma tomada convencional e de uma tomada GFCI; posicionar fios cenográficos nos terminais correspondentes; alinhar o conjunto e repetir a sequência. Uso simulado do NCVT para garantir segurança. O app conduz os checkpoints; não há relatório físico e a atividade não energiza componentes nem usa o frame da Aula 08.
- Depende de: Aula 00

### Aula 11
- **Teoria:** Integração e testes de circuito didático desenergizado. Técnicas de verificação de integridade e segurança de circuito usando o multímetro (escala de continuidade e resistência): verificação de curto-circuito (Fase-Neutro/Terra), verificação lógica do acionamento do switch loop e teste de integridade do aterramento (Ground path). O papel do handyman como resolvedor de problemas de conexões soltas e a fronteira legal em relação a novas instalações.
- **Prática:** Montagem do sistema funcional no módulo de parede em dinâmica de trio com papéis integrados (Montador de Dispositivos, Conector de Fiação Didática e Auditor de Multímetro/App): instalar tomada, switch e lâmpada no frame e realizar as conexões da fiação didática. A validação e o teste de funcionamento são executados 100% de forma segura pelo trio por meio de multímetro na escala de continuidade e resistência, seguindo checklist do app para validar o acionamento do switch loop, polaridade e descartar riscos de curto-circuito.
- Depende de: Aula 08, Aula 09, Aula 10

### Aula 12
- **Teoria:** Fixtures de teto como conjunto mecânico e elétrico-adjacente: anatomia de ventilador, bracket, canopy, motor, pás, kit de luz, soquetes, controle/pull chain, balanceamento, peso, caixa adequada para fan-rated support e leitura de manual. A aula mostra troca/instalação como sequência de peças, suporte e teste, mas mantém limites sobre fiação real, caixa inadequada e serviço residencial energizado.
- **Prática:** Prática focada em instalação/troca de ventilador e luz de teto em mock-up preparado na altura de trabalho confortável: o aluno tira o ventilador da caixa, confere peças, lê o manual, monta bracket, canopy, motor, pás, soquetes/luz, lâmpadas, controle/pull chain e fixações, remove o equipamento anterior do mock-up quando houver e coloca o novo conjunto no teto de treino. A prática inclui organização de peças, sequência de montagem, encaixes, alinhamento, fixação, checagem de movimento e entendimento do funcionamento básico do equipamento, sem tratar a atividade como instalação residencial real.
- Depende de: Aula 00

### Aula 13
- **Teoria:** Shower no padrão americano como conjunto de peças acessíveis e limites escondidos: shower arm, showerhead, filter, handheld, hose, diverter externo, washer/gasket, screen, PTFE tape, handle, escutcheon, cartridge e tub spout/diverter. Sintomas comuns como baixa vazão, gotejamento e vazamento. Técnicas de remoção mecânica e aplicação prática de silicone sanitário em áreas úmidas (recaulking) para prevenir infiltrações. Diferença entre a troca de acessórios acessíveis e intervenção em válvula/tubulação regulada.
- **Prática:** Prática em dupla na mesma estação mock de chuveiro no padrão residencial dos EUA, sem água real, com rotação "um executa, outro inspeciona pelo app, depois troca": cada aluno remove e reinstala um showerhead comum, monta um showerhead com filtro ou handheld com diverter/hose, confere gaskets e aplica fita PTFE no sentido horário de forma correta. Adicionalmente, executa a prática de remoção de silicone antigo com raspadores e aplicação de caulk de silicone 100% à prova d'água em junta cenográfica usando espátula ou o dedo com água e sabão.
- Depende de: Aula 00

### Aula 14
- **Teoria:** Vaso sanitário como sistema de tanque, bowl, fixação e vedação: fill valve, flush valve, flapper, chain, handle, overflow, supply line, shutoff, tank bolts, wax ring, flange, closet bolts, assento e sinais de instabilidade ou vazamento. A teoria ensina anatomia e diagnóstico de sintomas comuns, deixando claro onde há ajuste simples, peça acessível (troca de mecanismo interno de tanque, flapper ou assento), risco de vazamento oculto ou necessidade de plumber.
- **Prática:** Estação mock sem água real focada em vaso sanitário: desmontar e remontar a anatomia básica do tanque e do bowl, identificar fill valve, flush valve, flapper, chain, handle, overflow tube, tank bolts, supply line, shutoff valve, wax ring, flange, closet bolts e assento. O aluno trabalha a estrutura do problema por inspeção seca: simula substituição de flapper gasto, ajuste de corrente, troca de fill valve desalinhada, aperto de assento frouxo, posicionamento do anel de cera (wax ring) e nivelamento do vaso, registrando no app o diagnóstico e limites para encanador.
- Depende de: Aula 00

### Aula 15
- **Teoria:** Pia de cozinha/banheiro como anatomia de fluxo e vedação acessível: faucet, aerator, supply lines, shutoff valves, drain assembly, pop-up drain, basket strainer, tailpiece, P-trap, slip nuts, washers e pontos típicos de vazamento. Técnicas de vedação de ralos com Plumber's Putty e rosqueamento manual de conexões plásticas sem ferramentas para evitar rachaduras. A aula amplia para diagnóstico visual, sequência de montagem e linguagem de escopo, separando o reconhecimento em mock de intervenções em tubulação regulada.
- **Prática:** Estação mock sem água real focada em pia de cozinha/banheiro: desmontar e remontar a anatomia de torneira, supply lines, shutoff valves, drain assembly, pop-up drain ou basket strainer, tailpiece, P-trap, slip nuts, washers e conexões acessíveis. O aluno realiza a vedação de ralo com Plumber's Putty e faz a montagem manual do P-trap com arruelas novas. Identifica por inspeção seca problemas como washer faltando, porca desalinhada, P-trap invertido, supply line torcida, aerator sujo e ponto provável de vazamento, registrando no app.
- Depende de: Aula 00

### Aula 16
- **Teoria:** HVAC residencial na camada permitida de manutenção e triagem: retorno de ar, filtro, MERV, seta de airflow, periodicidade de troca, grelha/return vent, termostato, bateria, breaker/disconnect e fusível. Diagnóstico de falhas comuns em termostatos inteligentes (códigos de erro básicos, alimentação e baterias). A aula mostra como filtro sujo afeta o sistema, mas deixa compressor, refrigerante, furnace, blower, capacitor e ductwork técnico fora do escopo.
- **Prática:** Estação mock de HVAC sem sistema energizado, focada em manutenção básica e anatomia do problema: localizar return vent/filter slot, ler tamanho e direção do airflow no filtro, remover e instalar filtros de tamanhos diferentes, comparar filtro limpo/sujo, MERV e encaixe correto, limpar visualmente grelha/return vent e registrar no app sinais de restrição de ar. Em bancada de diagnóstico, o aluno também identifica termostato, bateria do termostato, breaker/disconnect e fusível como possíveis pontos de triagem, usando peças mock/desenergizadas; não troca fusível em sistema real, não abre equipamento energizado, não mexe em capacitor, refrigerante, compressor, furnace, blower, ductwork técnico ou qualquer reparo interno.
- Depende de:

## Aprovação (GATE-0)

- [ ] Stakeholder aprovou a semente
- [ ] Restrições duras conferidas (nada nas aulas viola)
- [ ] Cadeia de dependências entre aulas validada
- Data do congelamento: ____ (mudanças posteriores reabrem a aula desde a F1 + registro no Log)
