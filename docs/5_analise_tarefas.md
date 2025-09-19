# Análise de Tarefas

> **_NOTE:_**: A equipe deve descrever as funcionalidades mais importantes da interface/produto. A equipe deve modelar pelo menos 1 HTA, 1 GOMS e 1 CTT (de pelo menos 4 funcionalidades diferentes). Cada diagrama deve ter um texto explicando a funcionalidade.

## Iniciar Replicação de Movimentos
### HTA
O operador precisa iniciar a replicação dos movimentos humanos pelo robô. Essa tarefa envolve verificar conexões, ativar o comando e acompanhar o status do sistema.

<img width="1050" height="446" alt="image" src="https://github.com/user-attachments/assets/f695ffd8-3d65-4ec3-8e29-69bd281a1df7" />

### GOMS
**Meta:** Iniciar replicação dos movimentos do operador.<br><br>
**Operadores:**<br>
- Verificar status de conexão (ROS2, MQTT, energia).<br>
- Localizar e clicar no botão "Iniciar Replicação".<br>
- Confirmar ação em mensagem de confirmação.<br>
- Acompanhar logs e stream de vídeo.<br>

**Método:**<br>
1. Checar conexões.<br>
2. Selecionar botão "Iniciar Replicação".<br>
3. Confirmar inicialização.<br>
4. Monitorar execução.<br>

**Seletores:**<br>
- Se conexões estão ativas → prosseguir.<br>
- Se conexões falham → exibir mensagem de erro.<br>

Resumo: Permite ao usuário acionar a replicação verificando conexões, confirmando a inicialização e acompanhando a execução.<br>

### CTT

## Ajustar Velocidade e Amplitude
### HTA
O usuário acessa o painel de ajustes, define valores nos sliders de velocidade e amplitude e confirma as alterações para aplicar em tempo real.

<img width="959" height="404" alt="image" src="https://github.com/user-attachments/assets/da2201e3-788e-47a6-b24c-87dba8392c27" />

### GOMS
**Meta:** Ajustar parâmetros de movimento do robô..<br><br>
**Operadores:**<br>
- Acessar painel de ajustes..<br>
- Mover sliders de velocidade e amplitude.<br>
- Confirmar alterações.<br>

**Método:**<br>
1. Acessar tela de ajustes.<br>
2. Selecionar sliders de velocidade e amplitude.<br>
3. Definir valores.<br>
4. Confirmar ajustes.<br>

**Seletores:**<br>
- Se usuário confirma → aplicar novos valores.<br>
- Se cancela → manter valores anteriores.<br>

Resumo: Permite ao usuário ajustar sliders de velocidade e amplitude e confirmar alterações para aplicação em tempo real.<br>

### CTT

## Enviar Comandos Manuais para Juntas
### HTA
Funcionalidade para controle manual: o usuário seleciona a junta, define o valor desejado (slider ou numérico) e envia o comando para execução imediata.

<img width="728" height="406" alt="image" src="https://github.com/user-attachments/assets/b1bab6ea-de7e-419e-821d-b4eca3066061" />

### GOMS
**Meta:** Controlar manualmente cada junta do robô.<br><br>
**Operadores:**<br>
- Selecionar a junta a ser movida.<br>
- Inserir valor via slider ou campo numérico.<br>
- Enviar comando manual.<br>

**Método:**<br>
1. Acessar painel de controle manual.<br>
2. Selecionar junta desejada.<br>
3. Definir valor de posição/ângulo.<br>
4. Enviar comando.<br>

**Seletores:**<br>
- Se comando válido → robô executa.<br>
- Se comando inválido → exibir mensagem de erro.<br>

Resumo: Dá ao usuário a possibilidade de escolher uma junta, definir valores e enviar comandos diretos.<br>

### CTT

## Calibrar os Braços
### HTA
O usuário posiciona os braços do robô, inicia a calibração automática e salva a configuração, garantindo alinhamento e precisão nos movimentos.

<img width="1053" height="434" alt="image" src="https://github.com/user-attachments/assets/11729019-5e15-48d3-8a4e-e29ca148a208" />

### GOMS
**Meta:** Calibrar o robô para garantir alinhamento.<br><br>
**Operadores:**<br>
- Posicionar fisicamente os braços em ponto inicial.<br>
- Selecionar botão "Calibrar".<br>
- Confirmar calibração.<br>
- Salvar nova configuração.<BR>

**Método:**<br>
1. Preparar robô na posição inicial.<br>
2. Acionar função de calibração.<br>
3. Confirmar processo.<br>
4. Salvar parâmetros de calibração.<br>

**Seletores:**<br>
- Se calibração é aceita → armazenar valores.<br>
- Se falha → repetir procedimento.<br>

Resumo: O usuário posiciona os braços, inicia a calibração e salva as configurações para manter precisão.<br>

### CTT
