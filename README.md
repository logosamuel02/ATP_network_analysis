# ATP_network_analysis

Individual work developed in the fourth year of the data science degree in 2024

This network is about the games played by men in the Professional Tennis Association in 2023. Every year, the tennis season includes lots of tournaments of different importance. There are 4 Grand Slams, which are the most important, then Master’s 1000, 500, 250, and other tournaments that give ATP points like national selections tournaments. So, the network is defined as players, de nodes, and games between them, the edges. It is an undirected graph in order that if a sportsman plays versus another, then an edge from one to the other is set. Also, there is a weighted graph that takes the number of games that both sportsmen have played versus each other.

The dataset that corresponds to this network is in [1]. Much information is present in it, so many edge attributes like the surface, the date, the points won, the result of the match, etc. Also, information for players, such as name, nationality and playing hand. We do not know the exact number of nodes yet because players there are 2000, but not everyone can play an ATP match; maybe we will find 300 or 400; we will see that number when we do the cleaning, and 2986 edges, which also will be reduced in the cleaning. As we will see, there will be players with no games played due to some issue or just because their ranking is too low, so they can only play a few matches. Others are probably the best players because they have more games played. In tennis, as tournaments follow an eliminatory format, the more wins you also have, the more games you play; games and wins are highly correlated.

Having said this, we will do a complete network analysis of this, starting with a cleaning process. We could build our network differently as we have many attributes and different networks could be performed, but this is the essential and principal focus of doing it, as we are interested in extracting value from metrics.

Data adquired is from @JeffSackmann

[1] https://github.com/JeffSackmann/tennis_atp/blob/master/atp_matches_2023.csv
