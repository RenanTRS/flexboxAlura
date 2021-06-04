# Aula01 - Introdução ao flexsbox e fazendo o cabeçalho
## Arrumando Cabeçalho:  
```display: flex;``` Dentro do container para ativar o flexbox.  
```align-items: center;``` Alinhar os objetos dentro do container flex verticalmente no centro.  
```justify-content: space-between;``` Pega o espaço vazio e o coloca entre os itens.
## Terminando Cabeçalho:  
apenas ativou a ```display: flex;``` em outra propriedade para deixar os menus em linha.  

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

# Aula04 - Arrumando os elementos com flex para moblie
## Começando responsivo:
- No momento que se usa ```flex-direction: column;``` os eixos ficam invertidos.
## Flex order:  
```order: -1;``` Coloca o item em primeiro.
## Vantagens e o vídeo:  
```flex-grow: 1;``` Ele divide o tamanho vazio que sobrou e acrescenta ao item.
## Vantagens responsivo:  
```flex-shrink: 2;``` Diminui a anotação proporcionalmente em 2x a medida que a tela reduz o tamanho.