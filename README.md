# Desafio 6: Preveja os usuários com alta chance de deixar seu Streaming

Arquivos do Desafio:
https://www.notion.so/signed/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F9476d09e-5efc-4dee-8dd0-cbc871115ece%2Fstreaming_data.csv?table=block&id=35886d91-09b5-482b-8e57-582935ebf1d8&spaceId=6a055055-52ec-4ebb-a697-63027c951344&userId=c0845f00-59fb-4a0f-bb4a-c1e2314cd202&cache=v2

ChatGPT: Pode ser útil para iniciar sua pesquisa!

Python Graph Gallery: repositório com o passo a passo de como gerar gráficos utilizando as principais bibliotecas de Python

SciKit Learn: documentação com os principais modelos utilizados para classificação

# Preveja os usuários com alta chance de deixar seu Streaming

Utilize um modelo de classificação para mapear qual o perfil de usuários tem mais chance de deixar sua plataforma de streaming. Compreender quem é o perfil que está aumentando o churn do seu negócio é essencial para tomar ações que reduzam essas perdas, seja alterando critérios na venda ou modificando o produto.

# Contexto

Você trabalha em uma plataforma de streaming e a diretoria está preocupada com o alto índice de usuários cancelando as suas assinaturas. Eles acreditam que é possível prever se um usuário tem mais chance de deixar a plataforma antes que isso aconteça, e com base nessa informação tomar ações para reduzir o churn. Seu objetivo é criar um modelo de classificação capaz de prever se um usuário tem mais chance de cancelar a sua assinatura na plataforma ou não. Para isso, a empresa forneceu uma base de dados em csv contendo dados sobre as contas dos clientes.

# Sobre os dados

Uma adaptação do problema de ecommerce, disponível no Kaggle. Acesse os dados aqui: https://s3-us-west-2.amazonaws.com/secure.notion-static.com/75a740fb-4146-4 55a-8d13-6a24ba56d2c8/streaming_data.csv Os dados fornecidos possuem informações sobre as contas dos clientes na plataforma de streaming, divididos entre contas Basic, Standard e Premium, onde cada uma oferece uma gama maior de serviços que a anterior.

Coluna Descrição Tipo client_id Código de identificação do cliente Int age Idade do cliente Int gender Gênero do cliente String region Região de origem do cliente String subscription_days Dias de assinatura ativa do cliente Int subscription_type Tipo de conta String num_contents Quantidade de conteúdos assistidos Int avg_rating Avaliação média dos conteúdos da plataforma Int num_active_profiles Número de perfis ativos na plataforma Int num_streaming_services Quantidade de serviços de streaming que o cliente possui Int devices_connected Quantidade de dispositivos conectados à conta Int churned Se o cliente cancelou a conta ou não Int
