# Projeto de Interface Humano-Computador

Projeto apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Interface Humano-Computador (CC8122) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel) e Prof. Dr. Plino Thomaz Aquino Junior.

Este projeto se baseia no Trabalho de Conclusão de Curso (TCC) entitulado **Título do TCC** sob orientação do Professor **Nome do Orientador** e desenvolvido pelos seguintes alunos:

- Murilo da Fonseca Guimarães RA: 22.122.079-1
- Juan Caio Galera Parottini RA: 22.122.067-6
- Rafael Leal Silva RA: 22.122.029-6
- Vitor Lucas Fujita Felício RA: 22.122.077-5
  <br>
  
 1.2) **Título Original do TCC**

ATENA – Robô antropomórfico baseado no InMoov para replicação de movimentos humanos em tempo real

1.3) **Nome do orientador**

Rafael Gomes Alves

1.4) **Previsto desenvolver Interface?**

( ) Sim     (x) Não

Obs.: Apesar de não estar no escopo inicial, durante o desenvolvimento foi explorada a criação de uma interface protótipo para visualização e controle.

1.5) **Objetivo do trabalho**

Desenvolver um robô humanoide parcial (da cintura para cima), inspirado no projeto open-source InMoov, capaz de capturar os movimentos de uma pessoa por meio de visão computacional e replicá-los nos membros superiores do robô em tempo quase real.

1.6) **Qual o produto final?**

Um robô funcional da cintura para cima, com braços robóticos controlados por visão computacional e sincronizados por meio de comunicação em rede.

1.7) **Quem é o usuário final deste produto?**

Estudantes, pesquisadores , empresarios de empresas com insalubridade, e entusiastas de robótica que desejam estudar controle de movimento humanoide, visão computacional e interação homem-máquina.

1.8) **O que o usuário recebe de benefício ao usar esse produto?**

Possibilidade de estudo em robótica antropomórfica.

Ambiente prático para testar visão computacional aplicada a controle de atuadores.

Base para projetos educacionais, de pesquisa e futuras aplicações em teleoperação.

1.9) **Quais as funcionalidades da ferramenta (visão do usuário)?**

Captura de movimentos humanos através de câmera.

Reprodução dos movimentos nos braços do robô.

Comunicação em rede para atualização próxima ao tempo real (via MQTT).

Estrutura modular baseada em ROS2 para expansão futura.

1.10) **Quais tecnologias e ferramentas computacionais que pretendem usar neste projeto (TCC)?**

Hardware: Raspberry Pi, câmera ZED SDK, servomotores.

Software: ROS2, OpenCV (visão computacional), MQTT (comunicação em rede).

Linguagens: Python e C++.

Modelagem/Hardware: Estrutura criada utilizando peças de impressão 3D baseadas no InMoov.

1.11) **Qual é o contexto de uso dessa aplicação?**

O robô ATENA será utilizado em ambiente acadêmico e de pesquisa, para estudo de interação humano-robô, alem disto, pode ser usado em empresas e locais de trabalho insalubres. O contexto principal é o de Interação Humano-Robô, onde o movimento humano é capturado e traduzido para movimento robótico, permitindo estudar aspectos de tempo de resposta, precisão e colaboração homem-máquina.

# Desenvolvimento
 - [Analise de Concorrencia](https://github.com/vichelly/projeto-ihc/blob/main/docs/2_concorencia.md)
 - [Personas](https://github.com/vichelly/projeto-ihc/blob/main/docs/3_personas.md)
 - [Cenário de Análise/Problema](https://github.com/vichelly/projeto-ihc/blob/main/docs/4_cenarios.md)
 - [Análide de Tarefas](https://github.com/vichelly/projeto-ihc/blob/main/docs/5_analise_tarefas.md)
 - [Prototipação em Papel](https://github.com/vichelly/projeto-ihc/blob/main/docs/6_prototipacao.md)
 - [Coleta de Dados](https://github.com/vichelly/projeto-ihc/blob/main/docs/7_coleta_dados.md)
 - [Ciclo de vida da engenharia de usabilidade](https://github.com/vichelly/projeto-ihc/blob/main/docs/8_ciclo_vida.md)
 - [Modelo Conceitual](https://github.com/vichelly/projeto-ihc/blob/main/docs/9_modelo_conceitual.md)
 - [MOLIC](https://github.com/vichelly/projeto-ihc/blob/main/docs/10_molic.md)
 - [FIGMA](https://github.com/vichelly/projeto-ihc/blob/main/docs/11_figma.md)
 - [Planejamento da Avaliação](https://github.com/vichelly/projeto-ihc/blob/main/docs/12_planejamento_avaliacao.md)
 - [Avaliação de IHC através de Inspeção Heurística](https://github.com/vichelly/projeto-ihc/blob/main/docs/13_heuristica.md)
 - [Avaliação de Usabilidade baseado em Observação do Usuário](https://github.com/vichelly/projeto-ihc/blob/main/docs/14_observacao_usuario.md)
