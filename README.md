#Recuperação de Textos

Utilizando o corpus de notícias Reuters no seguinte link:

Corpus Reuters

Deve-se elaborar o Notebook Python descrevendo um processo de recuperação de textos visando retornar as notícias mais similares em relação à uma notícia de consulta. Utilize e compare as representações Bag-of-Words e TF-IDF, como também a métrica de similaridade Cosseno.



O que deve ser entregue:

O link de um repositório no GitHub contendo um notebook Python com a implementação do referido processo de recuperação de notícias. Finalmente, apresente para cada representação textual a validação do processo: a acurácia média de recuperação das 10 primeiras notícias recuperadas conforme as categorias (veja no corpus). Detalhando a seguir:

- Para cada notícia do corpus (considere como sendo a notícia de consulta) deve-se criar um ranking de similaridade em relação às demais notícias (excluindo-se a notícia de consulta). Deve-se verificar se a classe das top-10 notícias recuperadas na busca por similaridade pertencem a mesma classe da notícia de consulta. Se a i-ésima posição (dentre as top-10) são da mesma classe da notícia de consulta, contabilize o acerto. Faça isso para as primeiras 10 posições apenas!

       * Nesse caso, recomenda-se apresentar uma tabela com 10 posições, indicando a porcentagem de acerto (ou recuperação correta) das notícias buscadas.

       * Não se preocupar no momento com as notícias que estejam nas pastas de teste e treinamento (ainda não estudamos isso).
