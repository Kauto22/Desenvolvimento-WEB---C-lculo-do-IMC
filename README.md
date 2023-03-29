# Desenvolvimento-WEB---C-lculo-do-IMC
Trabalho bimestral do 2º de informática, utilizando HTML, CSS e JavaScript

Este repositório contém o desenvolvimento de um código para calcular o IMC de uma pessoa, onde foi utilizado a fórmula var IMC = peso/(altura**2), o IMC serve para
apontar o peso de uma pessoa e falar se está adequado,abaixo ou acima do peso:

HTML:

O Código HTML é composto por 5 DIVS, em que, a DIV principal em que se baseia todas as outras é denominada de "container".
Dentro de container se localiza a div "titulo" que possui como conteúdo uma tag <h2> para o título "Cálculo de IMC"
Ainda no interior de "container"



JavaScript:

O código JavaScript consiste completamente, inteiramente de uma única função, esta denominada de "CalcularIMC"
Em que é apresentado três constantes, definidas como "peso", "altura", "IMC"
Em que, "peso" e "altura" pegam os valores de ID dos elementos que são digitados pelo usuário anteriormente em HTML

![image](https://user-images.githubusercontent.com/111540350/228522823-8c1cb5b8-c2a6-4434-9da4-b04255bad861.png)

FÓRMULA IMC: 

![image](https://user-images.githubusercontent.com/111540350/228520265-271a6ec0-2360-4d91-ad48-d187c9d1f194.png)


Dessa forma utilizamos a estrutura de repetição IF/ELSE

" A estrutura condicional if/else é um recurso que indica quais instruções o sistema deve processar de acordo com uma expressão booleana. Assim, o sistema testa se uma condição é verdadeira e então executa comandos de acordo com esse resultado. "

EX 1:

if (IMC < 18.5) {
        document.getElementById("qr").innerText = `Seu IMC é: ${IMC.toFixed(2)} você está ABAIXO DO PESO`;
    }

EX 2:

else if (IMC >= 18.5 && IMC <= 24.9) {
        document.getElementById("qr").innerText = `Seu IMC é: ${IMC.toFixed(2)} você está no PESO IDEAL`;
    }
    
Assim, seguirá da mesma forma as outras condições propostas no código, que determinam se o usuário está Abaixo do Peso ou outras classificações de acordo com o resultado do cálculo matemático efetuado de acordo com os dados que o mesmo propôs na área designada. (FEITA POR HTML e CSS)

![image](https://user-images.githubusercontent.com/111540350/228518298-b9e311d4-daf3-4117-b4a9-99809e59a2a2.png)

RESULTADO FINAL DA VISUALIZAÇÃO DO CÓDIGO

![image](https://user-images.githubusercontent.com/111540350/228523219-32dc9e6c-62d2-4d0c-bced-4250c73243d4.png)









   
