<div align="center">
  
# PSET 1: Processamento de imagens
## — Linguagens de Programação —
### Preparado pelo Staff da MIT 6.009 (tradução: Abrantes Araújo Silva Filho)
</div>

<br>

### Aluno: Christopher Passos Thompson
### Prof. Abrantes Araújo Silva Filho
### Turma: CC3M

<br>
  
*LEIA COM ATENÇÃO!*  
Este PSET é uma tradução da primeira tarefa de programação que os alunos da
disciplina “MIT 6.009: Fundamentals of Programming” recebem logo no primeiro
dia de aula, feita para os alunos da disciplina “Linguagens de Programação” na
Universidade Vila Velha (UVV). Originalmente, no MIT, esta tarefa deveria ser
completada no prazo de uma semana mas, para os alunos aqui na UVV, o prazo será
de duas semanas. Por favor, leia com atenção todas as [instruções](https://github.com/Christhopas/PSET1/blob/main/pset-1.pdf).



## Questão 1 
226, 166, 119, 55


## Questão 2
![bluegill_invertida.png](https://github.com/Christhopas/Processamento-de-imagens/blob/main/Imagens%20geradas/bluegill_invertida.png)


## Questão 3

Cálculo:

80x0   +   (-0,07x53)   +   99x0 +

(-0,45x129)   +   127x1,20   +   (-0,25x148) +

175x0   +   (-0,12x174)   +   193x0

Resposta: 32,76


## Questão 4
![pigbird_correlacao.png](https://github.com/Christhopas/Processamento-de-imagens/blob/main/Imagens%20geradas/pigbird_correlacao.png)


## Questão 5
![python_nitida.png](https://github.com/Christhopas/Processamento-de-imagens/blob/main/Imagens%20geradas/python_nitida.png)

Cálculo: 
Sx,y = round(
    2 * (Ix-1, y-1)*0 + (Ix, y-1)*(-1) + (Ix+1, y-1)*0 +
         (Ix-1, y)*(-1) + (Ix,y)*5 + (Ix+1, y)*(-1) +
         (Ix-1, y+1)*0 + (Ix, y+1)*(-1) + (Ix+1, y+1)(*0) - Bx,y
         )


