# Integração Python e SQL
## Objetivo
A integração do Python com o SQL permite que execute comandos SQL diretamente pelo Python no seu banco de dados. Isso vai permitir a gente pegar consultas e já importar elas para dentro de uma análise no Python automaticamente.

## O que vamos precisar
- Para aprender, vamos usar o SQL Server, umas das ferramentas de gerenciamento de banco de dados mais usadas no Mercado. (Vamos instalar gratuitamente) https://www.microsoft.com/en-us/sql-server/sql-server-downloads instale o Developer, instale o 'básico' -> após instalar clique em 'Instalar SSMS' -> execute esse arquivo -> depois vai aparecer a opção de 'restart', clique para reiniciar o computador.

- Um banco de dados para testar -> usaremos o Contoso, https://drive.google.com/file/d/1Z0O5UyVopNgmi1d_0Lnfc0ciX20iEJ5n/view selecione o ContosoBIdemoBAK.exe
Extraia o arquivo Contoso, abra o banco de dados, (se você apagar sem querer o server name, vá no terminal do seu computador e digite: 'hostname', irá aparecer o nome para colocar no server name).

- Dica: coloque o arquivo no C:

- Clique com o botão direito no 'Databases' -> 'Restore Database' -> 'Device' -> '...' -> 'Add' -> Selecione o arquivo que você vai utilizar -> 'Ok' -> 'Ok' -> 'Ok' -> Vai carregar o arquivo Contoso e ele vai aparecer no banco de dados. 

## O que vamos usar no Python
Biblioteca pyodbc -> pode ser usada com a mesma estrutura para diversos bancos de dados, como SQL Server, MySQL, Oracle, Access, IBM, etc.

## Pré-requisitos 
- Jupyter Notebook (anaconda 3)
- Python
- Importar as bibliotecas 

## Sobre a Autora
Oi, eu sou a Fernanda! Estou aqui para contribuir com meu conhecimento e espero poder ajudar no desenvolvimento profissional de cada um de vocês.

[![Linkedin Badge](https://img.shields.io/badge/-Fernanda_Maki_Hirose-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fernanda-maki-hirose-801117208/)](https://www.linkedin.com/in/fernanda-maki-hirose-801117208/)  [![Gmail Badge](https://img.shields.io/badge/-femahi2020@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:femahi2020@gmail.com)](mailto:femahi2020@gmail.com)

