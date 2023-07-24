# Benchmark do OpenRouteService

## 1. Introdução

Benchmark da API do OpenRouteService, buscando traçar uma rota entre dois pontos (FGA e Conjunto Nacional) com o objetivo de avaliar a complexidade e a dificuldade em utilizar a ferramenta, bem como medir o seu tempo de resposta.

## 2. Visualizando as rotas


### 2.1 Bibliotecas

As seguintes bibliotecas foram usadas para avaliar a API:

    import openrouteservice as ors
    import folium
    import math

### 2.2 Chave da API

O ORS necessita de uma chave de ativação para poder traçar uma rota, ela pode ser obtida neste site [ORS Docs](https://openrouteservice.org/dev/#/api-docs) e utilizada como no codigo a seguir:

    client = ors.Client(key='5b3ce3597851110001cf6248db9786ac4c7446dea93a21d0c244d5b2')


## 3. Conclusão

## 4. Referências

[Getting Directions in Python with OpenRouteService-py](https://syntaxbytetutorials.com/vehicle-route-optimization-in-python-with-openrouteservice/)
[VROOM GitHub](https://github.com/VROOM-Project/vroom/blob/master/docs/API.md)

## 5. Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data  |
| :----: | :-------: | :---------: | :-----: | :---: | 
| 1.0    | Criando documentação do Benchmark do ORS | João Leles | ;---;| 17/07 |