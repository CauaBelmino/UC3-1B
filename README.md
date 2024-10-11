# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é meu caderno virtual. Aqui você encontrará todos os conceitos e atividades dessa unidade curricular. 

## Conteúdo Técnico
### JavaScript
#### o que é:
- JavaScript é uma linguagem de programação de orientada a objetos, utilizada para adicionar interatividade e dinamicidade a páginas web. Juntamente com HTML e CSS, e permite a manipulação do Document Object Model (DOM), comunicação assíncrona e desenvolvimento de aplicações web completas. Além disso, O JavaScript também pode ser executado no lado do servidor.

### VARIÁVEIS
#### var
- Têm escopo global ou de função. podem ser atualizadas e declaradas novamente. EX:
```js
var x = 10;
console.log(x); // 10

var x = 20; // Re-declaração
console.log(x); // 20
```

#### let
- Têm escopo de bloco. podem ser atualizadas, mas não podem ser declaradas novamente. EX:
```js  
let y = 10;
y = 30; // Isso é válido
console.log(y); // 30
```

#### const
- Não podem ser atualizadas nem declaradas novamente. EX:
```js    
const z = 10;
// z = 20; // Isso geraria um erro
console.log(z); // 10
```

### Tipos de dados
#### STRING
- UMA SEQUÊNCIA DE CARACTERES LIMITADA POR ASPAS SIMPLES (' ') OU ASPAS DUPLAS (" "). EX:
```js
let nome = "Tereza";
let sobrenome = 'oliveira';
```

#### NUMBER
- QUALONER NÚMERO INTEIRO OU DECIMAL REPRESENTADO SEM ASPAS. EX:
```js  
let idade = 30;
let altura = 1.75;
```

#### BOOLEAN
- REPRESENTA UM VALOR LOGICO (VERDADEIRO [TRUE] OU FALSO [FALSE]). EX:
```js    
let estaChovendo = TRUE;
let temSol = FALSE;
```

### ESTRUTURAS CONDICIONAIS 
#### IF/ELSE
- EXECUTA UM BLOCO DE CODIGO SE A CONDIÇÃO FOR VERDADEIRA (IF), CASO A CONDIÇÃO SEJA FALSA OUTRO BLOCO (ELSE [OPICIONAL]) SERÁ EXECUTADO. EX:
```js
let idade = 18;
if (idade >= 18) {
console.log("VOCE É MAIOR DE IDADE")
}else{
console.log("VOCE É MENOR DE IDADE")
}
```

#### SWITCH CASE
- PERMITE ESCOLHER ENTRE VÁRIAS OPÇÕES DE EXECUÇÃO COM BASE NO VALOR DE UMA EXPRESSÃO. EX:
```js  
let diaDaSemana = 3;

switch (diaDaSemana) {
  case 1:
    console.log("Hoje é segunda-feira!");
    break;
  case 2:
    console.log("Hoje é terça-feira!");
    break;
  case 3:
    console.log("Hoje   
 é quarta-feira!");
    break;   

  default:
    console.log("Dia inválido!");
}
```

## Atividades desenvolvidas
- Aula 08/08 https://codepen.io/chomebook-cau-/pen/wvLqeMG
- Aula 12/08 https://codepen.io/chomebook-cau-/pen/yLdbmEN
- Aula 16-20/08 https://codepen.io/chomebook-cau-/pen/ZEdvozJ
- Atividade tiktok https://codepen.io/chomebook-cau-/pen/bGPKBLB
- Aula 06/09 https://codepen.io/chomebook-cau-/pen/QWXzgpw
- Atividade array https://codepen.io/chomebook-cau-/pen/OJedjaR
- Aula 10/09 https://codepen.io/chomebook-cau-/pen/dyBrbWo
- Aula Jogo https://codepen.io/chomebook-cau-/pen/xxvVOpG
- Atividade função 04-07/10 https://codepen.io/chomebook-cau-/pen/qBeNzEg
- Split o8/10 https://codepen.io/chomebook-cau-/pen/oNKzoLO
- Atividade função array 10/10 https://codepen.io/chomebook-cau-/pen/dyxOdNZ
