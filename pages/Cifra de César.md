- A cifra de César consiste em um sistema de criptografia simples. Para que se possa criptografar a mensagem, pegasse uma letra de uma determinada palavra, e a troca pela letra que esteja 3 posições a sua frente, e assim sucessivamente com as demais letras .
  
  Exemplo:
- ### Criptografando a palavra “Arroz”
  
  a = a+3 = d
  
  r = +3 = u
  
  i = +3 = r
  
  z = + 3 =c
  
  Arroz = Duurc
  
  Contudo, também é possível seguir o mesmo modelo, porém com números, já neste caso, o alfabeto se inicia com o “A” sendo considerado “0” e a partir do momento em que uma soma ultrapassa o número 25, volta-se para o início do alfabeto:
- ### Criptografando a palavra “Arroz” com um deslocamento de 3
  
  Formula: Criptografar = En(x) = (x+n)
  
  ```
  Descriptografar = En(x) = (x-n)
  ```
  
  A = E³ ( 0 ) = (0+3) = 3 = D
  
  R = E³ ( 18 ) = (18+3) = 21 = U
  
  O = E³ ( 15 ) = (15+3) = 18 = R
  
  Z = E³ ( 25 ) = ( 25 +3) = 2 = C
  
  Arroz = 32121182
- ### Alfabeto e seus números:
  
  A = 0       J = 9      S = 18
  
  B = 1       K = 10   T = 19
  
  C = 2       L = 11    U = 20
  
  D = 3      M = 12   V = 21
  
  E = 4       N = 13    W = 22
  
  F = 5       O = 14    X = 23
  
  G = 6      P = 15     Y =24
  
  H = 7      Q = 16     Z =25
  
  I = 8        R = 17
  
  <!-- notionvc: 426271ff-179d-424e-8ad3-c4a0191c635c -->