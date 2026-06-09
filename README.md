# Atividade de Controle de Sistemas Dinâmicos

## Sintonia de Controladores P, PI e PID pelo Método de Ziegler-Nichols

Este repositório contém o projeto desenvolvido para a disciplina de Controle de Sistemas Dinâmicos I.

O objetivo do trabalho foi aplicar o método de Ziegler-Nichols em malha aberta para realizar a sintonia de controladores P, PI e PID.

## Dados do trabalho

**Alunos:** Bryan Goulart - 02320205, Diogo Gil de Oliveira - 02320513, Eduardo Peron - 02320356 e Emily Colen - 02320114
**Curso:** Engenharia da Computação
**Disciplina:** Controle de Sistemas Dinâmicos I
**Professora:** Virginia Klausner de Oliveira
**Instituição:** UNIVAP - Faculdade de Engenharias, Arquitetura e Urbanismo
**Turma:** 7 UNA
**Data de entrega:** 10/06/2026

## Link do Google Colab

O projeto também pode ser acessado pelo Google Colab:

https://colab.research.google.com/drive/1xi7kSP5YPfjMVzVtEhHF1selkwDzRLvV?usp=sharing

## O que foi feito

* Definição de uma planta em malha aberta;
* Aplicação de uma entrada degrau unitário;
* Obtenção da resposta ao degrau;
* Cálculo dos parâmetros K, L e T;
* Traçado da reta tangente no ponto de inflexão;
* Aplicação da tabela de Ziegler-Nichols;
* Sintonia dos controladores P, PI e PID;
* Fechamento da malha com realimentação negativa;
* Comparação da resposta com e sem controlador;
* Teste com entradas degrau, rampa e parábola;
* Comparação entre os controladores P, PI e PID.

## Planta utilizada

A planta utilizada no projeto foi:

G(s) = 6 / ((s + 1)(s + 2)(s + 3))

ou:

G(s) = 6 / (s³ + 6s² + 11s + 6)

Essa planta foi escolhida por ser estável, possuir polos reais e não possuir polo em zero.

## Método utilizado

Foi usado o método de Ziegler-Nichols em malha aberta.

Primeiro foi aplicada uma entrada degrau na planta sem controlador. Depois, a partir da curva de resposta, foram encontrados os valores de K, L e T.

Com esses valores, foram calculados os parâmetros dos controladores P, PI e PID.

## Arquivos do repositório

* `Atividade_Controle_de_Sistemas_Dinâmicos.ipynb`: notebook com o código do projeto;
* `Atividade_de_Controle_de_Sistemas_Dinâmicos.pdf`: documentação do trabalho;
* `README.md.

## Conclusão

O projeto mostrou de forma prática como a sintonia de controladores pode alterar a resposta de um sistema dinâmico.

Foi possível observar que os controladores P, PI e PID geram respostas diferentes, mudando características como velocidade, ultrapassagem e estabilização do sistema.
