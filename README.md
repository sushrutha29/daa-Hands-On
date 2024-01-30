b. Argue Selection sort correctness:

A detailed evaluation of the selection sort algorithm's accuracy can be obtained by analyzing it's detailed operations.  The least element from the unsorted part is chosen, and each time the algorithm runs, it is always placed at the beginning of the array. The algorithm's focus to maintaining the fact that the elements before the current position are sorted is essential to determining whether the sorting procedure is valid. It is essential to ensure the correctness of the sorting process. The algorithm continuously builds a sorted prefix for the array by carefully determining the minimum element and replacing it with the first unsorted element in every iteration. As a result, the selection sort makes sure that each phase of its process results in an array that is properly sorted. 

The selection sort algorithm has an O(n^2) time complexity, where "n" is the number of records in the array that is being considered. The algorithm's use of nested loops is what causes this complexity. The inside loop is in charge of determining the minimum element in the unsorted part for each iteration of the outer loop, which goes over each element of the array. The worst-case situation involves the outer loop running n times, with the inner loop identifying the minimal element running n times for each of these iterations.
Therefore, the total number of checks and swaps is proportional to n * (n-1) / 2, which reduces to O(n^2). 

System Specifications:

uname_result(system='Darwin', node='Sushruthas-MacBook-Pro.local', release='22.3.0', version='Darwin Kernel Version 22.3.0: Mon Jan 30 20:39:35 PST 2023; root:xnu-8792.81.3~2/RELEASE_ARM64_T8103', machine='arm64')
Total RAM: 8 MB
CPU Cores: 8
Storage Information: Total: 228 GB, Free: 149 GB
