
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

<img src="https://user-images.githubusercontent.com/101064720/166814129-22f1a66e-e08f-4b45-a435-a74e741b8324.PNG" width="300" align="right">
# Jogo Palavrinha

Baseado em no famoso jogo Wordle (no Brasil, Termoo), o Palavrinha consiste no jogador tentar acertar uma palavra de 5 letras, em português. O usuário tem 5 tentativas para acertar a palavra.
A cada rodada, o jogador descobre se acertou as letras que compõe a palavra e se estão na posição certa, a partir da cor que cada letra aparece (verde, amarelo e vermelho).

O jogo está adequado para o Jupyter Notebook e, no futuro, planejo adaptá-lo para aplicações Web.

## Métodos
### A palavra randômica
Foi utilizada uma lista de 6365 palavras em português, extraída da internet. Com a biblioteca Random, é escolhida aleatoriamente a palavra da rodada.
Em seguida, foi utilizada uma função que transforma a palavra de string para lista, cujos elementos são as letras. Cada elemento é avaliado para retirar caracteres especiais. 
O usuário então inicia o jogo e é iniciada a função que compara as letras da palavra escolhida pelo usuário com as da randômica, imprimindo as letras coloridas (class bcolors) conforme o acerto ou erro.

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/estefanialunardi/)
