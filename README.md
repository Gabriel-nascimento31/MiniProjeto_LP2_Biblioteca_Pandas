Esse miniprojeto foi desenvolvido na Fatec Rio Claro para a disciplina Linguagem da Programação 2. O miniprojeto teve como objetivo apresentar uma biblioteca Python, eu escolhi a biblioteca Pandas. A biblioteca Pandas é uma biblioteca Python de código aberto, desenvolvida especificamente para a manipulação e análise de dados tabulares de forma rápida e eficiente.


O miniprojeto é uma simulação do dia a dia de um analista de dados, simulando uma carga rápida de dados para análise de indicadores financeiros estratégicos.

Tecnologias utilizadas

Python: Linguagem de programação utlizada
Pandas: Biblioteca utilizada para manipulação, estruturação e análise de dados
Jupyter Notebook: Ambiente interativo para execução do código e apresentação dos resultados

Estrutura do projeto

analise_vendas.ipynb`: O jupyter notebook principal contendo o conjunto de dados embutido e todo o passo a passo do código 

Etapas demonstradas no miniprojeto

Criação do DataFrame:Transformação de um dicionário Python nativo em uma estrutura de dados tabular do Pandas (`pd.DataFrame`).
Tratamento e Consistência: Ajuste de tipos de dados (como conversão de datas) para garantir a precisão dos cálculos.
Engenharia de Dados: Criação de novas colunas calculadas em tempo de execução:
Cálculo dos faturamentos: Total, por produto e por região
Cálculo do ticket médio por venda: Calcula o ticket médio das vendas de todos os dias

Indicadores Gerados

O script responde automaticamente a perguntas cruciais de negócios:
 Qual o Faturamento Total e o Lucro Líquido da empresa no período?
 Qual o Ticket Médio gasto por transação?
 Qual região gera maior receita?


Para executar o miniprojeto clone o repositório, instale a biblioteca pandas e rode cada célula(notebook) do arquivo analise_vendas.ipynb
