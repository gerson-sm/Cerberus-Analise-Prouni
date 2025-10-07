# Análise de Equidade e Distribuição das Bolsas do Prouni (2016–2019)
Resumo do Projeto
O projeto tem como objetivo analisar a distribuição das bolsas do Prouni (Programa Universidade para Todos) no período de 2016 a 2019, a fim de identificar padrões, avaliar a equidade no processo de concessão e propor recomendações baseadas em dados.
A análise busca responder três grandes eixos de investigação:

•	Identificar padrões e tendências: compreender como as bolsas se distribuem por região, curso, tipo de curso, tipo de bolsa e grupos étnico-raciais.

•	Avaliar a equidade: verificar se há disparidades significativas na concessão das bolsas para diferentes perfis de estudantes.

•	Propor recomendações: sugerir melhorias para ampliar a inclusão e a transparência do programa, reforçando seu impacto social.
# Dataset Utilizado
Foram utilizadas as bases de dados do Prouni disponibilizadas pelo Ministério da Educação (MEC), referentes aos anos de 2016 a 2019, disponíveis em:
https://dadosabertos.mec.gov.br/prouni
O dicionário de dados oficial pode ser consultado em:
https://dadosabertos.mec.gov.br/images/pdf/dicionario-prouni-20161222.pdf
Cada base contém informações sobre:

•	Identificação dos beneficiários

•	Região, estado e município

•	Curso e tipo de curso (presencial/EAD)

•	Tipo de bolsa (integral ou parcial)

•	Sexo, faixa etária e cor/raça do estudante
# Bases de Dados
Para facilitar o acesso e a reprodução da análise, seguem os links das bases de dados utilizadas no projeto:

•	Base original do Prouni (2016–2019):
https://drive.google.com/file/d/1fOVUEpusTu_GwWlsfPAbzhAfwfuYsFqZ/view

•	Base tratada (limpa e consolidada):
https://drive.google.com/file/d/1uD8pbIced96760c0aac9BBgX6tzejIBo/view 

•	Esses arquivos permitem a conferência dos dados brutos e da versão utilizada para análise, garantindo transparência no processo.
# Etapas da Análise
1.	Exploração e Limpeza dos Dados

•	Padronização dos nomes das colunas e concatenação dos arquivos anuais.

•	Tratamento de valores nulos e inconsistentes.

•	Conversão de tipos de dados e normalização das variáveis categóricas.
2.	Análise Exploratória

•	Entendimento da distribuição das bolsas por variáveis demográficas e educacionais.

•	Identificação de padrões regionais e diferenças entre tipos de bolsa.

•	Construção de gráficos e tabelas descritivas para apoiar as conclusões.
3.	Geração de Insights

•	Comparações entre regiões e perfis de beneficiários.

•	Avaliação da representatividade racial e de gênero.

•	Interpretação dos resultados à luz das políticas públicas de inclusão.
# Tecnologias Utilizadas

•	Python (Pandas, NumPy, Matplotlib)

•	Google Colab para execução em nuvem

•	Looker para visualizações complementares

•	GitHub para versionamento e compartilhamento dos resultados
# Principais Descobertas
## Tipo de Bolsa
A análise da variável TIPO_BOLSA mostra que a maior parte das bolsas é integral (100%), evidenciando o papel social do Prouni no atendimento a estudantes de baixa renda.
As bolsas parciais (50%), embora menos numerosas, também têm importância significativa, apoiando famílias de renda intermediária.
Distribuição Regional
Há concentração nas regiões Sudeste e Nordeste, seguidas por Sul, Norte e Centro-Oeste.

•	O Sudeste lidera pela alta concentração urbana e de instituições privadas de ensino.

•	O Nordeste destaca-se pela ampla adesão ao programa, reforçando sua relevância social.

•	Norte e Centro-Oeste têm menor participação, possivelmente pela menor oferta institucional.

## Diversidade Racial
Os dados indicam avanços na inclusão racial, com presença relevante de estudantes negros (pretos e pardos).
Entretanto, a população branca ainda representa um grande percentual.
## Distribuição por Gênero
As mulheres representam a maioria dos beneficiários, confirmando a tendência nacional de maior presença feminina no ensino superior.
A menor participação masculina pode estar relacionada a fatores socioeconômicos e culturais, como inserção precoce no mercado de trabalho.
## Faixa Etária
O grupo 18–25 anos concentra cerca de 70% das bolsas, refletindo o foco do programa nos jovens recém-egressos do ensino médio.
Adultos entre 26–40 anos também aparecem de forma expressiva, indicando busca por requalificação.
Acima de 40 anos, há menor participação, sugerindo barreiras de acesso para essa faixa.
# Conclusão
A análise mostra que o Prouni é um instrumento efetivo de democratização do ensino superior privado, contribuindo para inclusão social, racial e de gênero.
Ainda assim, persistem desigualdades estruturais que limitam o acesso para determinados grupos e regiões, evidenciando a necessidade de políticas complementares e maior integração regional na oferta de bolsas.

