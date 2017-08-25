# conceito-restfull

Canais de estudo:

Dissertação de Joy Fielding sobre REST: </br>
http://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm

Design da API RESTful - Substantivos são bons e verbos são ruins: </br>
https://apigee.com/about/blog/technology/restful-api-design-nouns-are-good-verbs-are-bad

Os principais princípios do REST </br>
https://en.wikipedia.org/wiki/Representational_state_transfer

Boas práticas Rest Full </br>
http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api#requirements
</br>

Exemplos de sites com boas documentações</br>
https://stripe.com/docs/api#intro</br>
https://developer.github.com/v3/gists/#list-gists

Versões de APi devem ser usadas na URL ou cabeçalho</br>
https://stackoverflow.com/questions/389169/best-practices-for-api-versioning

Versões da API na URi podem quebrar o conceito criado por Roy em sua tese de mestrado:</br>
http://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm#sec_5_1_5

A interface REST foi projetada para ser eficiente para a transferência de dados de hipermídia de grandes grãos, otimizando o caso comum da Web, mas resultando em uma interface que não é otimizada para outras formas de interação arquitetônica.</br>

Claro, é possível incorporar a versão da API no URI básico, mas apenas para usos razoáveis é restritos, como depuração de um cliente da API que funciona com a nova versão da API. Essas APIs versionadas devem ser limitadas no tempo e estar disponíveis apenas para grupos limitados de usuários da API (como no caso de betas fechadas). Caso contrário, você compromete-se onde você não deveria.</br>

Abordagem que a Stripe levou ao controle de versão da API </br>
https://stripe.com/docs/api#versioning

Alias para consultas comuns </br>

Para tornar a experiência da API mais agradável para o consumidor médio, considere empacotar conjuntos de condições em caminhos RESTful facilmente acessíveis. Por exemplo, a consulta de ingressos recentemente fechada acima pode ser embalada como GET / tickets / recently_closed

Estudo sobre Came case vs Snake Cade( estudo de olhos)
http://ieeexplore.ieee.org/document/5521745/?reload=true&tp=&arnumber=5521745

Implementar o GZIP ganho de até 80% em estudos com Twitter

cabeçalho Link introduzido pelo RFC 5988 . Usado para paginacao e outras informações
https://tools.ietf.org/html/rfc5988#page-6

Muitas APIs gostam de retornar as informações de paginas adicionais, como uma contagem do número total de resultados disponíveis. Uma API que exige o envio de uma contagem pode usar um cabeçalho HTTP personalizado como X-Total-Count .




