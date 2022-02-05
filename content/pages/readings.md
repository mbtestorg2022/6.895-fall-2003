---
content_type: page
title: Readings
uid: 168b835a-d6fc-24a3-3113-0cc27e24ebbc
---

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
LEC #
{{< thclose >}}
{{< thopen >}}
TOPICS
{{< thclose >}}
{{< thopen >}}
READINGS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Week 1**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
Dynamic Multithreading
{{< tdclose >}}
{{< tdopen >}}


Cilk Manual 5.3.2 ([PDF]({{< baseurl >}}/resources/cilk_manual_532))

Minicourse on Multithreaded Programming ([PDF]({{< baseurl >}}/resources/minicourse)) (Courtesy of Harald Prokop. Used with permission.)


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Week 2**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}
Serial Performance and Caching
{{< tdclose >}}
{{< tdopen >}}


Sorting Code Handout ([PDF]({{< baseurl >}}/resources/sort_code))

C Code for Sorting ([C](/courses/electrical-engineering-and-computer-science/6-895-theory-of-parallel-systems-sma-5509-fall-2003/readings/sortcode.c))

ASM Code for Sorting (Excerpt) ([ASM](/courses/electrical-engineering-and-computer-science/6-895-theory-of-parallel-systems-sma-5509-fall-2003/readings/sortcode.asm))

_Cache-Oblivious Algorithms  
_  
Prokop's Masters Thesis ([PDF]({{< baseurl >}}/resources/cach_oblvs_thsis))  
FOCS Paper ([PDF]({{< baseurl >}}/resources/cach_oblivs_focs))


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Week 3**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}
Determinacy Detection and Race Detection
{{< tdclose >}}
{{< tdopen >}}


Feng, Mingdong, and Charles E. Leiserson. _Efficient Detection of Determinacy Races in Cilk Programs._

Cheng, Guang-Ien, Mingdong Feng, Charles E. Leiserson, Keith H. Randall, and Andrew F. Stark. "Detecting Data Races in Cilk Programs that Use Locks." In _Proceedings of the Tenth Annual ACM Symposium on Parallel Algorithms and Architectures_ (1998): 298-309.

The LCA Problem Revisited ([PDF]({{< baseurl >}}/resources/lca)) (Courtesy of Martin Farach-Colton and Michael Bender. Used with permission.)


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}
Consistency of the Memory Sub-System
{{< tdclose >}}
{{< tdopen >}}


Goodman, James R. _Using Cache Memory To Reduce Processor-Memory Traffic_. Department of Computer Sciences, University of Wisconsin-Madison Madison, WI: 19883, pp. 255-262.

Lamport, Leslie. "How to Make a Correct Multiprocess Program Execute Correctly on a Multiprocessor." _IEEE Trans. Computers_ 46 (February 14, 1993).

Frigo, Matteo, and Victor Luchangco. "Computation-Centric Memory Models." To appear in _Proceedings of the Tenth Annual ACM Symposium on Parallel Algorithms And Architectures (SPAA)._ MIT Laboratory for Computer Science, Massachusetts Institute of Technology. June 28-July 2, 1998.

Herlihy and Moss. _Transactional Memory: Architectural Support for Lock-Free Data Structures._ ([PDF]({{< baseurl >}}/resources/herlihy_mo93)) (Courtesy of Maurice Herlihy and J. Eliot Moss. Used with permission.)

Huang, Kai. _Data-Race Detection In Transaction Everywhere Parallel Programming._ ([PDF]({{< baseurl >}}/resources/kai_thesis))


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Week 4**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
6
{{< tdclose >}}
{{< tdopen >}}
Analyzing Space Bounds
{{< tdclose >}}
{{< tdopen >}}


Blumofe, Robert D., Charles E. Leiserson. "Space-Efficient Scheduling of Multithreaded Computations." _SIAM Journal on Computing_ 27, 1: 202-229. MIT Laboratory for Computer Science, Massachusetts.

Berger, Emery D., Kathryn S. McKinley, Robert D. Blumofe, and Paul R. Wilson. "Hoard: A Scalable Memory Allocator for Multithreaded Applications." In _Proceedings of the Ninth International Conference on Architectural Support for Programming Languages and Operating Systems_. Cambridge, MA: November 2000. Department of Computer Sciences, The University of Texas at Austin Austin, Texas. Department of Computer Science, University of Massachusetts Amherst, Massachusetts.

Blumofe, Robert D., Matteo Frigo, Christopher F. Joerg, Charles E. Leiserson, and Keith H. Randall. "An Analysis of Dag-Consistent Distributed Shared-Memory Algorithms." In _Proceedings of the 8th Annual ACM Symposium on Parallel Algorithms and_ _Architectures (SPAA)._ Department of Computer Sciences, The University of Texas at Austin, Texas. MIT Laboratory for Computer Science, Massachusetts.

Narlikar, Girija J., and Guy E. Blelloch. "Space-Efficient Scheduling of Nested Parallelism." _ACM Transactions on Programming Languages and Systems (TOPLAS)_ 21, 1 (January 1999): 138-173. Carnegie Mellon University.

Vee and Hsu. _A Scalable and Efficient Storage Allocator on Shared-Memory Multiprocessors._Singapore, Nanyang Avenue: Center for Advanced Information Systems, SAS Nanyang Technological University.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Week 5**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
8
{{< tdclose >}}
{{< tdopen >}}
Cilk Scheduler
{{< tdclose >}}
{{< tdopen >}}
Executing Multithreaded Programs Efficiently
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Week 9**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14
{{< tdclose >}}
{{< tdopen >}}
Competitive Snoopy Caching
{{< tdclose >}}
{{< tdopen >}}


Karlin, Anna R., Mark S. Manasse, Larry Rudolph, and Daniel D. Sleator. "Competitive Snoopy Caching." _Algorithmica 3_. Springer-Verlag, New York Inc., 1988, pp. 79-119.

Karlin, Anna R., Mark S. Manasse, Lyle A. McGeochj, and Susan Owicki. "Competitive Randomized Algorithms for Non-Uniform Problems" In _Proceedings, Symposium on Discrete Algorithms._ 1990, chapter 33, pp. 301-309.


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="3" >}}
**Week 13**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
22
{{< tdclose >}}
{{< tdopen >}}
Pick a Winner
{{< tdclose >}}
{{< tdopen >}}
Awerbuch, Baruch, Yossi Azar, Amos Fiat, and Tom Leighton. "Making Commitments in the Face of Uncertainty: How to Pick a Winner Almost Every Time." In _Proceedings of the 28th Annual ACM Symposium on Theory of Computing_ (1996): 519-530.
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}