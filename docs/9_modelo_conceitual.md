# Modelo Conceitual

## Cenário de Interação

### Cenário A - Tela Inicial
**Atores:** Estudantes, pesquisadores e curiosos por robótica.

Atualmente, pesquisadores e instituições interessadas em robôs humanoides preferem a página inicial de portais sobre robótica que **agrupem conteúdo de forma centralizada**, pois isso evita a necessidade de buscar informações em fontes fragmentadas, como vídeos dispersos, repositórios técnicos e artigos soltos. A falta de um ponto único de referência dificulta a compreensão das capacidades e objetivos de projetos técnicos. **Páginas iniciais que destacam descrições, imagens e demonstrações em um único local tornam mais fácil entender o propósito e as aplicações de tecnologias complexas.**<br>
Muitas vezes, ao encontrar informações isoladas, os visitantes não têm acesso a vídeos demonstrativos claros ou material multimídia confiável. **Quando há uma seção com vídeos oficiais e exemplos de uso reunidos, o visitante consegue visualizar rapidamente o funcionamento prático e avaliar a relevância do projeto.** A ausência de imagens explicativas e materiais de contextualização faz com que o público leigo tenha dificuldade em captar o valor da tecnologia. **Textos e blocos informativos que explicam objetivos, diferenciais e aplicações ajudam a transformar o interesse inicial em oportunidade de engajamento.**

### Cenário B - Tela de Venda
**Atores:** Representante institucional, gestor de laboratório, comprador público.

Atualmente, instituições interessadas em adquirir robôs enfrentam um processo burocrático e desorganizado [1]. **Em situações de interesse, o comprador acessa páginas informativas que exibem valores estimados, prazos e especificações de forma direta**, eliminando a necessidade de solicitar cotações por e-mail ou telefone [2]. **Ao dispor dessas informações de forma clara, o representante consegue rapidamente avaliar a viabilidade orçamentária e decidir prosseguir com a compra**, reduzindo o tempo gasto em trocas de mensagens e diminuindo a perda de oportunidades [3].<br>
Muitos locais que divulgam projetos técnicos mostram apenas artigos ou resultados de pesquisa, sem um caminho simples para manifestar interesse comercial [4]. **Quando existe uma seção dedicada para formalizar pedidos de cotação, o representante preenche dados institucionais básicos e recebe confirmação imediata de recebimento**, sem necessidade de criar conta ou negociar por e-mail, o que evita o abandono do processo por falta de praticidade [5].

### Cenário C - Diagnóstico / Comunicação
**Atores:** Técnico de manutenção, pesquisador em laboratório, operador remoto.

Em muitas soluções atuais de robótica, o diagnóstico e a comunicação com o robô são feitos por meio de linhas de comando complexas [1]. Isso exige conhecimento técnico avançado e dificulta a identificação rápida de falhas [2]. **Quando o operador deseja verificar o status de comunicação, ele costuma acessar uma área dedicada onde é possível visualizar indicadores de conexão de cada subsistema, em vez de depender apenas de comandos textuais.**<br>
Quando o robô perde conexão com algum componente, o operador precisa acessar múltiplos terminais e logs separados para verificar o problema [3]. Esse processo é demorado e propenso a erros, principalmente durante demonstrações públicas ou testes laboratoriais [4]. **Ao reunir informações relevantes em um único painel, o operador consegue testar conexões, interpretar registros e executar comandos de diagnóstico com menor risco de erro humano e com maior velocidade.**<br>
Além disso, a falta de uma interface visual integrada impede a visualização em tempo real do status de cada módulo, tornando o monitoramento ineficiente [5].**Com indicadores visuais de conectividade e operação, o operador entende rapidamente o status global do sistema, consegue reagir a falhas durante testes ao vivo e possui clareza imediata sobre o estado dos módulos sem necessidade de interromper a execução para leitura de logs complexos.**

### Cenário D - Controle Manual
**Atores:** Operador remoto, pesquisador em testes, desenvolvedor de controle.

