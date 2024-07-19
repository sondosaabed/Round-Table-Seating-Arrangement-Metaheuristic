# Round-Table-Seating-Arrangement-Metaheuristic
 Round table arrangemnet solution using Genetic Algorithm, Simulated Annealing, and Hill Climbing (Metaheuristic)

## Graph represntation of hate matrix
![image](https://github.com/user-attachments/assets/77959655-a370-4420-a843-c366e16d0a37)

## Algorthims Comparision

|Algorithm|Path|Minium Cost|Avg. per edge|
|---------|----|-----------|----|
|Genetic|['Khalid', 'Ayman', 'Hakam', 'Ahmed', 'Hani', 'Salem', 'Fuad', 'Kamal', 'Ibrahim', 'Samir']|15,528|16.8|
|Simulated Annealing|['Hakam', 'Ayman', 'Kamal', 'Fuad', 'Salem', 'Samir', 'Khalid', 'Ibrahim', 'Hani', 'Ahmed']|17,567|17.9|
|Hill Climbing|['Hani', 'Ibrahim', 'Kamal', 'Samir', 'Khalid', 'Ayman', 'Hakam', 'Ahmed', 'Fuad', 'Salem']|15,394|16.7|

> It is noticed that the minumum cost was achieved by the Hill climbing algorithm where it is equal to 15,394 with average 16.7 per edge. Then following it comes the Genetic algorithm where the minumum cost was 15,528 and on average 16.8 per edge. The worst minimum cost was using the simulated annealing which has reached 17,567 and on average 17.9 per edge.

## Conclusion
In conclusion, the objectives are met where three algorithms were implemnted to find the optimal round arrangement. The implemnations were called and evaluated mainly based on the minimum cost that they had. While all of them had find an arrangemnt the best algothim in terms of the minimum cost was the hill climbing algorithm, then followed by the Genetic and the worst one was the simulated annealing algorithm.
So the final seating arrangemnet was chosen to be the one that simulated annealing algorthim obtained, which is the minumum conflict between seats. Folwoing is it's visulization:
![image](https://github.com/user-attachments/assets/96fa9f1d-cc4e-4720-a9e2-b84fd4531e9e)
