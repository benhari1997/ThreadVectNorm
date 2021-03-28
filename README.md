# Vector Norm p-Thread Parallelisation
___
A vector Norm Calculation project  to get familiarized with POSIX threads and vectorization using AVX intrinsics.

The implemented norm is the following :

  ## <center> d(u) = &Sum;<sup>N-1</sup><sub>i=0</sub> &radic;|u<sub>i</sub>| </center>

This algorithm was implemented as an academic project for the _Multi-thread Parallel Programming_ lecture given by <a href="claude.tadonki@mines-paristech.fr">Prof.Claude Tandonki</a>.

 
> #### Execution :
___

This ML pipeline can be executed via : 

``` shell
cd src/
make
./parallel_norm.out
```
If you're on a Unix or Unix-like system.
 
> #### Snapshots :
___

<b>Rq</b> : Note that the result inconsistency is due to the use of single-precision floating-point format (float / 32bit pres).

![Example](examples\img-example.png)

> #### Requirements :
___
- C 
- pthread

___
___
> #### Authors : KADER Rami & Benhari Abdessalam 
> #### Date : 25/11/2020