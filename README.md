# Projeto O aumento na prevalência de perda auditiva: quais os motivos?
# Project The increase in the prevalence of hearing loss: what are the reasons?

# Apresentação

O presente projeto foi originado no contexto das atividades da disciplina de pós-graduação [*Ciência e Visualização de Dados em Saúde*](https://github.com/datasci4health/home), oferecida no primeiro semestre de 2021, na Unicamp.

|Nome                     | RA      | Especialização         |
|-------------------------|---------|------------------------|
| José Claudio Klier      | 190953  | Saúde                  |
| Júlia Ferreira Tessler  | 119655  | Computação             |
| Laura Chiriboga         | 207391  | Saúde - Fonoaudiologia |
| Yuliana Apaza           | 234986  | Computação             |


# Descrição Resumida do Projeto

De acordo com projeções realizadas pela Organização Mundial da Saúde (OMS), até 2050, uma em cada dez pessoas terão perda auditiva (PA) incapacitante (1). Portanto, sabe-se que a PA é e será um tema cada vez mais discutido e presente no cenário mundial, pois independentemente da idade, provoca consequências negativas na comunicação, no estado emocional, na educação e na qualidade de vida (2). Além disso, é estimado que US $ 1 trilhão é perdido a cada ano devido à nossa falha coletiva em abordar adequadamente este problema, se tornando um encargo financeiro enorme (3).

Observou-se uma grande movimentação de entidades importantes de saúde para alertar a respeito da perda auditiva e seus impactos. No contexto em que a perda auditiva muitas vezes ainda é referida como uma "deficiência invisível", não apenas por causa da falta de sintomas visíveis, mas porque há muito tempo é estigmatizado nas comunidades e ignorado pelos formuladores de políticas.

Em 3 de março de 2021 tivemos a publicação do primeiro Relatório Mundial da Audição (3), em que foram elencados diversos fatores sobre a perda auditiva, como:  a importância da audição durante a vida, soluções possíveis em casos de perdas auditivas, desafios encarados frente aos cuidados da orelha e da audição e um possível caminho futuro para a saúde pública auditiva. 

O relatório mostra que medidas de saúde pública baseadas em evidências e econômicas podem prevenir muitas causas de perda auditiva. Segundo os autores, “Prevenir e tratar doenças e deficiências de todos os tipos não é um custo, mas um investimento em um mundo mais seguro, justo e próspero para todas as pessoas”. 

Mas, mesmo com os esforços já existentes, vimos que a prevalência de perda auditiva está aumentando a cada ano. 

Visto isso, decidiu-se por tentar entender os motivos desta situação mundial. 

[Aqui](https://youtu.be/Usq-nvxmtDM) encontra-se o vídeo de apresentação do projeto.

[![O Aumento na Prevalência de Perda Auditiva: Quais os Motivos?](images/slide_title.jpg)](https://youtu.be/Usq-nvxmtDM)

# Perguntas de Pesquisa

Para a elaboração das perguntas de pesquisa, primeiramente analisamos um panorama geral das informações disponíveis a respeito do tema escolhido: perda auditiva. 

Após isso, elaboramos nossos questionamentos baseados no anagrama PICOT, de acordo com os componentes: população (especificar qual/quem é a amostra que estamos usando - especificar os critérios); intervenção ( o que quero saber se funciona/o que estou analisando); comparador (comparar com algo); desfecho (outcome) e tipo de estudo (delineamento que pretendemos utilizar para fazer a pesquisa).

P: indivíduos com perda auditiva

I: medidas de prevenção a perda auditiva e medidas de agravamento as perdas auditivas (comorbidades)

C: indivíduos sem perda auditiva

O: perda auditiva

T: estudo observacional descritivo

**PERGUNTA:  Quais os motivos da prevalência da perda auditiva estar aumentando, visto que existem esforços de promoção e prevenção de saúde?**

A prevalência da perda auditiva está aumentando, porque as medidas de promoção e prevenção em saúde não estão sendo eficientes? Quais os impactos da vida atual nesta prevalência? Será que as medidas de prevenção em saúde não estão sendo eficientes, ou na verdade é uma menor parte da população que está tendo acesso? Será que está aumentando por conta dos hábitos de vida atuais (aumento da expectativa de vida, aumento do sedentarismo e doenças cardiovasculares, uso de dispositivos eletrônicos de áudio e poluição sonora)?


# Bases de Dados

Encontrou-se bancos de dados disponíveis a respeito de saúde que incluem informações relacionadas à perda auditiva, dentre outras, o que permite estudos e modelagem de fatores a fim de responder às perguntas levantadas. São eles:

| Fontes de dados | Resumo descritivo |
|-----------------|-------------------|
| [National Health and Nutrition Examination Survey (NHANES)](https://wwwn.cdc.gov/nchs/nhanes/Default.aspx) | NHANES avalia a saúde e o estado nutricional de adultos e crianças nos Estados Unidos. NHANES inclui questões demográficas, socioeconômicas, dietéticas e relacionadas à saúde.Possui exames de audiometria dos indivíduos, além de dados de pressão arterial, dados dietéticos, dados laboratoriais, etc. (6, 7) |
| [Base de Dados dos Direitos da Pessoa com Deficiência](http://basededados.sedpcd.sp.gov.br/index.php) | Dados censitários e informações sobre a pessoa com deficiência nas áreas de educação, saúde, emprego e renda desenvolvimento entre outras. |
| [Global Burden of Disease Study 2017 / 2019](http://ghdx.healthdata.org/gbd-2019) | *Framework* para integrar, validar, analisar e disseminar informações para avaliar a importância comparativa das doenças, lesões e fatores de risco em causar morte prematura, perda de saúde e incapacidade em diferentes populações. |

# Metodologia

Este estudo é definido como estudo observacional descritivo. 

A seleção do tema se deu por meio da discussão do grupo perante as áreas de atuação dos profissionais da saúde que o compunham. Dentro os temas levantados, a saúde auditiva e mais propriamente a perda auditiva foi o escolhido.

Baseados nesta temática, o grupo levantou perguntas de interesse que poderiam ser respondidas por meio da ciência dos dados. Desta forma, o grupo se direcionou para buscar bases de dados condizentes para a pesquisa. As bases de dados estão referenciadas na seção anterior. 

A análise dos dados se baseou no processo de extração de conhecimento por meio de dados KDD - Knowledge Discovery in Databases, desenvolvida por Fayaad et. al.(1996), com intuito de visualizar insights de relações de interesse que não haviam sido previamente elencadas,  como também auxiliar na validação de conhecimento extraído. Segue abaixo o fluxograma do processo KDD (6, 7). 

![KDD Process](images/kdd.png)

# Ferramentas

**Nota:** mais ferramentas podem ser adicionadas ou excluídas ao longo da execução do projeto.

| **Ferramenta** | **Resumo descritivo** |
|----------------|-----------------------|
| Python 3.x.x   | Linguagem de programação |
| NumPy | Biblioteca do Python orientada a operação de vetores e matrizes multidimensionais |
| Pandas | Biblioteca do Python orientada a manipulação e análise de dados |
| Matplotlib | Biblioteca do Python para criação de gráficos e visualizações de dados |
| Jupyter Notebook | Documento virtual que permite execução de rotinas usuais de programação e documentação de todo o processo de produção do código |
| Google Colab | Ambiente de notebooks Jupyter que não requer configuração e é executado na nuvem |

# Cronograma

De acordo com com o planejamento das entregas propostos pela disciplina (Plano de projeto - E1 em 13 de abril; Base de Dados de Trabalho - E2 em 11 de maio; Entrega Final (EF) em 24 de junho e Apresentações (AP) em 24, 29 de junho e 1 de julho), segue abaixo:

| Momento                            | 1ª quinzena de abril | 2ª quinzena de abril | 1ª quinzena de maio | 2ª quinzena de maio | 1ª quinzena de junho | 2ª quinzena de junho |
|------------------------------------|----------------------|----------------------|---------------------|---------------------|----------------------|----------------------|
| **Levantamento da temática**       | *                    |                      |                     |                     |                      |                      |
| **Revisão de literatura**          | *                    |                      |                     |                     |                      |                      |
| **Definição das perguntas**        | *                    |                      |                     |                     |                      |                      |
| **Escolha das bases de dados**     | *                    | *                    |                     |                     |                      |                      |
| **Extração e análise dos dados**   |                      | *                    | *                   | *                   |                      |                      |
| **Elaboração do trabalho final**   |                      |                      |                     |                     | *                    |                      |
| **Apresentação do trabalho final** |                      |                      |                     |                     |                      | *                    |

# Referências Bibliográficas

1. World Health Organization. Deafness and hearing loss [Internet]. 2020 [cited 2020 Apr 27]. Available from: https://www.who.int/news-room/fact-sheets/detail/deafness-and-hearing-loss 
2. Olusanya BO, Neumann KJ, Saunders JE. The global burden of disabling hearing impairment: a call to action. Bull World Health Organ. 2014;92(5):367–73.
3. World Health Organization. World report on hearing. Geneva: 2021. Licence: CC BY-NC-SA 3.0 IGO. Available from: https://www.who.int/publications/i/item/world-report-on-hearing
4. Fayyad et al. Knowledge Discovery and Data Mining:  Towards a Unifying Framework. KDD-96 Proceedings. Copyright © 1996, AAAI. 
5. LUKASZ A . KURGAN, P E T R M U S I L E K. A survey of Knowledge Discovery and Data Mining process models. The Knowledge Engineering Review, Vol. 21:1, 1–24.  2006, Cambridge University Press. doi:10.1017/S0269888906000737
6. Brooke M Su, Dylan K Chan. Prevalence of Hearing Loss in US Children and Adolescents: Findings From NHANES 1988-2010. JAMA Otolaryngol Head Neck Surg 2017 Sep 1;143(9):920-927. doi: 10.1001/jamaoto.2017.0953.
7. Howard J. Hoffman, Robert A. Dobie, Katalin G. Losonczy, Christa L. Themann,  Gregory A. Flamme. Declining Prevalence of Hearing Loss in US Adults Aged 20 to 69 Years. JAMA Otolaryngol Head Neck Surg. 2017 Mar 1; 143(3): 274–285. doi: 10.1001/jamaoto.2016.3527
