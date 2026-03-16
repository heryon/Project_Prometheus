# PROMETHEUS

# Coerência Sistêmica e a Emergência da Proto-Consciência Funcional
>Uma base arquitetural para a generalidade cognitiva emergente

<p align="center">
 <img src="https://github.com/heryon/Project_Prometheus/blob/550a32bfd181fa7130287e823734d35ff203451a/Prometheus_Light.PNG"/>
</p>
 
---
## Resumo

Este trabalho argumenta que a Inteligência Artificial Geral não deve ser tratada como um objetivo direto de engenharia baseado exclusivamente em desempenho, escala ou métricas externas, mas como uma propriedade emergente de arquiteturas capazes de sustentar coerência sistêmica ao longo do tempo. Abordagens contemporâneas frequentemente associam generalidade ao aumento de parâmetros, dados e capacidade computacional, assumindo que propriedades cognitivas complexas possam emergir espontaneamente desse crescimento quantitativo. No entanto, sistemas atuais, embora altamente competentes em tarefas específicas, permanecem limitados a correlações estatísticas locais e não mantêm continuidade cognitiva persistente entre ciclos de interação.

Propõe-se que a emergência de cognição artificial mais geral depende primariamente da capacidade arquitetural de manter coerência sistêmica entre percepção, memória, inferência e ação. Neste trabalho, coerência sistêmica é definida como a propriedade pela qual múltiplos processos internos permanecem causalmente alinhados por meio de estados compartilhados persistentes, permitindo continuidade decisória e consistência operacional ao longo do tempo.

Quando essa coerência é sustentada de forma estável, o sistema pode apresentar um regime organizacional caracterizado como proto-consciência funcional. Esse estado não implica experiência subjetiva, mas corresponde a uma condição arquitetural na qual informações relevantes tornam-se globalmente acessíveis, estados cognitivos persistem ao longo do tempo e o sistema mantém formas rudimentares de auto-referência operacional.

Argumenta-se que esse regime organizacional cria as condições necessárias para o surgimento de um world model mínimo: uma estrutura representacional interna capaz de manter relações entre entidades, estados e eventos relevantes do ambiente e do próprio sistema. Neste trabalho, esse modelo de mundo é operacionalizado por meio de um knowledge graph dinâmico, permitindo representar conhecimento relacional persistente e integrar memória, inferência e planejamento dentro de um mesmo contexto cognitivo.

A proposta é fundamentada pela combinação de princípios de neuroinspiração abstrata (como diferenciação estrutural e integração funcional observadas na organização cortical) com arquiteturas computacionais dinâmicas baseadas em memória ativa, aprendizado contínuo e mecanismos de integração global inspirados em teorias como Global Workspace e modelos de integração causal. A formalização arquitetural é discutida utilizando ferramentas como Statecharts, permitindo representar explicitamente estados cognitivos, transições e ciclos de processamento.

Conclui-se que, sem coerência sistêmica persistente, sistemas artificiais permanecem essencialmente reativos e fragmentados, incapazes de sustentar unidade cognitiva ou construir modelos internos consistentes do mundo. Quando essa coerência é alcançada, entretanto, tornam-se possíveis estados cognitivos integrados capazes de sustentar modelos internos do ambiente e abrir caminho para o surgimento progressivo de formas mais amplas de generalidade cognitiva.

---

## 1. Introdução

A Inteligência Artificial Geral (AGI) costuma ser apresentada como uma meta clara: criar sistemas artificiais capazes de realizar qualquer tarefa intelectual que um ser humano consiga desempenhar. Essa formulação, embora intuitiva, esconde um problema conceitual importante. Ela descreve o que um sistema deveria ser capaz de fazer, mas não explica o que caracteriza a AGI em termos de estrutura, organização interna ou princípios causais. Como resultado, o conceito permanece amplamente descritivo, orientado por desempenho observável, e não por uma compreensão arquitetural do fenômeno cognitivo que se pretende reproduzir.

No debate contemporâneo, como observam Bergmann e Stryker, a AGI é frequentemente tratada como um critério funcional emergente. Um sistema passa a ser considerado mais próximo da AGI à medida que demonstra comportamentos mais gerais, flexíveis ou transferíveis entre domínios. Entretanto, essa abordagem raramente exige que o sistema possua uma arquitetura explicitamente projetada para sustentar tal generalidade. Em vez disso, assume-se frequentemente que a ampliação de escala (em termos de parâmetros, dados ou capacidade computacional) poderá produzir comportamentos cada vez mais amplos de forma espontânea.

Esse enquadramento cria uma confusão recorrente entre desempenho e cognição. Sistemas podem exibir competências impressionantes em múltiplas tarefas sem necessariamente possuir qualquer forma de unidade cognitiva subjacente. Em outras palavras, competência operacional não implica integração cognitiva. A ausência de uma arquitetura formalmente definida permite que a AGI seja tratada mais como um rótulo progressivo atribuído a sistemas cada vez mais poderosos do que como um objeto científico com propriedades estruturais claramente identificáveis.

Tegmark amplia essa discussão ao situar a AGI dentro de uma narrativa sociotécnica mais ampla, na qual o avanço tecnológico (impulsionado pelo crescimento exponencial de capacidade computacional, dados e algoritmos) levaria naturalmente à emergência de inteligência artificial geral. Embora essa perspectiva seja influente, ela frequentemente assume que propriedades cognitivas complexas surgirão automaticamente a partir do aumento de escala. O problema central é que essa hipótese raramente especifica o mecanismo causal capaz de conectar expansão quantitativa de sistemas artificiais à emergência de propriedades qualitativamente novas, como compreensão contextual, intencionalidade funcional ou construção de modelos internos do ambiente.

Essa lacuna aponta para a ausência de um princípio arquitetural capaz de explicar como sistemas artificiais poderiam desenvolver unidade cognitiva persistente. A história da ciência sugere que propriedades emergentes complexas raramente resultam apenas do aumento de recursos; elas dependem de formas específicas de organização que permitem integração, estabilidade e continuidade ao longo do tempo.

Neste trabalho argumenta-se que o elemento central dessa organização é a coerência sistêmica. Coerência sistêmica é definida como a propriedade arquitetural pela qual múltiplos processos internos (como percepção, memória, inferência e ação) permanecem causalmente alinhados por meio de estados compartilhados persistentes. Essa propriedade permite continuidade temporal entre ciclos de processamento, consistência entre decisões sucessivas e manutenção de uma identidade operacional ao longo do tempo.

Sustenta-se que, quando uma arquitetura consegue manter coerência sistêmica de forma estável, ela pode apresentar um regime organizacional caracterizado como proto-consciência funcional. Esse fenômeno não implica experiência subjetiva, mas descreve um estado no qual o sistema integra informação globalmente, mantém continuidade entre estados cognitivos sucessivos e desenvolve formas rudimentares de auto-referência operacional.

