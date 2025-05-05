# concurrency-parallelism-project-4-solved
**TO GET THIS SOLUTION VISIT:** [Concurrency-Parallelism Project 4 Solved](https://www.ankitcodinghub.com/product/concurrency-parallelism-project-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94287&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Concurrency-Parallelism Project 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this class you will learn/remember some basic concepts of concurrency and how to process data in parallel using the C programming language.

1 Introduction

The Game of Life12 is a zero players game, that was invented in 1970 by the British mathematician John Horton Conway. Conway developed an interest in a problem which was made evident in the 1940’s by mathematician John von Neumann, who aimed to find a hypothetical machine that had the ability to create copies of itself and was successful when he discovered a mathematical model for such a machine with very complicated rules on a rectangular grid. Thus, the Game of Life was Conway’s way of simplifying von Neumann’s ideas. It is the best-known example of a cellular automaton which is any system in which rules are applied to cells and their neighbours in a regular grid. Martin Gardner popularised the Game of Life by writing two articles for his column “Mathematical Games” in the journal Scientific American in 1970 and 1971.

You have been working with OpenMP in the past labs. In this lab you are expected to take a larger and more complex program and parallelize it with openMP.

2 Lab Work

2.1 Sequential version of the Game of Life

Clone the given version of a sequential implementation of the Game of Life in your device

(your own laptop or lab workstation) with the command

<pre>   git clone https://bitbucket.org/joaomlourenco/game_of_life_seq.git
</pre>
and compile it using the command make. make is a command that builds a project given in a project specification text file named Makefile. Open the text file Makefile with your favorite text editor and use the web to learn a bit about make and Makefile. You’ll need it again in the short future.

</div>
</div>
<div class="layoutArea">
<div class="column">
1 https://en.wikipedia.org/wiki/Conway’ s_Game_of_Life 2 http://web.stanford.edu/~cdebs/GameOfLife/

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
This project dependes on the “libpcre” library. In Linux you can install it with

<pre>        apt intall libpcre
</pre>
In macOS (with HomeBrew) can install it with brew install libpcre3-dev

And in Windows can install it with

I have no idea… is you know please share with us!

The given Makefile is rather versatile and should work for both Linux and macOS. If you adapt it for Windows, please share your adaptations in Piazza.

2.2 OpenMP version of the Game of Life

The given version of the Game of Life is sequential. Your job is to make a new parallel

version of this program using OpenMP!

Please follow these steps:

<ol>
<li>Compile and experiment with the given version. Carefully study (and make sure you understand) the given source code.</li>
<li>Change this program to use Terminal ANSI Escape Codes to: (a) Clear the screen (terminal) at the very beginning.(b) Position the cursor at coordinates (0,0) before printing the board, so that a board is printed overlapping the last board. This makes it easier to observe the evolution of the system.</li>
<li>Change the program to include a new optional flag “-p” with an integer as argument (from pause) that will make a pause for the given number of miliseconds before drawing the next frame.</li>
<li>Change the program to include a new optional flag “-q” (from quiet) so that only the last board (final state) is printed.</li>
<li>Create a parallel version of the program by using OpenMP.</li>
<li>Experiment your parallel version with different boards, board sizes and number of processors (remember you can use e.g. “OMP_NUM_THREADS=2 ./glife 100 tests/1.in” to run a simulation with just 2 processors). What is the achieved speedup? And ef- ficiency? And cost? IS there a relation between the board size and the speedup achieved?</li>
</ol>
Please remember to use GIT appropriately. Leran to work with branches and make a branch when you start a new phase from the list above, and merge your branch to your main version when the development is finished and appropriately tested/validated.

2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Acknowledgments

The text from the Introduction is an adaptation from the text in http://web.stanford. edu/~cdebs/GameOfLife/.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
