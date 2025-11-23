## 1. Tela Inicial

![Tela
Inicial](https://github.com/user-attachments/assets/300667d9-cc04-4447-9b5e-bef7172ecb08)

A tela inicial serve como ponto de entrada para o usuário, apresentando
o conceito do projeto, suas tecnologias envolvidas e as capacidades
esperadas do robô ATENA.

### Resumo das Funcionalidades

#### Demonstração em Ação

Área reservada para um vídeo mostrando o robô replicando movimentos em
tempo real.

#### Tecnologias Avançadas

Principais pilares do sistema: - Visão Computacional para captura de
movimentos humanos
- Processamento com ROS2 para controle articulado
- Comunicação MQTT via WebSocket
- Algoritmos de replicação para transformar poses humanas em movimentos
robóticos

#### Sobre o Projeto ATENA

Apresentação do objetivo do robô, sua inspiração humanoide e a motivação
para criar uma interface web acessível, responsiva e com capacidades de
diagnóstico.

### Especificações Técnicas

O protótipo utiliza: - Raspberry Pi 4
- ROS2 Jazzy
- MQTT over WebSocket
- 6 DOF de articulação
- Interface Web desenvolvida com React e TypeScript

### Métricas de Performance

Metas estabelecidas para o sistema: - 99.5% de precisão nos movimentos
- Latência inferior a 50 ms
- Operação contínua 24/7

A baixa latência é fundamental, pois ações correlacionadas devem ocorrer
em menos de 100 ms para serem percebidas como simultâneas pelo sistema
visual humano.

## 2. Dashboard do Sistema

![Dashboard](https://github.com/user-attachments/assets/20c3bcac-70b6-4e05-8b31-7ccaacdab974)

Esta tela reúne informações essenciais sobre o estado de hardware,
comunicação e articulações do robô.

### Camera Feed -- Live

Exibe o stream ao vivo do sistema em 1920×1080 a 30 fps. A taxa mínima
de 20 fps garante que o movimento seja interpretado como contínuo.

### Robot Model -- Powered

Mostra o modelo do robô com ângulos das juntas em tempo real.

### Controles Principais

Botões para: - Iniciar replicação
- Controle manual
- Ativar modo demonstração
- Desligar o sistema

### Status do Sistema e Hardware

Painéis exibem: - Estado da comunicação MQTT
- Estado do ROS2
- Telemetria elétrica
- Temperatura da CPU e dos servos

### Logs Detalhados

Mostra histórico de publicações e eventos, com opção de exportar
relatórios.

### Terminal Integrado

Permite envio direto de comandos MQTT ou ROS2, além de visualizar
tópicos e nós ativos.

## 3. Controle de Juntas

![Controle de
Juntas](https://github.com/user-attachments/assets/978e4056-4450-44b1-b484-3eaf2fa62318)

Esta área permite o controle individual ou global de cada junta do robô
ATENA.

### Controles Globais

Inclui sliders para velocidade geral, amplitude total e posição neutra.

### Visualização em Tempo Real

Modelo do robô atualiza conforme os sliders são ajustados.

### Controle Individual das Juntas

Sliders organizados para ombro, cotovelo e punho dos braços esquerdo e
direito.

## 4. Loja 

![Loja](https://github.com/user-attachments/assets/016169fa-d842-4d79-a5f1-b02e84a884df)

Tela para configuração e aquisição do protótipo ATENA.

### Robô ATENA -- Modelo Base

-   Preço: R\$ 4.999,00
-   6 DOF
-   Garantia de 2 anos

### Acessórios Opcionais

-   Câmera HD adicional
-   Base móvel

### Resumo do Pedido

Exibe o total da compra e botão para prosseguir ao pagamento.