Hoje, o controle manual dos movimentos de um robô humanoide costuma depender de scripts ou códigos diretos enviados via terminal [1]. Essa abordagem aumenta o risco de erro humano e dificulta ajustes finos durante testes [2]. **Quando o operador deseja ajustar manualmente uma junta, ele acessa uma área de controle dedicada, onde pode selecionar a junta desejada e visualizar o valor atual antes de enviar o comando de movimentação.**<br>
Em muitos casos, o operador precisa alterar parâmetros manualmente em arquivos de configuração ou enviar comandos serializados, sem nenhum retorno visual sobre o estado atual das juntas [3]. Esse processo é lento, inseguro e pouco intuitivo [4]. **Com o uso de elementos visuais como sliders e valores numéricos exibidos em tempo real, o operador possui maior precisão na decisão do valor a ser enviado e consegue observar instantaneamente o impacto da alteração.**<br>
Sem uma interface dedicada, torna-se inviável realizar demonstrações interativas ou ensinar o uso do robô para novos pesquisadores [5]. **Ao visualizar feedback imediato da execução do comando — como o valor atualizado da junta — o operador reduz erros, aumenta a segurança durante a manipulação do robô e torna o processo mais adequado até mesmo para usuários menos experientes.**

## **Design Centrado na Comunicação**

**Tela Inicial**

| tópico \> subtópico (diálogo) | falas e signos |
| :---- | :---- |
| apresentar visão geral do projeto | U: Quero entender o que é esse robô humanoide. |
| > centralizar informações importantes | D: Aqui está a página inicial com descrição, imagens e demonstrações em um único lugar. |
| comparar com buscas fragmentadas | U: Geralmente eu tenho que procurar vídeo em YouTube, GitHub, sites aleatórios… tudo separado.<br>D: Nesta página inicial o conteúdo está agrupado — textos, fotos e vídeos oficiais em uma única interface.  |
| > visualizar demonstrações oficiais | D: Aqui estão os vídeos de uso real do robô humanoide. |
| construir contexto técnico | U: Esses blocos explicando os objetivos e aplicações me ajudam a entender o valor da tecnologia. |
| converter interesse em engajamento | D: Quando você quiser explorar mais, pode acessar os menus de controle manual e diagnósticos.

**Tela de Compra**

| tópico > subtópico (diálogo) | falas e signos |
| :---- | :----|
| consultar informações de compra | U: Quero saber quanto custa esse robô e quais são as condições de aquisição. |
| > exibir valores estimados, prazos e especificações | D: Aqui estão os valores estimados, prazos e especificações de forma direta — sem necessidade de envio de email ou ligação. |
| avaliar viabilidade rápida | U: Assim consigo verificar se isso cabe no orçamento da instituição sem ficar esperando retorno de cotação. |
| reduzir burocracia | D: O objetivo é diminuir o tempo gasto em trocas de mensagens e evitar perda de oportunidades de aquisição. |
| solicitar cotação formal | U: Certo, quero formalizar a intenção de compra. Onde faço isso? |
| > formulário direto sem criar conta | D: Aqui está a seção dedicada para formalizar pedido de cotação — basta preencher os dados institucionais básicos. |
| confirmação imediata | U: Depois que eu preencher, preciso esperar um e-mail de aprovação? |
| > notificação instantânea | D: Não — a confirmação é imediata, sem necessidade de criar login ou continuar por email, tornando o processo mais prático. |

**Diagnóstico / Comunicação**

| tópico > subtópico (diálogo) | falas e signos |
| :----| :----|
| verificar status de comunicação do robô | U: Preciso conferir se todos os subsistemas do robô estão conectados corretamente. |
| > visualizar indicadores de conexão | D: Aqui estão os indicadores de conexão de cada módulo — sem depender apenas de comandos textuais. |
| identificar perda de conexão | U: Um dos módulos parece não estar respondendo, preciso saber onde está a falha. |
| > avaliar logs e terminais em ambiente centralizado | D: Todas as informações de diagnóstico estão reunidas em um único painel — sem necessidade de abrir múltiplos terminais separados. |
| melhorar velocidade de diagnóstico | U: Assim consigo entender mais rápido o que está acontecendo, principalmente durante demonstrações ao vivo. |
| > reduzir risco de erro humano | D: Aqui é possível testar conexões, interpretar registros e executar comandos de diagnóstico com menor risco de erro. |
| monitorar operação em tempo real | U: Consigo ver agora o status de cada módulo enquanto tudo está rodando? |
| > indicadores visuais de conectividade e operação | D: Sim — os indicadores visuais mostram o estado global do sistema em tempo real, sem precisar parar o robô para ler logs complexos. |

