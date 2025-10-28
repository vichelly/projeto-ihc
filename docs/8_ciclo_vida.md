# Características da Plataforma

| **Item** | **Descrição** | **Justificativa** |
|-----------|----------------|-------------------|
| **Software e Hardware da Plataforma** | A interface ATENA será executada em ambiente desktop, desenvolvida em Python, com comunicação via ROS2 e MQTT. O hardware previsto inclui um computador com processador i5 ou superior, 8 GB de RAM e conexão estável à rede. | Essas especificações garantem desempenho no uso do site, seja para usuários comuns como alunos, ou pesquisadores que presicam de um  ambiente estável durante a comunicação entre o sistema e o robô. |
| **Capacidades da Plataforma** | - Fornecer informações e imagens/videos sobre o robô ATENA.<br>- Possibilidade de compra de um robô ATENA.<br>- Suporte à comunicação em tempo real via ROS2.<br>- Envio e recepção de mensagens MQTT.<br>- Renderização de modelo 3D para visualização do robô.<br>- Armazenamento e exportação de logs.<br>- Interface responsiva e configurável. | Permitem controle preciso, monitoramento contínuo e feedback visual da replicação de movimentos, facilitando a análise e calibração. |
| **Restrições da Plataforma** | - Dependência de conexão estável entre ROS2 e MQTT.<br>- Limitação de desempenho em hardware mais simples.<br>- Requer instalação de bibliotecas externas (dependências Python).<br>- Não é compatível com dispositivos móveis. | Tais restrições decorrem da necessidade de sincronização de dados em tempo real e uso intensivo de recursos gráficos e computacionais. |

---

# Princípios Gerais do Projeto

| **Item** | **Descrição** |
|-----------|----------------|
| **Contexto de uso** | A interface do projeto ATENA consiste em um site de divulgação e venda do robô humanoide desenvolvido a partir do projeto original, oferecendo ao público uma plataforma informativa e interativa. Além de apresentar as características técnicas, funcionalidades e possibilidades de aquisição do robô, o site também permite que usuários que possuem acesso a uma unidade do ATENA realizem configurações básicas e diagnósticos remotos diretamente pela interface web. O sistema foi projetado para ser acessado de qualquer computador com conexão à internet, utilizando navegadores modernos sem a necessidade de instalação de software adicional. Essa abordagem visa garantir portabilidade, praticidade e acessibilidade, permitindo o uso tanto em contextos técnicos quanto comerciais. Os principais ambientes de utilização incluem instituições acadêmicas e laboratórios de pesquisa, onde o site poderá ser usado para divulgar o produto, fornecer informações técnicas detalhadas e, em alguns casos, realizar ajustes e calibrações remotas em robôs ATENA disponíveis para demonstração local. Além disso, o sistema poderá ser empregado em eventos científicos e feiras tecnológicas, facilitando a apresentação pública do robô e incentivando o interesse em sua aquisição ou integração em projetos educacionais. Assim, o ambiente de utilização da interface equilibra dois objetivos principais: promover a divulgação e comercialização do robô ATENA, e oferecer ferramentas de controle e configuração para usuários que possuam o robô, sendo ele uma aquisição própria ou apenas uma amostra, garantindo uma experiência completa e integrada, tanto informativa quanto funcional.|
| **Nome da referência** | **ISO 9241-151: Ergonomics of Human-System Interaction — Guidance on World Wide Web User Interfaces**|
| **Descrição da referência e importância** | A **ISO 9241-151** fornece diretrizes específicas para o design de interfaces web, com foco em acessibilidade, navegação, clareza da informação e eficiência na interação online. Essa norma orienta a estruturação de sites que envolvem divulgação, comércio eletrônico e interação técnica, garantindo que o conteúdo seja compreendido facilmente e que o usuário consiga realizar ações (como compras e envios de formulários) de maneira fluida e intuitiva. No contexto do projeto ATENA, ela é essencial para assegurar que a experiência do usuário seja **intuitiva, confiável e consistente**, tanto na parte de divulgação e venda do robô quanto nas funções técnicas de diagnóstico e controle. |
| **Link de referência** | [ISO 9241-151: Ergonomics of Human-System Interaction — Guidance on World Wide Web User Interfaces](https://www.iso.org/standard/37031.html) |

---

# Metas de Usabilidade

### Contexto de uso

- **Usuário:** Entusiastas, alunos e pesquisadores da área de robótica e computação.  
- **Tarefas:** Visualizar informações sobre o robô, realizar compra de um robô ATENA, iniciar replicação, calibrar movimentos, monitorar logs, ajustar parâmetros e diagnosticar falhas.  
- **Condições ambientais:**  
  - **Software:** Navegadores modernos (Google Chrome, Mozilla Firefox, Microsoft Edge) com suporte a HTML5 e WebSockets para comunicação com o robô..  
  - **Equipamento:** Computador desktop ou notebook com acesso à internet estável e, em casos de configuração do robô, conexão direta via rede local ou USB. 
  - **Ambiente físico:** Ambientes variados, desde salas de aula e laboratórios até escritórios e residências, com iluminação adequada e condições de trabalho confortáveis.  
  - **Ambiente organizacional:** Instituições acadêmicas, centros de pesquisa, startups e feiras tecnológicas, onde o site é utilizado para fins de divulgação, compra ou demonstração técnica do robô ATENA.  

### Exigências para a Usabilidade

| **Tipo** | **Descrição** |
|-----------|----------------|
| **Exigências qualitativas** | - Interface deve ser intuitiva, com menus claros e feedback visual imediato.<br>- As funções críticas (ex: iniciar replicação, calibrar) devem exigir confirmação do usuário.<br>- Mensagens de erro devem ser compreensíveis e informativas.<br>- O sistema deve permitir monitoramento visual (modelo 3D e logs).<br>- Deve haver consistência entre as telas (configuração, diagnóstico, calibração). |
| **Exigências quantitativas** | - **Eficácia:** Usuário deve conseguir concluir tarefas principais (iniciar replicação, calibrar, exportar relatório) em até 2 minutos sem erro crítico.<br>- **Eficiência:** O número médio de cliques ou ações para cada tarefa deve ser menor que 5.<br>- **Satisfação:** Pelo menos 90% dos usuários devem avaliar a interface como “fácil de usar” ou superior em questionário de pós-teste. |
