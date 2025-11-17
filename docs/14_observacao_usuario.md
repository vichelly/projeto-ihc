# 1.Fluxograma de Avaliação de Usabilidade por Observação do Usuário

<img alt="Fluxograma_observacao_usuario.png" src="imagens/observacao_usuario/Fluxograma_observacao_usuario.png" width="300"/>


---


# 2.Descrição do Procedimento de Preparação do Teste

| Passo        | Descrição                                                                               |
| ------------ | --------------------------------------------------------------------------------------- |
| Passo 1 | Definição de Objetivos, Escopo e Método (Observação remota, 4 usuários distintos) |
| Passo 2 | Elaboração da lista de 4 tarefas-cenário (Início, Adquirir, Diagnóstico, Controle).                     |
| Passo 3 | Definição dos 4 perfis de usuário (Pesquisador, Leigo, Técnico, Comprador).  |
| Passo 4 | Preparação do Material de Apoio (TCLE, Roteiro de tarefas, Questionários).                      |
| Passo 5 | Preparação do Ambiente Remoto (Google Meet + Link do App) e realização de teste-piloto.                                |
| Passo 6 | Observação individual de cada participante executando as tarefas (remotamente).                                      |
| Passo 7 | Registro de tempo, erros, grau de sucesso e reações comportamentais.                                          |
| Passo 8 | Aplicação de questionário de satisfação pós-teste e entrevista breve.                                           |
| Passo 9 | Consolidação dos dados (tabelas) e análise de tendências (conclusão).                                           |


---


# 3.Resultados do teste

### Vitor Lucas

| Tarefa | Grau de Sucesso | Total de Erros | Tipos de Erros                                           | Tempo Necessário | Grau de Satisfação |
| ------ | --------------- | -------------- | -------------------------------------------------------- | ---------------- | ------------------ |
| 1      | Sucesso    | 1              | (1) Clicou no botão "Dashboard" (Hero) antes de rolar para ver o vídeo e o form.           | 12s               |  Satisfeito    |
| 2      | Sucesso  | 0              | - | 36s              | Satisfeito      |
| 3      | Sucesso  | 2              | (1) Tentou clicar no "Robot Model" (SVG) para obter logs. (1) Demorou para achar o filtro de logs.       | 1 min 15 seg              | Satisfação alta  |
| 4      | Sucesso  | 1              | (1) Não encontrou botão “Exportar PDF” de imediato       | 1 min 15 seg              | Satisfação alta  |

### Murilo 

| Tarefa | Grau de Sucesso | Total de Erros | Tipos de Erros                                  | Tempo Necessário | Grau de Satisfação |
| ------ | --------------- | -------------- | ----------------------------------------------- | ---------------- | ------------------ |
| 1      | Sucesso Total   | 0              | —                                               | 5s               | Muito satisfeita   |
| 2      | Sucesso Parcial   | 2              | (1) Clicou em "Finalizar Pagamento" sem preencher os campos (esperava validação). (1) Se assustou com o preço.| 8s               | Alta satisfação    |
| 3      | Falha | 4              | (1) Clicou no "Terminal" e digitou "ajuda". (1) Não entendeu a diferença de MQTT/ROS2. (1) Se sentiu "sobrecarregado" com os logs. (1) Desistiu. | timeout              | Frustração Alta  |
| 4      | Falha | 3              | (1) Moveu o slider do ombro para 180° bruscamente. (1) Tremeu ao ver o modelo 2D se mexer. (1) Desistiu com "medo de quebrar". | 40s              | Confusão  |


### Juan
| Tarefa | Grau de Sucesso | Total de Erros | Tipos de Erros                                                | Tempo Necessário | Grau de Satisfação |
| ------ | --------------- | -------------- | ------------------------------------------------------------- | ---------------- | ------------------ |
| 1      | Sucesso  | 0              | -    | 9s               | Leve frustração    |
| 2      | Não Tentou   | 0              | —                                                             | -               | -    |
| 3      | Sucesso  | 1              | (1) Elogiou os filtros de logs, mas queria salvar/exportar uma visualização filtrada, não apenas o JSON. | 13s              | Satisfação alta  |
| 4      | Sucesso  | 0              | (Testou os limites, o reset, e a gravação. Elogiou os limites de segurança). | 60s              | Satisfação  |

### Rafael
| Tarefa | Grau de Sucesso | Total de Erros | Tipos de Erros                                                | Tempo Necessário | Grau de Satisfação |
| ------ | --------------- | -------------- | ------------------------------------------------------------- | ---------------- | ------------------ |
| 1      | Sucesso  | 0              | (Leu as seções "Estatísticas" e "Sobre o Projeto" com atenção).    | 1 min 50 seg              | Satisfeito    |
| 2      | Sucesso   | 1              |     (1) Não entendeu o que era "Base Móvel" e procurou descrição (não havia).          |    1 min 05 seg            | Satisfeito    |
| 3      | Não Tentou  | 0              | - | -              | -  |
| 4      | Não Tentou  | 0              | - | -              | -  |

---

# Conclusão da avaliação por observação do usuário

*Pontos positivos*
- Interface intuitiva e fluida para tarefas básicas.

- Processo de configuração de layout rápido e direto.

- Feedback visual adequado ao salvar configurações.

- Ferramentas de relatório com resultados visualmente claros (dashboard e heatmap).

*Pontos negativos*
- Falta de feedback visual em algumas operações (ex: exportação).

- Ausência de confirmação preventiva antes de exclusões e exportações.

- Alguns ícones e rótulos pouco claros para usuários inexperientes.

- Necessidade de documentação contextual (ex: pequenos tutoriais no sistema).
