# BUSINESS INTELLIGENCE - ANLISE E KPI's LOGISTICOS

Resultado da participação da segunda semana de Alura Challenge para o desafio de Business Intellingence. O case da semana foi criar uma análise com base em dados de um controle Logistico de entregas, pedidos e prazos de entregas. Utilizando a ferramenta Microsoft Power Bi foi possível resolver os problemas propostos.

## Ferramentas:
Utilizado como ferramenta de Análise de Data Visualization o Power Bi

## Objetivos:
No desafio precisavamos criar alguns KPI's Logístico, sendo:

⦁	Entregas feitas no prazo

⦁	Entregas fora do prazo

⦁	índice de ocorrências de pedidos por Estado

⦁	Qual o nível médio de estoque dos itens

⦁	Ship to Door - tempo médio entre a compra até chegar o item no cliente

⦁	Número de veículos disponíveis na frota para entrega

Explorando também alguns visuais com a criação de visuais com HTML baseados em um indíce de porcentagem de veículos disponíveis, de forma que o ícone torna-se preenchido conforme a procentagem de veículos em trânsito aumenta.
![image](https://github.com/lucasdelegredo/BI-Logistica/assets/74476423/b0d0d353-9a72-49e5-94be-7813540877dd)


# Dashboard
## ⦁	Página de visualização dos principais KPI's conforme os objetivos da análise:
![image](https://github.com/lucasdelegredo/BI-Logistica/assets/74476423/fc2bb688-db05-4626-9079-cabffea9a024)

### Extras
Foi criado alguns indíces a mais do que o solcitado pensando que de alguma forma pudessemos visualizar qual a porcentagem de atraso acontece mais em qual tipo de veículos para entre: carro, caminhonete ou moto. 
![image](https://github.com/lucasdelegredo/BI-Logistica/assets/74476423/b6eef107-af81-4ad4-b15d-726e5f861952)

E também um indíce que somava a quantidade do valor em estoque:
![image](https://github.com/lucasdelegredo/BI-Logistica/assets/74476423/1bef356a-53f8-4874-b532-71fb4f1775e4)


## Relacionamento de Dados
![image](https://github.com/lucasdelegredo/BI-Logistica/assets/74476423/b62c1523-99f2-463f-9638-e0ae5bcb7e7b)
Pensando que temos várias bases de dados nós precisamos relacionar elas de maneira correta, e dupliquei a tabela de estoque que possuia o balanço geral das contagens ao longo do mês do estoque. Nessa outra base duplicada com o nome de "saldo atual" foi pegado apenas a contagem mais recente de saldo de cada produto para que pudessemos relacionar com o registro de "Produtos" e assim saber qual o valor em estoque daquele produto em específico.
