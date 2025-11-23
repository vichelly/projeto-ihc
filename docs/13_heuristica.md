1) **Avaliação de IHC através de inspeção HEURÍSTICA \[1 solução completa por pessoa da equipe \- todas as telas do projeto\]**

> **_NOTE:_**: SOMENTE VIOLAÇÕES

Dez Heurísticas de Nielsen

**Descrição da avaliação**

Avaliação heurística, definida por Nielsen e Molich (1994), é um método de avaliação de usabilidade onde um avaliador procura problemas de usabilidade numa interface com o usuário através da análise e interpretação de um conjunto de princípios ou heurísticas. Este método de avaliação é baseado no julgamento do avaliador.

**Tabela 1 \- Conjunto de heurísticas de Nielsen (1994)**

| **1\.** | **Visibilidade do status do sistema:** |
| :---- | :---- |
| O sistema deve sempre manter os usuários informados sobre o que está acontecendo através de feedback apropriado, em um tempo razoável. | Não há feedback explícito ao clicar nos botões de "Iniciar Replicação", "Modo Demo" e "Desligar" na tela de Diagnóstico. <br><br> **Correção:** Adicionar um pop-up demonstrando feedback sobre o status da operação realizada <br><br> **Grau de severidade:** 1 (Cosmético) - Não há necessidade de correção imediata.|
| **2\.** | **Compatibilidade entre sistema e mundo real:**|
| O sistema deve utilizar a linguagem do usuário, com palavras, frases e conceitos familiares para ele, ao invés de termos específicos de sistemas. Seguir convenções do mundo real, fazendo com que a informação apareça em uma ordem lógica e natural. | N/A |
| **3\.** | **Controle e liberdade para o usuário:** |
| Estão relacionados à situação em que os usuários frequentemente escolhem as funções do sistema por engano e então necessitam de "uma saída de emergência” claramente definida para sair do estado não desejado sem ter que percorrer um longo diálogo, ou seja, é necessário suporte a *undo* e *redo*. | Não há opção de "Undo" ao alterar os sliders na tela de Controle Manual. <br><br> **Correção:** Adicionar um botão de undo para cada slider, para que seja possível que o usuário retorne à um estado anterior <br><br> **Grau de severidade:** 2 (Simples) - Problema de baixa prioridade (pode ser reparado). |
| **4\.** | **Consistência e padrões:** |
| Referem-se ao fato de que os usuários não deveriam ter acesso a diferentes situações, palavras ou ações representando a mesma coisa. A interface deve ter convenções não-ambíguas. | Ícones de Início e Diagnóstico são iguais. <br><br> **Correção:** Alterar um dos ícones para que ambos tenham uma identidade própria <br><br> **Grau de severidade:** 1 (Cosmético) - Não há necessidade de correção imediata. |
| **5\.** | **Prevenção de erros:** |
| Os erros são as principais fontes de frustração, ineficiência e ineficácia durante a utilização do sistema. | Não há aviso de confirmação antes de executar testes no diagnóstico nem no controle manual. <br><br> **Correção:** Adicionar um aviso e obrigar o usuário confirmar ciência do usuário antes de permitiar a execução de testes <br><br> **Grau de severidade:** 4 (Muito Grave) - Muito grave, deve ser reparado de qualquer forma |
| **6\.** |  **Reconhecimento em lugar de lembrança:** |
| Tornar objetos, ações, opções visíveis e coerentes. O usuário não deve ter que lembrar informações de uma parte do diálogo para outra. Instruções para o uso do sistema devem estar visíveis ou facilmente acessíveis. | N/A |
| **7\.** | **Flexibilidade e eficiência de uso:** |
| A ineficiência nas tarefas pode reduzir a eficácia do usuário e causar-lhes frustração. O sistema deve ser adequado tanto para usuários inexperientes quanto para usuários experientes. | Não há uma opção para buscar informações nos logs. <br><br> **Correção:** Adicionar uma opção de busca nos logs <br><br> **Grau de severidade:** 3 (Grave) - Problema de alta prioridade (deve ser reparado) |
| **8\.** | **Projeto minimalista e estético:** |
| Os diálogos não devem conter informações irrelevantes ou raramente necessárias. Cada unidade extra de informação em um diálogo compete com unidades relevantes e diminui sua visibilidade relativa. | N/A |
| **9\.** | **Auxiliar os usuários a reconhecer, diagnosticar e recuperar erros:** |
| Mensagens de erro devem ser expressas em linguagem natural (sem códigos), indicando precisamente o erro e sugerindo uma solução. | Não há uma solução para erros que aparecem nos logs. <br><br> **Correção:** Adicionar uma possível solução para caso um erro seja retornado nos logs <br><br> **Grau de severidade:** 3 (Grave) - Problema de alta prioridade (deve ser reparado) |
| **10\.** | **Ajuda e documentação:** |
| Mesmo que seja melhor que o sistema possa ser usado sem documentação, pode ser necessário fornecer ajuda e documentação. Tais informações devem ser fáceis de encontrar, ser centradas na tarefa do usuário, listar passos concretos a serem seguidos e não ser muito grandes. A ajuda deve estar facilmente acessível e on-line. | Não há um botão de ajuda em nenhuma tela do sistema. <br><br> **Correção:** Adicionar um botão de ajuda para cada módulo do sistema <br><br> **Grau de severidade:** 2 (Simples) - Problema de baixa prioridade (pode ser reparado) |

**Tabela 2 \- Grau de severidade dos problemas de usabilidade**

| Grau de severidade | Tipo | Descrição |
| ----- | :---- | :---- |
| 0 | Sem importância | Não afeta a operação da interface |
| 1 | Cosmético | Não há necessidade imediata de solução |
| 2 | Simples | Problema de baixa prioridade (pode ser reparado) |
| 3 | Grave | Problema de alta prioridade (deve ser reparado) |
| 4 | Catastrófico | Muito grave, deve ser reparado de qualquer forma. |

**Heuristica 1 - Visibilidade do estado do sistema:**
<img width="1273" height="933" alt="image" src="https://github.com/user-attachments/assets/dbc7e225-5129-4612-a268-eed4c9e6d4f8" />

> **_NOTE:_**: **escolher a tabela de declaração de violação padrão da equipe**

2) **INDICAÇÃO DE BOAS PRÁTICAS DE HEURÍSTICA \- HEURÍSTICAS NÃO VIOLADAS \[1 solução completa por pessoa da equipe\]**

> **_NOTE:_**: **1 EXEMPLO DO SEU SISTEMA ONDE A HEURÍSTICA FOI ATENDIDA (ISSO NÃO É USADO NO MERCADO, SERVE APENAS PARA APRENDIZADO)**
