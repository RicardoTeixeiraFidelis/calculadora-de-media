# calculadora-de-media
algoritmo "media de notas"
var
nome:caracter
nota1, nota2, nota3, nota4, media:real
inicio
  escreval("digite o nome do aluno: ")
  leia (nome)
  escreval("Digite as notas do aluno: ")
  escreval("Nota do primeiro bimestre: ")
  leia (nota1)
   escreval("Nota do segundo bimestre: ")
  leia (nota2)
   escreval("Nota do terceiro bimestre: ")
  leia (nota3)
   escreval("Nota do quarto bimestre: ")
  leia (nota4)
  media <- (nota1 + nota2 + nota3 + nota4) / 4
  escreval("A media das notas do aluno(a) ", nome, " é de ", media)
fimalgoritmo
