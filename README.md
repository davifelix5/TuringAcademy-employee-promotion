# Enunciado do projeto

## Contexto 

Nos últimos anos, o mercado de trabalho tem mudado muito, e muitas profissões
tiveram um crescimento muito grande; com isso, uma grande empresa que fabrica
roupas, a TurinGucci, precisa saber quais de seus funcionários devem ser promovidos
para que a produtividade da empresa cresça!

Por esse motivo, foi contratada uma segunda empresa especializada em serviços de
RH, o Grupo Touring, para analisar dados a respeito de cientistas de dados. O Grupo
Touring busca ajuda na **construção de um modelo para predizer se um determinado
funcionário deve ser promovido ou não**.

Por isso, sabendo do seu sucesso na análise feita para o processo seletivo para a
empresa, o Grupo Touring te propõe um desafio a mais: **além de limpar e analisar
alguns dados para eles, você terá que construir um modelo que prediz se um
determinado funcionário deve ou não ser promovido**. Portanto, você deverá limpar
os dados fornecidos e realizar uma análise rápida a fim de obter insights
interessantes, como por exemplo quais as relações entre as colunas, e quais colunas
mais se relacionam com a target (se o funcionário deve ou não ser promovido). 

Por fim, você deverá **treinar um modelo que tenha bons resultados para realizar a
predição necessária**. Para isso, utilize os conhecimentos adquiridos nas aulas a
respeito das bibliotecas de manipulação e análise de dados e sobre aprendizado
supervisionado e métricas.


## Informações sobre o dataset


Os datasets contidos nos arquivos "train.csv" e "test.csv" possuem informações a respeito de candidatos para um determinado
processo seletivo. 

As colunas presentes são:

- **employee_id**: ID único do funcionário;
- **department**: departamento do funcionário;
- **region**: região de emprego (não ordenada);
- **education**: nível educacional do funcionário;
- **gender**: gênero do funcionário
- **recruitment_channel**: canal de recrutamento para o funcionário;
- **no_of_trainings**: número de treinamentos completados em anos passados,
sejam em soft skills, technical skills, etc.
- **age**: idade do funcionário;
- **previous_year_rating**: avaliação do funcionário para o ano anterior;
- **length_of_service**: duração do serviço em anos;
- **awards_won**?: se ganhou algum prêmio em anos anteriores, recebe 1, do
contrário 0;
- **avg_training_score**: pontuação média nas avaliações de treinamento atuais;
- **is_promoted**: (Target) recomendado ou não para promoção.
