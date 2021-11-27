# typeorm
TypeORM - Exemplos

npm install typeorm --save

npm install reflect-metadata --save

npm install @types/node --save-dev

npm install typeorm -g

typeorm init --name exemplo2 --database pg

yarn typeorm migration:generate
# cria uma migration manualmente

yarn typeorm migration:create -n CreateUser

yarn typeorm migration:run

yarn typeorm migration:revert

yarn typeorm migration:show

yarn typeorm query "select * from <tabela>"

# Criar uma entity

npx typeorm entity:create -n <entity>

Referências
===========
https://www.youtube.com/watch?v=ZBlW5IBdhKk&list=PLDqnSpzNKDvn-3cpMf3yPn7gTnb3ooy4b

https://www.youtube.com/watch?v=6o0Vw0665kw&list=PLDqnSpzNKDvn-3cpMf3yPn7gTnb3ooy4b&index=2

https://www.youtube.com/watch?v=f--l_P6pa44&list=PLDqnSpzNKDvn-3cpMf3yPn7gTnb3ooy4b&index=3

https://www.youtube.com/watch?v=EHnTVyvr2nw&list=PLDqnSpzNKDvn-3cpMf3yPn7gTnb3ooy4b&index=4

https://www.youtube.com/watch?v=FDnuLtSxEEQ&list=PLDqnSpzNKDvn-3cpMf3yPn7gTnb3ooy4b&index=5
