# SENA-project

In our project we have used the Genshin dataset and performed some analysis.Genshin impact is a popular game which involves a lot of characters from 4 different nations.Each character has their own weapon and their visions.The characters are considered as nodes and the connection between them is edges.we made some analysis in this dataset like finding the strongest nation,predicting the rarity of the characters and finding the important character and then the popular character.

Which nation is stronger?

As mentioned,the game has 4 nations among which 2 nations have only 2 characters in them.So we are ignoring them and we are going to consider only other 2 nations.Each character has two grades such as ATK and DEF which are given based on their performance and role in the game.Considering the ATK and DEF values we have displayed a graph for each nation.

prediction of rarity

Rarity is a column in the dataset for all characters which represents the difficulty level of reaching that particular character by other characters  in the game.Now we are splitting the dataset into training and testing dataset with testing as 20% of the data and remaining as training.And then we are training the model using the train dataset to predict the test values.

Who is important and who is popular?

For this Analysis we have used the node_list and edge_list.First considering the network as a directed graph we are calculating the indegrees and outdegrees of all characters.Considering the undirected graph we are calculating the degree centrality.To find the important character we have calculated degree centrality,closeness,betweenness and eigenvector centrality for all characters.