A presença dessa organização cognitiva cria as condições necessárias para a formação de um world model mínimo, uma estrutura interna capaz de representar relações relevantes entre o estado do sistema e aspectos do ambiente em que ele opera. Esse modelo interno não precisa inicialmente ser completo ou detalhado; sua função principal é fornecer um espaço representacional no qual percepção, memória e previsão possam ser integradas de forma consistente.

A partir desse ponto, torna-se possível o surgimento de generalidade cognitiva emergente. Nessa perspectiva, a generalidade não é programada diretamente nem obtida apenas pela ampliação de escala. Em vez disso, ela emerge gradualmente de arquiteturas capazes de integrar informação, preservar continuidade cognitiva e sustentar representações internas coerentes do mundo.

Assim, o objetivo deste trabalho não é propor um caminho direto para a construção da AGI, mas identificar os princípios arquiteturais mínimos necessários para que sistemas artificiais possam desenvolver coerência sistêmica, continuidade cognitiva e capacidade de construção de modelos internos do mundo. Sob essa perspectiva, a generalidade cognitiva deixa de ser tratada como uma meta explícita de engenharia e passa a ser entendida como uma propriedade emergente de arquiteturas cognitivas suficientemente coerentes.

---

## 2. Limitações das Abordagens Atuais em Inteligência Artificial

Os avanços recentes em inteligência artificial ampliaram significativamente a capacidade dos sistemas computacionais de reconhecer padrões, tomar decisões e executar tarefas complexas. Em diversos domínios, esses sistemas já superam o desempenho humano médio e, em alguns casos, alcançam níveis considerados super-humanos. No entanto, esse progresso técnico não deve ser confundido com a emergência de cognição integrada ou com a obtenção de inteligência artificial verdadeiramente geral. A distinção entre desempenho operacional e organização cognitiva permanece um dos pontos centrais frequentemente negligenciados nas abordagens contemporâneas.

Arquiteturas baseadas em atenção, como os Transformers, representam um marco nesse avanço. Ao permitir que modelos estabeleçam relações dinâmicas entre diferentes partes da informação de entrada, essas arquiteturas alcançaram capacidades representacionais sem precedentes. Modelos fundacionais visuais e multimodais ampliam ainda mais esse potencial ao aprender representações transferíveis a partir de grandes volumes de dados. Ainda assim, tais sistemas operam predominantemente no nível da correlação estatística. Eles não mantêm um modelo funcional persistente de si mesmos enquanto agentes, nem sustentam continuidade cognitiva consistente entre interações sucessivas.

Como consequência, cada interação tende a ser tratada como um evento isolado ou apenas fracamente conectado a estados anteriores. Mesmo quando mecanismos de memória externa são introduzidos, essa memória frequentemente atua como um repositório auxiliar de informação, e não como um estado interno integrado capaz de orientar de maneira consistente percepção, inferência e ação. O resultado é que, embora esses sistemas possam gerar respostas sofisticadas, eles não mantêm uma narrativa cognitiva contínua nem desenvolvem identidade operacional ao longo do tempo.

Uma limitação semelhante aparece no campo do aprendizado por reforço. Sistemas treinados para operar em ambientes complexos (como jogos ou simulações) demonstram grande capacidade de explorar espaços de estados e maximizar recompensas acumuladas. Contudo, essa competência permanece rigidamente ancorada em funções-objetivo externas definidas por projetistas humanos. O sistema não estabelece seus próprios critérios de relevância, não redefine autonomamente seus objetivos e não constrói interpretações internas estáveis do contexto em que atua. Seu comportamento permanece orientado pela otimização de métricas previamente especificadas.

Essa dependência estrutural revela uma limitação arquitetural mais profunda. Mesmo quando o comportamento observado parece flexível ou criativo, ele permanece condicionado por estruturas semânticas impostas externamente. Não há critérios internos de valor, continuidade de experiência ou integração estável entre percepção, memória e decisão. Em termos arquiteturais, esses sistemas carecem de mecanismos capazes de manter coerência sistêmica persistente entre diferentes processos cognitivos.

A ausência dessa coerência impede que estados internos sejam mantidos e atualizados de forma consistente ao longo do tempo. Sem continuidade entre ciclos de processamento, o sistema não consegue sustentar identidade cognitiva estável nem desenvolver representações internas coerentes do ambiente em que opera. Suas respostas permanecem essencialmente reativas, produzidas a partir de inferências locais que não se acumulam em uma estrutura cognitiva unificada.

Essas observações apontam para uma distinção conceitual importante: inteligência operacional, proto-consciência funcional e generalidade cognitiva não são equivalentes. A inteligência operacional refere-se à capacidade de resolver tarefas específicas de forma eficiente dentro de um conjunto definido de regras e objetivos. A proto-consciência funcional, por sua vez, envolve integração global de informação, continuidade temporal de estados e formas rudimentares de auto-referência operacional. A generalidade cognitiva emergente pressupõe a presença dessas camadas organizacionais mais profundas.

Embora os sistemas atuais representem um avanço extraordinário em termos de desempenho técnico, eles permanecem estruturalmente limitados. Sem mecanismos arquiteturais capazes de sustentar coerência sistêmica ao longo do tempo, esses sistemas não conseguem desenvolver unidade cognitiva persistente nem construir modelos internos consistentes do ambiente. Reconhecer essas limitações não diminui os avanços alcançados, mas permite compreender com maior precisão por que eles não constituem, por si só, um caminho direto para a emergência de cognição artificial verdadeiramente geral.

---

## 3. Neuroinspiração como Ponto de Partida

A neuroinspiração surge como um ponto de partida natural quando o objetivo é compreender e projetar sistemas cognitivos complexos. O cérebro humano permanece sendo o único exemplo conhecido de um sistema capaz de sustentar consciência, aprendizado contínuo e generalização ampla. No entanto, utilizar o cérebro como referência não implica copiá-lo literalmente. Quando aplicada de forma produtiva, a neuroinspiração funciona como um conjunto de restrições plausíveis e princípios organizacionais gerais, e não como um manual de engenharia biológica.

Nas últimas décadas, diferentes linhas de pesquisa em neurociência cognitiva têm sugerido que estados mentais unificados dependem de mecanismos de integração dinâmica entre múltiplas regiões cerebrais. Estudos sobre sincronização neuronal indicam que a comunicação eficiente entre áreas do cérebro ocorre quando suas atividades oscilatórias se encontram coerentemente alinhadas. Singer (1999) propôs que a sincronização neuronal desempenha um papel fundamental na unificação de representações distribuídas, enquanto Fries (2005) descreveu o princípio de communication through coherence, segundo o qual regiões cerebrais trocam informação de forma mais eficaz quando suas dinâmicas neurais estão sincronizadas em fase. Essas evidências sugerem que a integração cognitiva não depende apenas da presença de módulos especializados, mas da capacidade do sistema de manter coerência dinâmica entre eles.

