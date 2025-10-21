# Modelo Conceitual

## Cenário A - Teleoperação em Ambiente Insalubre
**Atores:**
Rafael (técnico de laboratório), Sistema ATENA (interface de teleoperação), Robô InMoov (humanoide manipulador)

Rafael, técnico de um laboratório químico, precisa realizar inspeções e manipulações em um ambiente com produtos perigosos. Para evitar exposição e melhorar a precisão, ele utiliza o sistema ATENA, que permite controlar o robô InMoov remotamente. Ele acessa o sistema a partir da sala de controle e conecta-se ao robô localizado dentro do laboratório. Após o login, o sistema realiza a calibração dos sensores de visão e movimento, ajustando os gestos de Rafael aos do robô. Com a operação iniciada, o técnico executa ações como abrir válvulas, mover frascos delicados e ajustar conexões. Durante o processo, o sistema fornece feedback visual e sonoro, indicando força aplicada, posição dos braços e possíveis riscos. Caso o sistema detecte movimentos imprecisos, uma notificação solicita recalibração. Ao finalizar a tarefa, Rafael encerra a sessão e recebe um relatório automático com dados de tempo, precisão e alertas de segurança.

## Cenário B - Treinamento em Robótica
**Atores:**
Prof. Daniel (instrutor), Estudantes de Engenharia, Sistema ATENA (interface de teleoperação), Robô InMoov (humanoide didático)

Durante a disciplina de Robótica Aplicada, o professor Daniel utiliza o sistema ATENA para oferecer aos alunos uma experiência prática de teleoperação e controle humano-robô. Por meio da plataforma, os estudantes acessam remotamente o robô InMoov disponível no laboratório da instituição. Cada grupo conecta-se à interface pelo computador, ajustando parâmetros como velocidade, amplitude e delay dos movimentos. O sistema sincroniza os gestos capturados por câmera com os motores do robô, permitindo que os alunos observem a resposta física em tempo real. Durante as atividades, os alunos testam diferentes configurações, verificam a precisão dos movimentos e discutem como o software interpreta os comandos humanos. O professor acompanha as sessões, podendo enviar mensagens e registrar métricas de desempenho. Ao final, o sistema gera relatórios automáticos com indicadores de eficiência, estabilidade e tempo de resposta, auxiliando na avaliação do aprendizado prático.

## Cenário C - Monitoramento Remoto de Robôs
**Atores:**
Pesquisador Lucas (engenheiro de controle), Equipe de desenvolvimento, Sistema ATENA (interface de diagnóstico e telemetria), Robô InMoov (protótipo humanoide)

O pesquisador Lucas trabalha em um projeto de controle autônomo de robôs humanoides. Durante os testes, ele utiliza a interface ATENA para monitorar remotamente o robô InMoov instalado no laboratório. A plataforma exibe informações em tempo real sobre tensões, correntes, temperatura dos motores, ângulos das juntas e status de comunicação ROS2 e MQTT. Através do painel de Diagnóstico e Comunicação, Lucas identifica uma falha em um dos atuadores do braço direito. Ele envia um comando de teste diretamente pela interface e observa a resposta visual no modelo 3D do robô. O sistema também registra os logs e permite exportar relatórios automáticos com os eventos detectados. Enquanto isso, outros membros da equipe acessam simultaneamente os mesmos dados, discutindo ajustes de calibração e estratégias de correção, sem necessidade de deslocamento físico ao laboratório.

## Cenário D - Dificuldade de Configuração e Ajuste
**Atores:**
Operadores

Operadores enfrentam dificuldades para calibrar e ajustar parâmetros do robô humanoide, como amplitude de movimento e sensibilidade dos sensores, pois o processo requer modificações diretas em código ou arquivos de configuração. Durante o uso, o operador precisa alternar entre testes práticos e edições manuais, o que torna a experiência complexa e sujeita a erros. A ausência de uma interface visual acessível prolonga o tempo de calibração e pode causar configurações incorretas, afetando o desempenho do robô. Usuários iniciantes têm mais dificuldade, mas até especialistas enfrentam lentidão ao ajustar parâmetros finos. Um sistema que ofereça controle intuitivo e feedback em tempo real reduziria o tempo de preparação, diminuiria erros e tornaria o robô mais acessível para diferentes perfis de operadores.
