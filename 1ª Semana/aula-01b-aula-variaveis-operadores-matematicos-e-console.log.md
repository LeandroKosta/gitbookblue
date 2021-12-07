# Aula 01b - \[AULA] Variáveis, operadores matemáticos e console.log()

### O que vamos aprender?

* <mark style="color:blue;">**Características do JavaScript**</mark>
* <mark style="color:blue;">**Console.log();**</mark>
* <mark style="color:blue;">**Comando Prompt();**</mark>
* <mark style="color:blue;">**Variáveis em JavaScript**</mark>
* <mark style="color:blue;">**Operadores em JavaScript**</mark>

## Características do <mark style="color:blue;">JavaScript</mark>!

* Orientada a objeto;
* Sem distinção entre tipos e obejtos;
* A herança é feita através do protótipo;
* As propriedades e métodos podem ser adicionadas a qualquer objeto dinamicamente;
* Os tipos de dados das variáveis não precisam ser declaradas (tipagem dinâmica);
* Não pode escrever automaticamente no disco rigído;
* Linguagem não compilada;

#### Em resumo:

JavaScript é uma linguagem de script orientada a objetos, multiplataforma. É uma linguagem pequena e leve. Dentro de um ambiente de host (por exemplo, um navegador web) o JavaScript pode ser ligado aos objetos deste ambiente para prover um controle programático sobre eles.

## Processo de Organização!

Vamos preparar nosso ambiente de trabalho criando uma pasta chamada <mark style="color:blue;">**"Blue Edtech",**</mark> escolha o melhor local para criar está pasta.

![](<../.gitbook/assets/1.criar pasta blueedtech.png>)

Agora dentro da pasta <mark style="color:blue;">**"Blue Edtech"**</mark> vamos criar outra pasta chamada <mark style="color:blue;">**"Módulo 1"**</mark>.

![](<../.gitbook/assets/2.criar pasta modulo1.png>)

Dentro da pasta <mark style="color:blue;">**"Módulo 1"**</mark> vamos criar uma pasta chamada <mark style="color:blue;">**"Aula01"**</mark>.

![](<../.gitbook/assets/3.criar pasta aula01.png>)

Agora clique com o botão direiro do mouse na pasta <mark style="color:blue;">**"Aula01"**</mark>, vai aparecer está aba, em <mark style="color:blue;">**"abrir com"**</mark> selecione o <mark style="color:blue;">**"VSCode"**</mark>.

![](<../.gitbook/assets/4.abrir pasta aula1 com vscode.png>)

Agora que já estamos dentro do VsCode, vamos colocar a mão na massa e criar nosso primeiro arquivo.

Nesse momento estamos dentro da pasta <mark style="color:blue;">**"Aula01"**</mark>, vamos criar um <mark style="color:blue;">**"Novo Arquivo"**</mark>.

![](<../.gitbook/assets/5.criar novo arquivo.png>)

Vamos nomear nosso "Novo Arquivo" de <mark style="color:blue;">**index.js**</mark> e apertar o entrer, com isso o arquivo será criado e aberto ao lado conforme imagem abaixo.

![](<../.gitbook/assets/6.abrir novo arquivo.png>)

Agora vamos aprender nosso primeiro comando.

## Console.log() em JavaScript

Exibe uma mensagem na console do navegador.

Considerado "mais agradável" para a exibição de uma mensagem por não envolver um pop-up. A mensagem será exibida no sonsole do navegador.

### Sintaxe:

console.log(obj1\[, obj2, ..., objN]);

console.log(msg\[, subst1, ..., substN]);

### Bora Lá Codar!

No seu VsCode digite o seguinte comando:

```
console.log ("Olá Bluemers!");
```

![](<../.gitbook/assets/7.digitar console.log.png>)

Agora vamos abrir um terminal para executar no codigo.

No menu principal clique em <mark style="color:blue;">**"Terminal"**</mark> e depois em <mark style="color:blue;">**"Novo Terminal"**</mark>.

![](<../.gitbook/assets/8.abrir novo terminal.png>)

Vai aparecer um terminal na tela, logo abaixo do seu código conforme a imagem abaixo, agora vamos digitar o seguinte comando para executar o nosso console.log.

```
node index.js
```

![](<../.gitbook/assets/9.digitar node index.js.png>)

{% hint style="info" %}
Dica Blue: Sempre que possível aprenda a ler e entender a documentação da linguagem ou comando que você está aprendendo.
{% endhint %}

### Exemplo:&#x20;

{% hint style="info" %}
Dica Blue: No terminal se você aperta a seta para cima no teclado os comandos que foram digitados anteiormente no terminal vão ser selecionados, basta escolher e aperta entrer, assim não precisa digitar novamente, ganhando tempo na execução do código.
{% endhint %}

###
