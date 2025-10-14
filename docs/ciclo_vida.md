# Características da Plataforma

| **Item** | **Descrição** | **Justificativa** |
|-----------|----------------|-------------------|
| **Software e Hardware da Plataforma** | A interface ATENA será executada em **ambiente desktop**, desenvolvida em **Python (usando Qt/PySide ou Tkinter)**, com comunicação via **ROS2** e **MQTT**. O hardware previsto inclui um **computador com processador i5 ou superior**, **8 GB de RAM** e **conexão estável à rede**. | Essas especificações garantem desempenho estável durante a comunicação em tempo real entre o sistema e o robô. |
| **Capacidades da Plataforma** | - Suporte à comunicação em tempo real via ROS2.<br>- Envio e recepção de mensagens MQTT.<br>- Renderização de modelo 3D para visualização do robô.<br>- Armazenamento e exportação de logs.<br>- Interface responsiva e configurável. | Permitem controle preciso, monitoramento contínuo e feedback visual da replicação de movimentos, facilitando a análise e calibração. |
| **Restrições da Plataforma** | - Dependência de conexão estável entre ROS2 e MQTT.<br>- Limitação de desempenho em hardware mais simples.<br>- Requer instalação de bibliotecas externas (dependências Python).<br>- Não é compatível com dispositivos móveis. | Tais restrições decorrem da necessidade de sincronização de dados em tempo real e uso intensivo de recursos gráficos e computacionais. |

---

# Princípios Gerais do Projeto

| **Item** | **Descrição** |
|-----------|----------------|
| **Contexto de uso** | A interface ATENA será utilizada em **laboratórios de robótica e pesquisa**, por **alunos e pesquisadores** responsáveis por operar o robô humanoide ATENA. O uso ocorre em **ambiente controlado**, com **equipamentos de computação conectados ao robô via rede local**. O objetivo é **monitorar, calibrar e controlar os movimentos** do robô, garantindo segurança e precisão. |
| **Nome da referência** | **Norma ISO 9241-210: Ergonomia da interação humano-sistema** |
| **Descrição da referência e importância** | A ISO 9241-210 fornece diretrizes para o **design centrado no usuário**, promovendo interfaces que priorizam usabilidade, eficiência e satisfação. É essencial para garantir que o sistema ATENA seja acessível, claro e seguro para operadores de diferentes níveis de experiência. |
| **Link de referência** | [ISO 9241-210 (Ergonomics of Human-System Interaction)](https://www.iso.org/standard/77520.html) |

---

# Metas de Usabilidade

### Contexto de uso

- **Usuário:** Alunos e pesquisadores da área de robótica e computação.  
- **Tarefas:** Iniciar replicação, calibrar movimentos, monitorar logs, ajustar parâmetros e diagnosticar falhas.  
- **Condições ambientais:**  
  - **Software:** Sistema ATENA (interface desktop).  
  - **Equipamento:** Computador conectado ao robô via ROS2 e MQTT.  
  - **Ambiente físico:** Laboratório controlado e silencioso.  
  - **Ambiente organizacional:** Instituição acadêmica com fins de pesquisa e desenvolvimento.  

### Exigências para a Usabilidade

| **Tipo** | **Descrição** |
|-----------|----------------|
| **Exigências qualitativas** | - Interface deve ser **intuitiva**, com menus claros e feedback visual imediato.<br>- As funções críticas (ex: iniciar replicação, calibrar) devem exigir **confirmação do usuário**.<br>- Mensagens de erro devem ser **compreensíveis e informativas**.<br>- O sistema deve permitir **monitoramento visual** (modelo 3D e logs).<br>- Deve haver **consistência entre as telas** (configuração, diagnóstico, calibração). |
| **Exigências quantitativas** | - **Eficácia:** Usuário deve conseguir concluir tarefas principais (iniciar replicação, calibrar, exportar relatório) em até **2 minutos** sem erro crítico.<br>- **Eficiência:** O número médio de cliques ou ações para cada tarefa deve ser **menor que 5**.<br>- **Satisfação:** Pelo menos **80% dos usuários** devem avaliar a interface como “fácil de usar” ou superior em questionário de pós-teste. |