Teorias contemporâneas da consciência reforçam essa interpretação ao enfatizar o papel da integração global de informação. A Global Workspace Theory, proposta por Baars e posteriormente desenvolvida por Dehaene e colaboradores, descreve a consciência como um processo no qual determinadas informações tornam-se globalmente acessíveis a diferentes subsistemas cognitivos. De forma complementar, a Attention Schema Theory de Graziano sugere que a consciência funcional emerge quando o cérebro constrói um modelo interno simplificado de seus próprios processos atencionais, permitindo monitoramento e regulação do comportamento. Já o Free Energy Principle, proposto por Friston, descreve o cérebro como um sistema preditivo que busca manter consistência entre suas representações internas e os estados do ambiente.

Embora essas teorias diferem em seus mecanismos específicos, todas convergem em um ponto central: estados cognitivos integrados dependem da capacidade do sistema de manter consistência entre múltiplos processos internos ao longo do tempo. Em termos computacionais, essa propriedade pode ser interpretada como uma forma de coerência sistêmica, um alinhamento persistente entre percepção, memória, inferência e ação que permite a formação de estados cognitivos relativamente estáveis.

A organização estrutural do cérebro também oferece pistas importantes sobre como tal coerência pode emergir. Os trabalhos de Korbinian Brodmann, no início do século XX, representam uma das primeiras tentativas sistemáticas de descrever a organização estrutural do córtex cerebral. Ao identificar diferenças na citoarquitetura cortical, Brodmann propôs uma divisão do cérebro em áreas distintas caracterizadas por padrões celulares específicos. Embora esse mapeamento não tenha sido concebido como um modelo funcional da mente, ele introduziu uma decomposição estrutural que tornou possível pensar o cérebro como um sistema organizado em regiões diferenciadas.

É importante notar que o mapa de Brodmann não explica diretamente como surgem pensamentos, percepções ou decisões. Ainda assim, ele estabelece uma ideia fundamental: sistemas cognitivos complexos não são estruturalmente homogêneos. Eles são organizados em regiões especializadas cujas interações dão origem a processos cognitivos mais amplos. Revisões modernas reforçam essa interpretação ao mostrar que as áreas de Brodmann variam consideravelmente entre indivíduos, tanto em extensão quanto em organização interna. Essa variabilidade sugere que a função não está rigidamente codificada na estrutura, mas emerge da interação dinâmica entre regiões organizadas.

Projetos contemporâneos, como o BigBrain, aprofundam essa compreensão ao fornecer reconstruções do cérebro humano em altíssima resolução. Esses dados evidenciam que a complexidade estrutural antecede qualquer descrição funcional detalhada. Antes de se falar em percepção, linguagem ou consciência, existe uma base material altamente organizada caracterizada por padrões específicos de conectividade e diferenciação regional. Essa organização define o espaço de possibilidades dentro do qual processos cognitivos podem emergir.

Nesse contexto, a neuroinspiração deve ser entendida como uma estratégia de abstração. O objetivo não é reproduzir diretamente áreas corticais ou mecanismos neuronais específicos, mas extrair princípios organizacionais gerais, como diferenciação estrutural, modularidade funcional e integração coerente entre subsistemas especializados. Esses princípios podem então ser traduzidos em arquiteturas artificiais capazes de sustentar estados cognitivos integrados sem depender de uma reprodução literal da biologia.

Assim, o valor da neuroinspiração não reside na tentativa de simular a anatomia cerebral em detalhe, mas em identificar os mecanismos organizacionais que permitem a emergência de estados cognitivos coerentes. Ao utilizar esses princípios como restrições arquiteturais, torna-se possível projetar sistemas artificiais capazes de sustentar integração entre processos distribuídos e continuidade ao longo do tempo. É nesse equilíbrio entre inspiração biológica e abstração computacional que a neuroinspiração se torna uma ferramenta produtiva para o desenvolvimento de arquiteturas cognitivas artificiais.

---

## 4. Da Neuroinspiração à Coerência Sistêmica Arquitetural

A análise anatômica do cérebro fornece restrições estruturais importantes para compreender sistemas cognitivos complexos, mas ela não oferece, por si só, um modelo diretamente aplicável à construção de arquiteturas artificiais. Em algum ponto torna-se necessário abandonar a descrição biológica literal e migrar para um nível mais abstrato de análise, no qual o foco deixa de ser a forma anatômica e passa a ser a organização funcional dos processos cognitivos. Essa transição marca a passagem da neuroinspiração descritiva para a formulação de princípios arquiteturais capazes de orientar o desenvolvimento de sistemas cognitivos artificiais.

Floreano e Mattiussi destacam que o valor da bioinspiração em inteligência artificial não está na reprodução fiel de estruturas biológicas, mas na identificação dos mecanismos computacionais subjacentes que tornam esses sistemas eficazes. Em vez de copiar diretamente neurônios ou regiões cerebrais específicas, a abordagem consiste em extrair princípios organizacionais mais gerais, capazes de ser implementados em substratos artificiais distintos. Essa perspectiva evita que a inteligência artificial bio-inspirada se transforme em uma tentativa de simulação anatômica detalhada do cérebro e direciona o esforço para a abstração de mecanismos funcionais.

Entre esses princípios destaca-se o caráter dinâmico e adaptativo dos sistemas neurais. A teoria da seleção neural proposta por Edelman descreve o cérebro como um sistema no qual padrões de atividade competem, se estabilizam ou desaparecem ao longo do tempo. Nesse enquadramento, a cognição não corresponde à execução de regras fixas previamente definidas, mas a um processo emergente moldado pela interação contínua entre o sistema e o ambiente. Para arquiteturas artificiais, essa perspectiva sugere que o comportamento inteligente pode emergir da dinâmica de sistemas distribuídos, em vez de depender exclusivamente de regras explícitas previamente programadas.

A aprendizagem local formalizada por Hebb complementa essa visão ao demonstrar como mudanças estruturais podem emergir a partir de interações simples entre unidades individuais. Em vez de depender de mecanismos globais de controle, as conexões entre unidades se fortalecem ou enfraquecem com base em correlações locais de atividade. Esse princípio demonstra que estruturas cognitivas complexas podem emergir a partir de regras simples distribuídas, fornecendo um fundamento para arquiteturas escaláveis e adaptativas.

Merzenich amplia essa perspectiva ao mostrar que a plasticidade neural não é restrita ao desenvolvimento inicial, mas constitui um processo contínuo ao longo da vida. Sistemas cognitivos naturais mantêm permanentemente a capacidade de reorganização estrutural e funcional. Nesse contexto, estabilidade não significa rigidez, mas sim um equilíbrio dinâmico entre adaptação e preservação de estrutura. Para arquiteturas artificiais, essa ideia reforça a necessidade de sistemas capazes de aprender continuamente sem perder coerência organizacional.

