# Aztec-Diamonds
A small collection of work related to Aztec Diamonds

An Aztec Diamond of rank n is a symmetrical union of squares given by the plane |x| + |y| < n, creating a diamond shape pattern. The tilings are built with 4 types of dominoes, which are denoted by whether they are vertical or horizontal and which way the darker end of the domino appears. Each of the 4 types of dominoes is represented by its own color in the image below. 

<img width="200" alt="Aztec Diamond of rank 3" src="https://github.com/kenchareddyh/Aztec-Diamonds/assets/52467420/60ba183b-94bc-4e55-ba00-b4c1d127fe1b">

The domino-shuffle algorithm allows us to generate an Aztec Diamond of any rank n uniformly at random from all possible tilings. The notebook in this repo provides this algorithm

There are several interesting observations that can be made as the rank of the tilings approach infinity. One of those is the Arctic Circle Theorem, which is where a circular boundary appears within the aztec diamond that separates a frozen region from a disordered region. The frozen region is where all the orientation of the dominoes is stuck and doesn't change. The disordered region is still random with the orientation of the dominoes. The circular boundary is well defined.

<img width="300" alt="Arctic Circle" src="https://github.com/kenchareddyh/Aztec-Diamonds/assets/52467420/e2a70f06-3b9d-497b-ac3a-2281f4f803b8">




See this wiki for further investigation https://en.wikipedia.org/wiki/Aztec_diamond
