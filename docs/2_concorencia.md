# Análise de concorrência

- **[Shadow Robot Company](https://shadowrobot.com)** → mãos robóticas dexterous para manipulação fina e teleoperação.
  <img width="1495" height="738" alt="image" src="https://github.com/user-attachments/assets/1eb2f2f7-4f5c-4c6b-a7d7-d139c5790c7f" />
- **[Poppy Project](https://www.poppy-project.org/en)** → mãos robóticas dexterous para manipulação fina e teleoperação.
  <img width="984" height="604" alt="image" src="https://github.com/user-attachments/assets/c4bac2d3-127a-46f4-b04f-d5cd27c9479d" />
- **[Kinova Gen3](https://www.kinovarobotics.com/product/gen3-robots)** → mãos robóticas dexterous para manipulação fina e teleoperação.
  <img width="1504" height="846" alt="image" src="https://github.com/user-attachments/assets/0b2a1d81-dccf-4e2c-a546-c88c6ea08e9f" />
  
---

## Quadro Comparativo

| Campo                | Shadow Robot Company | Poppy Project | Kinova Gen3 |
|----------------------|----------------------|---------------|-------------| 
| **Produto-âncora**   | Dexterous Hand (mão robótica 5-dedos, ~20 DoF, múltiplos sensores táteis e posicionais) | Humanoide open-source modular (3D printed, controlado por ROS) | Braço robótico leve (6/7 DoF), projetado para pesquisa e reabilitação |
| **Funcionalidades**  | Manipulação hábil, sensores táteis, integração EtherCAT, teleop avançado | Plataforma modular humanoide/quadrúpede, fácil de customizar, integração com ROS, Python e simuladores | Controle preciso, integração ROS nativa, teleoperação, sensores de torque, leve e portátil |
| **UX Reportado**     | Alta destreza; curva de aprendizado e integração elevada; usado em nichos críticos (nuclear) | Amigável para pesquisadores e makers; requer montagem e calibração manual | Fácil de usar em laboratórios; confiável para teleoperação; curva de aprendizado moderada |
| **Modelo de Negócio**| Venda B2B sob encomenda; bundles com consultoria e suporte | Open-source + kits vendidos por parceiros; comunidade ativa | Venda comercial direta (B2B, academia, pesquisa), suporte e manutenção |
| **Faixa de Preço**   | ~US$100k+ (sistemas completos, varia conforme opções) | Baixo custo (kits ~€8k–15k dependendo do distribuidor) | ~US$25k–40k dependendo da configuração |
| **Forças**           | Destreza de referência; sensores avançados; histórico em aplicações críticas | Open-source, acessível, personalizável; forte comunidade de pesquisa | Precisão, leveza, integração ROS, usado em reabilitação e pesquisa |
| **Fraquezas**        | Custo muito elevado; integração complexa; suporte customizado | Limitações mecânicas (impressão 3D), não indicado para cargas pesadas | Preço ainda alto para hobby/educação; limitado a braço, não humanoide completo |
| **Oportunidades**    | Manipulação fina em ambientes perigosos; nichos onde cobots não chegam | Ensino, pesquisa, robótica educativa e prototipagem rápida | Aplicações em saúde, reabilitação, teleop em ambientes insalubres |
| **Ameaças**          | Mãos robóticas mais baratas e modulares; evolução de luvas hápticas | Concorrência de kits educacionais mais baratos e braços robóticos low-cost | Concorrência de braços mais baratos (DIY, open-source); players maiores em reabilitação |

---

## 🎯 UX — Observações do Mercado
- **Shadow:** altíssima destreza e qualidade tátil, porém requer integração especializada.  
- **Poppy:** fácil de usar em pesquisa, acessível, mas limitado em robustez mecânica.  
- **Kinova Gen3:** experiência confiável, pensado para integração ROS, muito usado em laboratórios.  

---

## 💰 Preços e Modelos de Negócio
- **Shadow:** modelo B2B, venda sob encomenda, ticket médio na casa de **US$100k+**.  
- **Poppy:** modelo open-source, kits de hardware entre **€8k–15k**.  
- **Kinova Gen3:** venda comercial para pesquisa/indústria, faixa de **US$25k–40k**.  

---

## 📊 Padrões e Tendências
1. Integração completa: manipulação + háptica + visão.  
2. Oferta como solução (hardware + software + suporte + SLA).  
3. Forte valorização de tecnologias que reduzam exposição humana em ambientes insalubres.  
4. Mercado segmentado: players high-end atendem nichos críticos → abre espaço para soluções **acessíveis e modulares**.  
5. Crescente interesse em **open-source humanoides (Poppy, InMoov)** e **braços de fácil integração (Kinova)**.  

---

## ✅ Pontos Positivos / Negativos
- **Shadow** → (+) Destreza e sensores de referência / (–) Preço alto e integração difícil.    
- **Poppy** → (+) Open-source e acessível / (–) Mecânica limitada, não robusta para indústria.  
- **Kinova Gen3** → (+) Precisão, confiabilidade, integração ROS / (–) Preço elevado para fora do meio acadêmico.  

---

## 📌 Conclusão
- **Shadow** é referência em manipulação fina, mas inacessível para a maioria dos usuários comuns.  
- **Poppy** abre espaço em pesquisa e educação com baixo custo e modularidade.  
- **Kinova Gen3** é forte em aplicações de saúde e pesquisa, equilibrando robustez e integração.  
- O **ATENA** pode se destacar ao oferecer **humanoide acessível, modular, com teleoperação via visão computacional e integração ROS2 + MQTT**, atingindo um público que hoje fica entre o open-source experimental e os sistemas comerciais caros.


---
> **_NOTE:_**: O fator mais importante desta entrega é a equipe conseguir identificar e documentar prints de telas de interfaces concorrentes (ou interfaces representativas para o público alvo). Esses prints serão usados na fase de caracterização de padrões, affordances, heurísticas, etc. CONCORRENTE NÃO É IDÊNTICO E SIM ATUANDO NA MESMA ÁREA
1. Identifique os principais concorrentes mais utilizados pelo seu público-alvo. X
> **_NOTE:_**: link, descrição e imagens de ilustração
2. Descreva as características e funcionalidades de cada concorrente.
3. Colete opniões sobre a experiência do usuário (UX) de cada concorrente.
4. Apresente os preços e modelos de negócio de cada concorrente.
5. Identifique padrões e tendências no mercado.
6. Elabore relatórios e sumarize os resultados.
7. Extraia pontos positivos/negativos e faça recomendações.