**Controle Manual**

| tópico > subtópico (diálogo) | falas e signos |
| :---- | :---- |
| controlar manualmente os movimentos do robô | U: Preciso ajustar manualmente uma junta do robô para calibrar o movimento. |
| > selecionar junta e visualizar valor atual | D: Aqui é possível escolher qual junta será controlada e ver o valor atual antes de enviar qualquer comando. |
| enviar comando com precisão | U: Quero enviar um comando de movimentação com um valor mais seguro e preciso. |
| > uso de sliders e valores numéricos em tempo real | D: Os sliders e os valores numéricos mostram em tempo real a escala de movimento — facilitando a escolha exata do valor desejado. |
| observar resultado da alteração | U: Preciso confirmar se o movimento realmente foi executado da forma esperada. |
| > feedback imediato da execução do comando | D: O valor atualizado da junta é exibido imediatamente, reduzindo risco de erro e aumentando a segurança da manipulação. |
| ensinar e demonstrar a operação a novos usuários | U: Quero usar essa interface durante uma demonstração com novos pesquisadores. Eles não dominam comandos via terminal. |
| > operação visual acessível a usuários menos experientes | D: O controle visual substitui comandos complexos — permitindo demonstrações interativas mesmo para quem não tem conhecimento técnico profundo. |

## **Mapa de Objetivos**
<img width="1072" height="707" alt="image" src="https://github.com/user-attachments/assets/af1d985d-7e9d-49ce-b28e-92b534bb312c" />

**Legenda:** <br>
<img width="335" height="373" alt="image" src="https://github.com/user-attachments/assets/6b8ae84a-393b-4312-ad2d-2273426d7562" />

## Explorar pagina inicial ##
| signo                          | origem  | observações                  | Tipo de conteúdo | restrição sobre conteúdo      | valor default                    | prevenção                                                  | recuperação                                                                                             |
| ------------------------------ | ------- | ---------------------------- | ---------------- | ----------------------------- | -------------------------------- | ---------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| lista de vídeos demonstrativos | domínio | coleção de vídeos oficiais   | vídeo            | deve ter pelo menos 1 item    | —                                | PP: indicar “vídeo oficial demonstrativo” / mini‐descrição | RA: caso indisponível → informar “vídeo não disponível temporariamente”                                   |
| informações técnicas do robô   | domínio | specs gerais, resumo técnico | texto/numérico   | não pode ter campos em branco | texto básico institucional       | PA: impedir publicação se houver campo vazio               | RA: indicar qual campo não foi preenchido corretamente                                                    |
| galeria de imagens do robô     | domínio | imagens reais do modelo      | imagem           | deve ter pelo menos 1 imagem  | imagem placeholder institucional | PP: legenda indicando que imagens são oficiais             | RA: mostrar placeholder se faltar imagem                                                                  |
| resumo centralizado do projeto | domínio | descrição macro do robô      | texto            | não pode ser nulo             | resumo institucional             | PP: destacar texto introdutório curto no topo da página    | CE: se o conteúdo não puder ser carregado (corrompido / remoto) informar para tentar novamente mais tarde |

## Comprar robô ##
| signo                      | origem  | observações                      | Tipo de conteúdo | restrição sobre conteúdo                     | valor default             | prevenção                                            | recuperação                                                             |
| -------------------------- | ------- | -------------------------------- | ---------------- | -------------------------------------------- | ------------------------- | ---------------------------------------------------- | ----------------------------------------------------------------------- |
| modelo de robô selecionado | usuário | escolha de um modelo disponível  | texto / seleção  | deve existir na lista de modelos do domínio  | —                         | PA: só habilitar modelos válidos / catálogo          | RA: caso modelo removido → mensagem para selecionar outro               |
| preço exibido              | domínio | valor monetário do modelo        | numérico         | não pode ser negativo                        | —                         | PP: mostrar formato monetário (R$ xxx,xx)            | RA: mostrar mensagem “valor indisponível no momento”                    |
| adicionar itens opcionais  | usuário | upgrades, módulos extra          | lista seleção    | cada item deve estar no catálogo             | lista vazia               | PA: impedir seleção de item não disponível           | RA: remover item inválido e notificar                                   |
| prazo estimado de entrega  | domínio | cálculo baseado em CEP + estoque | texto/numérico   | deve ter formato válido (ex: “7 dias úteis”) | —                         | PP: label “estimativa”                               | AL: se prazo maior que média, pedir confirmação                         |
| método de pagamento        | usuário | cartão / pix / boleto            | seleção          | não pode ser nulo                            | —                         | PA: só habilitar “finalizar” após método selecionado | RA: caso método inválido → pedir nova seleção                           |
| finalizar pagamento        | usuário | ação final                       | ação             | depende de método escolhido                  | desabilitado inicialmente | PA: botão desabilitado até condição válida           | CE: transação falhou → instruir a tentar outro método / contato suporte |

