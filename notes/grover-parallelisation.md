# Parallelisation of Grover's algorithm

We are interested in the problem of finding the (single) index $i$ corresponding to some "marked element" in an unsorted database of $N$ elements. This is commonly referred to as an _unstructured search problem_.

We assume that Grover's algorithm for solving unstructured search problems on quantum computers does indeed result in finding the index $i$ corresponding to some marked element in an unsorted database of $N$ elements in $O(\sqrt{N})$ time. That, we take this result to be true. This is result is known as the _quadratic speedup_ of Grover's algorithm.

This is in contrast to the best known classical algorithm for this problem, brute-force search, which takes $O(N)$ time.

Now, we assume we have $k$ processors/computers that we can run in parallel to try to find the marked element. Any unstructured search problem can simply be parallelised by assigning different parts of the search space to independent processors/computers.

In the classical case, we split the search into $k$ parts, and run each part on a different processor. Intuitively, each processor is now only exploring a search space of ${N/k}$ operations, and so the total time taken to find the marked element is $O({N/k})$ with $k$ classical processors.

In the quantum case, we can do the same thing. We simply split the search into $k$ parts, and run each part on a different quantum processor running Grover's algorithm. For each processor, since the search space is $N/k$, the time taken is $O(\sqrt{N/k})$ (by the quadratic speedup of Grover's algorithm). Therefore, the total time taken to find the marked element is $O(\sqrt{N/k})$ with $k$ quantum processors.

The key idea here is that when parallelising by splitting the search space, we're essentially reduce the advantage that each individual quantum computer can achieve.
