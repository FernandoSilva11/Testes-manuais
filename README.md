# Testes-manuais

Repositório contendo exemplos de alguns testes manuais que desenvolvi e realizei a execução.

O site utilizado para realizar os testes foi o E-commerce Kabum. 

Os testes foram focados em 3 áreas - Responsividade, Pesquisa e Carrinho de compras. Essas 3 áreas foram escolhidas pois se tratam de áreas importantes para e-commerce.

   — Responsividade - Grande parte da população acessa site mais a internet pelo celular do que pelo computado então e muito importante que a aplicação suporte diferentes resoluções. 

   -Pesquisa - É importante que a pesquisa esteja funcionando conforme o esperado, trazendo aquilo que é pesquisado de maneira rápida e direta, ou informando de maneira clara que o site não possui aquele produto, se esse for o caso.

   -Carrinho - Uma das partes mais importantes de um E-commerce, visa ser um resumo da compra e uma das partes finais. Deve conter campo para digitar cep e também campo para digitar cupons de descontos, além de informar com clareza os produtos e preços presentes naquela compra.

<p align="center">

  <img src="https://user-images.githubusercontent.com/50935903/179132744-5636c47b-07d1-41f6-99b1-69f84e97216f.png#center">

</p>

Motivo para que os alguns casos fossem dados como status - inconsistência encontrada:

*Observação: O que EU considerei como "inconsistências" foram baseadas em experiências minhas em outros sites do mesmo estilo e seguimento, pode ser que algumas dessas "inconsistências" que citei sejam intencionais e para a empresa não seja algo fora do padrão deles.

Funcionalidade Pesquisa - 1 inconsistência encontrada
  1. Caso 1 - Realizar pesquisa de um produto não cadastrado - O sistema retornou diversos produtos que não tinham nenhuma semelhança com o que foi pesquisado, que no caso foi cadeira de praia..

Funcionalidade Carrinho - 2 inconsistências encontradas
  1. Caso 3 - Inserir cep inválido - O sistema nada informou ao inserir cep inválido, e isso pode levar o usuário a pensar que 
está inserindo corretamente e que o problema está no site.
  2. Caso 4 - Adicionar item, clicar em continuar comprando e adicionar o mesmo item novamente. - Sistema não adiciona uma nova unidade daquele item ao carrinho, continua exibindo apenas o valor 1.
