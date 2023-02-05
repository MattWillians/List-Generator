# List-Generator
Esse é um projeto em Python de um gerador de listas, pode ser customizado para diferentes usos

o projeto em si, surgiu da minha necessidade de criar uma tabela com mais de 15000 dados falsos, para serem inseridos em uma tabela de SQL.

neste projeto, eu estava necessitando de:
- Nomes falsos de empresas
- codigos de países
- renda mensal da empresa
- nivel de satisfação de 1 a 10
- e a data do primeiro contato conosco (de janeiro de 2019 até dezembro de 2019)

a saída deste programa ficaria assim:
- INSERT INTO ourclients (CountryCode, CompanyName, MensalIncome, PartnershipStart, SatisfactionLevel) VALUES ("{codigoDePais}","{nomeDaEmpresa}",{rendaMensal},"{primeiroContato}",{nivelDeSatisfacao});

depois o programa escreve esta saida em um arquivo TXT para uso futuro em outros lugares
