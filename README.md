
# **HYRO — Robô Híbrido para Assistência Doméstica**

Trabalho de Interação Humano-Robô (IHR) apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Interação Humano-Robô (IHR) (CCR230) do curso de Engenharia de Robôs, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

## Componentes do Grupo

> - Rafaela Botter - 11.122.066-1
> - Letícia Galante - 11.122.071-1
> - Joaquim Jonkel -
> - Rafael Vale -


## Resumo

 O HYRO é um robô de assistência doméstica com estrutura humanoide e rodas nas extremidades das pernas, projetado para auxiliar pessoas com dificuldades na realização de atividades cotidianas, especialmente idosos e pessoas com mobilidade reduzida. Seu diferencial está na combinação de mobilidade, interação por voz e assistência personalizada, permitindo buscar e transportar objetos, oferecer companhia por meio de conversas e disponibilizar uma função de contato de emergência para acionar familiares ou serviços de assistência quando necessário. O HYRO busca proporcionar maior autonomia, segurança e conforto aos usuários, tornando o ambiente doméstico mais acessível e promovendo uma interação intuitiva e acolhedora entre humanos e robôs.



## Introdução

Idosos e pessoas com mobilidade reduzida podem enfrentar dificuldades em tarefas cotidianas, além de situações de isolamento e dificuldade para pedir ajuda em emergências. Nesse contexto, a robótica assistiva pode contribuir para melhorar a autonomia, a segurança e a qualidade de vida dessas pessoas.

O HYRO é um robô de assistência doméstica com estrutura humanoide e rodas nas extremidades das pernas. Por meio de comandos de voz, ele poderá auxiliar na busca e no transporte de objetos, oferecer companhia e facilitar o contato de emergência com familiares ou serviços de assistência.


**Objetivo em uma frase:** promover autonomia, segurança e bem-estar no ambiente doméstico.
**Experiência desejada:** simples, acolhedora e segura, proporcionando uma interação natural e acessível.

</details>

## Público-Alvo e Stakeholders

Idosos, pessoas com mobilidade reduzida e indivíduos com dificuldades para realizar tarefas cotidianas, que necessitam de auxílio, companhia e maior segurança no ambiente doméstico.

### Stakeholders

- **Primários** — idosos e pessoas com mobilidade reduzida que utilizam o HYRO para buscar objetos, receber companhia e acionar contatos de emergência.
- **Secundários** — familiares, cuidadores e profissionais de assistência, que podem acompanhar o usuário e receber solicitações de ajuda.
- **Terciários** — demais moradores da residência, profissionais de saúde e serviços de emergência, que podem ser impactados pelo uso do robô e pelo acionamento de seus recursos.

</details>

### Personas

- **Persona primária — Maria, 72 anos:** aposentada, mora sozinha e possui dificuldade de locomoção. Utiliza o celular para tarefas básicas, mas prefere comandos de voz por serem mais práticos. Busca ajuda para pegar objetos, ter companhia e contatar familiares em emergências.

- **Persona secundária — João, 45 anos:** filho de Maria, trabalha em período integral e se preocupa com a segurança e o bem-estar da mãe. Deseja que o HYRO ajude nas atividades cotidianas e facilite o contato em situações de emergência.

- **Outras personas — Pessoas com mobilidade reduzida:** usuários de diferentes idades e contextos sociais que necessitam de auxílio em tarefas domésticas e valorizam autonomia, acessibilidade e segurança.

### Informações que o robô deve conhecer

- Nome e preferências de comunicação do usuário.
- Necessidades de acessibilidade e limitações de mobilidade relevantes para a interação.
- Lista de contatos de emergência autorizados.
- Preferências e comandos para as tarefas disponíveis.
- Localização dos objetos e ambientes relevantes, quando necessário.

Essas informações devem ser fornecidas ou autorizadas pelo usuário, respeitando sua privacidade e segurança.

### Mapa de empatia

![Mapa de empatia](empatiamaria.png)


<details>
<summary>📄 Persona primária: Maria, 72 anos</summary>

