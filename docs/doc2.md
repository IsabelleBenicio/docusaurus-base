---
id: doc2
title: Caso de Uso 001 <Nome Ficticio> 
sidebar:  Especificação UC
---
## OBJETIVO
Este item descreve o objeto do documento e não do projeto. O objetivo do projeto deve ser descrito em um documento conhecido como "documento de visão". Os textos em itálico são explicações de como preencher este documento e precisam ser removidos

## ATORES

Listar os atores que podem se utilizar deste caso de uso, com por exemplo:gerente, analista, requerente, etc. Nunca usar termos genéricos como "usuário". Para identificação dos atores deve-se tentar identificar:
* Quem deverá suprir, utilizar ou remover informações do sistema.
*	Quem deverá utilizar cada funcionalidade do sistema.
*	Quem é o interessado no requisito definido.
*	Na organização, onde o sistema será utilizado.
*	Quem realizará a manutenção do sistema.
*	Quais os recursos externos do sistema.
*	Os sistemas com os quais o produto a ser desenvolvido deverá interagir.

## PRÉ-CONDIÇÕES

Listar as pré-condições para que este caso de uso seja executado, como por exemplo: analista deve estar logado no sistema e ter permissão para acesso à função. Algumas vezes, quando se combina que esta condição de ator logado é default, pode-se omiti-la. Se não houverem pré-condições, escrever simplesmente "Não se aplica" ou "Nenhuma pré-condição especial é requerida".  

    Ex.:
        O usuário deverá ter perfil de acesso adequado para executar as operações.

        
## PÓS-CONDIÇÕES
Listar as pós-condições, ou seja, o resultado do caso de uso. Muitas vezes, fica óbvio; por exemplo, na inclusão de um usuário, a pós-condição é que o usuário foi incluído. Mesmo assim, é recomendado incluir.

## REFERÊNCIAS

Não se deve anexar documentos padrões do projeto como Atas de Reunião, Cronograma, Documento de Visão, Documento de Arquitetura, Documento de Especificação de Tela, Manual de Integração, etc. Se for necessário alguma referência a um desses documentos, deve-se relacionar o documento e a seção específica onde está a informação útil. No caso de não haver informações a serem inseridas, escrever “Não se aplica.” 

    Ex.: 
        VOX_PROJETO_EspecificacaoDeTela_Assunto_Versao_NumRedmine

## FLUXOS DE EVENTOS 
### Fluxo Básico
#### S01 - <Título do Subfluxo>
Ex:
B1.	Esse caso de uso se inicia quando o analista deseja consultar o relatório de consultas prévias indeferidas;  
B2.	O sistema carrega a tela com as opções de filtros; [1]Tela 1 - Filtros;   

B3.	O analista informa os dados e escolhe a opção gerar relatório; [FA01]  

B4.	O sistema recupera e exibe o resultado da consulta; [FE01] [1]Tela 2 - Relatório de Consultas Prévias Indeferidas;   

B5.	O caso de uso se encerra. 

### Fluxos Alternativos 
#### FE01 - <Título da exceção> 
Ex:
A1.	O fluxo alternativo inicia quando o analista deseja consultar o relatório de consultas prévias indeferidas por analista;  

A2.	O analista informa os dados e escolhe a opção gerar relatório;   

A3.	O sistema recupera e exibe o resultado da consulta; [FE01] [1]Tela 3 - Relatório de Consultas Prévias Indeferidas por Analista  

A4.	O fluxo alternativo se encerra.
### Fluxos de Exceção
EX:  

S1.	xxxxx  

S2.	xxxxx

## REGRAS DE NEGÓCIO 
### RN01 - Título da regra de negócio
Seção opcional contendo as regras de negócio. Se houver uma regra de negócios que seja compartilhada em mais de um caso de uso, recomenda-se usar o documento de Regras de Negócio. Cada regra deverá ser numerada e receber um nome autoexplicativo, de preferência. Logo a seguir, prossegue-se com a descrição do texto relacionado à regra em si, que deverá ser feito de forma clara e sem ambiguidades. É livre o uso de tabelas, gráficos, desenhos e diagramas. Se a regra for complexa, recomenda-se colocar exemplos das situações. No caso de não haver informações a serem inseridas, escrever “Não se aplica.”

## MENSAGENS 
#### 8.1. Mensagens de tela

## RELACIONAMENTO COM OUTROS UC'S

### Casos de Uso de Inclusão
[PI01] – <Título>  

Ex.: 
No passo xxxx do Fluxo (Básico ou FAxx) este caso de uso inclui o caso de uso Xxxxx.

### Casos de Uso de Extensão
[PE01] – <Título>
Ex.: No passo xxxx do Fluxo (Básico ou FAxx) este caso de uso inclui o caso de uso Xxxxx.  

## INFORMAÇÕES ADICIONAIS

![](static\img\analysis.png)