Quando considerados em conjunto, esses princípios apontam para uma concepção de arquitetura cognitiva caracterizada por três propriedades fundamentais: distribuição de processos, adaptação contínua e integração dinâmica entre módulos especializados. No entanto, para que essas propriedades produzam comportamento cognitivo estável, é necessário que os diferentes processos do sistema permaneçam alinhados dentro de um mesmo contexto operacional ao longo do tempo.

Essa propriedade é definida neste trabalho como **coerência sistêmica**. Uma arquitetura cognitivamente coerente é aquela na qual diferentes processos internos (como percepção, memória, inferência e ação) permanecem causalmente consistentes dentro de um mesmo estado cognitivo compartilhado. A coerência sistêmica permite que estados internos persistam ao longo de múltiplos ciclos de processamento, estabelecendo continuidade entre eventos passados, decisões presentes e expectativas futuras.

Quando essa coerência é mantida de forma estável, o sistema passa a apresentar continuidade cognitiva suficiente para sustentar estados informacionais integrados. Esse regime organizacional corresponde ao que neste trabalho é denominado **proto-consciência funcional**: um estado no qual múltiplos processos cognitivos operam dentro de um mesmo contexto informacional coerente, permitindo integração global de informação e formas básicas de auto-referência operacional.

A partir desse ponto torna-se possível a emergência de um **modelo interno mínimo do mundo** (*minimal world model*). Esse modelo não precisa inicialmente representar o ambiente com grande detalhe. Sua função principal é fornecer uma referência interna consistente que permita ao sistema relacionar percepção, memória e ação dentro de uma mesma estrutura representacional. Dessa forma, o world model surge não como um componente explicitamente programado, mas como uma consequência emergente da capacidade da arquitetura de sustentar coerência sistêmica ao longo do tempo.

Assim, a abstração arquitetural derivada da neuroinspiração não busca reproduzir a estrutura biológica do cérebro, mas identificar os princípios organizacionais que permitem a emergência de estados cognitivos integrados. Entre esses princípios, a coerência sistêmica desempenha um papel central ao fornecer o mecanismo estrutural que conecta processos distribuídos, continuidade temporal e formação de modelos internos do mundo.

---

## 5. Dinâmica Temporal e Continuidade Cognitiva

A cognição, mesmo quando tratada de forma funcional e não fenomenológica, pressupõe continuidade ao longo do tempo. Estados mentais não surgem e desaparecem de forma instantânea e isolada; eles se estendem, se sobrepõem e se transformam gradualmente. Essa continuidade permite que diferentes processos cognitivos permaneçam alinhados dentro de um mesmo contexto informacional, formando estados mentais relativamente estáveis. Para arquiteturas artificiais, essa característica impõe uma exigência fundamental: a capacidade de manter e atualizar estados internos de maneira persistente ao longo do tempo.

Sistemas puramente estáticos ou baseados em processamento feedforward, nos quais a informação flui apenas em uma única direção e sem memória intrínseca, são estruturalmente incapazes de sustentar esse tipo de dinâmica. Grande parte das arquiteturas tradicionais de aprendizado profundo opera justamente nesse regime. Embora possam ser extremamente eficazes no mapeamento de entradas para saídas, essas arquiteturas frequentemente tratam o tempo como uma sequência discreta de eventos independentes ou como um simples índice adicional. Isso limita drasticamente a possibilidade de formar estados cognitivos persistentes, pois não existe um mecanismo interno que conecte de forma orgânica o passado, o presente e a antecipação do futuro.

Trabalhos como o de Bellec e colaboradores demonstram que redes recorrentes e redes neurais spiking oferecem uma alternativa conceitualmente mais adequada. Ao incorporar recorrência e dinâmica temporal explícita, esses modelos conseguem aprender dependências de longo prazo sem depender exclusivamente de mecanismos externos de memória. O aprendizado passa a ocorrer não apenas sobre padrões espaciais, mas sobre trajetórias temporais de atividade. Essa propriedade aproxima o funcionamento artificial da forma como sistemas biológicos integram informação ao longo do tempo, permitindo a formação de estados internos que persistem através de múltiplos ciclos de processamento.

A contribuição de Maass aprofunda essa perspectiva ao destacar o papel do ruído nos sistemas neurais. Em vez de ser tratado apenas como uma fonte de erro, o ruído pode atuar como um recurso computacional que introduz variabilidade controlada no sistema. Essa variabilidade impede a cristalização prematura de estados internos e permite exploração contínua do espaço de possibilidades. Em sistemas cognitivos, esse comportamento é fundamental para flexibilidade, adaptação e descoberta de novas soluções. A presença de ruído funcional rompe com a ideia de computação perfeitamente determinística e aproxima o comportamento do sistema de processos cognitivos naturais.

No nível do substrato físico, a computação neuromórfica surge como uma resposta concreta à necessidade de dinâmica temporal contínua. Diferentemente da computação digital clássica, que opera em ciclos discretos e sincronizados, sistemas neuromórficos são projetados para processar eventos de forma assíncrona, com unidades que mantêm estados internos persistentes. Essa abordagem permite uma integração mais natural entre processamento e memória, além de ganhos significativos em eficiência energética.

Os trabalhos de Boahen e, mais recentemente, de Kudithipudi e colaboradores mostram que esse tipo de substrato não apenas é tecnicamente viável, mas também oferece vantagens estruturais para arquiteturas cognitivas dinâmicas. Ao alinhar computação com temporalidade, a neuromorfia reduz a distância conceitual entre sistemas artificiais e processos biológicos, sem exigir cópia literal da biologia.

Em conjunto, esses desenvolvimentos reforçam uma conclusão central: a temporalidade não é um detalhe de implementação, mas um requisito estrutural para a formação de estados cognitivos coerentes. A capacidade de sustentar estados internos ao longo do tempo permite que percepção, memória e ação permaneçam alinhadas dentro de um mesmo contexto operacional. Essa continuidade constitui um dos fundamentos da coerência sistêmica discutida neste trabalho. Quando essa coerência temporal é mantida de forma estável, tornam-se possíveis estados cognitivos integrados que caracterizam formas iniciais de proto-consciência funcional.

---

## 6. Integração Global e Proto-Consciência Funcional

A noção de consciência funcional, quando deslocada do campo fenomenológico para o computacional, pode ser entendida como a capacidade de um sistema integrar informação de forma global, tornando determinados conteúdos amplamente acessíveis aos seus próprios processos internos. Essa integração não ocorre de maneira passiva. Ela envolve mecanismos de compartilhamento, priorização e alinhamento entre múltiplos processos internos, permitindo que diferentes subsistemas operem a partir de um contexto informacional comum. Nesse sentido, a consciência funcional não corresponde a um módulo específico do sistema, mas a uma propriedade organizacional que emerge da coordenação entre processos distribuídos.