- **Vê:** objetos fora de alcance, móveis e ambientes domésticos que exigem deslocamento.
- **Ouve:** sons da casa, televisão e orientações do HYRO por voz.
- **Diz e faz:** pede para o HYRO buscar objetos, conversa com ele e utiliza a função de contato de emergência quando necessário.
- **Pensa e sente:** deseja manter sua independência, sentir-se segura e ter companhia no dia a dia.
- **Dores:** dificuldade de locomoção, necessidade de ajuda em tarefas simples e receio de não conseguir pedir ajuda em uma emergência.
- **Ganhos:** maior autonomia, praticidade, companhia e facilidade para contatar familiares.

</details>

![Mapa de empatia](empatiajoão.png)


<details>
<summary>📄 Persona secundária: João, 45 anos</summary>

- **Vê:** a rotina da mãe, suas dificuldades diárias e o HYRO auxiliando nas tarefas domésticas.
- **Ouve:** relatos da mãe sobre o robô e recebe contatos quando ela precisa de ajuda.
- **Diz e faz:** configura os contatos de emergência, ajuda na adaptação ao robô e verifica se ele atende às necessidades da mãe.
- **Pensa e sente:** preocupa-se com a segurança e o bem-estar da mãe e busca soluções confiáveis para ajudá-la mesmo quando está ausente.
- **Dores:** dificuldade de estar presente o tempo todo e preocupação com possíveis emergências.
- **Ganhos:** maior tranquilidade, apoio à rotina da mãe e facilidade de comunicação em situações que exigem assistência.

</details>

## Contexto de uso

O HYRO será utilizado principalmente em ambientes residenciais, como casas e apartamentos, compartilhados por pessoas com diferentes idades e necessidades. O ambiente pode apresentar móveis, corredores estreitos, objetos fora de alcance e obstáculos que dificultam a locomoção. O robô será especialmente útil para idosos e pessoas com mobilidade reduzida, mas poderá auxiliar outros moradores que necessitem de apoio em atividades cotidianas.

O contexto social envolve a convivência entre familiares, cuidadores e moradores, considerando também situações em que o usuário passa períodos sozinho. O HYRO deverá oferecer uma interação acessível por voz, respeitando diferentes níveis de familiaridade com a tecnologia e condições econômicas e culturais.

Antes de iniciar uma tarefa, o robô deverá conhecer o mapa do ambiente, sua localização, os obstáculos e as áreas acessíveis, além das capacidades necessárias para executar a solicitação. Também deverá conhecer as preferências de interação do usuário e, caso a função de emergência esteja habilitada, os contatos previamente cadastrados e autorizados.

## Jornada do usuário

1. O usuário percebe que precisa de ajuda para pegar um objeto fora de alcance.
2. O usuário chama o HYRO por voz, e o robô responde para indicar que está disponível *(verbal)*.
3. O usuário solicita que o robô busque o objeto desejado. Se necessário, o HYRO faz perguntas para esclarecer a solicitação *(verbal)*.
4. O robô confirma o pedido e se desloca pelo ambiente, desviando de móveis, pessoas e outros obstáculos *(espacial)*.
5. Ao chegar ao objeto, o HYRO utiliza seus mecanismos de manipulação para pegá-lo, caso a tarefa seja compatível com suas capacidades *(espacial)*.
6. O robô retorna até o usuário e informa verbalmente que trouxe o objeto, utilizando movimentos ou sinais visuais para indicar sua intenção *(verbal + não-verbal)*.
7. O usuário recebe o objeto e confirma que a tarefa foi concluída. O HYRO permanece disponível para novas solicitações *(verbal)*.
8. Em uma situação de emergência, o usuário poderá solicitar contato com um familiar ou serviço de assistência por meio de um comando específico. O robô confirma a solicitação e inicia o contato conforme as configurações autorizadas *(verbal)*.

Durante a interação, o ambiente poderá apresentar ruídos, circulação de pessoas e obstáculos inesperados. O HYRO deverá adaptar seu deslocamento, comunicar dificuldades e interromper a tarefa quando identificar condições inseguras.

## Análise de concorrência

