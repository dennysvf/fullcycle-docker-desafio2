# fullcycle-docker-desafio2
Desafio do curso fullcycle-docker-desafio2 .

### Descrição do desafio
> A ideia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro no banco de dados mysql, cadastrando um nome na tabela people e deve retornar o nome FullCycle este nome cadastrado logo abaixo.

__O retorno da aplicação node.js para o nginx deverá ser:__
```html
<h1>Full Cycle</h1>

- Lista de nomes cadastrada no banco de dados.
```

### Requisitos
1. Toda a aplicação deve estar disponível na porta 8080.

  
### Para rodar :zap:
```
git clone https://github.com/dennysvf/fullcycle-docker-desafio2.git

cd fullcycle-docker-desafio2

docker-compose up [-d]
```
<br/>
<br/>
