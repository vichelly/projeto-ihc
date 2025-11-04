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
> **_NOTE:_**: cada um coloca seu mapa de objetivos e deverá ter um diagrama de consolidação

4) **Esquema Conceitual de Signos**

> **_NOTE:_**: fazer a junção das 3 tabelas abaixo em uma única

| Credenciais (C) \- credenciais para acesso ao sistema |  |  |
| :---- | :---- | :---- |
| **signo** | **origem** | **observações** |
| usuário | domínio |  |
| senha | domínio |  |

| Credenciais (C) \- credenciais para acesso ao sistema |  |  |  |
| :---- | :---- | :---- | :---- |
| **signo** | **Tipo de conteúdo** | **restrição sobre conteúdo** | **valor default** |
| usuário | texto | não pode ser nulo | — |
| senha | texto | não pode ser nulo | — |

| Credenciais (C) \- credenciais para acesso ao sistema |  |  |
| :---- | :---- | :---- |
| **signo** | **prevenção** | **recuperação** |
| usuário | PP: campo obrigatório | RA |
| senha | PP campo obrigatório  | RA |