- **Amazon Astro:** robô doméstico móvel voltado à segurança residencial, monitoramento e interação com moradores. Seu ponto positivo é a navegação autônoma e a integração com recursos de casa inteligente. Como limitação, não foi projetado principalmente para manipular objetos e prestar assistência física a pessoas com mobilidade reduzida.

- **ElliQ:** robô assistivo voltado especialmente ao público idoso, com foco em companhia, conversação, lembretes e promoção do bem-estar. Seu diferencial é a interação social. Como limitação, não possui locomoção doméstica com rodas nem capacidade de buscar e transportar objetos.

- **temi:** robô móvel com interação por voz, navegação autônoma e recursos de telepresença. Seus pontos positivos incluem mobilidade em ambientes internos e comunicação remota. Como limitação, sua configuração padrão não oferece a manipulação de objetos necessária para todas as tarefas propostas para o HYRO.

### Comparação e justificativa

Existem soluções que atendem parcialmente às necessidades do HYRO, principalmente nas áreas de companhia, comunicação, navegação e segurança residencial. Entretanto, essas funcionalidades são frequentemente encontradas em plataformas distintas.

A equipe considera especialmente interessantes o ElliQ, pela interação social e pelo foco no público idoso, e o temi, pela mobilidade e comunicação por voz. O HYRO busca combinar esses aspectos com uma estrutura humanoide e capacidade de manipulação de objetos, além de oferecer uma opção de contato de emergência.

Como alternativa, aplicativos, assistentes virtuais e dispositivos de chamada de emergência podem atender a necessidades específicas com menor custo, mas não oferecem a mesma combinação de mobilidade física, manipulação e interação presencial proposta para o HYRO.

## Design do Robô

### Forma, função e affordances

O HYRO possui uma estrutura humanoide, com cabeça, tronco, braços e pernas com rodas nas extremidades. Sua forma deve comunicar claramente suas funções: os braços indicam a capacidade de pegar objetos, a cabeça representa a percepção do ambiente e a comunicação por voz permite solicitar tarefas sem depender de telas ou controles físicos.

A acessibilidade será considerada por meio de comandos simples, fala clara, volume ajustável e tempo suficiente para o usuário responder. O robô deverá sinalizar suas intenções por voz e movimentos, além de permitir a interrupção de tarefas.

Para seguir o princípio de "prometer menos e entregar mais", o HYRO deverá informar suas capacidades e limitações de forma transparente, sem sugerir que consegue realizar tarefas que não foram implementadas ou testadas.

### Grau de antropomorfismo

O HYRO será posicionado entre os padrões **minimalista e humanoide** no espectro máquina-humano. A presença de cabeça, tronco e braços facilita a compreensão de suas funções e pode tornar a interação mais natural, enquanto as rodas reforçam sua identidade robótica.

O design deverá priorizar uma aparência amigável, sem tentar reproduzir perfeitamente um ser humano. Um rosto simplificado, expressões visuais discretas e movimentos previsíveis ajudam a evitar o vale da estranheza e reduzem expectativas irreais sobre suas capacidades sociais.

### Padrões de design

**1. Apresentação inicial:** o HYRO cumprimenta o usuário, identifica-se e informa brevemente como pode ajudar, permitindo que a pessoa compreenda suas funcionalidades.

**2. Confirmação e feedback:** antes de executar comandos ambíguos ou ações relevantes, o robô confirma a solicitação. Durante a tarefa, informa seu progresso e comunica quando a conclui ou encontra dificuldades.

A combinação desses padrões torna a interação mais previsível e acessível, reduzindo erros de interpretação e aumentando a confiança do usuário no sistema.

### Valores e ética

**Valores:**

- **Autonomia e acessibilidade:** permitir que pessoas com diferentes capacidades físicas interajam com o robô e realizem solicitações sem depender de interfaces complexas.
- **Segurança e privacidade:** proteger o usuário durante a movimentação e manipulação de objetos, respeitando seus dados pessoais e sua autorização para contatos de emergência.

**Risco ético:** o usuário pode confiar excessivamente no HYRO e acreditar que ele garante assistência em qualquer emergência.

**Mitigação:** informar claramente as limitações do sistema, solicitar confirmação antes de acionar contatos quando possível e comunicar se uma chamada não puder ser realizada. O HYRO deverá ser apresentado como um recurso complementar de assistência, e não como substituto de cuidadores ou serviços de emergência.