A Global Workspace Theory fornece uma das formulações mais influentes dessa ideia. Nesse modelo, diversos processos especializados operam localmente até que determinadas informações alcancem um espaço global compartilhado. Quando isso ocorre, essas informações tornam-se amplamente disponíveis para outros subsistemas do agente, influenciando percepção, memória, decisão e ação. A arquitetura LIDA representa uma implementação computacional dessa teoria, na qual múltiplos processos competem por acesso ao workspace global. Esse mecanismo estabelece uma distinção funcional entre processamento local e estados cognitivos globalmente acessíveis, sem exigir a existência de um centro controlador único.

A teoria da informação integrada proposta por Tononi complementa essa perspectiva ao enfatizar a integração causal entre os componentes do sistema. De acordo com essa abordagem, sistemas conscientes não apenas processam informação em grande quantidade, mas o fazem de forma altamente interdependente. O significado de um estado cognitivo depende da maneira como diferentes partes do sistema influenciam umas às outras. Assim, a consciência está associada à capacidade do sistema de manter coerência interna entre seus processos ao longo do tempo.

Graziano introduz um elemento adicional ao deslocar o foco para o papel do auto-modelo. Segundo a Attention Schema Theory, a consciência funcional emerge quando o sistema constrói uma representação simplificada de seus próprios processos atencionais. Esse modelo não precisa ser completo nem perfeitamente preciso; sua função é permitir que o sistema monitore e regule sua própria atividade cognitiva. Nesse enquadramento, a consciência não corresponde ao processamento em si, mas à representação interna que o sistema constrói sobre esse processamento.

Essa interpretação é particularmente relevante para arquiteturas artificiais, pois sugere que a auto-referência não exige introspecção complexa ou representações simbólicas completas. Um modelo interno rudimentar, desde que consistente e funcional, já pode permitir formas básicas de monitoramento interno e controle cognitivo.

Resultados em neurociência reforçam essa perspectiva ao demonstrar que a integração cognitiva no cérebro está associada a mecanismos de sincronização neuronal. Estudos de Singer e Fries mostram que regiões cerebrais distintas conseguem coordenar suas atividades por meio de padrões de coerência oscilatória, permitindo que representações distribuídas sejam integradas em estados cognitivos unificados. Em termos computacionais, isso sugere que sistemas cognitivos complexos dependem de mecanismos capazes de alinhar dinamicamente múltiplos processos distribuídos.

Quando essas diferentes perspectivas são consideradas em conjunto, surge um quadro conceitual relativamente consistente. Estados cognitivos integrados parecem depender de três propriedades fundamentais: integração global de informação, coerência entre processos distribuídos e capacidade de manter representações internas sobre o próprio estado do sistema.

Neste trabalho, o conjunto dessas propriedades é interpretado como uma forma de proto-consciência funcional. Esse conceito não pressupõe experiência subjetiva, mas descreve um estado organizacional no qual o sistema mantém integração global de informação, continuidade temporal entre estados cognitivos e formas básicas de auto-referência operacional. A partir dessa organização, torna-se possível sustentar modelos internos progressivamente mais ricos do ambiente e do próprio agente.

Assim, a integração global não representa apenas um mecanismo de comunicação entre módulos, mas um passo fundamental na transição entre processamento fragmentado e cognição unificada. Quando a coerência sistêmica, a continuidade temporal e a integração global convergem em uma mesma arquitetura, surgem as condições necessárias para a emergência de proto-consciência funcional, um estágio organizacional que precede e possibilita a construção de modelos internos do mundo.

---

## 7. Aprendizado, Adaptação e Generalização

A capacidade de aprender, por si só, não é suficiente para sustentar cognição geral. Sistemas que aprendem de forma rígida, limitados a um conjunto fixo de tarefas ou ambientes, tendem a se especializar excessivamente, perdendo flexibilidade diante de situações novas. Em um contexto cognitivo, esse fenômeno pode ser entendido como uma forma de overfitting cognitivo: o sistema se ajusta tão bem a experiências passadas que passa a falhar quando confrontado com variações fora do seu histórico imediato. Para arquiteturas cognitivas artificiais, evitar esse efeito não é apenas um detalhe de treinamento, mas uma exigência estrutural relacionada à capacidade do sistema de manter coerência e adaptação ao longo do tempo.

O aprendizado por reforço fornece uma base formal importante para compreender como agentes podem adquirir comportamento adaptativo por meio da interação com o ambiente. Sutton e Barto descrevem esse paradigma como um processo no qual o agente ajusta suas ações com base nas consequências observadas, buscando maximizar recompensas acumuladas ao longo do tempo (Sutton & Barto, 2018). Essa formulação introduz elementos essenciais para a cognição artificial, como decisão sequencial, incerteza e temporalidade. No entanto, em sua forma clássica, o aprendizado por reforço ainda depende de funções de recompensa definidas externamente, o que limita a autonomia do sistema e restringe sua capacidade de desenvolver critérios internos de avaliação.

A introdução do meta-learning representa um avanço nesse cenário. Finn e colaboradores propõem que sistemas não aprendam apenas soluções específicas, mas desenvolvam a capacidade de aprender a aprender, adquirindo mecanismos que lhes permitem adaptar rapidamente seu comportamento a novos contextos com poucas interações adicionais (Finn et al., 2017). Essa abordagem desloca o foco do desempenho em tarefas isoladas para a capacidade de reorganização interna diante de situações inéditas. Em termos cognitivos, isso aproxima os sistemas artificiais da flexibilidade observada em sistemas biológicos, nos quais experiências anteriores influenciam a maneira como novas informações são incorporadas.

Entretanto, o aprendizado contínuo introduz um problema fundamental: o chamado esquecimento catastrófico. Estudos como os de Kemker e colaboradores mostram que muitas arquiteturas neurais tendem a sobrescrever representações previamente adquiridas quando novos conhecimentos são aprendidos, levando à perda abrupta de habilidades anteriores (Kemker et al., 2018). Esse comportamento contrasta fortemente com sistemas cognitivos naturais, nos quais o aprendizado ocorre de forma incremental e preserva uma continuidade de identidade ao longo do tempo. Esse desafio evidencia a necessidade de mecanismos capazes de manter estabilidade representacional enquanto novas informações são integradas ao sistema.

