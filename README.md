<h1 align="center"> 
	  Sistema de Recomendação 📽️🎞️🍿
</h1>

<h4 align="center"> 
	  ✔️ Concluído | V1.0.0
</h4>

## Sobre
As plataformas de streaming enfrentam o desafio constante de oferecer aos usuários recomendações relevantes, que os levem a descobrir novos conteúdos e a terem uma experiência mais personalizada. Esse projeto aborda a personalização de recomendações de filmes.
Utilizando uma abordagem de filtragem colaborativa: técnica amplamente usada em sistemas de recomendação para prever as preferências ou interesses de um usuário com base nas opiniões ou comportamentos de usuários semelhantes.

<img src="https://github.com/Amanda-Torres/SistemaDeRecomendacao/assets/106416909/312ba4df-03dd-42f3-a175-19c849af79ca">

## Como funciona
Identificamos os usuários semelhantes (vizinhos próximos) de um usuário alvo a partir do algoritmo KNN. E recomendamos 10 filmes com melhores avaliações de acordo com o vizinho mais próximo que ainda n foram avaliados pelo usuário alvo.

## Dados utilizados
Os dados utilizados nesse projeto foram obtidos do conjunto de dados do MovieLens, especificamente o subconjunto [ml-latest-small](https://grouplens.org/datasets/movielens/latest/). Este conjunto de dados utiliza dados reais, coletados de usuários do MovieLens ao longo do tempo. São dados públicos e estão disponíveis para download no site do [GroupLens](https://grouplens.org/datasets/movielens/).

## Ferramentas Utilizadas

<div style="display: inline-block;">  
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="python" width="80"> &nbsp;&nbsp;&nbsp;&nbsp;
    <img src="https://github.com/Amanda-Torres/MovieMatch/assets/106416909/2783849f-5307-499c-b7aa-fb392f2f812d" alt="Colab" width="150">
</div>
