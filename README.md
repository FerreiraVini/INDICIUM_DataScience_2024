# INDICIUM_DataScience_2024
Data science project test for INDICIUM

PT/BR
Este projeto foi desenvolvido como parte do processo seletivo da INDICIUM, desafio de Ciência de dados.
Dentro da pasta 'indicium data science project' encontram-se os arquivos para a execução do jupyter notebook com a análise de dados, incluindo o arquivo .csv, o arquivo de requisitos para a execução do projeto, bem como o arquivo com as respostas das perguntas do desafio (perguntas copiadas abaixo).

Arquivos na pasta 'Indicium data science project':

Challenge Answers.docx - Respostas para as perguntas do desafio. Este arquivo foi enviado também como PDF para o email selecao.lighthouse@indicium.tech

LH_CD_Vinicius_Guimaraes_Ferreira.ipynb - Jupyter Notebook com o código e a análise dos dados apresentados.

modelo.pkl - modelo LightGBM gerado ao término da análise de dados

requirements.txt - aquivo em txt com os requisitos para o notebook

teste_indicium_precificacao.csv - Arquivo .csv com os dados a serem analisados

Read_preprocess_model_fit_LH_CD_Vinicius_Guimaraes_Ferreira.ipynb - Jupiter notebook apenas com as funções necessárias para leitura, processamento e fitting do modelo. Arquivo pronto para leitura de bases de dados maiores.

Observações:
Todo o texto do jupyter notebook encontra-se em inglês.
Em caso de download e execução do notebook, atentar-se ao path do arquivo .csv, e aos requisitos.


________________________________________
Os objetivos requeridos para este projeto foram:

Desafio Cientista de Dados
________________________________________

Introdução

	Olá candidato(a), o objetivo deste desafio é testar os seus conhecimentos sobre a resolução de problemas de negócios, análise de dados e aplicação de modelos preditivos. Queremos testar seus conhecimentos dos conceitos estatísticos de modelos preditivos, criatividade na resolução de problemas e aplicação de modelos básicos de machine learning.  É importante deixar claro que não existe resposta certa e que o que nos interessa é sua capacidade de descrever e justificar os passos utilizados na resolução do problema. 

Desafio

Você foi alocado(a) em um time da Indicium que está trabalhando atualmente junto a um cliente no processo de criação de uma plataforma de aluguéis temporários na cidade de Nova York. Para o desenvolvimento de sua estratégia de precificação, pediu para que a Indicium fizesse uma análise exploratória dos dados de seu maior concorrente, assim como um teste de validação de um modelo preditivo.

Seu objetivo é desenvolver um modelo de previsão de preços a partir do dataset oferecido, e avaliar tal modelo utilizando as métricas de avaliação que mais fazem sentido para o problema. O uso de outras fontes de dados além do dataset é permitido (e encorajado). Você poderá encontrar em anexo um dicionário dos dados.


Entregas

1.	Faça uma análise exploratória dos dados (EDA), demonstrando as principais características entre as variáveis e apresentando algumas hipóteses de negócio relacionadas. Seja criativo!
2.	Responda também às seguintes perguntas:
a.	Supondo que uma pessoa esteja pensando em investir em um apartamento para alugar na plataforma, onde seria mais indicada a compra?
b.	O número mínimo de noites e a disponibilidade ao longo do ano interferem no preço?
c.	Existe algum padrão no texto do nome do local para lugares de mais alto valor? #WORD MAP
3.	Explique como você faria a previsão do preço a partir dos dados. Quais variáveis e/ou suas transformações você utilizou e por quê? Qual tipo de problema estamos resolvendo (regressão, classificação)? Qual modelo melhor se aproxima dos dados e quais seus prós e contras? Qual medida de performance do modelo foi escolhida e por quê?
4.	Supondo um apartamento com as seguintes características:

{'id': 2595,
 'nome': 'Skylit Midtown Castle',
 'host_id': 2845,
 'host_name': 'Jennifer',
 'bairro_group': 'Manhattan',
 'bairro': 'Midtown',
 'latitude': 40.75362,
 'longitude': -73.98377,
 'room_type': 'Entire home/apt',
 'price': 225,
 'minimo_noites': 1,
 'numero_de_reviews': 45,
 'ultima_review': '2019-05-21',
 'reviews_por_mes': 0.38,
 'calculado_host_listings_count': 2,
 'disponibilidade_365': 355}

Qual seria a sua sugestão de preço? Existe este anuncio!!! Price 225

5.	Salve o modelo desenvolvido no formato .pkl. 
6.	A entrega deve ser feita através de um repositório de código público que contenha:
a.	README explicando como instalar e executar o projeto
b.	Arquivo de requisitos com todos os pacotes utilizados e suas versões
c.	Relatórios das análises estatísticas e EDA em PDF, Jupyter Notebook ou semelhante conforme passo 1 e 2.
d.	Códigos de modelagem utilizados no passo 3 (pode ser entregue no mesmo Jupyter Notebook).
e.	Arquivo .pkl conforme passo 5 acima.
Todos os códigos produzidos devem seguir as boas práticas de codificação.


Dicionário dos dados

	A base de dados de treinamento contém 16 colunas. Seus nomes são auto-explicativos, mas, caso haja alguma dúvida, a descrição das colunas é:

id – Atua como uma chave exclusiva para cada anúncio nos dados do aplicativo
nome - Representa o nome do anúncio
host_id - Representa o id do usuário que hospedou o anúncio
host_name – Contém o nome do usuário que hospedou o anúncio
bairro_group - Contém o nome do bairro onde o anúncio está localizado
bairro - Contém o nome da área onde o anúncio está localizado
latitude - Contém a latitude do local
longitude - Contém a longitude do local
room_type – Contém o tipo de espaço de cada anúncio
price - Contém o preço por noite em dólares listado pelo anfitrião
minimo_noites - Contém o número mínimo de noites que o usuário deve reservar
numero_de_reviews - Contém o número de comentários dados a cada listagem
ultima_review - Contém a data da última revisão dada à listagem
reviews_por_mes - Contém o número de avaliações fornecidas por mês
calculado_host_listings_count - Contém a quantidade de listagem por host
disponibilidade_365 - Contém o número de dias em que o anúncio está disponível para reserva

__________________________________________________________________________________________________________________________