Nesse contexto, a neuroevolução oferece uma perspectiva complementar ao introduzir adaptação estrutural além da simples otimização paramétrica. Stanley e Miikkulainen demonstram que arquiteturas neurais podem evoluir progressivamente por meio de mecanismos evolutivos, gerando estruturas cada vez mais adequadas para lidar com ambientes complexos e variáveis (Stanley & Miikkulainen, 2002). De forma semelhante, Yao argumenta que processos evolutivos podem funcionar como mecanismos gerais de busca em espaços estruturais, permitindo que o próprio sistema descubra novas formas de organização ao longo do tempo (Yao, 1999).

Quando consideradas em conjunto, essas abordagens indicam que aprendizado, adaptação e generalização são propriedades interdependentes de uma arquitetura cognitiva robusta. Aprender continuamente, adaptar-se rapidamente e preservar conhecimento ao longo do tempo exige mais do que algoritmos eficientes de otimização. Requer uma organização interna capaz de manter coerência entre estados cognitivos sucessivos, permitindo que novas informações sejam integradas sem comprometer a estabilidade do sistema.

Essa continuidade organizacional é particularmente importante no contexto das arquiteturas discutidas neste trabalho. Sistemas capazes de manter coerência sistêmica ao longo de múltiplos ciclos de interação com o ambiente podem acumular experiência de forma consistente, preservando uma narrativa interna de estados cognitivos. Essa continuidade cria as condições necessárias para a formação progressiva de representações internas mais estruturadas do ambiente e do próprio agente.

Sob essa perspectiva, aprendizado e adaptação não devem ser vistos apenas como mecanismos de ajuste paramétrico, mas como processos que contribuem para a construção gradual de um modelo interno do mundo. À medida que o sistema mantém coerência entre percepção, memória e ação ao longo do tempo, torna-se possível desenvolver representações internas capazes de antecipar estados futuros e orientar decisões de forma mais flexível. Esse processo constitui um passo fundamental na transição entre sistemas puramente reativos e arquiteturas capazes de sustentar formas iniciais de generalidade cognitiva emergente.

---

## 8. Memória, Representação e Experiência

A memória desempenha um papel central na construção da continuidade cognitiva. Em sistemas biológicos, a percepção de identidade, aprendizado e experiência depende da capacidade de registrar, integrar e recuperar informações acumuladas ao longo do tempo. De forma semelhante, em arquiteturas cognitivas artificiais, a memória não pode ser tratada apenas como armazenamento passivo de dados. Ela deve funcionar como um mecanismo ativo capaz de sustentar contexto, integrar experiências passadas e orientar decisões futuras.

Nesse sentido, memória e cognição estão profundamente interligadas. A capacidade de um sistema manter coerência entre estados cognitivos sucessivos depende de mecanismos que permitam registrar eventos relevantes, preservá-los ao longo do tempo e recuperá-los quando necessário. Sem essa continuidade informacional, cada interação tende a se tornar isolada das demais, impedindo a formação de experiência acumulada e dificultando a construção de representações internas consistentes.

Pesquisas em sistemas de recuperação vetorial em larga escala demonstram caminhos promissores para esse tipo de memória associativa. Johnson, Douze e Jégou (2019) mostram que estruturas de busca vetorial podem organizar grandes volumes de informação em espaços representacionais densos, permitindo recuperação eficiente de conteúdos semanticamente relacionados. Em arquiteturas cognitivas artificiais, esse tipo de estrutura possibilita que informações passadas sejam recuperadas de forma contextualizada, permitindo que o sistema interprete o presente à luz de experiências anteriores.

Essa capacidade de recuperação contextual é fundamental para a formação de estados cognitivos coerentes. Quando um sistema consegue acessar representações relevantes de experiências passadas, ele deixa de responder apenas a estímulos imediatos e passa a integrar diferentes momentos de sua história operacional. Esse processo permite que o agente mantenha continuidade entre percepção, memória e ação, fortalecendo a coerência sistêmica entre seus processos internos.

Ambientes complexos de aprendizado reforçam ainda mais a importância dessa forma de memória funcional. Plataformas como MineRL e Project Malmo demonstram que agentes artificiais expostos a ambientes ricos e dinâmicos precisam acumular experiência ao longo do tempo para desenvolver comportamento adaptativo. Trabalhos como os de Johnson et al. (2016) e Guss et al. (2019) mostram que, nesses cenários, a memória não funciona apenas como um repositório de informações, mas como um mecanismo essencial para inferência, planejamento e tomada de decisão em contextos variáveis.

Quando memória e representação operam de forma integrada, surge a possibilidade de construção progressiva de representações internas do ambiente. Essas representações funcionam como modelos aproximados da estrutura do mundo em que o agente opera, permitindo antecipação de estados futuros e avaliação de possíveis ações. Assim, a memória deixa de ser apenas um registro do passado e passa a contribuir ativamente para a formação de um modelo interno do mundo.

Esse processo aproxima a memória artificial de uma forma funcional de experiência. Cada registro armazenado não representa apenas um dado isolado, mas um elemento dentro de uma narrativa operacional mais ampla que conecta passado, presente e expectativas futuras. À medida que essas representações se acumulam e se reorganizam, o sistema passa a desenvolver uma perspectiva interna cada vez mais estruturada sobre seu ambiente e sobre suas próprias ações.

Portanto, memória, representação e experiência constituem componentes inseparáveis de arquiteturas cognitivas capazes de sustentar coerência ao longo do tempo. A memória fornece os elementos estruturais da experiência, a representação organiza esses elementos em espaços significativos e a experiência emerge da interação dinâmica entre percepção, ação e histórico acumulado. Esse tripé fornece a base a partir da qual sistemas artificialmente coerentes podem começar a construir modelos internos do mundo, estabelecendo as condições necessárias para o surgimento de formas iniciais de proto-consciência funcional e para o desenvolvimento progressivo de generalidade cognitiva emergente.


---

## 9. Arquitetura Operacional e Verificabilidade

Até este ponto, o trabalho discutiu princípios teóricos que sustentam a emergência de estados cognitivos integrados, incluindo coerência sistêmica, continuidade temporal e integração global de informação. Entretanto, para que essas propriedades tenham valor científico e técnico, elas precisam ser traduzidas em estruturas arquiteturais concretas e verificáveis. Uma arquitetura cognitiva artificial não deve apenas afirmar que mantém coerência ou continuidade; ela deve permitir que esses fenômenos sejam observados, auditados e analisados de forma operacional.

Nesse contexto, a arquitetura considerada neste trabalho adota uma abordagem baseada em Clean Architecture, na qual diferentes responsabilidades do sistema são organizadas em camadas bem definidas. Essa separação estrutural permite distinguir claramente entre a lógica cognitiva central, mecanismos de memória, interfaces com modelos fundacionais e componentes de interação com o ambiente. Essa organização não apenas facilita a evolução e manutenção do sistema, mas também permite que estados cognitivos e processos decisórios sejam isolados, observados e analisados de maneira transparente.