## Diagnosticar status do sistema ##

| signo                             | origem  | observações                                     | tipo de conteúdo | restrição                                    | valor default | prevenção                                                       | recuperação                                             |
| --------------------------------- | ------- | ----------------------------------------------- | ---------------- | -------------------------------------------- | ------------- | --------------------------------------------------------------- | ------------------------------------------------------- |
| lista de módulos detectados       | domínio | módulos encontrados no scan de hardware ou rede | lista            | pode estar vazia se não detectar nenhum      | lista vazia   | PP: label “Nenhum módulo detectado ainda”                       | CE: instruir checar cabos / alimentação                 |
| status do módulo selecionado      | domínio | ping / heartbeat / flag de estado               | texto / cor      | deve estar em {OK, Falha, Instável}          | —             | PA: somente mostrar estados válidos                             | RA: destacar módulo com falha e sugerir retestar        |
| botão “testar módulo”             | usuário | ação que dispara ping/handshake                 | ação             | só válido se um módulo estiver selecionado   | desabilitado  | PA: botão desabilita enquanto não há seleção                    | RA: exibir mensagem de falha do teste                   |
| log de resposta                   | domínio | texto retornado do teste                        | texto            | pode ser vazio                               | vazio         | PP: aviso “log será exibido após teste”                         | RA: destacar linhas com erro                            |
| botão “testar todos”              | usuário | varre todos módulos                             | ação             | só habilitado se existir pelo menos 1 módulo | desabilitado  | AL: aviso “isso pode levar alguns segundos — deseja continuar?” | CE: se timeouts massivos → sugerir checar rede física   |
| indicador visual global de status | domínio | a soma do estado dos módulos                    | cor / ícone      | deve sempre refletir o estado computado      | —             | PA: não deixar selecionar cor arbitrária                        | RA: exibir mensagem “status atualizado após retestagem” |

## Realizar controle manual ##

| signo                      | origem  | observações                              | tipo de conteúdo        | restrição                                           | valor default          | prevenção                                      | recuperação                                             |
| -------------------------- | ------- | ---------------------------------------- | ----------------------- | --------------------------------------------------- | ---------------------- | ---------------------------------------------- | ------------------------------------------------------- |
| junta selecionada          | domínio | junta atual que o slider está comandando | item de lista           | deve existir no catálogo de juntas                  | —                      | PA: só permite selecionar juntas existentes    | RA: se junta inválida → mensagem “junta não encontrada” |
| slider posição da junta    | usuário | movimenta posição alvo                   | valor numérico contínuo | limitado ao range mecânico da junta (ex: 0° a 180°) | posição atual da junta | PA: bloqueia arrastar além do limite           | RA: se motor recusar → mostrar erro do driver           |
| valor numérico atual       | domínio | mostra leitura atual do encoder / sensor | número contínuo         | deve refletir estado real da junta                  | leitura atual          | PP: label “valor monitorado em tempo real”     | RA: se leitura falhar → texto “leitura indisponível”    |
| botão “enviar movimento”   | usuário | confirma comando de posição              | ação                    | só habilitado se slider mudou de estado             | desabilitado           | AL: confirmação “aplicar este valor ao robô?”  | RA: se actuator falhar → mensagem com causa             |
| botão “resetar posição”    | usuário | retorna a posição neutra/base da junta   | ação                    | só habilitado se não está na posição neutra         | desabilitado           | AL: “reset irá mover fisicamente — confirmar?” | CE: se falhar reset → instruir checar hardware          |
| indicador de carga/esforço | domínio | sensor de carga (torque)                 | número contínuo         | range seguro definido pelo fabricante               | valor atual            | PP: legenda explicando faixa segura            | RA: se ultrapassa → destacar vermelho e sugerir parar   |

