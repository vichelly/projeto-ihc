# Análise de Tarefas

# Tela Inicial 
## Pagina inicial do ATENA
### HTA
Pagina inicial do site sobre o robô ATENA

<img width="764" height="691" alt="image" src="https://github.com/user-attachments/assets/f922ee54-140e-436e-8ca1-9d7f0c59d781" />

### GOMS

**Meta:** Explorar informações sobre o robô e enviar sugestões.<br><br>
**Operadores:**<br>
- Clicar em abas ou menus.<br>
- Assistir vídeos e rolar página.<br>
- Preencher campo de sugestão.<br>
- Clicar em botão “Enviar”.<br>

**Método:**<br>
1. Acessar o site.<br>
2. Explorar vídeos, imagens e descrições.<br>
3. Acessar a seção “Sobre o Projeto”.<br>
4. Enviar sugestão de melhoria.<br>

**Seletores:**<br>
- Se o usuário deseja apenas conhecer → encerra após etapa 3.<br>
- Se o usuário deseja contribuir → prossegue para etapa 4.<br>

Resumo: O visitante entra na página inicial, navega pelos materiais de divulgação, conhece as funcionalidades do robô e, caso queira, envia sugestões diretamente pelo formulário.<br>

### CTT

<img width="553" height="532" alt="image" src="https://github.com/user-attachments/assets/f488c926-ba60-40a5-a005-a5b52a384b5f" />

**Legenda CTT:**<br>
<img width="399" height="344" alt="image" src="https://github.com/user-attachments/assets/b476b39b-1338-43a7-96e9-d2e6d1914cb4" />

# Tela de Venda 
## Venda do robô
### HTA
Possibilita a compra de um robô ATENA

<img width="1267" height="455" alt="image" src="https://github.com/user-attachments/assets/84ea81f3-1262-4a62-b269-8ff850d52eed" />

### GOMS

**Meta:** Adquirir um robô ATENA pelo site.<br><br>
**Operadores:**<br>
- Clicar em botão de compra<br>
- Selecionar acessórios opcionais<br>
- Preencher informações de pagamento.<br>
- Clicar em confirmar.<br>

**Método:**<br>
1. Acessar a seção de compra.<br>
2. Escolher acessórios opcionais.<br>
3. Inserir dados de pagamento.<br>
4. Confirmar a compra e verificar o recebimento da confirmação.<br>

**Seletores:**<br>
- Se pagamento autorizado → exibe mensagem de sucesso.<br>
- Se erro no pagamento → exibe alerta e permite tentar novamente.<br>

Resumo: O usuário acessa a tela de venda, escolhe a versão do robô, insere seus dados de pagamento e finaliza a compra. O sistema gera uma confirmação visual e envia um e-mail automático com os detalhes do pedido.<br>

### CTT

<img width="682" height="380" alt="image" src="https://github.com/user-attachments/assets/97440e57-d092-40b2-83f3-8d7d0f279e17" />

# Tela de Diagnóstico / Comunicação
## Diagnóstico e Comunicação
### HTA
Permite o usuário verificar conexões e status em tempo real, analisar logs de eventos e enviar comandos de teste.

<img width="1392" height="394" alt="image" src="https://github.com/user-attachments/assets/495db693-1742-455e-b8ca-cfa1dd04bfa5" />

### GOMS
**Meta:** Verificar status e realizar testes de comunicação.<br><br>
**Operadores:**<br>
- Clicar no menu “Diagnóstico”.<br>
- Rolar lista de logs.<br>
- Digitar comando de teste no terminal.<br>
- Clicar em “Exportar Relatório”.<br>

**Método:**<br>
1. Abrir tela de Diagnóstico/Comunicação.<br>
2. Conferir status das conexões.<br>
3. Consultar registros de log.<br>
4. Enviar comando de teste.<br>
5. Exportar relatório se necessário.<br>

**Seletores:**<br>
- Se status normal → apenas registrar.<br>
- Se erro → reenviar comando ou acionar suporte.<br>

Resumo: O usuário entra na tela de diagnóstico, checa conexões, analisa logs, testa comandos e exporta relatórios em caso de falhas.<br>

### CTT

<img width="655" height="439" alt="image" src="https://github.com/user-attachments/assets/20763361-c430-42ef-9db1-e743c0caa291" />

# Tela de Controle Manual
## Enviar Comandos Manuais para Juntas
### HTA
O usuário seleciona a junta, define o valor desejado (slider ou numérico) e envia o comando para execução imediata.

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

<img width="641" height="336" alt="image" src="https://github.com/user-attachments/assets/8c8f6745-ff2b-4c0b-8800-d7fc7478a84d" />

