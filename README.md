# Bem vindo a API - 99 Heroes


###### Está API tem como objetivo disponibilizar um banco de dados com 99 heróis para utilização em projetos livres. Esta API pode ser usada em projetos escolares ou em aplicações de front-end que consomem API. Até o momento 20 heróis foram adicionados ao projeto. API de uso público.

## Retornos:
**id** (Retorna um Inteiro com o id único do herói) 

**nome_real_heroi** (Retorna uma String com o nome do herói)

**nome_identidade_atual**(Retorna uma String com o nome da identidade atual do herói)

**nome_afiliacao**(Retorna uma String com o nome da principal afiliação do herói)

**principal_base_de_operacoes**(Retorna uma String com a base de operações do herói)

**moralidade**(Retorna uma String com a moralidade do herói)

**nome_cidadania**(Retorna uma String com a cidadania do herói)

**estado_civil**(Retorna uma String com o estado civil do herói)

**ocupacao** (Retorna uma String com a principal ocupação do herói)

**sexo** (Retorna uma String com o sexo do herói)

**altura** (Retorna um Double com a altura do herói) 

**peso** (Retorna um Double com o peso do herói) 

**universo** (Retorna uma String com o universo do herói)

**imagem_principal** (Retorna uma String com o link da imagem de capa do jogo)

**imagem_secundaria_1** (Retorna uma String com a alguma imagem do jogo #1)



## Endpoints:
##### Retorna todos os heróis:
https://herokuapi20heroes.herokuapp.com/GetMethod/GetAllHeroes

##### Retorna herói por nome:
https://herokuapi20heroes.herokuapp.com/GetMethod/GetHeroByName/{name}

##### Retorna herói por genêro:
https://herokuapi20heroes.herokuapp.com/GetMethod/GetHerosByGender/{gender}

##### Retorna herói por cidadania:
https://herokuapi20heroes.herokuapp.com/GetMethod/GetHerosByCitizenship/{citizenship}

##### Retorna herói por universo:
https://herokuapi20heroes.herokuapp.com/GetMethod/GetHerosByUniverse/{universe}

##### Retorna herói por id:
https://herokuapi20heroes.herokuapp.com/GetMethod/GetHeroById/{id}

## Exemplos:

#### ***RETORNAR TODOS OS HERÓIS:***
###### Para verificar todos os heróis que existem na api, basta utilizar o endpoint ***/GetMethod/GetAllHeroes***. Nele você tem o retorno de um json com todos os heróis por ordem do ***ID***.
![allheroes](https://user-images.githubusercontent.com/62068883/170247052-17bf865f-d8ef-4a6c-8372-583ec4cd09b2.PNG)


#### ***RETORNAR HERÓI POR NOME:***
###### Para verificar um heróis buscando por nome, basta utilizar o endpoint ***/GetMethod/GetHeroByName/{name}***. Nele você precisa informar o nome do herói que quer encontrar. Se o nome do herói for correspondente a algum do banco, será retornado o json com os detalhes do herói, porém caso seja um valor inválido, irá retornar um ***null***.
![allheroes](https://user-images.githubusercontent.com/62068883/170247052-17bf865f-d8ef-4a6c-8372-583ec4cd09b2.PNG)


#### ***RETORNAR HERÓI POR GENÊRO:***
###### Para verificar um heróis buscando por genêro, basta utilizar o endpoint ***/GetMethod/GetHerosByGender/{gender}***. Nele você precisa informar o genêro do herói que quer encontrar. Se o nome do genêro for correspondente a algum do banco, será retornado o json com os todos os heróis com esse genêro, porém caso seja um valor inválido, irá retornar um ***null***.
![allheroes](https://user-images.githubusercontent.com/62068883/170247052-17bf865f-d8ef-4a6c-8372-583ec4cd09b2.PNG)


#### ***RETORNAR HERÓI POR CIDADANIA:***
###### Para verificar um herói buscando por cidadania, basta utilizar o endpoint ***/GetMethod/GetHerosByCitizenship/{citizenship}***. Nele você precisa informar a cidadania do herói que quer encontrar. Se a cidadania for correspondente a alguma do banco, será retornado o json com os todos os heróis com essa cidadania, porém caso seja um valor inválido, irá retornar um ***null***.
![allheroes](https://user-images.githubusercontent.com/62068883/170247052-17bf865f-d8ef-4a6c-8372-583ec4cd09b2.PNG)

#### ***RETORNAR HERÓI POR UNIVERSO:***
###### Para verificar um herói buscando por universo, basta utilizar o endpoint ***/GetMethod/GetHerosByUniverse/{universe}***. Nele você precisa informar o universo do herói que quer encontrar. Se o universo for correspondente a alguma do banco, será retornado o json com os todos os heróis desse universo, porém caso seja um valor inválido, irá retornar um ***null***.
![allheroes](https://user-images.githubusercontent.com/62068883/170247052-17bf865f-d8ef-4a6c-8372-583ec4cd09b2.PNG)


#### ***RETORNAR HERÓI POR ID:***
###### Para verificar um herói buscando por id, basta utilizar o endpoint ***/GetMethod/GetHeroById/{id}***. Nele você precisa informar o ID do herói que quer encontrar. Se o ID for correspondente a algum ID do banco, será retornado o json com o herói correspondente a esse ID, porém caso seja um valor inválido, irá retornar um ***null***.
![allheroes](https://user-images.githubusercontent.com/62068883/170247052-17bf865f-d8ef-4a6c-8372-583ec4cd09b2.PNG)
