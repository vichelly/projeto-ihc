# Análise de Tarefas

> **_NOTE:_**: A equipe deve descrever as funcionalidades mais importantes da interface/produto. A equipe deve modelar pelo menos 1 HTA, 1 GOMS e 1 CTT (de pelo menos 4 funcionalidades diferentes). Cada diagrama deve ter um texto explicando a funcionalidade.

# Tela Inicial 
## Pagina inicial do ATENA
### HTA

### GOMS

### CTT

# Tela de Venda 
## Venda do robô
### HTA

### GOMS

### CTT

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

<img width="1132" height="536" alt="image" src="https://github.com/user-attachments/assets/dfd72e0d-a207-4957-952b-4ec8da85013a" />

**Legenda CTT:**<br>
<img width="399" height="344" alt="image" src="https://github.com/user-attachments/assets/b476b39b-1338-43a7-96e9-d2e6d1914cb4" />

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

<img width="1155" height="386" alt="image" src="https://github.com/user-attachments/assets/7d859570-dd77-417a-a062-b6eb2667e98d" />

**Legenda CTT:**<br>
<img width="399" height="344" alt="image" src="https://github.com/user-attachments/assets/b476b39b-1338-43a7-96e9-d2e6d1914cb4" />
