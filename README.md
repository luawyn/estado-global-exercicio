# estado-global-exercicio

## Exercício: Pokédex

Nesse bloco, o exercício de todas as aulas será o desenvolvimento de uma Pokédex. 

## 📩  O que deve ser entregue nesta etapa?
    
        
### 🔀 Exercício 1 - Router
        
Assim como foi feito em aula, crie as rotas do seu projeto, conectando as três páginas do projeto:PokemonsListScreen ( que é a Home), PokedexScreen e PokemonDetailScreen.

Uma dica para essa atividade é desenhar as arvores de componentes do seu projeto, desde do componente Router, passando pelos componentes páginas e terminando em componentes menores, que podem, inclusive, estar em mais de uma página. 
        
### 🔲  Exercício 2- Criação de Componentes Visuais
        
Agora é a hora de botar a mão na massa e começar a codar! Mas antes que vocês comecem, é importante deixarmos claro uma coisa:
        
As aulas seguintes vão ser muito importantes para que vocês consigam usar o estado de uma maneira diferente da que conhecem até agora. Portanto, a dica é que no exercício de hoje, vocês se restrinjam à parte visual do site, sem conectar com a API do pokemon.
        
Ou seja, definam as cores  primária e secundária do site, criem o componente card de pokemon, para que ele possa depois receber as informações da API. Criem o Header, a parte visual da página de detalhes, etc.

Abaixo segue alguns templates para ajudar vocês a visualizar as páginas: 

### Home
- Em cada card de Pokemon deve haver um botão para adicioná-lo à Pokedex e um outro botão para acessar os detalhes do Pokemon.
- Além disso, no header dessa página, deve haver um botão para acessar a página da Pokedex, detalhada à seguir.

![Captura de Tela 2022-11-30 às 01 21 34](https://user-images.githubusercontent.com/71261731/204706905-94dacc9e-c1ac-4822-9bbc-6b2c7b34519f.png)
### Detail
- No cabeçalho, além de um botão de voltar para a última página que o usuário estava, haverá um botão (na direita) para adicionar ou remover da Pokedex a partir da página de detalhes. Esse botão deve verificar se o Pokemon detalhado já está na Pokedex ou não e, a partir disso, adicionar ou remover o Pokemon da Pokedex.

![Captura de Tela 2022-11-30 às 01 24 01](https://user-images.githubusercontent.com/71261731/204707151-22466014-0f71-4ce5-b033-9887657f0654.png)
### Pokedex
- Em cada card de Pokemon deve haver um botão para removê-lo da Pokedex e um outro botão para acessar os detalhes do Pokemon. (Ou seja, um componente bastante semelhante ao utilizado na Home)
- Além disso, no header dessa página, deve haver um botão para voltar para a Home, página com a lista de Pokemons vinda da API.

![Captura de Tela 2022-11-30 às 01 24 54](https://user-images.githubusercontent.com/71261731/204707266-e3d1d7e1-08be-4a6a-97f7-71571affe9c6.png)

## Exemplo de layout das paginas descritas acima
http://nonchalant-afterthought.surge.sh/ 


 ### 🗂 Exercício 2 - Collection do Postman
    
   Vocês viram que será necessário o uso de alguns endpoints de uma API pública: a Poke API. 
    
   Uma coisa bem comum que fazemos quando vamos usar uma API pública, que não possui uma collection pronta, é criar a collection de endpoints que vamos usar. Isso é bem importante para que não precisemos ficar indo e voltando na documentação da API e para que tenhamos todos os endpoints necessários para o projeto separados no Postman. 
    
   Portanto, a partir da descrição do projeto que vocês acabaram de ler, criem no Postman, em uma collection separada, os endpoints que vocês imaginam que vão precisar durante o projeto.
    
   Para entregar essa collection, pelo Postman, exporte ela para um documento e acrescente esse documento no repositório do projeto. Para exportar uma collection do postman, siga esse print:
   
  ![Captura de Tela 2022-11-30 às 02 01 30](https://user-images.githubusercontent.com/71261731/204711603-ba3a7836-55b1-4da6-9804-f42692852755.png) 
