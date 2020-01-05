# Algorithm Research Papers
This repository contains a summary of some research articles related to advanced algorithm analysis.

## Bidirectional Conditional Insertion Sort algorithm; An efficient progress on the classical insertion sort [[Published article]](https://www.sciencedirect.com/science/article/pii/S0167739X17301711) 

![alt text](https://github.com/elitcenk/Algorithm-Papers/blob/master/bcis.PNG)

- New efficient sorting algorithm, which called Bidirectional Conditional Insertion Sort (BCIS), based on insertion sort concept.
- In the algorithm, sorting is done by adding small elements to the left part and big elements to the right part. Because of this idea, it is called Bidirectional.
- Because it is added in two-sided order, there are fewer operations in read / write operation.
- Classical insertion sort, yielded much better results.
- In small size arrays (up to 1500), they achieved a faster result than Quick sort in average case time.
- In sequences with a large number of duplicates, Quick sort has yielded better results.

A.S. Mohammed, Ş.E. Amrahov, F.V. Çelebi, Bidirectional Conditional Insertion Sort algorithm; An efficient progress on the classical insertion sort, Future Gener. Comput. Syst. 71 (2017) 102-112

## New and improved search algorithms and precise analysis of their average-case complexity [[Published article]](https://www.sciencedirect.com/science/article/pii/S0167739X18319307) 

![alt text](https://github.com/elitcenk/Algorithm-Papers/blob/master/bs.PNG)

- Showed that performance increased with the change of the position of conditional operation in BS algorithm. In algorithms, it is possible to achieve better performance by checking the situation that is most likely to come first.

![alt text](https://github.com/elitcenk/Algorithm-Papers/blob/master/BQS_ITS.PNG)

- Proposed new efficient ITS algorithm by extending TS algorithm. ITS algorithm is faster than correct binary search. Reducing the number of comparisons per iteration.


- Proposed Binary-Quaternary Search (BQS) algorithm. BQS uses new dividing technique. It divides array, by 2 or 4 randomly.
- ITS and BQS algorithms make fewer comparisons than the correct implemantation of BS algorithm.

Ş.E. Amrahov, A.S. Mohammed, F.V. Çelebi, New and improved search algorithms and precise analysis of their average-case complexity, Future Gener. Comput. Syst. 95 (2019) 743-753
