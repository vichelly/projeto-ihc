<img width="838" height="1605" alt="imagem2" src="https://github.com/user-attachments/assets/300667d9-cc04-4447-9b5e-bef7172ecb08" />
A tela inicial funciona como ponto de entrada para o usuário, apresentando o conceito do projeto, suas tecnologias envolvidas e as capacidades esperadas do robô ATENA.

Resumo das Funcionalidades

Demonstração em Ação
Área reservada para vídeo exibindo o robô replicando movimentos em tempo real.

Tecnologias Avançadas
Destaque para os pilares tecnológicos do sistema:

Visão Computacional: captura de movimentos humanos;

Processamento ROS2: controle articulado via nós e tópicos;

Comunicação MQTT: conectividade remota via WebSocket;

Replicação Inteligente: algoritmos dedicados à transformação e execução das poses humanas.

Sobre o Projeto ATENA
Introdução ao objetivo do robô, seu fundamento humanoide e a motivação da interface web (acesso intuitivo, responsivo e com ferramentas de diagnóstico).

Especificações Técnicas
O protótipo utiliza:

Raspberry Pi 4

ROS2 Jazzy

MQTT over WebSocket

6 DOF de articulação

Interface em React + TypeScript

Métricas de Performance
O sistema tem como meta:

99.5% de Precisão de Movimento

Latência < 50 ms

Operação contínua 24/7
A baixa latência é crucial, pois para que uma ação seja percebida como causa de outra pelo sistema perceptual humano, ambas devem ocorrer em menos de 100 ms.

Contribua com o Projeto
Campo interativo para envio de sugestões ou feedback.

<img width="1062" height="1747" alt="imagem1" src="https://github.com/user-attachments/assets/20c3bcac-70b6-4e05-8b31-7ccaacdab974" />

Esta é a área de controle e observação do sistema, reunindo informações essenciais sobre o estado de hardware, comunicação e articulações.

Componentes e Funcionalidades

Camera Feed – LIVE
Visualiza o stream ao vivo (1920×1080 @ 30fps).
A taxa acima de 20fps é importante para que o Sistema Perceptual humano interprete o movimento como contínuo.

Robot Model – POWERED
Exibe o modelo do robô com os ângulos das juntas em tempo real, como:

L Shoulder: 105°

R Elbow: 120°

Controles Principais
Botões amplos para:

Iniciar Replicação

Controle Manual

Modo Demo

Desligar
O dimensionamento segue a Lei de Fitts, garantindo menor tempo de apontamento através do aumento da área clicável.

Status do Sistema e Hardware
Painéis agrupando:

Estado MQTT (Conectado)

Estado ROS2 (Ativo)

Telemetria elétrica (Tensão, Corrente)

Temperatura da CPU e Servos

Logs Detalhados
Histórico de publicações e eventos (ROS2 e MQTT), com opção de exportar relatório.

Terminal Integrado
Permite envio direto de comandos MQTT/ROS2 e exibição de tópicos e nós ativos — ferramenta útil para depuração.

<img width="864" height="727" alt="imagem4" src="https://github.com/user-attachments/assets/978e4056-4450-44b1-b484-3eaf2fa62318" />

Esta seção permite ao usuário manipular cada junta do robô ATENA de forma individual ou global, essencial para testes e teleoperação.

Funcionalidade da Tela

Controles Globais
Sliders para:

Velocidade global do movimento

Amplitude global

Botão para resetar para a posição neutra

Visualização em Tempo Real
O modelo gráfico reflete instantaneamente as mudanças aplicadas pelos sliders.
Esse feedback imediato é importante, pois o processamento cognitivo depende da sincronização perceptual-motora.

Controle Individual das Juntas
Sliders separados dos braços esquerdo e direito, permitindo controlar:

Ombro

Cotovelo

Punho
A divisão visual segue o princípio da Proximidade da Gestalt, agrupando elementos relacionáveis.

<img width="889" height="565" alt="imagem3" src="https://github.com/user-attachments/assets/016169fa-d842-4d79-a5f1-b02e84a884df" />

Tela que simula uma experiência de “loja”, onde o usuário pode configurar e adquirir o protótipo ATENA.

Elementos Principais

Robô ATENA – Modelo Base

Preço: R$ 4.999,00

6 DOF

Garantia de 2 anos

Avaliação do produto

Acessórios Opcionais

Câmera HD Adicional

Base Móvel

Resumo do Pedido
Exibe total da compra e botão Prosseguir para Pagamento.
