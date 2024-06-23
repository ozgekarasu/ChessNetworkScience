# ChessNetworkScience

# Analyzing Opening Choices and Player Strengths in Online Chess: A Network Analysis Approach

## Overview
This project investigates the relationship between chess opening choices and player strengths using network analysis techniques. The analysis is based on data obtained from the Lichess4545 online chess league. By constructing a player-opening bipartite network, we explore the interplay between players and their preferred opening moves, providing insights into strategic preferences and potential advantages at different skill levels.

## Introduction
Chess is a widely enjoyed strategic board game with millions of players worldwide. The opening moves in chess set the stage for the subsequent development and outcome of the game, making an investigation of opening choices crucial. This project employs network analysis to investigate opening preferences among players of different skill levels, using data from an online chess league.

## Dataset
The dataset used in this project is obtained from the API of Lichess.org, one of the most popular chess platforms globally. It includes data from the Lichess4545 league, covering games played between 2015-11-01 and 2023-01-23. The dataset consists of:
- 31,188 matches
- 3,498 players
- 473 different opening types
- Elo ratings ranging from 802 to 2641

  A single game data taken from the dataset looks like this:
  ![Ekran Görüntüsü (3920)](https://github.com/ozgekarasu/ChessNetworkScience/assets/128151657/e610cefd-97c7-4c10-925f-865ecde08d14)


## Objectives
The main objectives of this research are:
1. Investigating the relationship between chess openings and player levels, determined by their Elo ratings, using visual network analysis and statistics.
2. Analyzing the chess community and different playing habits using network analysis techniques such as closeness and betweenness centrality.
3. Establishing a link between player level and gameplay habits using the Community Detection algorithm, specifically the Louvain method.

## Methodology
We constructed a player-opening bipartite network to analyze the relationship between opening choices and player strengths. The analysis included:
- Visual network analysis to explore the centrality metrics of the network.
- Community detection to identify groups of players with similar opening preferences and performances.
- Statistical validation using Elo ratings.

## Findings
The analysis revealed several key insights:
- Players of different skill levels exhibit distinct opening preferences.
- Certain opening moves are more prevalent among players of specific skill levels.
- Higher-rated players tend to choose openings with higher complexity.
- Community detection identified groups of players with similar opening strategies, highlighting the strategic differences among players of varying skill levels.

## Conclusion
This project demonstrates that network analysis is an effective tool for studying the relationship between chess opening choices and player strengths. The findings provide valuable insights for chess players and game analysts, offering guidance on training strategies and opening selections. Future research could expand the dataset and incorporate additional variables to further explore the dynamics between openings and player strengths.

## References
- About lichess.org. (n.d.). Retrieved from [lichess.org](https://lichess.org/about)
- Almeira, N., Schaigorodsky, A. L., Perotti, J. I., & Billoni, O. V. (2017). Structure Constrained By Metadata In Networks Of Chess Players. Nature.
- Marzo, G. D., & Servedio, V. D. (2023). Quantifying the complexity and similarity of chess openings using online chess community data. Nature.

## Appendix



![Ekran Görüntüsü (3921)](https://github.com/ozgekarasu/ChessNetworkScience/assets/128151657/b612e117-7247-468f-825b-9dfd2ee4a019)


![Ekran Görüntüsü (3922)](https://github.com/ozgekarasu/ChessNetworkScience/assets/128151657/87bdf28e-badd-4646-a1b5-477eda178568)


![Ekran Görüntüsü (3923)](https://github.com/ozgekarasu/ChessNetworkScience/assets/128151657/83182b4d-fed5-4ae9-ae9d-2353457edb94)


![Ekran Görüntüsü (3925)](https://github.com/ozgekarasu/ChessNetworkScience/assets/128151657/9b993b91-5152-47c0-959e-3cab6ab208e4)


![Ekran Görüntüsü (3926)](https://github.com/ozgekarasu/ChessNetworkScience/assets/128151657/285c70e9-474d-4f28-9731-2453f6236d20)


![Ekran Görüntüsü (3927)](https://github.com/ozgekarasu/ChessNetworkScience/assets/128151657/af5eece7-c301-4724-b990-fbc4c7eab8de)


![Ekran Görüntüsü (3928)](https://github.com/ozgekarasu/ChessNetworkScience/assets/128151657/77942482-c9b7-4c3b-bef0-1e8b6da66a46)


![Ekran Görüntüsü (3929)](https://github.com/ozgekarasu/ChessNetworkScience/assets/128151657/2936e182-e88d-4896-bb18-d6e43db8f094)


![Ekran Görüntüsü (3930)](https://github.com/ozgekarasu/ChessNetworkScience/assets/128151657/4259e71f-45bf-43b1-952b-e50f06c7d5bb)


![Ekran Görüntüsü (3931)](https://github.com/ozgekarasu/ChessNetworkScience/assets/128151657/f92be456-a0fc-4e40-a1a0-3cc3841c6c48)


![Ekran Görüntüsü (3932)](https://github.com/ozgekarasu/ChessNetworkScience/assets/128151657/e97578f9-1567-437e-8591-21279977d6bd)
