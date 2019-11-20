---
id: doc6
title: Espcx de Tela 001 <Nome Ficticio>
sidebar_label: Espcx de Tela 001 <Nome Ficticio>
---
Essa especificação refere-se ao caso de uso [Caso de Uso 001 \<Nome Ficticio>](doc2)

## Nome
Este item refere-se ao nome do artefato

## Atores
Listar os atores que podem se utilizar deste caso de uso, com por exemplo:gerente, analista, requerente, etc. Nunca usar termos genéricos como "usuário". Para identificação dos atores deve-se tentar identificar:
* Quem deverá suprir, utilizar ou remover informações do sistema.
* Quem deverá utilizar cada funcionalidade do sistema.
* Quem é o interessado no requisito definido.
* Na organização, onde o sistema será utilizado.
* Quem realizará a manutenção do sistema.
* Quais os recursos externos do sistema.
* Os sistemas com os quais o produto a ser desenvolvido deverá interagir.

## Detalhamento da apresentação 
### Tela 1 - Filtros
### Protótipo 
![imagem de exemplo](https://lh3.googleusercontent.com/-oz1zNYxgkes/XdPnhCtrJcI/AAAAAAAAAD0/FhQ7wVfnev8ZgWFQkAzI6Vgb07C0LS9mwCK8BGAsYHg/s0/2019-11-19.png)

imagem de exemplo 

### Campos 

|Nome| Tipo |Formato| Tamanho | Máscara |Obrigatório| Valor Padrão|Editável| Banco|
|---|---|---|---|---|---|---|---|---|
|Período  |  text  |  I  | -  |  DT |  S | N/A | S  |  dt_resposta (sigfacil.s_orgao_solicitacao) |
|Protocolo| text   | A   | -  | N/A | N  | N/A | S  |  co_protocolo (sigfacil.s_solicitacao)      |
|Motivo   |Checkbox| A   | -  | N/A | N  | N/A | S  | ds_motivo_indeferimento (sigfacil.s_orgao_solicitacao)  |


 * **Período:**  Text - inteiro - Mascara: Data - obrigatório - dt_resposta (sigfacil.s_orgao_solicitacao)  

 * **Protocolo:** Text - Alfanumérico  - 13 caracteres. - AMP0000000000 (RN210) - obrigatório -  editavel - co_protocolo (sigfacil.s_solicitacao)  



	

