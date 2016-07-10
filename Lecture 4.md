* Counting
    (n) N choose K is the number of k element subsets of the n element set.  
    (k)

    You can either choose them one at a time with regard to order for n! / (n-k)! possibilities

    If you want unordered list, use n! / ((n-k)! * k!), by taking first all ordered lists then divide them by all possible permutation of the k elements.

* From Book
    The count principle: consider some process which consists of r stages:  
        suppose that there are n1 results at the first stages

        for every possible result of stage 1, there are n2 possible results at the 2nd stage

        and so on, until we have n1 * n2 * ... nr total stage

    When selecting k objects out of a collection of n objects, if the order matters then we are looking at a permutation, else a combination. In either case we are looking at a partition of a collection of n objects into different subsets.

    If we would like to divide the the choice of k elements out of n element set without regard to order, then the total sum would be (n n1)(n-n1 n2)...(n-n1-..-nr-1 nr) which reduces to n!/n1!n2!..nr!, called the multinominal coefficient and is denoted by (n n1,n2,...nr)

    