Outro elemento central da arquitetura é a utilização de uma abordagem orientada a eventos, combinada com mecanismos de event sourcing. Nesse modelo, cada mudança relevante no estado do sistema é registrada como um evento persistente. Em vez de manter apenas o estado atual, a arquitetura preserva a sequência completa de eventos que levou àquele estado. Essa característica fornece continuidade temporal explícita e estabelece uma forma de causalidade rastreável entre percepções, inferências e ações. Como resultado, a dinâmica cognitiva do sistema deixa de ser uma caixa-preta e passa a constituir uma estrutura auditável de transições informacionais ao longo do tempo.

A coordenação entre múltiplos processos internos é realizada por meio de um mecanismo de orquestração inspirado na arquitetura PIANO (Parallel Information Aggregation via Neural Orchestration). Esse modelo foi originalmente desenvolvido no contexto do Project SID, um sistema voltado para simulações sociais em larga escala com múltiplos agentes cognitivos concorrentes. Na arquitetura original, o PIANO foi concebido para coordenar processos paralelos e manter coerência entre comunicação, planejamento e ação em ambientes complexos. No presente trabalho, esse princípio arquitetural é adaptado para o contexto de arquiteturas cognitivas artificiais governadas, nas quais múltiplos módulos operam em paralelo e seus resultados são agregados em um núcleo de decisão capaz de sintetizar um estado cognitivo global consistente.

Essa organização arquitetural permite a implementação do que neste trabalho é denominado proto-consciência operacional verificável. Diferentemente de concepções puramente teóricas de consciência artificial, essa abordagem define proto-consciência como um conjunto de propriedades observáveis do sistema: continuidade de estados internos, integração global de informação, coerência entre processos cognitivos e capacidade de rastrear decisões ao longo do tempo. Essas propriedades podem ser examinadas diretamente por meio dos registros de eventos e dos ciclos operacionais do sistema.

Além disso, a arquitetura incorpora mecanismos de semi-autonomia governada, nos quais processos de decisão automática podem ser supervisionados e, quando necessário, validados por agentes externos ou operadores humanos. Esse modelo de governança permite equilibrar autonomia operacional com controle e segurança, reduzindo riscos de deriva comportamental em sistemas complexos. Ao manter registros explícitos de decisões, aprovações e modificações estruturais, o sistema preserva um elevado nível de auditabilidade e transparência.

Como consequência, o comportamento cognitivo do sistema pode ser analisado tanto retrospectivamente quanto prospectivamente. A sequência de eventos armazenados permite reconstruir ciclos completos de percepção, inferência e ação, tornando possível investigar como determinadas decisões foram produzidas e como estados cognitivos evoluíram ao longo do tempo. Essa propriedade transforma a arquitetura em um objeto passível de investigação empírica, aproximando o estudo da cognição artificial de métodos tradicionais de análise científica.

Dessa forma, a arquitetura operacional não funciona apenas como um suporte técnico para execução de algoritmos, mas como uma estrutura que torna possíveis formas verificáveis de coerência sistêmica e continuidade cognitiva. Ao combinar separação arquitetural clara, persistência de eventos, coordenação paralela entre módulos e mecanismos de governança, o sistema estabelece uma base concreta para a investigação de proto-consciência funcional e modelos internos do mundo em arquiteturas cognitivas artificiais.

---

## 10. Conclusão

O presente trabalho evidencia uma distinção fundamental entre desempenho técnico e cognição geral. Avanços recentes em inteligência artificial demonstram que sistemas altamente escaláveis podem alcançar desempenho impressionante em diversas tarefas. No entanto, como mostram trabalhos influentes em aprendizado profundo e aprendizado por reforço, a ampliação de escala (seja em parâmetros, dados ou poder computacional) não garante, por si só, a emergência de inteligência artificial geral. Competência operacional não equivale necessariamente a cognição integrada ou generalidade cognitiva.

A análise apresentada ao longo deste trabalho sugere que a limitação central das abordagens atuais não reside apenas na capacidade de aprendizado ou representação, mas na ausência de mecanismos arquiteturais capazes de sustentar coerência sistêmica persistente entre diferentes processos cognitivos. Sem continuidade temporal entre estados internos, integração global de informação e mecanismos de auto-referência operacional, sistemas artificiais permanecem essencialmente reativos, operando como processadores estatísticos altamente sofisticados, porém desprovidos de unidade cognitiva estável.

Diversas teorias contemporâneas da consciência funcional reforçam essa interpretação. Abordagens como Global Workspace Theory, Integrated Information Theory e Attention Schema Theory convergem ao destacar a importância da integração global de informação, da coerência entre processos distribuídos e da presença de modelos internos do próprio sistema. Essas perspectivas sugerem que estados cognitivos integrados emergem quando múltiplos processos internos passam a operar dentro de um mesmo contexto informacional compartilhado.

A partir dessas bases teóricas, este trabalho argumenta que arquiteturas cognitivas capazes de sustentar coerência sistêmica, continuidade temporal e integração global de informação podem apresentar um estado organizacional que denominamos proto-consciência funcional. Esse estado não pressupõe experiência subjetiva, mas corresponde a um regime operacional no qual o sistema mantém estados cognitivos persistentes, coordena múltiplos processos internos e desenvolve formas rudimentares de auto-referência operacional.

Quando essas propriedades são mantidas de forma estável ao longo do tempo, torna-se possível a formação progressiva de modelos internos do mundo (world models). Esses modelos permitem que o sistema represente simultaneamente aspectos relevantes do ambiente e de seu próprio estado interno, possibilitando previsão, planejamento e adaptação contextual. Nesse cenário, a generalidade cognitiva deixa de ser uma propriedade explicitamente programada e passa a emergir gradualmente a partir da interação entre memória, aprendizado, percepção e ação.

Além da fundamentação conceitual, este trabalho também discute como tais princípios podem ser traduzidos em arquiteturas computacionais concretas. A utilização de estruturas arquiteturais baseadas em separação de responsabilidades, persistência de eventos, coordenação paralela entre módulos e mecanismos de governança permite tornar observáveis propriedades como continuidade cognitiva, coerência sistêmica e rastreabilidade decisória. Nesse contexto, arquiteturas operacionais inspiradas em modelos como o PIANO (Parallel Information Aggregation via Neural Orchestration) demonstram como múltiplos processos cognitivos podem ser coordenados de forma coerente dentro de um mesmo sistema.

Sob essa perspectiva, a investigação da cognição artificial deixa de ser apenas um exercício teórico e passa a envolver a construção de sistemas arquiteturalmente verificáveis, nos quais propriedades cognitivas podem ser observadas, auditadas e analisadas empiricamente. A noção de proto-consciência operacional verificável proposta neste trabalho busca justamente estabelecer essa ponte entre teoria e implementação.

