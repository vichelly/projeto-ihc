# Projeto de Interface Humano-Computador

Projeto apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Interface Humano-Computador (CC8122) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel) e Prof. Dr. Plino Thomaz Aquino Junior.

Este projeto se baseia no Trabalho de Conclusão de Curso (TCC) entitulado **Título do TCC** sob orientação do Professor **Nome do Orientador** e desenvolvido pelos seguintes alunos:

- Vitor Lucas Fujita Felício RA: 22.122.077-5
- Murilo da Fonseca Guimarães RA: 22.122.079-1
- Rafael Leal Silva RA: 22.122.029-6
- Juan Caio Galera Parottini RA: 22.122.067-6
 1.2) Título Original do TCC

ATENA – Robô antropomórfico baseado no InMoov para replicação de movimentos humanos em tempo real

1.3) Nome do orientador

Rafael Gomes Alves

1.4) Previsto desenvolver Interface?

( ) Sim     (x) Não

Obs.: Apesar de não estar no escopo inicial, durante o desenvolvimento foi explorada a criação de uma interface protótipo para visualização e controle.

1.5) Objetivo do trabalho

Desenvolver um robô humanoide parcial (da cintura para cima), inspirado no projeto OpenSource InMoov, capaz de capturar os movimentos de uma pessoa por meio de visão computacional e replicá-los nos membros superiores do robô em tempo quase real.

1.6) Qual o produto final?

Um robô funcional da cintura para cima, com braços robóticos controlados por visão computacional e sincronizados por meio de comunicação em rede.

1.7) Quem é o usuário final deste produto?

Estudantes, pesquisadores e entusiastas de robótica que desejam estudar controle de movimento humanoide, visão computacional e interação homem-máquina.

1.8) O que o usuário recebe de benefício ao usar esse produto?

Possibilidade de estudo em robótica antropomórfica.

Ambiente prático para testar visão computacional aplicada a controle de atuadores.

Base para projetos educacionais, de pesquisa e futuras aplicações em teleoperação.

1.9) Quais as funcionalidades da ferramenta (visão do usuário)?

Captura de movimentos humanos através de câmera.

Reprodução dos movimentos nos braços do robô.

Comunicação em rede para atualização próxima ao tempo real (via MQTT).

Estrutura modular baseada em ROS2 para expansão futura.

1.10) Quais tecnologias e ferramentas computacionais que pretendem usar neste projeto (TCC)?

Hardware: Raspberry Pi, câmera ZED SDK, servomotores.

Software: ROS2, OpenCV (visão computacional), MQTT (comunicação em rede).

Linguagens: Python e C++.

Modelagem/Hardware: Estrutura baseada em peças impressas 3D do InMoov.

1.11) Qual é o contexto de uso dessa aplicação?

O robô ATENA será utilizado em ambiente acadêmico e de pesquisa, para estudo de interação humano-robô. O contexto principal é o de IHC (Interação Humano-Computador), onde o movimento humano é capturado e traduzido para movimento robótico, permitindo estudar aspectos de tempo de resposta, precisão, telepresença e colaboração homem-máquina.
## Resumo


## Introdução

Sobre o produto ou serviço que seu grupo está desenvolvendo, responda:
- Apresente uma breve descrição.
- Apresente o objetivo. 
- Apresente o usuário final.
- Apresente os principais benefícios para o usuários.
- Apresente as funcionalidades.
- Apresente as tecnologias e ferramentas computacionais utilizadas.
- Apresente o contexto de uso.
- O produto ou serviço prevê o desenvolvimento de interface? (Sim/Não)

## Publico Alvo

- Determine qual o grupo específico de pessoas ou organizações para as quais este produto ou serviço é direcionado.
- Descreva as caracteristicas demográficas, comportamentais, psicográficas ou geográficas deste público alvo que o torna mais propenso a se interessar pelo que está sendo oferecido neste projeto ou serviço.

## Análise de concorrência

1. Identifique os principais concorrentes ou softwares mais utilizados pelo seu público-alvo.
2. Colete informações sobre os concorrentes selecionados.
3. Analise as características e funcionalidades dos concorrentes.
4. Avalie a experiência do usuário (UX).
5. Examine os preços e modelos de negócio.
6. Pesquisa de satisfação do cliente e opiniões.
7. Identifique padrões e tendências no mercado.
8. Elabore relatórios e sumarize os resultados.
9. Extraia pontos positivos e faça recomendações.

### Personas

