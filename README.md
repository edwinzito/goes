# Cantina Legal

Projeto integrador das disciplinas **Banco de Dados** e **Linguagem de Programação**, ministrada por..., no Colégio Estadual Góes Calmon, localizado em ......

* **Alunos:** Edwin, Henrique, Renato, Sandra, e Uilton.
![Capa](https://upload.wikimedia.org/wikipedia/commons/c/c7/School_lunch.jpg)

****

## Problema
* Segundo o artigo 3º da Lei Nº 11.947, de 16 de junho de 2009, "a alimentação escolar é direito dos alunos da educação básica pública e dever do Estado e será promovida e incentivada com vistas no atendimento das diretrizes estabelecidas nesta Lei". A mesma lei diz que ela deve corresponder às espectativas higiênicas e culturais daquela localidade.
* Há um enorme empenho por parte do Colégio Estadual Goés Calmon em proporcionar uma boa alimentação aos seus alunos, fazendo com que assim, estejam energizados para desempenharem as atividades escolares. Com essa premissa, o colégio oferece um cardápio diversificado, com uma diversidade de nutrientes necessários para o desenvolvimento nutricional dos matriculados.
* Entretanto, o colégio não fornece de forma ininterrupta um guia com o cardápio semanal, fazendo com que os alunos não saibam com antecedência o prato que será servido, e seu respectivo teor nutricional. O projeto "Cantina Legal" propõe, através de um aplicativo aliado a um banco de dados, fazer um controle do que é posto no prato dos alunos.

## Proposta de solução
O aplicativo "Cantina Legal" possui dois módulos: o primeiro é o **controle interno dos nutrientes** necessários para a produção das merendas; o segundo módulo é o **cardápio semanal**.

### 1. Controle de estoque e dados nutricionais
Para o controle interno dos nutrientes necessários para a produção das merendas, classificando-os por:<br>
* :apple: **Nome:** Nome do alimento<br>
* :broccoli:	**Tipos:** A classificação do alimento. Fruta, vegetal, alimentos de origem animal, massa, grão<br>
* :watermelon:	**Valor nutricional**: Dados nutricionais dos alimentos.<br>
* :milk_glass: **Lactose**:  Dado *booleano* (Sim ou não) que indica se o alimento contém lactose.<br>
* :bread: **Glúten**: Dado booleano que indica se o alimento contém glúten.<br>
* :onion: **Quantidade em estoque:** Quanto se tem do produto disponível no estoque da cantina.<br>
* :pear: **Medida:** Demonstrar em qual grandeza, o produto está sendo quantificado. Seja em quilos (kg), litros (L), centímetros (cm), unidades, etc.<br>
* :salt: **Perecibilidade:** Dado *booleano* (Sim ou não). Indica se o produto perde facilmente a sua qualidade durante o tempo.<br>
* :carrot:	**Data da compra:** Quando o alimento foi comprado.<br>
* :egg: **Data da validade:** Prazo estipulado que o alimento pode perecer.<br>
* :bread: **Fornecedor:** Dados do estabelecimento ou comerciante que forneceu o produto.

### 2. Cardápio da semana
O **segundo** módulo é a disponibilização do cardápio antecipado do semana, para que o aluno fique ciente do teor nutritivo e saiba antecipadamente se pode ou gosta de determinado alimento:<br>
* :rice: **Nome do prato:** Nome do prato resultante da combinação dos materiais alimentícios em estoque.<br>
* :cookie: **Tipo de refeição**: como esse prato pode ser classificado: bebida, lanche, almoço, sobremesa, jantar, etc.
* :stew: **Data e hora:** Horário que o prato será servido.<br>
* :poultry_leg: **Ingredientes:** Os ingredientes que comprõem o prato.<br>
* :green_salad: **Composição nutricional**: a composição nutricional do prato servido.<br>
* :ballot_box: **Popularidade**: índice numérico que indica a popularidade do prato em questão entre os alunos. Dado obtido a partir de votação direta dos estudantes.

Com tais informações, o aluno sabe antecipadamente qual lanche será servido naquela semana, cabendo a ele se programar se irá ou não ao comer a alimentação fornecida pela cantina do colégio. 
Os discentes cadastrados poderão informar possíveis alergias ou outras restrições alimentares decorrentes da saúde. 
Esse processo digitaliza o acesso ao cardápio semanal da cantina, além de permitir o controle de quais estudantes podem ter restrições alimentares, como alergias e intolerância à lactose e ao glúten. 

## Funcionalidades:
* `Funcionalidade 1`: Gerenciar[^1] os materiais. 
* `funcionalidade 2`: Manter validades e quantidades dos produtos.
* `Funcionalidade 3`: Notificar quando o produto estiver em falta.
* `Funcionalidade 4`: Gerenciar os  produtos da cantina.

[^1]: Inclui as operações básicas: CREATE, READ, UPDATE, DELETE.

## Aplicação

 
## Ferramentas utlizadas
[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/1869px-Python-logo-notext.svg.png" height="40px">](https://www.python.org/)  <img src="https://cdn-icons-png.flaticon.com/512/2306/2306173.png" height="40px">

