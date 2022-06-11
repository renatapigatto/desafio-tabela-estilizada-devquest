# Desafio de Tabela Estilizada 

Esse repositório contém o primeiro desafio do curso DevQuest, no qual os alunos deveriam usar seus conhecimentos básicos de HTML e CSS para criar duas tabelas iguais ao exemplo abaixo:
<br></br>
<img src="./src/exemplo-tabelas.png" alt="exemplo das tabelas a serem recriadas">

## ❗ Materiais & Regras

Para isso, foram fornecidos os dados das tabelas, bem como as cores de fundo. Além disso, havia uma regra: não deveríamos estilizar as tabelas usando as tags HTML, deveríamos criar classes. 
<br></br>

## 💻 Linguagens Utilizadas
<img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg"> HTML 5
<img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg"> CSS 3
<br></br>


## 🤓 Aprendizados & Dificuldades

Fazer o código HTML foi relativamente simples e rápido, especialmente porque usei o atalho de criação de tabelas. Isso me poupou bastante tempo. 

A minha maior dificuldade foi na hora de definir quais classes seriam suficientes para estilizar a tabela, sem que o código ficasse muito extenso e/ou confuso.

No fim optei por fazer uma mescla de classe + tag. Acho que dessa forma tanto o HTML quanto o CSS ficaram organizados, fáceis de ler e também fáceis de editar no caso de ser necessário fazer alterações na página. 

Uma coisa interessante que aconteceu durante os meus testes das classes foi perceber que ao colorir o background das células individualmente, não foi necessário usar a propriedade ```border```. Inicialmente eu achei que seria necessário fazer uso dessa propriedade e no processo acabei aprendendo a propriedade 

```border-collapse: collapse```

que faz com que as células compartilhem de uma borda comum, como no exemplo abaixo:

<img src="https://i7x7p5b7.stackpathcdn.com/codrops/wp-content/uploads/2015/02/bordercollapse.png" alt="exemplo de uma tabela com borda separada versus uma com borda compartilhada">


## 💭 Alternativa

Depois de ter terminado o projeto (ou de ter achado que terminei), foi impossível não continuar pensando nele e em formas de melhorá-lo. Assim, acabou me ocorrendo outra solução para as classes e acho que vale deixar registrado aqui.

No HTML, ao invés de usar 3 classes diferentes  (```"tabela-padrao"``` para as duas tabelas e ```"cabecalho-tabela-moda"``` e ```"cabecalho-tabela-casa"``` para o cabeçalho de cada tabela, respectivamente), eu usaria somente uma classe diferente para cada tabela:
```
<table class="tabela-moda">
<table class="tabela-casa">
```
E no CSS usaria as combinações de classe+tag para o estilo:

```
.tabela-moda th{
    color: #ffffff;
    background-color: #BB86FC;
    padding: 5px;
}

.tabela-moda td{
    color: #ffffff;
    background-color: #424250;
    padding: 5px;
}

.tabela-casa th{
    color: #ffffff;
    background-color: #00C4B4;
    padding: 5px;
}

.tabela-casa td{
    color: #ffffff;
    background-color: #424250;
    padding: 5px;
}
```
Esse CSS fica um pouco mais longo que o que o do arquivo, porém me parece mais organizado. Não cheguei a uma conclusão de qual dos dois seria melhor, mas fiquei feliz de ter conseguido pensar em duas soluções diferentes e que acredito serem boas. 
