# nutri-app
Aplicativo que calcula as calorias e macronutrientes da dieta construída pelo usuário. Deve ser desenvolvido em python ou javascript.

A ideia é que o usuário construa cada refeição, com os alimentos e quantidades desejadas, e o aplicativo retorne a quantidade de calorias e de cada macronutriente (carboidratos, proteínas, gorduras, fibras, etc.), além dos respectivos percentuais em relação à quantidade alvo

O aplicativo oferece sugestões de cada macronutriente de acordo com o objetivo, mas é possível realizar alterações

É possível ainda cadastrar alimentos que não estão no banco e gerar fatos aleatórios sobre nutrição.

Seguem as telas desenhadas para este aplicativo:

## Tela principal
![image](https://github.com/leticiafaria7/nutri-app/assets/95353211/b3abafe7-1bb3-4949-a7f5-cae113868c30)

## Planejador
Inicialmente, são feitas algumas perguntas para o usuário:
- Objetivo: pode ser emagrecimento, hipertrofia ou manutenção do peso
- Peso: o peso em kg do usuário, para auxiliar nos cálculos dos macronutrientes
- Sexo: a quantidade recomendada de ferro varia com o sexo do usuário

![image](https://github.com/leticiafaria7/nutri-app/assets/95353211/a20136d6-5fe3-4e2b-acdf-ea29c120e09c)

Após o preenchimento das perguntas, os totais são preenchidos de acordo com a recomendação, sendo possível ao usuário fazer alterações nos números. A tela de dicas mostra algumas recomendações de especialistas:

![image](https://github.com/leticiafaria7/nutri-app/assets/95353211/38675e88-0460-4c87-b2b8-dc2c073732c8)

Finalizado o preenchimento, o planejador tem a seguinte tela:

![image](https://github.com/leticiafaria7/nutri-app/assets/95353211/437fbb58-a92d-4251-9257-80cb2b2d3618)

Nela, é possível escolher a opção de cada refeição, e escolhidas as opções, o gráfico mostra o percentual de calorias e de cada macronutriente total da dieta diária.

As barras ficam verdes e vermelhas de acordo com o macro e com o objetivo. Por exemplo: se for uma dieta para emagrecimento, caso o total de calorias fique abaixo de 100%, a barra fica verde; se ficar acima, fica vermelha. Se for uma dieta para hipertrofia, caso o percentual de carboidratos fique abaixo de 100%, a barra fica vermelha; se ficar acima, fica verde.

É possível cadastrar uma opção de refeição também. A tela de cadastro de refeições é a seguinte:

![image](https://github.com/leticiafaria7/nutri-app/assets/95353211/8db06097-d604-4da4-91d9-d3833784d183)

É necessário escolher a refeição e colocar as quantidades de cada alimento escolhido em termos da porção de referência. A tabela à direita fornece as quantidades totais de cada macro para aquela refeição. Adicionando um alimento, é possível inserir mais uma linha na tabela. É possível consultar as quantidades de calorias e de cada macro para os alimentos, nesta tela:

![image](https://github.com/leticiafaria7/nutri-app/assets/95353211/561b1034-1ed9-4c52-a10f-6020c0bacb81)

É possível simular as quantidades com a porção desejada.

É possível também cadastrar um alimento que não está no banco. O cadastro de alimento tem a seguinte tela:

![image](https://github.com/leticiafaria7/nutri-app/assets/95353211/0d9fa84b-cf47-46ba-a99f-b9db11c7ed6f)

É necessário colocar o nome do alimento e o preparo (cru, cozido, grelhado, etc), a porção de referência em gramas e pode colocar uma quantidade aproximada (1 unidade, 1 colher de sopa, etc); depois disso, coloca-se as quantidades de macro daquele alimento para aquela porção de referência.

## Gerar dieta

Após a escolha das opções de cada refeição, é possível gerar a dieta, que será exibida nesta tela:

![image](https://github.com/leticiafaria7/nutri-app/assets/95353211/91b478b1-2d28-4e57-a9ee-0688a50db3d4)

É possível então salvar a dieta no próprio programa para consultar ou então gerar um PDF.

## Ideias futuras

Fazer um histórico de delta calórico de acordo com a quantidade de calorias ingeridas no dia.