### Protótipo no papel

> 💡
> Modele o seu robô com desenhos de formas primitivas (caixas, cilindros, esferas): forma, tamanho, rosto/olhos, partes móveis, tela. É o protótipo mais barato e rápido — lembre-se do lema "**teste cedo, teste sempre**".
>

<details>
<summary>📄</summary>

 Corpo afunilado sobre uma base omnidirecional (três rodas onidirecionais, em arranjo triangular); "cabeça" arredondada com dois olhos, uma antena/sensor no topo; tela na parte de cima do torso, com o nome do robô; sem braços — apenas um anel de luz na base para sinalizar status. Altura total ≈1,55 m; diâmetro da base ≈0,90 m.

<img alt="Esboço do robô Rumo - V1'" src="rumo_esboco_v1.png" height="380"/>
<img alt="Esboço do robô Rumo - V2'" src="rumo_esboco_v2.png" height="380"/>
<img alt="Esboço do robô Rumo - V3'" src="rumo_esboco_v3.png" height="380"/>

</details>

## Ações do robô

> 💡
> Para cada ação:
> - Descreva a ação.
> - Determine os pré-requisitos para que a ação aconteça
> - Determine o que se espera que seja modificado no ambiente quando a ação é finalizada

<details>
<summary>📄</summary>

**Guiar até o destino** — pré-requisito: destino escolhido no menu e caminho livre conhecido no mapa do dia. Ao finalizar: o visitante está fisicamente no laboratório e o robô retorna à posição de espera no saguão.

**Dar informação rápida** — pré-requisito: pergunta reconhecida dentro do conjunto de perguntas frequentes cadastradas. Ao finalizar: a resposta foi falada e também exibida na tela.

</details>

## Interações do robô

### Espacial

> 💡
> - Descreva **onde** o robô se posiciona em relação ao usuário (distância e orientação do corpo), usando as **zonas de proxêmica** (Hall) e as **F-formations**.
> - Como o robô **inicia** a interação (direção de aproximação) e como **sinaliza** para onde vai?
> - Para cada interação espacial:
>   - Descreva a interação.
>   - Determine os pré-requisitos para que a interação aconteça.
>   - Determine a resposta emocional esperada do usuário quando a interação é finalizada.
> - O que o robô faz ao encontrar pessoas **paradas, em conversa ou em grupo**, e ao passar por elas num corredor (sem cruzar entre pessoas conversando)?
> - Proponha **um ajuste** desse comportamento espacial para um contexto de uso diferente do principal.

<details>
<summary>📄</summary>

- **Posicionamento:** aborda o grupo a uma distância social (2–3 m), sempre pela frente, nunca por trás.
- **Início da aproximação:** aproxima-se em diagonal (nunca em linha reta "contra" a pessoa), reduzindo a velocidade a 1,5 m de distância.
- **Sinalização de destino:** gira a "cabeça" na direção do laboratório antes de começar a andar.
- **Grupos e corredores:** ao encontrar duas pessoas conversando, contorna por trás delas, sem passar entre as duas; para grupos maiores, aguarda uma abertura natural na formação.
- **Ajuste de contexto:** em dias normais de aula (sem evento), o robô aumenta a distância de abordagem, já que há menos ruído social e mais espaço livre no saguão.

</details>

### Verbal

> 💡
> - A interação verbal do robô será **restrita** (comandos, FSM) ou **aberta** (LLM/chatbot)? Justifique a escolha.
> - Para cada interação verbal:
>   - Descreva a interação.
>   - Determine os pré-requisitos para que a interação aconteça.
>   - Determine a resposta emocional esperada do usuário quando a interação é finalizada.
> - Como o robô lida com o **timing** das respostas (silêncio, marcadores conversacionais como "uh-huh")?
> - Que tipo de voz (TTS) o robô usa, e por que ela **combina** com a aparência e o propósito dele?
> - Identifique **uma limitação** do reconhecimento de fala (ruído, sotaque, vocabulário) que afetaria o seu cenário de uso, e como mitigá-la.

