### The Great Internet Mersenne Prime Search
<br/>
GIMPS is a distributed computing project that is actively searching for Mersenne primes

The new prime is only the 51st known Mersenne prime ever discovered. Mersenne primes were named for the French monk Marin Mersenne, who studied these numbers more than 350 years ago. GIMPS, founded in 1996, has discovered the last 17 Mersenne primes. Volunteers download a free program to search for these primes, with a cash award offered to anyone lucky enough to find a new prime. Prof. Chris Caldwell maintains an authoritative web site on the largest known primes, and has an excellent history of Mersenne primes.

Patrick is one of thousands of volunteers using free GIMPS software available at www.mersenne.org/download/. Credit for this prime goes not only to Patrick Laroche for running the Prime95 software, Woltman for writing the software, Blosser for keeping the Primenet server running smoothly, and the thousands of GIMPS volunteers that sifted through millions of non-prime candidates.  In recognition of all the above people, official credit for this discovery goes to "P. Laroche, G. Woltman, A. Blosser, et al."

You can read a little more in the press release.

More News and Discussions
GIMPS forums — Here you can chat with fellow GIMPS members, get help with installation questions, learn more about how GIMPS works, etc.

Make Math History!!
You could discover one of the most coveted finds in all of Mathematics - a new Mersenne prime number. We've found fifteen already. Join in on this fun, yet serious research project. All you need is a personal computer, patience, and a lot of luck.

In addition to the joy of making a mathematical discovery, you could win a (USD) $3,000 cash GIMPS Research Discovery Award for each Mersenne prime discovered, and the Electronic Frontier Foundation is offering a $150,000 award to the first person or group to discover a 100 million digit prime number! See how GIMPS will distribute this award if we are lucky enough to find the winning 100 million digit prime.

What are Mersenne primes and why do we search for them?
Prime numbers have long fascinated amateur and professional mathematicians. An integer greater than one is called a prime number if its only divisors are one and itself. The first prime numbers are 2, 3, 5, 7, 11, etc. For example, the number 10 is not prime because it is divisible by 2 and 5. A Mersenne prime is a prime of the form 2P-1. The first Mersenne primes are 3, 7, 31, 127 (corresponding to P = 2, 3, 5, 7). There are only 51 known Mersenne primes.

GIMPS, the Great Internet Mersenne Prime Search, was formed in January 1996 to discover new world-record-size Mersenne primes. GIMPS harnesses the power of thousands of small computers like yours to search for these "needles in a haystack".

Most GIMPS members join the search for the thrill of possibly discovering a record-setting, rare, and historic new Mersenne prime. Of course, there are many other reasons.
<br/>
<strong> Answer </strong>
<br/>
No, the frist three are the only primes in such pattern.
<br/>
For $n=4$, we have $21219553216129$ divides $p_4$. 
<br/>
(Note: this result was first obtained on 2/24/2022 through one month of paid cloud computing which should be credited to the original author, see 
<a href="https://www.zhihu.com/question/512482114/answer/2319816820?utm_id=0"> Original Answer (in Chinese) </a>.
<br/>
For $n\geq{4}$, we have $34276387$ divides $p_5$, and in general, $4423$ divides $p_6$ or greater. In fact, there might be only finitely many divisors for all $p_n$. 
<br/>
(Note: this incredible general case result was obtained by another author which can be found under the same link).

**[Generalized] Mixed Tower Sum (2023.1.19; open)**
<br/>
How many primes are there in the form $p={^{a}2}+{^{b}3}$, where ${a}\neq{b}$, finitely or infinitely many?
<br/>
<strong> Comment </strong>
<br/>
None.




**2. $N$ Factorial Sum (2022.10.9; open)** 
<br/>
For any integer $n\geq{1}$, is there always a prime that can be obtained from combinations of addition and subtraction of all elements in the set $\lbrace{1!, 2!, 3!, …, n!}\rbrace$? 
Such as
$p_1={1!}\pm{0!},$
$p_2={2!}\pm{1!},$
$p_3={3!}\pm{2!}\pm{1!},$
$\cdots,$
$p_n=n!\pm(n-1)!\pm(n-2)!\pm(n-3)!\pm\cdot\cdot\cdot\pm{1!}.$
<br/>
<strong> Comment </strong>
<br/>
This statement reamins true for $p_{1}$ to $p_{257}$ and likely to be true for all positive integers. Considering the prime density around $n!$ with such combination shoud be $\frac{2^{n-1}}{nlog(n)}>1$.

**[Generalized] Two Factorial Sum (2022.10.10; partially solved)**
<br/>
For all integers ${n}\geq{k}\geq{1}$, can we always find a prime of form ${n!}\pm{k!}\pm{1!}$? If not, could there be finitely many exceptions? 
<br/>
<strong> Comment </strong>
<br/>
The answer to the first question is 'no', and the second is 'maybe', these counter examples only appeared at $n=\lbrace{63, 161, 382, 902}\rbrace$ for $n\leq1200$.

**[Generalized] Three Factorial Sum (2022.10.12; open)**
<br/>
For all ${a}\geq{b}\geq{c}\geq{1}$, can we always find a prime of form ${a!}\pm{b!}\pm{c!}\pm{1}$?
<br/>
<strong> Comment </strong>
<br/>
None.




**3. Collatz Sequence Sum (2022.10.25; open)**
<br/>
If we randomly assign $\pm$ to all elements of a Collatz sequence, i.e.
$C(1)=1$,
$C(2)=2-1$,
$C(3)=3-10+5+16-8-4-2+1$,
$C(4)=4-2-1$,
$C(5)=5-16+8+4-2+1$,
$C(6)=6+3-10-5+16-8-4+2+1$,
will at least one combination always converge a 0 or 1?  
<strong> Comment </strong>
<br/>
None.




### Computation Problems
**1.** Is $2\cdot3^{3^{3^{3}}}-1$ prime?
<br/>
<strong> Answer </strong>
<br/>
No, it has the smallest divisor $2504371752217$.

**2.** Is $3^{3^{3^{3}}}+4$ prime?
<br/>
<strong> Comment </strong>
<br/>
None.

**3.** Is $3^{3^{2^{2^{2}}}}-2^{2^{2^{2^{2}}}}$ prime?
<br/>
<strong> Comment </strong>
<br/>
None.

**4.** Is $3^{2^{2^{2^{2}}}}+2^{2^{2^{2^{2}}}}$ prime?
<br/>
<strong> Comment </strong>
<br/>
None.




<p/>
<html lang="en">
<head>
<meta http-equiv="content-type" content="text/html; charset=utf-8">
<script type="text/javascript" charset="utf-8" src="
https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML,
https://vincenttam.github.io/javascripts/MathJaxLocal.js"></script>
</head>
