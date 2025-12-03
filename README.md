# Número Secreto
## O projeto consiste em digitar o “número chute” até que ele valide com o “número secreto” e aparaça a imagem de parabenização para quem o acertar.
### Nesse código de JavaScript foram definidas as variáveis: **numeroMaximo**, **numeroSecreto**, **chute** e **tentativas**.
   #
#### **Uma breve explicação sobre a função de cada variável:**
   A variável **numeroMaximo** está com o valor 1000 (podendo ser alterado a qualquer momento), e esse é o limite que o *Math.random()* gerará; 
   #
   Depois tem a variável **numeroSecreto** recebendo o valor “parseInt(Math.random() * numeroMaximo + 1”. *ParseInt* é uma declaração para que o *Math.random()* gere números acima de 0, que seria basicamente um número inteiro. Já o *Math.random()* tem como finalidade gerar números aleatórios, dessa forma, faz com que o projeto gere um número diferente cada vez que abre o *index.html* ou aperta *F5* no navegador. Quando múltiplicado pelo **numeroMaximo**, é definido que gerará até um número a menos, por isso é colocado "+1";
   #
   A variável **chute** não está com um valor definido, portanto, cada vez que digitar um valor no alerta, esse valor será armazenado na variável. O intuito é que esse valor coincida com o valor da variável **numeroSecreto**;
   #
   Já a variável **tentativas** está definida com o valor 1, e ela será usada como incrementador, então, toda vez que digitar um chute e não acertar, será somado “+1” e o acerto também será somado como uma tentativa.
   #
#### **Uma breve explicação sobre o código:**
   No código tem uma condição de repetição (*while*), nela foi definida que o **chute** é diferente do **número secreto**, o que quer dizer, enquanto não acertar o número secreto, a condição de repetição será executada. E dentro dela tem a condição de comparação (*if e else*), nela foi definida que a variável chute recebeu o valor de *prompt*, que seria, toda vez que digitar um número, será definido na variável, e como está em repetição, só terá um fim quando o número do prompt for igual ao número definido na variável **numeroSecreto**; 
   #
  Logo abaixo da condição de repetição temos a variável **tentativas** em condição de contador (++), nela, cada tentativa contabiliza +1 (até mesmo o acerto do número secreto será contabilizado como uma tentativa), e o resultado aparecerá no “Alerta” com o número secreto.
  #
  E por último temos um “Operador Ternário”, que substitui o que era para ser mais uma condição de comparação (*if/else*), e nele estão as variáveis **palavraTentativa** e **tentativas**. A ideia foi comparar, de forma lógica, se a variável **tentativas** tiver mais de 1 como valor definido, aparecerá “tentativas” no prompt, senão, aparecerá “tentativa”.
  #
### Esse foi um projeto realizado na Alura, utilizei o código HTML e CSS da plataforma, porém, refiz o código JavaScript para estudar Lógica de Programação, e ao concluir o curso, ganhei um certificado.

<img loading="lazy" src="https://avatars.githubusercontent.com/u/4975968?s=280&v=4" width="40" height="40"/>

