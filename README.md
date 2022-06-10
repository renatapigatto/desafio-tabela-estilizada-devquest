# Desafio de Tabela Estilizada 

Esse repositório contém o primeiro desafio do curso DevQuest, no qual os alunos deveriam usar seus conhecimentos básicos de HTML e CSS para criar duas tabelas iguais ao exemplo abaixo:
<br></br>
<img src="./src/exemplo-tabelas.png" alt="exemplo das tabelas a serem recriadas">
<br></br>

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