# cpts223

1.
            Machine processing power in the scope of this assignment does affect execution time. When I put my computer in energy-saving mode,
            the execution time decreases. This makes sense given the runtime is finite. If we were talking about an asymptotic distribution,
            then it wouldn't matter in the grand scheme of things since the orders of magnitude would be equivalent.

2.
          The std::list performed better. The conditions in which it performs better in the scope of this assignment are constant insert and removal time.
          It is constant because only a few pointers at most have to be changed to allow the list to link together properly, as it grows and shrinks.
          The time complexity of printing the list takes O(n) but the list is still faster, likely due to the vector having to reasize arrays and copy elements
          over. As for lookup time, the vector is certainly mroe efficient in that regard, as lookup time is constant. And while the list is faster in this
          program, it is only faster by about 2 seconds.
   
3.
           Since M just defines the interval of selection, it's runtime is constant throughout the progression of the program. N, on the other hand,
           is the population size which is linear so N definitly has the largest impact on runtime for this program.

