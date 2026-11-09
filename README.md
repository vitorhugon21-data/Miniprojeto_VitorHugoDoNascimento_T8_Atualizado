# Miniprojeto_VitorHugoDoNascimento_T8_Atualizado

# Objetivos
Análise de uma base de dados varejistas na qual eu realizei a leitura, limpeza, tratamento e análise dos dados. Com o intuito de entender as características dos clientes da base.

# Origem da Base
A base é salva em arquivo csv, tem origem este dataset do kaggle: https://www.kaggle.com/datasets/namespaiva/base-varejo?resource=download
Foi utilizado a linguagem python, biblioteca pandas e desenvolvido no Google Colab

# Significado das Colunas
DATA: Data da aquisição
CO_ID: Código único da transação (pedido/compra)
CL_ID: Código único do cliente. 
CL_GENERO: Género registado do cliente
CL_EC: Escolaridade do cliente
CL_FHL: Quantidade de filhos associado ao cliente
CL_SEG: Segmento do cliente
PR_ID: Código único do produto
PR_CAT: Categoria do produto 
PR_NOME: Nome do produto

# Etapas do Projeto
1. Leitura e Organização
2. Limpeza e Padronização
3. Funções e Organização
4. Análise
5. Exportação
6. Conclusões

# Decisões de Limpeza
As decisões de limpeza foram: retirada de linhas que continham N#D, colunas com Umnamed e a sua separação por ponto e vírgula, pontos que melhoram e deixam a base sem erros ou espaços em brancos. Não foram realizados a exclusão das duplicatas por falta de fatores de detalhamento que definem se a linha é uma duplicata ou apenas um outro registro com as mesmas descrições

# Conclusões

1. Após a conferência inicial, foi visto que a base não estava ainda separada por colunas, todas juntas na mesma coluna, após isso foi feita a delimitação e notada que tinha 14 colunas e 830000 linhas, depois da limpeza indo para 10 colunas e 826350 linhas.

2. Existem 826350 valores de compras preenchidas, valores não definidos, nulos ou brancos e contando duplicatas, não foi retirada as duplicatas por não ter certeza de duplicidade, podendo ser registros diferentes de ocasiões diferentes e características iguais.

3. Há 6 categorias e 228 itens sendo vendidas, onde a categoria de alimentação e o item Presunto Cozido, sendo os mais vendidos. O setor de Acessório é o menos vendido e tendo apenas 2 produtos.

4. Produtos como alcool, alho, absorvente, ração para passarinho e abacate são os produtos menos vendidos. Destaque para a ração de passarinho, este produto tem uma diferença considerável de vendas para as rações para cachorros e gatos, sem importar se é seco ou úmido.

5. Há 1000 clientes na base, tendo em sua maioria do gênero feminino, elas que levam vantagem em todas as categorias, tendo mais relevância em Alimentos, higiene e limpeza. Foi notado que elas tem em seu top 5 produtos de limpeza, diferente dos homens que o top 5 é formado apenas por alimentos.

6. As pessoas com nenhum filho são maioria, sendo mais que a metade dos clientes e tendo uma média inferior a de 1,2 filhos. O máximo de filhos, em pelo menos um cliente, são 4. Com a curiosidade de que pessoas sem filhos tem em seu top 5 de compras papinhas para crianças.

**Recomendação**: Mais detalhamento para diferenciação de duplicatas e colunas detalhando valores para mais análises voltadas a questões de descontos, vendas em valores, custos, faturamento e outros.

**Limitação**: Não tem a possibilidade de fazer uma análise voltada a valores, pois não conta valores pagos, descontos e outros. Outra limitação foi a questão das duplicatas, sem um detalhamento maior de data temporal com horas, minutos e segundos.

# Como executar

git clone https://github.com/o-teu-utilizador/o-teu-repositorio.git
pip install pandas













