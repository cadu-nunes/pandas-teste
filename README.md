# pandas-teste

*Descrição do projeto e do seu contexto.*

O projeto é um dashboard interativo de desempenho acadêmico, desenvolvido em Python com Dash, Plotly e Pandas. 
Ele permite que usuários acompanhem e comparem as notas dos alunos ao longo dos semestres, visualizando as notas reais e previstas,
e exibindo indicadores como a média histórica do aluno e a média geral da disciplina. O objetivo é facilitar o acompanhamento 
do desempenho acadêmico de maneira visual e interativa.

*Instruções claras de como executar o projeto (incluindo dependências e como instalar usando o pip, se necessário).*

*1. Instalar as dependências:*
Certifique-se de ter o Python instalado em seu sistema. Depois, instale as bibliotecas necessárias usando o pip:

Abra o terminal ou prompt de comando e execute:

*pip install pandas plotly dash*

*2. Obter os arquivos do projeto:*
Certifique-se de ter os arquivos do projeto. Os principais são:

comparacao_real_expectativa.csv (arquivo de dados)

PANDA.PY (script principal com a lógica do dashboard)

*3. Executar o projeto:*
Após instalar as dependências e obter os arquivos do projeto, execute o script PANDA.PY:

*python PANDA.PY*


*4. Ajustes no arquivo CSV (se necessário):*

Caso queira usar seus próprios dados, certifique-se de que o arquivo CSV siga a mesma estrutura de colunas

que o projeto original (incluindo "RA_Aluno", "Cod_Disciplina", "Nota", "Semestre_Label").



*Nome de todos os integrantes e a função de cada um no desenvolvimento.*

Product Owner (PO): Caique

Scrum Master: Kleber

Time de Desenvolvimento: Alisson, Bruno, Carlos



*Questionário Obrigatório na Apresentação:*

*1 - Como funciona o pip no Python e como ele foi utilizado no projeto?*

O pip é o gerenciador de pacotes do Python, usado para instalar bibliotecas externas. 
No projeto, ele foi usado para instalar pandas, plotly e dash, que são essenciais para manipular dados, 
gerar gráficos e construir o dashboard interativo.


*2 - Como foi feita a organização dos arquivos e pastas no projeto?*

 A organização dos arquivos do projeto foi feita de forma simples e direta:
comparacao_real_expectativa.csv: arquivo de dados em formato CSV, contendo as informações dos alunos, disciplinas, notas e previsões.
PANDA.PY: script principal em Python que contém a lógica do dashboard utilizando Dash, Plotly e Pandas.
README.md: arquivo de documentação (markdown), geralmente usado para explicar o propósito do projeto, como rodá-lo e suas dependências.

*3 - O que é arquitetura de software e como o grupo aplicou isso no projeto?*

A arquitetura de software organiza o sistema em partes com funções definidas. No projeto, isso foi aplicado separando os dados, o código (PANDA.PY) 
e a documentação (README.md), usando bibliotecas específicas para cada tarefa (como pandas e dash) e mantendo uma estrutura simples e clara.