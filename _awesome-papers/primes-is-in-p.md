---
title: PRIMES is in P
layout: single
author_profile: true
classes: wide
tags:
  - Computer Science
  - Complexity Theory
---

Available [here](/assets/awesome-papers/primes%20is%20in%20P.pdf).

In the paper, the authors proposed

The AKS algorithm is of great theoretical significance, even though it doesn’t offer a promis- ing runtime in practice. Actually some randomized algorithms preceding it exhibit better runtime on real computers, approximately on the order of O∼(log3 n) [Aar03]. Those al- gorithms are randomized, meaning there is a very low probability of error, or there’s no chance of mistake but the algorithm might take a very long time to run [Sti08]. AKS test is the first deterministic, rigorous, polynomial-time primality testing method. It eliminates the little probability of error that mathematicians had tried for many years to make it go away.

Prime numbers are integers only divisible by 1 and itself. Identifying primes ef- ficiently has been a longstanding open question in complexity theory. The AKS test paper presented a polynomial time algorithm for deciding prime numbers, marking a milestone in the way towards understanding prime numbers [AKS04]. The authors came up with a modified form of Fermat’s primality test with reduced runtime. They proved that the performance of a limited number of that test is sufficient to decide whether a integer is prime. With the fact that both the runtime of a single test and the number of tests needed are on the order of polynomial, the total time complexity of the algorithm is polynomial.