- Descreva as personas que irão interagir com a aplicação ou produto. Deixe claro suas principais caracteristicas e contextos sociais, econômicos e culturais.
- Quais informações sobre o usuário o serviço ou poduto deve guardar?

  - Persona primaira ...
  - Persona secundária ...
  - Outras personas ...

### Mapa de empatia

![Mapa de empatia](empatia.png)

- Determine o mapa de empatia[^1] de pelo menos uma persona primária e uma sercundária.
  - O que o usuário vê: aqui estamos falando do ambiente visual em que o usuário se encontra. Ou seja, o que ele efetivamente enxerga, as pessoas e objetos que estão ao seu redor. Isso ajuda a entender o contexto em que o usuário está inserido e as influências visuais que está recebendo.
  - O que o usuário ouve: neste quadrante, buscamos entender o que o usuário está ouvindo, os sons que o cercam e como eles influenciam suas ações.
  - O que o usuário diz e faz: aqui consideramos ações e comportamentos que o usuário apresenta durante sua interação com serviço ou poduto.
  - O que o usuário pensa e sente: neste quadrante, buscamos entender os pensamentos, sentimentos, emoções e percepções que o usuário tem em relação ao serviço ou poduto. Quais expectativas o usuário cria sobre o serviço ou poduto?
  Que tipo de serviço ou poduto mais agrada essa persona?
  - Dores: quando falamos sobre dores do usuário, estamos fazendo referência a quaisquer obstáculos, necessidades ou frustrações que o usuário possa experimentar ao tentar realizar uma tarefa ou alcançar um objetivo. Isso inclui, por exemplo, problemas de usabilidade, dificuldades de acesso ou outros desafios que podem afetar a experiência do usuário.
  - Ganhos: nesse caso estamos falando de quaisquer benefícios ou recompensas que o usuário possa experimentar ao utilizar o serviço ou poduto. Isso pode incluir economia de tempo ou facilidade de uso, por exemplo. Que desejos do usuário o serviço ou poduto satisfaz?

## Contexto de uso

- Descreva o ambiente em que o serviço ou poduto deve ser utilizado.
- Qual/quais o(s) contexto(s) sociais, econômicos e culturais existentes neste ambiente?
- Quais informações sobre o ambiente, o serviço ou poduto deve guardar antes de iniciar a interação?
- O que normalmente deve estar acontecendo com o ambiente quando o usuário interagir com o serviço ou poduto?

## Jornada do usuário

- Criar uma narrativa para o o seu serviço ou poduto com o usuário.
- Determine o que o usuário realiza desde a primeira até o última interação com o serviço ou poduto.
  - Descreva o que acontece ou pode acontecer passo a passo
  - Como a tarefa começa? Como a tarefa se desenvolve? Como a tarefa termina?


<!--
## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?
 -->
 
## Coleta de dados

## Modelo de tarefas

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

### Prototipação em baixo nível (papel)
#### Avaliação heurística

### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->
Quero desenvolver uma interface de usuário para um projeto chamado Atena, um robô humanoide baseado no InMoov, que possui apenas a parte superior do corpo (da cintura para cima). O sistema utiliza Raspberry Pi, ROS2, visão computacional e MQTT.

A função principal do robô é capturar os movimentos dos braços de uma pessoa por câmera e replicá-los em tempo quase real.

Preciso de uma interface web (dashboard) acessível pelo navegador, hospedada no Raspberry Pi, que permita:

Stream de vídeo da câmera que captura a pessoa.

Um modelo simplificado (2D ou 3D) do robô mostrando a posição atual dos braços.

Controles principais

Botões: Iniciar replicação, Pausar, Controle manual, Modo demonstração.

Sliders para ajustar a velocidade e amplitude dos movimentos.

Opção de enviar comandos manuais para cada junta.

Monitoramento de estado

Indicadores de conexão MQTT e ROS2.

Logs básicos (ex: "Movimento recebido", "Erro no motor", etc.).

Estado da energia (ligado/desligado).

Configurações

Calibração dos braços.

Ajuste de parâmetros de sensibilidade e delay.

Perfil de usuário (salvar configurações).

Comunicação

Backend deve conversar com ROS2 e MQTT.

<img width="644" height="558" alt="image" src="https://github.com/user-attachments/assets/cea61c70-9211-4b17-a561-5474c6436926" />

[https://bolt.new/oauth2?code=aWlK-T0lSspGGMbcu9kRP01Max7J4LR0tTVPWR-E0OQ&state=6ebc71d1-f4dd-4c4b-81ce-6064bb2c39f0](https://bolt.new/~/sb1-jveugx49)
