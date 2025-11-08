##  Análise de Campanha de Marketing - Perfil de Clientes (EDA)

Este repositório contém uma Análise Exploratória de Dados (EDA) realizada sobre um conjunto de dados de marketing. O objetivo é dissecar os dados para entender padrões de consumo, identificar perfis de clientes e extrair insights que possam orientar futuras estratégias de marketing digital.

##  🎯 Objetivo do Projeto
O objetivo principal desta análise é realizar uma Análise Exploratória de Dados (EDA) para responder a perguntas de negócio fundamentais sobre o comportamento do cliente.

Queremos "ouvir" o que os dados têm a dizer para identificar quem são os clientes mais valiosos e como eles se comportam.

##  📊 Dataset Utilizado
Para este estudo, utilizámos o "Marketing Campaign Dataset", um conjunto de dados popular e detalhado disponível publicamente na plataforma Kaggle.

Fonte: Kaggle - Marketing Campaign Dataset

Descrição: O dataset agrega dados de 2.240 clientes, incluindo informações demográficas (idade, renda, escolaridade, agregado familiar), hábitos de consumo (gastos em vinhos, frutas, carne, etc.) e o desempenho em campanhas de marketing anteriores.

##  ❓ Perguntas de Negócio (Questões da Análise)
A nossa exploração foi guiada pelas seguintes perguntas-chave:

Qual é o perfil demográfico médio dos clientes (distribuição de idade, renda e nível educacional)?

Existe uma relação clara entre a renda anual do cliente e o seu gasto total na plataforma?

O nível educacional influencia o volume de gastos?

Como a composição familiar (número de crianças ou adolescentes em casa) afeta o gasto total do cliente?

Quais são os produtos (ex: vinhos, carne, frutas) preferidos pelos clientes que mais gastam?

##  💡 Principais Descobertas e Conclusões
Através da visualização e análise dos dados, chegámos às seguintes conclusões principais:

Renda é Chave: Existe uma forte correlação positiva entre a renda (Income) e o gasto total (Total_Spent). Clientes com rendas mais altas gastam exponencialmente mais.

Educação Importa: O gasto médio aumenta significativamente com o nível educacional. Clientes com PhD (Doutoramento) e Master (Mestrado) apresentam uma mediana de gastos muito superior à dos clientes com Graduation (Licenciatura).

Filhos em Casa = Menos Gastos: Esta foi uma das descobertas mais impactantes. Clientes sem filhos ou adolescentes em casa têm um gasto médio drasticamente superior. O gasto diminui progressivamente com cada criança/adolescente adicionado ao lar.

Perfil do "Cliente Ideal" (High-Value): Com base na análise, o perfil de cliente que mais gasta tende a ser:

Mais velho (45-65 anos).

Possui uma renda anual elevada (acima de 80.000).

Tem um nível educacional alto (Mestrado ou Doutoramento).

Não tem filhos ou adolescentes a viver em casa.

Estes insights sugerem que campanhas de marketing para produtos de alto valor (como vinhos e carnes) devem ser segmentadas para este perfil específico, enquanto produtos mais económicos podem ser direcionados para famílias maiores.

##  🛠️ Ferramentas Utilizadas
Linguagem: Python

Bibliotecas:

pandas (para manipulação e limpeza de dados)

matplotlib (para visualização de dados)

seaborn (para visualização estatística avançada)

Jupyter Notebook (como ambiente de análise)
