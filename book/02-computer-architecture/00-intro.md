# How Computers Work (Part 1): Computer Hardware & Architecture

This chapter covers a variety of topics related to how computers "work," focusing on computer hardware and architecture. One goal for this chapter is to help you gain an understanding of how the basic logical and mathematical operations underlying computation are performed mechanically. 

We will also use a simulation of CPU architecture to learn more about how an instruction is processed along the CPU data path cycle and how values from memory are incorporated into CPU instructions. We are doing this to gain more experience with understanding a computer’s mechanical operations at a higher level of abstraction. 

Finally, this chapter covers reading and writing basic assembly language, to help us see the 0s and 1s underneath higher level programming and apply them to basic algorithms.

## <i class="fa-solid fa-hands-clapping" aria-hidden="true"></i> Acknowledgements

The author consulted Chapter 5, "Computing Components" from Nell Dale and John Lewis' *[Computer Science Illuminated, Seventh Edition](https://www.jblearning.com/catalog/productdetails/9781284155617)* textbook (Jones & Barlett Learning, 2020; ISBN: 9781284155617) when writing this lab.

Sections of this lab are based on the "Data path & memory" lab:
- Created: Jerod Weinman, 16 March 2009
- Modified: Jerod Weinman, 20 April 2011
- Modified: Jerod Weinman, 4 April 2014
- Portions adapted from Dave Reed, “A Balanced Introduction to Computer Science,” Exercises 14.1-14.6.

Sections of this lab are based on the "Machine language" lab:
- Created: Jerod Weinman, March 16, 2009
- Revised: Janet Davis, April 27, 2012
- Revised: Janet Davis, March 12, 2013
- Revised: Jerod Weinman, 4 April 2014
- Adapted from Dave Reed, “A Balanced Introduction to Computer Science,” Exercises 14.9, 14.10, and 14.13. 

This lab's lecture segments were adapted from the following PBS *[Crash Course Computer Science](https://www.pbs.org/show/crash-course-computer-science/)* episodes:
- "[How Computers Calculate - the ALU](https://www.pbs.org/video/how-computers-calculate-the-alu-crash-course-computer-sci-sm5zov/)"
- "[Registers & RAM](https://www.pbs.org/video/registers-and-ram-crash-course-computer-science-6-lddkcd/)"
- "[The Central Processing Unit (CPU)](https://www.pbs.org/video/the-central-processing-unit-cpu-crash-course-computer-sci-v5aynn/)"
- "[Instructions & Programs](https://www.pbs.org/video/instructions-programs-crash-course-computer-science-8-ai4emg/)"

## <i class="fa-regular fa-bookmark" aria-hidden="true"></i> Companion Content

Michael S. Mahoney. “The Histories of Computing(s).” *Interdisciplinary Science Reviews, vol. 30, no. 2* (June 2005): 119–135. [doi.org/10.1179/030801805X25927](https://doi.org/10.1179/030801805X25927)
  - Framing questions:
    * What are some of the arguments Mahoney makes about the nature of computing history? How does he talk about change over time, or the nature of evolution and revolution?
	* Don't get too fixated on specific examples or developments mentioned in the article. Think about the arguments he makes about the relationship of computing technologies, individual people, and larger societal structures.

## <i class="fa-solid fa-list-ol" aria-hidden="true"></i> Chapter Table of Contents

```{tableofcontents}
```

## <i class="fa-solid fa-clipboard-question" aria-hidden="true"></i> Application

[Link to application question template](https://docs.google.com/document/d/1SpHmyZkN7b5wmtY0n8y5jI6JxBanZXg8UVZOoNPIv_o/copy) (ND users, Google Doc)

## <i class="fa-solid fa-chalkboard-user" aria-hidden="true"></i> In-Class Work

- 9/10 (T): Mahoney discussion
- 9/12 (R): Collaborative problem solving (exploring computer architecture)


## <i class="fa-solid fa-list-check" aria-hidden="true"></i> Assignments 

- Weekly reflection (due end of day Friday, submit on Canvas)
- Individual application questions (due end of day Friday, submit on Canvas)
- Collaborative problem solving (due end of class Thursday, group submission on Canvas)