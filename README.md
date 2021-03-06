# semana-omnistack-11-backend-alterada

Esse repositório contem a api desenvolvida na Semana Omnistack 11, porém, com uma arquitetura diferente.
Essa api foi desenvolvida usando Lint, ES6 (babel como transpiler), prettier e posteriormente serão adicionados testes com Jest.

A arquitetura consiste no uso de:
* Repository: camada que consiste armazenar todas as consultas feitas no banco de dados.
* Services: camada que faz a intermediação entre a Repository e a Controller.
* Controller: camada que consiste em tratar os dados das requisições para realizar o consumo aos serviços na camada Services.
* Routes: camada que consiste nos endpoints da api realizando o redirecionamento para a camada de controle de dados (Controller).
* Database: camada contendo as configurações, migrations e o banco de dados (sqlite).
