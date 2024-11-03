# 
<h1>Desafio 2: Modelando do zero</h1>
<h3>Ordem de Serviço: Oficina Mecânica</h3>
<p>O desafio era criar um esquema conceitual para Banco de Dados do zero de uma Oficina Mecânica. </p>
<p>Narrativa:</p>
<p>Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica.</p>
<p>Clientes levam veículos à oficina mêcanica para serem consertados ou para passarem por revisões periódicas;</p>
<p>Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega;</p>
<p>A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra;</p>
<p>O valor de cada peça também irá compor a OS;</p>
<p>O cliente autoriza a execução dos serviços;</p>
<p>A mesma equipe avalia e executa os serviços;</p>
<p>Os mecânicos possuem código, nome, endereço e especialidade;</p>
<p>Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos;</p>
<p>Uma OS pode ser composta por vários serviços e um mesmo serviço pode estar contido em mais de uma OS;</p>
<p>Uma OS pode ter vários tipos de peça e uma peça pode estar presente em mais de uma OS.</p>
<hr>
<p>Criei as entidades que achei que seriam mais importantes com seus respctivos atributos, fazendo os relacionamentos de acordo com a narrativa.</p>
