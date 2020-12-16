# GitStudy

## Esse documento foi feito com base no vídeo da Rocketseat
# Link: [Rockeatseat](https://www.youtube.com/watch?v=2alg7MQ6_sI&t=939s)
# Ajuda do (Luiz)[]

### Requisitos
- git instalado na máquina globalmente
- conta no github

### Começo
Primeiramente instalamos o git na nossa máquina, use esse link para acessar a página de dowload de acordo com o seu sistema operacional: [Instalação do git](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git)

## Antes de tudo
Assim como tudo na vida, existe o básico que dá pra sobreviver e o que vai deixar ainda mais fácil sua vida, então deixarei separado em duas partes, o essencial para postar um projeto no github e o que vai lhe dar uma ajudinha a mais.

### O essencial

#### onfiguração do git
Para usarmos o git precisamos configurar um 'marcador' que ficará no nosso projeto para caso alguém que o veja queira se comunicar com a gente, então atensão USE INFORMAÇÕES FORMAIS! Não use nomes fictícios como shadowFoxy120 kkk.

##### Passos
- Configuração do nome: `git config --global user.name "Fulano de Tal"`
- Configur do email: `git config --global user.email fulanodetal@exemplo.br`

### Começamos um projeto git com
`` git init ``

### Podemos ver o estado do desenvolvimento com:
Após ter os arquivos na sua pasta dê esse comando e veja o status do projeto no momento (Aconselho também depois do git add ver o status).  
``git status``

### Adicionando os arquivos na fila para colocar no repositório
Para começarmos temos que colocar os arquivos na fila, aí depois podemos colocar eles no reposítório.  
``git add caminho/nome_arquivo ou . (para caso for tudo)``

### Adicionamos um ponto na linha do tempo
Um ponto na histório do repositório é quando alocamos algo no nosso repositório, como podemos adicionar várias vezes uma atualização no repositório colocamos um nome a essa atulização (mas também é adicionado um id que podemos trabalhar depois)  
``git comit -m 'Nome-Ponto-Historia'``

### Podemos ver os ponto na linha do tempo:
``git log``

### Informações do ponto da história
Com o git show podemos ver as informações sobre o ponto na histório do repositório, como quem fez as mudanças, o que foi mudado, entre outros de uma forma mais completa.  
``git show [id_arquivo = Para caso queremos especificar o ponto]``

### Gerenciamento de linhas paraleras/alternativas/ramificação através do. Nota: caso sozinho só apresenta as ramificações:
``git brach [nome_ramificacao = Para caso queira criar uma ramificação][-D = Caso queira deletar uma ramificação]``

### Mudanças no tempo e ramificações:
Com o git é possível fazer o impossível, podemos desde mudar entre ramificações até mudança no tempo.  
``git checkout nome_ramificacao[nome_ramificaçãõ = Também pode recurar uma ramificação][[nome_ramificação = Para caso queira especificar a ramificação]--nome_arquivo = Para caso queira recuperar a ultima versão do arquivo]``

### Para unir as ramificações usamos o:
``git merge nome_ramificacao``

### Para nos conectarmos ao repositório na nuvem:
``git remote add origin link_repositorio``

### Para atualizarmos nosso repositótio na nuvem:
``git push``
#### No caso da primeira vez no repositório online:
``git push -u origin master``

### No caso de não quisermos toda vez que mandarmos algo para o repositório do git ter que colocar senha:
``git config credential.helper store``

### Podemos pegar um projeto já iniciado através do:
``git clone link_repositorio``

### Podemos atualizar o projeto com os dados em nuvem:
``git pull``

### Movendo arquivos
Podemos mover arquivos entre o projeto com o git.  
`git mv caminho/arquivo`

### Removendo arquivos
Podemos remover arquivos do projeto com o git.  
`git rm caminho/arquivo`

> Esse é um projeto pessoal e introdução ao básico do git, mas nunca dispense a documentação original.  
> [git](https://git-scm.com/doc)
