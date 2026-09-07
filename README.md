# prospecção de clientes com python e powerbi
  Em muitos cenários comerciais, equipes de vendas enfrentam dificuldades
  para prospectar novos clientes por trabalharem com listas brutas de 
  CNPJs, perdendo tempo com empresas inativas ou sem dados de contato.
  O objetivo desse exercicio é utilizar um script em python que consulta
  a API da ReceitaWS, realiza a limpeza, validação e enriquecimento das
  informações e gera uma base otimizada para alimentar um dashboard
  analitico e operacional no PowerBI.

  # Bibliotecas Utilizadas
    * Pandas: Biblioteca de manipulação e análise de dados

    * Requests: Biblioteca para realização de requisições a sites e APIs

    * openpyxl: Biblioteca que ira modificar os arquivos que serão acessados pelo powerbi

    * os: Biblioteca que irá interagir com o sistema de arquivos do sistema operacional.

# API utilizada no projeto

    * ReceitaWS: Nesse projeto iremos utilizar a API da ReceitaWS que tem
    como objetivo acessar as informações de empresas através do CNPJ

    * Limite de Requisições: A versão pública da API permite apenas 3 requisições por minuto.

    * link do site da API: https://developers.receitaws.com.br/?_gl=1*1rfqhri*_gcl_aw*R0NMLjE3ODg4MDc0OTMuQ2p3S0NBand3Zm5VQmhBdEVpd0FmUXBBWXRPbk5CZWF2ZWdlNXdRWXhoMFdCcTlLdGRZT2tzTDZhYUN2WVBlY0J6QVdZVVd3SHBySEZ4b0NMWVlRQXZEX0J3RQ..*_gcl_au*NDg1MzMwNjUuMTc4MjQxMzYzOQ..*_up*MQ..*_gs*MQ..&gclid=CjwKCAjwwfnUBhAtEiwAfQpAYtOnNBeavege5wQYxh0WBq9KtdYOksL6aaCvYPecBzAWYUWwHprHFxoCLYYQAvD_BwE&gbraid=0AAAAADf89S_afycagpHKh_AR8ta-0ixpT

# Funcionalidades do sistema
                                Python

    * O sistema deverá criar na pasta do projeto um diretório que irá
    conter todas as planilhas analisadas.

    * O sistema devera acessar a pasta que contém os CNPJs que serão
    acessados

    * O sistema devera realizar requisições a API do ReceitaWS para verificar as informações das empresas.

    * O sistema devera analisar os dados com o objetivo de realizar
    a higienização e tratamento dos dados como CNPJs inválidos, campos
    vázios, retornos com erro, etc.

    * O sistema deverá salvar os dados publicos em uma planilha excel
    que irá ser acessada pelo powerbi.

                            PowerBI
    * O PowerBI devera acessar as planilhas de dados criadas pelo python
    com o objetivo de criar gráficos que exibe a distribuição de empresas
    por categorias.

             Métricas que deverão ser abordadas no DashBoard

                         KPIs no Topo

    * Total de CNPJs Processados

    * % de CNPJs Ativos

    * % de CNPJs Inativos
    
    * % de Empresas com e-mail/telefone disponiveis

                        Segmentação Estratégica (Gráficos Interativos)

    * Geográfico: Distribuição por Estado (UF) e Cidade (visão de mapa ou barras)

    * Setorial: Principais ramos de atuação das empresas com base no CNAE
    principal.

    * Porte: Separação por porte da empresa.

                            Tabela de Prospecção
    * Uma tabela detalhada onde o vendedor aplica o filtro por empresas
    , por Estado e por disponibilidade de contato.

    

    