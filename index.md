Algoritmo "meu primeiro código"

Var
  L1,L2,L3: real
  EQ , ES, ISO, TRI:logico
Inicio
     Escreva("Digite o primeiro lado: ")
     Leia(L1)
     Escreva("Digite o segundo lado: ")
     Leia(L2)
     Escreva("Digite o terceiro lado: ")
     Leia(L3)
     TRI<- (L1<L2 + L3) e (L2<L1+L3) e (L3<L1+L2)
     EQ <- (L1=L2) e (L2=L3)
     ES <- (L1<>L2) e (L2<>L3) e (L1<>L3)
     ISO<- (L1=L2) e (L1<>L3) ou (L3=L1) e (L2<>L3) ou (L2=L3) e (L2<>L1)
     Escreval("Pode formar um triangulo? ",TRI)
     Escreval("O triangulo e EQUILATERO? ",EQ)
     Escreval("O triangulo e ESCALENO? ",ES)
     Escreval("O triangulo e ISOCELES? ",ISO)
Fimalgoritmo