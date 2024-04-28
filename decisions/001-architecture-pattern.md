# Decisão de Padrão Arquitetural de Software

## Descrição do Contexto e Problema

Qual o padrão mais adequado para utilização nos microserviços?

Diante de diversas possibilidades de padrão que atualmente existem para a construção de um software, busca-se escolher um que nos permita mudar frameworks com facilidade, ou seja tendo um baixo acomplamento. Desta forma acreditamos que será possível aproveitar melhor as escolhas de diversas tecnologias que trabalhar com microserviços nos proporciona, facilitando a mudança de um framework ou biblioteca que seja mais adequado para a tarefa do software.

## Opções

* Hexagonal
* Layered
* Onion
* CQRS

## Decisão

Opção escolhida: Hexagonal

É uma opção que nos dará a liberdade que buscamos nas separações das camadas em relação a outros como Onion (ainda que este seja bastante parecido) ou Layered (e este seja como um precursor). Apesar do CQRS não ser incompativel com o uso do Hexagonal, foi preferido neste primeiro momento o uso do Hexagonal.
