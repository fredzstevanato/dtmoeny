### Create React App

### Styled Components

  Nesta aplicação foi utilizada a estratégia  CSS in JS , ou seja CSS no javascript atráves da biblioteca styled-components addicionada com o comando: 

    ``` 
  yarn add styled-components
  yarn add -D @types/styled-components
    ```
    
  Existe uma series de vantagens em utilizar esta biblioteca entre elas podemos destacar a utilização do CSS em escopo, trabalhar com valores dinâmicos através de varias e valores do próprio JS, diminuição nos DEAD CODE, e Server side render.

  #### Criando estilizações globais

    Foi criado o arquivo em src/styles/global.ts, foram geradas configurações padrãoes e medias queries com tamanhaos 1080px e 720px, logo foi definido valores em porcentagem para os tamanhos das fontes, sendo utilizado por padrão neste projeto a unidae de media *rem* essas configurações fazem com que as fontes diminuam dependendo do tamanha da tela do usuário, começando assim o processo de responsividade e acessibilidade.