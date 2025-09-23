## Análise e Dashboard Campeonato Brasileiro (2014 a 2023)

## Objetivo do Projeto
Analisar e entender os principais KPIs do Campeonato Brasileiro de Futebol ao longo do tempo e explorar o desempenho por clubes e jogadores.

1ª Aba – Análise por Clube
<img width="1421" height="784" alt="análise por clube" src="https://github.com/user-attachments/assets/24f9ae8e-5a34-4af1-8f12-383871728492" />

Nesta aba temos uma visão temporal de gols marcados e sofridos em cada temporada. É obrigatório selecionar um clube no filtro, pois a análise é feita por clube.

Nos indicadores ao lado do primeiro gráfico, apresentamos a quantidade total de gols marcados, a quantidade total de gols sofridos e a média de gols por partida.

Também temos um gráfico de linhas mostrando o percentual de aproveitamento por temporada do clube selecionado, com uma linha de referência indicando o aproveitamento médio.

No canto superior direito, há um gráfico de barras horizontais com o percentual de gols feitos pelo clube selecionado por minuto da partida. Já na parte inferior, outro gráfico de barras horizontais mostra o percentual de aproveitamento contra cada adversário. Equipes que aparecem com 100% significam que perderam todos os jogos disputados contra o clube selecionado.

2ª Aba – Análise por Atleta
<img width="1429" height="795" alt="análise por atleta-gols" src="https://github.com/user-attachments/assets/9310e9b5-be17-48e3-afb1-86f5124379c6" />

Nesta aba temos uma visão focada nos atletas e nos gols. É possível selecionar tanto o clube quanto a temporada nos filtros superiores, sendo que, por padrão, todas as temporadas estão marcadas.

O primeiro gráfico apresenta uma matriz em formato de mapa de calor que mostra a quantidade de gols feitos por atleta. A intensidade da cor representa maior número de gols, e as colunas representam as temporadas.

No gráfico abaixo, vemos a quantidade de gols feitos pelo clube filtrado contra os seus principais “vítimas”, ordenados de forma decrescente.

No lado direito, na parte superior, há um gráfico de barras horizontais que traz o percentual de gols por faixa de minuto da partida, permitindo identificar e correlacionar jogadores e temporadas.

Já no gráfico inferior, temos uma visão percentual por tipo de gol, com as seguintes categorias:

Gol normal: gols de bola rolando ou em cobranças de falta/escanteio.

Gol de pênalti.

Gol contra.

3ª Aba – Análise por Cartões
<img width="1433" height="786" alt="análise de cartões" src="https://github.com/user-attachments/assets/1182d756-ac3d-48de-8617-c01fbdeef6f2" />

Nesta terceira e última aba, temos uma análise por clube (filtro superior) dos cartões amarelos e vermelhos.

O primeiro gráfico mostra a evolução ao longo do tempo, por temporada, em que as barras representam a quantidade de cartões e a linha indica a média de cartões por partida naquela temporada.

No canto inferior direito, há uma matriz em formato de mapa de calor que mostra quais jogadores do clube selecionado receberam mais cartões ao longo das temporadas.

Já no canto superior direito, temos a distribuição percentual de cartões por minuto da partida, onde é possível observar uma clara tendência de aumento após o intervalo — algo que faz total sentido no contexto do jogo.

## Dashboard Online
Para maior entendimento, disponibilizo o dashboard publicado no link abaixo:

👉 [Visualizar Dashboard no Power BI](https://app.powerbi.com/view?r=eyJrIjoiZTJjOTljMmEtMGRmYS00MmQ5LThmZTYtNDdlMjc2ZGVmMWNhIiwidCI6ImI3NmZlZDcxLWEwNjgtNDM4MC05OTcyLWEwMzEwZDc0ZTZmZSJ9)

## Medidas e Indicadores
Na pasta `dashboard/medidas` é possível encontrar as principais medidas criadas em DAX para entender os indicadores.


