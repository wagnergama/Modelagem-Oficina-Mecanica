# Modelagem Oficina Mecânica
>
Neste projeto foi modelado um esquema conceitual para o uma oficina mecânica com base na narrativa abaixo. Utilizei o [MySQL Workbench](https://www.mysql.com/products/workbench/)
>
## Narrativa:
* Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
>
* Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas (Isso sera colocado na OS em tipo de serviço)
* Cada veículo é designado a uma equipe de *mecânicos* que identifica os serviços a serem executados e preenche uma OS com data de entrega.
* A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
* O valor de cada peça também irá compor a OS;
* Cliente autoriza a execução dos serviços (Alterando o Status da OS)
* A mesma equipe avalia e executa os serviços. 
* Os mecânicos possuem código, nome, endereço e especialidade
* Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.
