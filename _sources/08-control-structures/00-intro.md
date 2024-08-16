# Control Structures in Python
 
According to Busbee and Braunschweig's "[Structured Programming](https://press.rebus.community/programmingfundamentals/chapter/structured-programming/)" *Programming Fundamentals*, "One of the most important concepts of programming is the ability to control a program so that different lines of code are executed or that some lines of code are executed many times. The mechanisms that allow us to control the flow of execution are called control structures. Flowcharting is a method of documenting (charting) the flow (or paths) that a program would execute. There are three main categories of control structures:"
  * Sequence [executes in given sequence]
  * Selection [selects between two or more flows using condition or question]
  * Iteration [repeats same piece of code multiple times]
  
This chapter provides an introduction to control structures in the Python programming langauge. Topics covered include:
- Control flow and control structures
- Event-controlled and count-controlled loops
- Looping structures in Python (`for` and `while`)

```{admonition} <i class="fa-solid fa-hands-clapping" aria-hidden="true"></i> Acknowledgements
:class: tip, dropdown 
PLACEHOLDER
```

## <i class="fa-solid fa-hands-clapping" aria-hidden="true"></i> Acknowledgements

When building this lab, the author consulted materials developed by:
- [Dr. Peter Bui](http://www3.nd.edu/~pbui/) for the [CSE 10101 "Elements of Computing I" course](https://www3.nd.edu/~pbui/teaching/cdt.30010.fa16/).
  * [Conditional and Alternative Execution](http://nbviewer.jupyter.org/urls/gitlab.com/snippets/25773/raw)
  * [Loops](http://nbviewer.jupyter.org/urls/gitlab.com/snippets/26115/raw)
- [Dr. Janet Davis](https://cs.whitman.edu/~davisj/) for the the [CSC 105 "The Digital Age" course](https://www.cs.grinnell.edu/~davisjan/csc/105/2012S/). 
  * [Laboratory: Programming in Python (Decisions and Repetition)](http://www.cs.grinnell.edu/~davisjan/csc/105/labs/python3.html)
- [Dr. Corey Pennycuff](https://www3.nd.edu/~cpennycu/) for the [CSE 10101 Elements of Computing (Fall 2019)](https://www3.nd.edu/~cpennycu/2019/fa-CSE10101-CDT30010.html).
  * [Control flow structures](https://www3.nd.edu/~cpennycu/2019/assets/fall/EOC/19.09.03.ipynb)
  * [Looping structures](https://www3.nd.edu/~cpennycu/2019/fa-CSE10101-CDT30010.html)
- [Dr. Lindsay K. Mattock](http://lindsaymattock.net/) for the the [SLIS 5020 Computing Foundations course](http://lindsaymattock.net/computingfoundations.html). 

Definitions and explanations in this lab are adapted from Kenneth Leroy Busbee and Dave Braunschweig, *[Programming Fundamentals: A Modular Structured Approach, 2nd Edition](https://press.rebus.community/programmingfundamentals/)* (Rebus Press, 2018)
- [Chapter V, Loops](https://press.rebus.community/programmingfundamentals/part/loops/)

## <i class="fa-regular fa-bookmark" aria-hidden="true"></i> Companion Content

Nathan Ensmenger. "Chapter 5: The Rise of Computer Science." In [*The Computer Boys Take Over: Computers, Programmers, and the Politics of Technical Expertise*](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph005788353) (Cambridge: MIT Press, 2010): 111-136.
- Framing questions:
  * What does Ensmenger say in this chapter about what constitutes coding/programming?
    * Folks fan be thinking about types of work, as well as the nature of that work. We can also pay attention to the types of skills emphasized, and the influence of academic institutions or structures. 
	* Academic institutions or structures can be particular college or universities....but they can also be fields of study or disciplines.
  * What does Ensmenger say about the academic communities and stakeholders that shaped the early Computer Science field?
    * Folks can be thinking about background information presented in the chapter, motivations and priorities, and hiring practices.
  * After reading the chapter, how are you thinking about what computer science "is"? 
    * Is it science, formal logic, mathematics....or something else entirely?
	* How might the history we're reading about influence or shape the current computing/programming landscape?
	* What connections can folks make with your experiences/impressions around computing as an academic pursuit?

## <i class="fa-solid fa-list-ol" aria-hidden="true"></i> Chapter Contents

```{tableofcontents}
```

## <i class="fa-solid fa-clipboard-question" aria-hidden="true"></i> Application

Your answers to this chapter's application questions should be added to the notebook template.
- [Google Colab link](https://colab.research.google.com/drive/1HVYyphtxpPUzhVISngj-PWfeZ7OPcmd7?usp=sharing) (ND users only)

Your Google Colab notebook should be located in the `wk10-control-structures` [Google Drive folder](https://drive.google.com/drive/folders/1btaMEcpz_IoKgNZU4fTmf4l_n9dsga1V?usp=drive_link) (ND users only)

Submit the Colab link on Canvas for the assignment submission.

## <i class="fa-solid fa-chalkboard-user" aria-hidden="true"></i> In-Class Work

- 10/29 (T): Ensmenger discussion
- 10/31 (R): Collaborative problem solving (Python control structures)

## <i class="fa-solid fa-list-check" aria-hidden="true"></i> Assignments 

- Week #10 reflection (due end of day Friday, submit on Canvas)
- Individual application questions (due end of day Friday, submit on Canvas)
- Collaborative problem solving (due end of class Thursday, group submission on Canvas)