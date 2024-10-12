# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é meu caderno virtual. Aqui você encontrará todos os conceitos e atividades dessa unidade curricular. 

## Conteúdo Técnico
### JavaScript
#### o que é:
- JavaScript é uma linguagem de programação de orientada a objetos, utilizada para adicionar interatividade e dinamicidade a páginas web. Juntamente com HTML e CSS, e permite a manipulação do Document Object Model (DOM), comunicação assíncrona e desenvolvimento de aplicações web completas. Além disso, O JavaScript também pode ser executado no lado do servidor.

### VARIÁVEIS
#### VAR
- Têm escopo global ou de função. podem ser atualizadas e declaradas novamente. EX:
```js
var x = 10;
console.log(x); // 10

var x = 20; // Re-declaração
console.log(x); // 20
```

#### LET
- Têm escopo de bloco. podem ser atualizadas, mas não podem ser declaradas novamente. EX:
```js  
let y = 10;
y = 30; // Isso é válido
console.log(y); // 30
```

#### CONST
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

### OPERADORES LÓGICOS 
#### USADOS PARA COMBINAR CONDIÇÕES. ELES RESPONDEM PERGUNTAS COMO "E", "OU" e "NÃO".
- E (&&): AMBAS AS CONDIÇÕES PRECISAM SER VERDADEIRAS. EXEMPLO: 
```js
let idade = 30;
idade >= 18 && temCarteiraDeMotorista
```

- OU (||): APENAS UMA DAS CONDIÇÕES PRECISAM SER VERDADEIRA. EXEMPLO: 
```js
let estaEnsolarado = true;
let estaFrio = false;

if (estaEnsolarado || !estaFrio) {
    console.log("Posso sair!");
} else {
    console.log("Melhor ficar em casa.");
}
```

- NÃO (!): INVERTE O RESULTADO DE UMA CONDIÇÃO. EXEMPLO: 
```js
let estaChovendo = false;

if (!estaChovendo) {
  console.log("Podemos ir à praia!");
}
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

### ARRAY
- SERVE PARA GUARDAR VÁRIOS VALORES, UM EM CADA POSIÇÃO. ESSES VALORES PODEM SER NÚMEROS, PALAVRAS, OU OUTRAS ARRAYS. EX: 
```js
// Criando um array de frutas
let frutas = ["maçã", "banana", "laranja"];

// Acessando um elemento do array
console.log(frutas[0]); // Imprime: maçã
```

### FUNÇÃO  
- SÃO BLOCOS DE CÓDIGO QUE DESEMPENHAM UM PAPEL FUNDAMENTAL PODENDO SER CHAMADOS E EXECUTADOS VARIAS VEZES EM DIFERENTES PARTES DO PROGRAMA PERMITINDO A ORGANIZAÇÃO LÓGICA. EX:
```js
let nome = "Tereza";

function saudacao(nome) {
  console.log("Olá, " + nome + "!");
}

saudacao("Tereza"); // Imprime: Olá, Tereza!
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
