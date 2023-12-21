# Projeto BI SuperStore
> Para visualizar a documentação técnica  do projeto revelando as escolhas e tomada de decisão veja mais em LINK. 




# Estrutura de diretórios do projeto


|── data_layer                                         
|  |──  raw_data_layer

|── doc

|── src



*  data_layer - Neste repositório repousa todos os dados do projeto inclusive o backup do banco de dados. 

*  doc - Armazena toda a documentação do projeto.

*  src - Todos os scripts SQL utilizados para criação do banco.


## Ambiente de desenvolvimento 

O projeto foi todo desenvolvido com as ferramentas Microsoft SQL Server. Entre as ferramentas estão:


    * SQL Server Management Studio 2019 (SSMS)
    
    * SQL Server Integrations Services (SSIS)
    
    * SQL Server Analysis Services (SSAS)
    
    * Visual Studio Community 2019


Para acessar, visualizar e testar o projeto pode-se optar por dois caminhos:

    1 - Restauração do backup do banco de dados no SSMS em /data_layer/OLTP_DB_STORE.bak 
    2 - Execução dos scripts do projeto encontrado em /src , na seguinte ordem de execução:

            1 - 01-oltp-tabelas.sql
            2 - 02-oltp-preparacao-dos-dados.sql
            3 - 03-oltp-constraints.sql


## Histórico de atualizações

* <feat> v1 estável do projeto
      --  Estrutura de repositório e Projeto OLTP completo.
