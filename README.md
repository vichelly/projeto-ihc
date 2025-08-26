# projeto-ihc


<img width="644" height="558" alt="image" src="https://github.com/user-attachments/assets/cea61c70-9211-4b17-a561-5474c6436926" />

Quero desenvolver uma interface de usuário para um projeto chamado Atena, um robô humanoide baseado no InMoov, que possui apenas a parte superior do corpo (da cintura para cima). O sistema utiliza Raspberry Pi, ROS2, visão computacional e MQTT.

A função principal do robô é capturar os movimentos dos braços de uma pessoa por câmera e replicá-los em tempo quase real.

Preciso de uma interface web (dashboard) acessível pelo navegador, hospedada no Raspberry Pi, que permita:

Visualização em tempo real

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

Interface deve usar WebSockets ou MQTT over WebSocket para atualizações em tempo real.

Quero que você gere o layout em HTML/CSS/JS (ou React) com foco em:

Design simples, intuitivo e responsivo.

Dashboard dividido em seções claras: Visualização, Controle, Status e Configurações.

Uso de ícones e feedback visual para facilitar a interação.

[https://bolt.new/oauth2?code=aWlK-T0lSspGGMbcu9kRP01Max7J4LR0tTVPWR-E0OQ&state=6ebc71d1-f4dd-4c4b-81ce-6064bb2c39f0](https://bolt.new/~/sb1-jveugx49)
