# Introduction to Logic Design using PyRTL

In this introductory tutorial, we will discuss <a href = "https://en.wikipedia.org/wiki/Hardware_description_language">Hardware Description Languages</a>, and the <a href = "https://pyrtl.readthedocs.io/en/latest">PyRTL</a> framework, in order to gain a base understanding of how to perform Logic Design hardware in computers.


These notebooks and guides were initially developed in the Fall 2022 Semester of <a href ="https://canvas.nd.edu/courses/53612/pages/lecture-notes-and-schedule">CSE 10001 - Principles of Computing for Business Majors</a> at the University of Notre Dame by Professor <a href ="https://engineering.nd.edu/faculty/matthew-morrison">Matthew Morrison</a>."

These notebooks were implemented in a two-week sequence to help business majors learn the importance of logic design in the context of the impact of computing hardware on the economy, especially with the passage of the CHIPS Act.

The objective of introducing these topics to Business majors was presented to the students as follows:
> The objective for this reading assignment and final project is to <b>position you as an informed leader in the semiconductor space, so you can productively manage and lead hardware desginers on your team while simultaneously effectively conveying your challenges, achievements, and vision to investors</b>."

## Prerequisites for Completion

The students had completed 10 weeks of Python programming using Jupyter Notebooks.

The introductory directions for installing all the appropriate tools in Jupyter for the class may be found here at the beginning of the first homework assignment: <a href = "https://canvas.nd.edu/courses/91978/pages/homework-01-hardware-programming">Homework 01 - Hardware, Programming</a>

The full course Lecture Notes and Schedule may be found at the following link: https://canvas.nd.edu/courses/53612/pages/lecture-notes-and-schedule"

Prior to the Logic Design sequence, the students covered topics including:
<ul>
    <li>Introduction to Computational Thinking and Hardware</li>
    <li>Data Representation</li>
    <li>Variables, Expressions, and Functions</li>
    <li>CPU and Conditional Executions</li>
    <li>Advanced Conditionals and HTML Printing</li>
    <li>Iteration, Lists, and Sequences</li>
    <li>Algorithms</li>
    <li>Strings and Duplicates</li>
    <li>File I/O</li>
    <li>Data Structures, such as <code>dict</code></li>
    <li>Operating Systems and Recursion</li>
    <li>Images and Image Filters</li>
    <li>Intellectual Property</li>
    <li>The Internet and Networks</li>
</ul>

## Outline

To gain the most benefit from these notebooks, follow the sequence below, including <b>Preview Reading</b>, <b>In-Class Coding Assignments</b>, and the breakdown of the Final Project.

|Assignment|Objectives|Notes and Starter Notebooks|
|:--|:--|:--|
|Reading 1 - <a href ="https://nbviewer.org/github/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/readings/Reading%201%20-%20Introduction%20and%20Logic%20Gates.ipynb">Introduction and Logic Gates</a> |In this preview reading, students will:<br><ul><li>Discover of Impact of Semiconductor Design on the Economy</li><li>Learn the fundamentals of logic gates and their operation</li><li>Learn the foudational implementation of PyRTL</ul>|Contains PyRTL-specific installation instructions for Jupyter Notebooks|
|In-Class Coding 1 - Logic Design - Combinational Logic|In this lecture, you will:<ul><li>Implement Basic Logic Gates</li><li>Use Python Functions to implement combinational logic</li></ul> | <ul><li><a href ="https://github.com/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/inclass/In-Class%201%20-%20Blank.ipynb">In-Class Coding 1 - Blank Starter Notebook</a></li><br><li><a href ="https://nbviewer.org/github/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/inclass-sols/In-Class%201%20-%20Solution.ipynb">In-Class Coding 1 Solutions with PyRTL Waveforms</a></li> |
|Reading 2 - <a href ="https://nbviewer.org/github/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/readings/Reading%202%20-%20Logic%20Blocks%20and%20Advanced%20Logic%20Circuits.ipynb">Logic Blocks and Advanced Logic Circuits</a>|In this preview reading, students will:<br><ul><li>Learn how to implement Combinational Logic Design using the PyRTL Framework</li><li>Build their understanding through the design of a one-bit Full Adder</li></ul>| |
|In-Class Coding 2 - Logic Design - Full Adder|In this lecture, you will:<br><ul><li>Develop and test a 1-bit Full Adder</li><li>Use Recursion to develop a 4-bit Full Adder with connected gates</li></ul>|<ul><li><a href ="https://github.com/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/inclass/In-Class%202%20-%20Blank.ipynb">In-Class Coding 2 Starter Notebooks</a></li><br><li><a href ="https://github.com/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/inclass-sols/In-Class%202%20-%20Solutions.ipynb">In-Class Coding 2 Solutions with PyRTL Waveforms</a></li></ul>|
|Reading 3 - <a href ="https://github.com/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/readings/Reading%203%20-%20Finite%20State%20Machines.ipynb">Finite State Machines</a>|<ul><li>Combinational Logic Design</li></ul>| |
|In-Class Coding 3 - Logic Design - Finite State Machines|In this lecture, you will:<br><ul><li>Use a register to store the state value for a Finite State Machine</li><li>Learn to compare the sequential output with a PyRTL Waveform</li></ul>|<ul><li><a href ="https://github.com/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/inclass/In-Class%203%20-%20Blank.ipynb">In-Class Coding 3 Starter Notebook</a></li><br><a href ="https://nbviewer.org/github/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/inclass-sols/In-Class%203%20-%20Solutions.ipynb">In-Class Coding 3 Solutions with PyRTL Waveforms</a>|
|Final Project |The goal of this lab assignment to allow you to explore using PyRTL to perform logic design and logic simulation of a proposed task.| <a href ="https://nbviewer.org/github/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/final_project/final_project.ipynb">Project Description and Requirements</a><p></p><b>Example Solutions</b><ul><li><a href = "https://nbviewer.com/github/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/final_project/security_system.ipynb">Security System FSM</a></li><li><a href = "https://nbviewer.com/github/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/final_project/simple_game.ipynb">Simple Game</a></li><li><a href = "https://nbviewer.com/github/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/final_project/train_fsm.ipynb">Train Track Decision FSM</a></li><li><a href = "https://nbviewer.com/github/mmorri22/sscs-ose-code-a-chip.github.io/blob/main/ISSCC25/pyrtl/final_project/western_adventure.ipynb">Western Adventure Game</a></li></ul> |