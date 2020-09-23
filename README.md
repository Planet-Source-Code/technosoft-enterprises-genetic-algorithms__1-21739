<div align="center">

## Genetic Algorithms


</div>

### Description

Introduces uses and ways to implement the revolutionary AI technology... genetic algorithms.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Technosoft Enterprises](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/technosoft-enterprises.md)
**Level**          |Advanced
**User Rating**    |4.6 (32 globes from 7 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/technosoft-enterprises-genetic-algorithms__1-21739/archive/master.zip)





### Source Code

<H2><center>Genetic Algorithms</center></H2><br><br>
<b>I. Introduction: </b><br>
Genetic algorithms are a revolutionary new way to use minimal computational power to handle infinitely complicated calculations. This new AI concept 'evolves' so that it does not waste ANY of your computer's memory. It is almost a very advanced trial-and-error system that filters out the incorrect 'guesses.' A programmer who can use all of these capabilities to his/her advantage will be much in demand in the software industry of the near future.<br><br>
<b>II. The Setup of a Genetic Algorithm:</b><br>
The three subsections (IIa through IIc) talk about the three steps the algorithm goes through. The situation is the following: there is a "blackbox" function that takes in eight input numbers and outputs one value. The genetic algorithm does not know what mathematical operations are conducted within the blackbox function. However, the user of the genetic algorithm tells it that he/she wishes to know the input numbers to be put in to come out with an output number (specified by the user.)<br>
<i>IIa. Step 1 -- Initialization</I><br>
The genetic algorithm (known as GA from here on) starts by making a small population of 16 'chromosomes.' These chromosomes are random 32-bit binary strings. After these 16 chromosomes are created, step 2 begins.<br>
<i>IIb. Step 2 -- Fitness Calculation</i><br>
The GA takes the chromosomes one by one and breaks the 32 binary characters down into 8 sections of 4. (i.e. 1101-0010-1101-0110-1010-0101-1010-1110) These eight sections are then decoded in regular (base-10) integers and inputted into the blackbox function. The GA then calculates how close the output for that chromosome is to the optimum target value. The closer the chromosome is to the target value the higher of a fitness value they are awarded. This process is repeated for all the chromosomes currently in the system.<br>
<i>IIc. Step 3 -- Reproduction and Mutation</i><br>
After all the chromosomes have been evaluated, the ones with lower fitness numbers are 'exterminated' and the others are allowed to reproduce. A random crossover point between the father and mother chromosomes is chosen. For Example:<br>
Father: 00110101<br>
Mother: 01001010<br>
Random Crossover Point: 3<br>
Child (three from the father, five from the mother): 00101010<br>
After that, some children undergo random mutation where one of the binary digits is changed. Steps 2 and 3 are repeated until the results match the target number.<br><br>
<b>III. Final Note</b><br>
This tutorial has only introduced the idea of genetic algorithms. In Part 2, we will explain how to program them and use them in everything from medical applications to one-time pad encryption. Thanks for your interest and we hope you'll be waiting for the next one!

