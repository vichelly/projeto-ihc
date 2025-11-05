# Análise de Tarefas

# Tela Inicial 
## Pagina inicial do ATENA
### HTA
Pagina inicial do site sobre o robô ATENA

<img width="973" height="725" alt="image" src="https://github.com/user-attachments/assets/12198af6-45da-4a46-976b-25cc88e00db4" />

### GOMS

**GOAL 1:** Explorar informações sobre o robô ATENA e enviar sugestões<br>

METHOD 1.A: acessar e explorar o site<br>
(SEL.RULE: o usuário deseja conhecer o robô ou contribuir com sugestões)

- OP. 1.A.1: acessar o site do projeto
- OP. 1.A.2: clicar nas abas ou menus disponíveis
- OP. 1.A.3: assistir vídeos e rolar a página
- OP. 1.A.4: acessar a seção “Sobre o Projeto”

**GOAL 1.B:** enviar uma sugestão<br>

METHOD 1.B.A: preencher e enviar formulário de sugestão<br>
(SEL.RULE: o usuário deseja contribuir com o projeto)

- OP. 1.B.A.1: preencher o campo de sugestão
- OP. 1.B.A.2: clicar no botão “Enviar”

SEL.RULE geral:<br>
Se o usuário deseja apenas conhecer o projeto → encerrar após OP. 1.A.4<br>
Se o usuário deseja contribuir → prosseguir para GOAL 1.B<br>

### CTT

<img width="553" height="532" alt="image" src="https://github.com/user-attachments/assets/f488c926-ba60-40a5-a005-a5b52a384b5f" />

**Legenda CTT:**<br>
<img width="399" height="344" alt="image" src="https://github.com/user-attachments/assets/b476b39b-1338-43a7-96e9-d2e6d1914cb4" />

# Tela de Venda 
## Venda do robô
### HTA
Possibilita a compra de um robô ATENA

<img width="1108" height="414" alt="image" src="https://github.com/user-attachments/assets/1d7a8b5a-67b5-4568-ae4d-2f7cde288c17" />

### GOMS

**GOAL 1:** Adquirir um robô ATENA

METHOD 1.A: realizar o processo de compra<br>
(SEL.RULE: o usuário deseja adquirir o robô pelo site)

- OP. 1.A.1: acessar a seção de compra
- OP. 1.A.2: clicar no botão de compra
- OP. 1.A.3: selecionar acessórios opcionais
- OP. 1.A.4: preencher informações de pagamento
- OP. 1.A.5: clicar em confirmar
  
**GOAL 1.B:** finalizar e validar a compra

METHOD 1.B.A: verificar status da transação<br>
(SEL.RULE: resultado da autorização do pagamento)

- OP. 1.B.A.1: se pagamento autorizado → exibir mensagem de sucesso
- OP. 1.B.A.2: se erro no pagamento → exibir alerta e permitir nova tentativa
### CTT

<img width="682" height="380" alt="image" src="https://github.com/user-attachments/assets/97440e57-d092-40b2-83f3-8d7d0f279e17" />

# Tela de Diagnóstico / Comunicação
## Diagnóstico e Comunicação
### HTA
Permite o usuário verificar conexões e status em tempo real, analisar logs de eventos e enviar comandos de teste.

<img width="1392" height="394" alt="image" src="https://github.com/user-attachments/assets/495db693-1742-455e-b8ca-cfa1dd04bfa5" />

### GOMS
**GOAL 1:** Verificar status e realizar testes de comunicação<br>

METHOD 1.A: realizar diagnóstico completo<br>
(SEL.RULE: o usuário acessa a tela para verificar conexões e funcionamento do robô)

- OP. 1.A.1: acessar o menu “Diagnóstico”
- OP. 1.A.2: conferir status das conexões
- OP. 1.A.3: rolar lista de logs recentes
- OP. 1.A.4: digitar comando de teste no terminal
- OP. 1.A.5: clicar em “Exportar Relatório”

**GOAL 1.B:** analisar resultado e tomar ação apropriada<br>

METHOD 1.B.A: validar resposta do sistema<br>
(SEL.RULE: comportamento do robô após comando de teste)

- OP. 1.B.A.1: se status normal → apenas registrar
- OP. 1.B.A.2: se erro detectado → reenviar comando ou acionar suporte

### CTT

<img width="655" height="439" alt="image" src="https://github.com/user-attachments/assets/20763361-c430-42ef-9db1-e743c0caa291" />

# Tela de Controle Manual
## Enviar Comandos Manuais para Juntas
### HTA
O usuário seleciona a junta, define o valor desejado (slider ou numérico) e envia o comando para execução imediata.

<img width="728" height="406" alt="image" src="https://github.com/user-attachments/assets/b1bab6ea-de7e-419e-821d-b4eca3066061" />

### GOMS
**GOAL 1:** Controlar manualmente cada junta do robô<br>

METHOD 1.A: realizar comando de controle manual<br>
(SEL.RULE: o usuário deseja ajustar uma junta específica do robô)

- OP. 1.A.1: acessar o painel de controle manual
- OP. 1.A.2: selecionar a junta desejada
- OP. 1.A.3: definir valor de posição/ângulo via slider ou campo numérico
- OP. 1.A.4: enviar comando manual

**GOAL 1.B:** validar execução do comando<br>

METHOD 1.B.A: verificar resposta do sistema<br>
(SEL.RULE: resultado da execução do comando)

- OP. 1.B.A.1: se comando válido → robô executa movimento
- OP. 1.B.A.2: se comando inválido → exibir mensagem de erro

### CTT

<img width="641" height="336" alt="image" src="https://github.com/user-attachments/assets/8c8f6745-ff2b-4c0b-8800-d7fc7478a84d" />