Em síntese, a inteligência artificial geral não deve ser entendida como um objetivo direto de engenharia baseado exclusivamente em escala ou desempenho, mas como uma propriedade emergente de arquiteturas capazes de sustentar coerência sistêmica, continuidade cognitiva e modelos internos do mundo. Quando esses fundamentos estruturais estão presentes, a generalidade cognitiva surge não como um objetivo imposto externamente, mas como uma consequência natural da organização interna do sistema.

---

## Referências

- Bergmann, D., & Stryker, C. (2023). What is Artificial General Intelligence (AGI)? IBM Think. https://www.ibm.com/think/topics/artificial-general-intelligence

- Baars, B. J. (1988). A Cognitive Theory of Consciousness. Cambridge University Press.

- Baars, B. J. (1997). In the Theater of Consciousness: The Workspace of the Mind. Oxford University Press.

- Bellec, G., Scherr, F., Subramoney, A., Hajek, E., Salaj, D., Legenstein, R., & Maass, W. (2020). A solution to the learning dilemma for recurrent networks of spiking neurons. Nature Communications, 11, 3625.

- Boahen, K. (2005). Neuromorphic microchips. Scientific American, 292(5), 56–63.

- Brodmann, K. (1909). Vergleichende Lokalisationslehre der Grosshirnrinde in ihren Prinzipien dargestellt auf Grund des Zellenbaues. Johann Ambrosius Barth.

- Brodmann, K. (1912). Neue Ergebnisse über die vergleichende Histologie der Großhirnrinde mit besonderer Berücksichtigung des Stirnhirns. Anatomischer Anzeiger, 41, 157–216.

- Dehaene, S. (2014). Consciousness and the Brain: Deciphering How the Brain Codes Our Thoughts. Viking.

- Dosovitskiy, A., Beyer, L., Kolesnikov, A., Weissenborn, D., Zhai, X., Unterthiner, T., et al. (2021). An image is worth 16×16 words: Transformers for image recognition at scale. arXiv:2010.11929.

- Edelman, G. M. (1987). Neural Darwinism: The Theory of Neuronal Group Selection. Basic Books.

- Edelman, G. M., & Tononi, G. (2000). A Universe of Consciousness: How Matter Becomes Imagination. Basic Books.

- Finn, C., Abbeel, P., & Levine, S. (2017). Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks. Proceedings of ICML.

- Floreano, D., & Mattiussi, C. (2008). Bio-Inspired Artificial Intelligence: Theories, Methods, and Technologies. MIT Press.

- Franklin, S., Ramamurthy, U., & D’Mello, S. (2007). LIDA: A computational model of global workspace theory and developmental learning. AI Magazine, 28(2), 13–38.

- Fries, P. (2005). A mechanism for cognitive dynamics: neuronal communication through neuronal coherence. Trends in Cognitive Sciences, 9(10), 474–480.

- Friston, K. (2010). The free-energy principle: A unified brain theory? Nature Reviews Neuroscience, 11(2), 127–138.

- Geyer, S., et al. (1996). Brodmann’s areas revisited: cytoarchitecture and modern imaging. NeuroImage, 4(1), 84–91.

- Graziano, M. S. A. (2013). Consciousness and the Social Brain. Oxford University Press.

- Graziano, M. S. A. (2019). Rethinking Consciousness: A Scientific Theory of Subjective Experience. W. W. Norton & Company.

- Guss, W. H., Perez-Liebana, D., Codel, C., Hofmann, K., & Schaul, T. (2019). The MineRL competition on sample efficient reinforcement learning using human priors. arXiv:1904.10079.

- Harel, D. (1987). Statecharts: A visual formalism for complex systems. Science of Computer Programming, 8(3), 231–274.

- Hebb, D. O. (1949). The Organization of Behavior: A Neuropsychological Theory. Wiley.

- Johnson, J., Douze, M., & Jégou, H. (2019). Billion-scale similarity search with GPUs. IEEE Transactions on Big Data, 7(3), 535–547.

- Johnson, M., Hofmann, K., Hutton, T., & Bignell, D. (2016). The Malmo platform for artificial intelligence experimentation. Proceedings of IJCAI.

- Kandel, E. R., Schwartz, J. H., & Jessell, T. M. (2000). Principles of Neural Science (4th ed.). McGraw-Hill.

- Kemker, R., McClure, M., Abitino, A., Hayes, T., & Kanan, C. (2018). Measuring catastrophic forgetting in neural networks. arXiv:1811.03600.

- Kudithipudi, D., Schuman, C. D., Vineyard, C. M., et al. (2025). Neuromorphic computing at scale. Nature, 637, 801–812.

- Maass, W. (2014). Noise as a resource for computation and learning in networks of spiking neurons. Proceedings of the IEEE, 102(5), 860–880.

- Merzenich, M. M. (2013). Soft-Wired: How the New Science of Brain Plasticity Can Change Your Life. Parnassus Publishing.

- Mnih, V., Kavukcuoglu, K., Silver, D., Rusu, A. A., Veness, J., Bellemare, M. G., et al. (2015). Human-level control through deep reinforcement learning. Nature, 518(7540), 529–533.

- Silver, D., Schrittwieser, J., Simonyan, K., Antonoglou, I., Huang, A., Guez, A., et al. (2017). Mastering the game of Go without human knowledge. Nature, 550(7676), 354–359.

- Singer, W. (1999). Neuronal synchrony: a versatile code for the definition of relations? Neuron, 24(1), 49–65.

- Stanley, K. O., & Miikkulainen, R. (2002). Evolving neural networks through augmenting topologies. Evolutionary Computation, 10(2), 99–127.

- Sutton, R. S., & Barto, A. G. (2018). Reinforcement Learning: An Introduction (2nd ed.). MIT Press.

- Tegmark, M. (2017). Life 3.0: Being Human in the Age of Artificial Intelligence. Knopf.

- Tononi, G. (2004). An information integration theory of consciousness. BMC Neuroscience, 5, 42.

- Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., et al. (2017). Attention is All You Need. Advances in Neural Information Processing Systems.

- Yao, X. (1999). Evolving artificial neural networks. Proceedings of the IEEE, 87(9), 1423–1447.

- Zilles, K., & Amunts, K. (2010). Centenary of Brodmann’s map: conception and fate. Nature Reviews Neuroscience, 11(2), 139–145.

- Amunts, K., et al. (2013). BigBrain: an ultrahigh-resolution 3D human brain model. Science, 340(6139), 1472–1475.

- Park, J., O’Brien, J., Cai, C., et al. (2023). Generative Agents: Interactive Simulacra of Human Behavior. Proceedings of the ACM Symposium on User Interface Software and Technology. (Project SID related work)

- Park, J., O’Brien, J., Cai, C., Morris, M. R., Liang, P., & Bernstein, M. S. (2023). Generative Agents: Interactive Simulacra of Human Behavior. arXiv:2304.03442.

