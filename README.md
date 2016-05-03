# Big-O-Notation
A simple remedial exercise of Big O Notation. 

# Notes:

* Big O is not a measure of the time of a algorithm, but how well a algorithm scales as the size of the data increases

```

fn(n) = 45n^3 + 20n^2 + 19

fn(1) = 84 
fn(2) = 459
fn(10)= 47,019 

Has a Big O of O(n^3) because in all reality, adding 19 and 20n^2 does not impact as much as when you see 45n^3 impact when n is 10 the result is 45,000
```


O(1) means it is constant performance regardless of the data size
O(n) means it is proportional to the size of data. ( eg one loop ) this is the minimum because we have to look at everyone.
O(n^2) Bubble Sort, this is not so good. because it is nested. ( eg one loop inside another loop )
O(log n) Binary Search, this is good. because the increasing the number of data is halved each time. 
O(n log n) Quick Sort, this is amazing. because we compare once and once only.