<details>
<summary>📄</summary>

**Restrita** — usa uma árvore de diálogo (FSM) com um conjunto fechado de destinos e perguntas frequentes, pois o saguão é ruidoso e o vocabulário esperado é previsível; mais confiável do que abrir para um LLM.

**Timing:** ao processar um pedido, o robô emite um "hum" sonoro curto e pisca os olhos em sequência, evitando silêncio constrangedor.

**Voz:** TTS de tom jovem e neutro, volume ajustável ao ruído do saguão — combina com o porte pequeno do robô (uma voz grave soaria estranha).

**Limitação do ASR:** o ruído do evento atrapalha o reconhecimento de nomes de professores e disciplinas. **Mitigação:** escolhas críticas (curso, laboratório) são feitas por toque na tela; o reconhecimento de fala só é usado para perguntas simples de sim/não.

</details>

### Não-verbal

> 💡
> - Escolha **dois canais** não verbais (olhar, gesto, toque, postura, ritmo, imitação) e descreva como o robô os usaria.
> - Para cada interação não-verbal:
>   - Descreva a interação.
>   - Determine os pré-requisitos para que a interação aconteça.
>   - Determine a resposta emocional esperada do usuário quando a interação é finalizada.
> - Explique como o robô **perceberia** as pistas não verbais correspondentes da pessoa.
> - Descreva um caso em que a **falta de coordenação** entre fala e comportamento não verbal quebraria a interação.
> - Proponha **uma pista não verbal exclusiva** do robô (sem equivalente humano direto) que ajudaria na comunicação.

<details>
<summary>📄</summary>

**Canais escolhidos: olhar e postura.**
- **Olhar:** os "olhos" de LED giram na direção de quem está falando com o robô e na direção da rota a seguir.
- **Postura:** o corpo se inclina levemente para frente ao iniciar a aproximação (convite) e se afasta/gira de lado ao encerrar a interação (despedida).

**Percepção:** uma câmera de profundidade detecta se a pessoa está olhando para o robô (atenção) e se está parada olhando ao redor (sinal de estar perdida).

**Falta de coordenação:** se o robô disser "vamos ao laboratório de robótica" mas girar para o lado errado, o grupo hesita e para de segui-lo — a confiança se quebra.

**Pista exclusiva do robô:** um anel de luz na base pisca em verde quando o robô está confiante do caminho e em amarelo quando está recalculando a rota — sem equivalente humano direto, mas comunica incerteza de forma clara.

</details>

## Emoção

> 💡
> - Escolha um **modelo de emoção** (categorias básicas de Ekman, modelo OCC ou modelo dimensional — Russell ou PAD) e justifique a escolha para o seu caso de uso.
> - Descreva **como** o robô perceberia o estado emocional do usuário, e por quais canais (rosto, voz, postura, outro).
> - Defina **quando** o robô deve mimetizar a emoção da pessoa e **quando não deve** (lembre-se da exceção da raiva — retribuir raiva raramente ajuda a resolver o conflito).
> - Identifique um risco de **gerenciamento de expectativas**: se o robô parece emocionalmente responsivo, que outras capacidades sociais o usuário passa a esperar dele? O robô consegue cumprir essa expectativa?

<details>
<summary>📄</summary>

**Modelo:** categorias básicas de Ekman (feliz, surpreso, neutro) — simples o suficiente para expressar por luzes e tom de voz, sem exigir um rosto detalhado.

**Percepção:** o robô reconhece tom de voz alterado (frustração) pelo microfone e expressões faciais básicas pela câmera, para saber se o visitante está confuso ou satisfeito.

**Mimetismo:** mimetiza entusiasmo — se o visitante se anima ao ver o laboratório de robótica, o robô "sorri" com as luzes — mas **nunca** mimetiza a impaciência de um visitante apressado; nesse caso mantém tom calmo e oferece um caminho mais curto.

**Risco de expectativa:** se o robô demonstra "empolgação", visitantes podem esperar que ele converse sobre assuntos abertos (ex.: "e as notas de corte?"). O robô precisa deixar claro, de forma simpática, quando um assunto está fora do seu escopo.

</details>

---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     
[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>
