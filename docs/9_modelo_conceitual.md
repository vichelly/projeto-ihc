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

### Cenário D - Dificuldade de Configuração e Ajuste
**Atores:** Operador remoto, pesquisador em testes, desenvolvedor de controle.

Hoje, o controle manual dos movimentos de um robô humanoide costuma depender de scripts ou códigos diretos enviados via terminal [1]. Essa abordagem aumenta o risco de erro humano e dificulta ajustes finos durante testes [2]. **Quando o operador deseja ajustar manualmente uma junta, ele acessa uma área de controle dedicada, onde pode selecionar a junta desejada e visualizar o valor atual antes de enviar o comando de movimentação.**<br>
Em muitos casos, o operador precisa alterar parâmetros manualmente em arquivos de configuração ou enviar comandos serializados, sem nenhum retorno visual sobre o estado atual das juntas [3]. Esse processo é lento, inseguro e pouco intuitivo [4]. **Com o uso de elementos visuais como sliders e valores numéricos exibidos em tempo real, o operador possui maior precisão na decisão do valor a ser enviado e consegue observar instantaneamente o impacto da alteração.**<br>
Sem uma interface dedicada, torna-se inviável realizar demonstrações interativas ou ensinar o uso do robô para novos pesquisadores [5]. **Ao visualizar feedback imediato da execução do comando — como o valor atualizado da junta — o operador reduz erros, aumenta a segurança durante a manipulação do robô e torna o processo mais adequado até mesmo para usuários menos experientes.**

2) **Design Centrado na Comunicação**

**Nome do Cenário: XXXXXX**

| tópico \> subtópico (diálogo) | falas e signos |
| :---- | :---- |
|  | U: Preciso … |
| \>  | U: Quero … D: Aqui está o mapa |
|  | U:  |
|  | U:  |
|  | D: Aqui está a informação filtrada |

3) **Mapa de Objetivos**
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
