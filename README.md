# GitStudy

## Esse documento foi feito com base no vídeo da Rocketseat
# Link: [Rockeatseat](https://www.youtube.com/watch?v=2alg7MQ6_sI&t=939s)

### Começamos um projeto git com
`` git init ``

### Criamos ou atualizamos as mudanças da linha do tempo com:
``git add nome_arquivo ou . (para caso for tudo)``

### Adicionamos um ponto na linha do tempo
``git comit -m 'Nome-Ponto-Historia'``

### Podemos ver o estado do desenvolvimento com:
``git status``

### Podemos ver os ponto na linha do tempo:
``git log``

### Apresenta o ponto na história:
``git show [id_arquivo = Para caso queremos especificar o ponto]``

### Gerenciamento de linhas paraleras/alternativas/ramificação através do. Nota: caso sozinho só apresenta as ramificações:
``git brach [nome_ramificacao = Para caso queira criar uma ramificação][-D = Caso queira deletar uma ramificação]``

### Mudanças entre ramifacações:
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
