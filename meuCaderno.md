# Aula01 - Introdução ao flexsbox e fazendo o cabeçalho
## Arrumando Cabeçalho:  
```position: flex;``` Dentro do container para ativar o flexbox.  
```align-items: center;``` Alinhar os objetos dentro do container flex verticalmente no centro.  
```justify-content: space-between;``` Pega o espaço vazio e o coloca entre os itens.
## Terminando Cabeçalho:  
apenas ativou a ```position: flex;``` em outra propriedade para deixar os menus em linha.  

# Aula02 - Fazendo o footer e controlando melhor os elementos
## Arrumando o footer:  
```justify-content: space-around;``` Pega o espaço vazio e o coloca em volta dos elementos.
## Arrumando o course map:  
```flex-direction: column;``` Faz o flex em coluna.  
```flex-wrap: wrap;``` Faz a quebra da coluna.  
```flex-flow: column wrap;``` Faz os dois comandos acima em um.  

# Aula03 - Grid principal e limitações do flexbox
## Arrumando course grid:
- Flex não é bom para fazer um grid.  
## Terminando course grid:  
- Foi utilizado ```nth-child()``` para retirar margins de alguns itens.