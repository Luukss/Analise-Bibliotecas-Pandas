# Analise-Bibliotecas-Pandas

#O dataset de varejo que temos é composto por métricas e KPIs para uma loja de varejo, unindo e tratando duas bases de dados: vendas e clientes.

Com conceitos como joins entre tabelas, union entre bases, data visualization e premissas de negócio. Tudo com foco em técnica mas sem perder o contexto do negócio. Correlacionar dados cadastrais e demográficos dos clientes com seus padrões de compra, para entender melhor nosso público e personalizar estratégias.

Podemos segmentar clientes por faixa etária e analisar diferenças de comportamento entre esses grupos em termos de:
Frequência e valor de compra
Produtos e categorias favoritas
Canal de compra preferido

Também podemos unir dados geográficos para entender diferenças regionais nas vendas e no perfil dos clientes. A união de bases de dados relacionais é um recurso muito poderoso para enriquecer análises e obter insights de negócio.
Algumas métricas e KPIs foram solicitados pela loja de varejo para serem calculados ​​a partir da união das bases de vendas e clientes:

Departamentos Mais Vendidos
Média de Preço e Frete por Departamento
Vendas por Mês
Média de Renda por Canal de Venda
Média de Idade por Bandeira

Além dos KPIs solicitados, algumas premissas e regras do negócio foram passadas para tratamento na análise de dados:
Erro no Sistema para Estado Civil
Foi identificado um erro no sistema onde, para vendas sem informação de estado (UF), o estado está sendo preenchido automaticamente como Mato Grosso do Sul.
Essa premissa deve ser considerada na análise, tratando vendas sem UF como MT para não distorcer resultados regionais.

Validador de Preço x Frete
Outra premissa é que o preço não pode ser maior do que o preço + frete, pois isso geraria prejuízo nas vendas.
Devemos criar uma rotina de validação nos dados para identificar e tratar essas ocorrências onde preço > preço + frete.

Exploramos o contexto e os conceitos que serão abordados no case apresentado.


Unindo bases de dados relacionais
Calculando KPIs com Pandas, NumPy e outras bibliotecas
Aplicando premissas de negócio na análise de dados
Gerando insights sobre vendas, receita e perfil de clientes

Com esses conhecimentos, você será capaz de executar análises de dados valiosas para o contexto de negócio de uma empresa. Bons estudos!
