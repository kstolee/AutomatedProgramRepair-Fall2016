##CSC 591/791 Syllabus -- Automated Program Repair

North Carolina State University

Fall 2016

Monday/Wednesday 11:45 AM - 1:00 PM

Instructor: Dr. Kathryn Stolee (ktstolee@ncsu.edu)

Textbook: none

###Prerequisites
CSC510 (Software Engineering) or graduate or senior standing with at least 3.0 GPA, good knowledge of at least one high level programming language.

##Overview
All software has bugs. In this special topics course, you will learn about modern techniques in automated fault repair, that is, techniques that locate and patch faults. We will explore state-of-the-art research  You will also have the opportunity to build a simple automated program repair engine. 

##Schedule (subject to change):
| Dates   | Topic                     | Tool*      | In-class | Due |
------------|---------------------------|------------|-------------------------------| -----|
| Aug 17  | Introduction              | &nbsp;     | |
| Aug 22  | What are bugs?            |            | [Paper: Bug characteristics in open source software](http://dl.acm.org/citation.cfm?id=2683130) || 
| Aug 24  | What makes a good patch?  | | [Paper: A human study of patch maintainability]() ||
| Aug 29  | Basic Static analysis | | Activity: control and data flow analysis for source code ||
| Aug 31  | Basic Dynamic analysis | | | |
| Sept 7 | Mining source code | Boa | [Paper: Mining Source Code Repositories with Boa]()||
| Sept 12 | Finding bugs: static analysis | FindBugs | [Paper: Evaluating Static Analysis Defect Warnings On Production Software](http://dl.acm.org/citation.cfm?id=1251536)| |
| Sept 14 | Finding bugs: static analysis | | | HW#1: CFG for source code |
| Sept 19| Finding bugs: spectrum-based | Tarantula | [Paper: Empirical evaluation of the tarantula automatic fault-localization technique]()||
| Sept 21| Finding bugs: spectrum-based | | Activity: beauty contest from HW#1||
| Sept 26 | Finding bugs: dynamic analysis | Emma | [Paper: Regression testing in continuous and largescale environments]()| 
| Sept 28| Finding bugs: dynamic analysis | Randoop | |HW#2: Tarantula implementation| 
| Oct 3|  Finding bugs: mutation | PIT |   ||
| Oct 5 | Finding bugs: mutation | | | |
| Oct 10| Program repair: Genetic | GenProg | Paper: Automatically finding patches using genetic programming | |
| Oct 12|Program repair: Genetic | |   ||
| Oct 17| SMT Solvers | Z3 | In-class activity: Z3| HW#3: Mutation-driven program repair | 
| Oct 19| Symbolic Execution | Klee| | |
| Oct 24 | Program repair: Synthesis-guided | CodeHint | [Paper: CodeHint](http://dl.acm.org/citation.cfm?id=2568250) | Project proposal|
| Oct 26 | Program repair: Synthesis-guided | |  [Paper: SemFix](), Activity: peer review and one-on-one project meetings|
| Oct 31 | Program repair: Semantic Search-based | | [Paper: Solving the search for source code](http://dl.acm.org/citation.cfm?id=2581377) | 
| Nov 2  |Program repair: Semantic Search-based| | [Paper: Repairing programs with semantic code search](http://dl.acm.org/citation.cfm?id=2916260) | | 
| Nov 7 | Future of Program Repair | | Activity: brainstorming | | 
| Nov 9| Future of Program Repair | |  | | 
| Nov 14 | Future of Program Repair | |  | Project mid-report| 
| Nov 16 |Future of Program Repair | |  | | 
| Nov 21 | Project work | |  In-class office hours | |
| Nov 28 | Project presentations | | |
| Nov 30 |Project presentations| | Project reports | 

## Tool Review and Presentation:
Students will explore and demonstrate a research tool to the class. The focus of these presentations will be on what it does, illustrated through examples. These tools will be related to the topic covered in class and may include:
* [Boa](http://boa.cs.iastate.edu)
* [Findbugs](http://findbugs.sourceforge.net/)
* [Randoop](https://pmd.github.io/)
* [Emma] (http://emma.sourceforge.net/)
* [Klee] (https://klee.github.io/)
* [CodeHint] (http://jgalenson.github.io/codehint/)
* [Z3]( https://github.com/Z3Prover/z3)
* [CodeHunt](http://research.microsoft.com/en-us/projects/codehunt/)
* [PIT](http://pitest.org/)

##Project:
Students will conduct a project related to bugs, fault localization, or program repair. This project will consist of reproducing a study*, creating a new tool, extending an existing tool, adapting an existing tool to a new domain, or similar. The final deliverable will be a paper in 2-column ACM format. Students will make their tools and/or evaluation artifacts available on GitHub.

Possible Projects:
* Mining open source code:
  - Identify errors in regular expressions
  - Explore the scope of patches in bug fixes
* Fixing bugs in regular expressions via
  - Mutation operators
  - Code search
  - Semantic clustering
* Fixing bugs with code search via
  - Executing patches with i/o pairs
  - Bootstrapping the tests and guess/check 
* Patching bugs via:
  - New mutation operators
  - Modified mutation operators

##Grading:
* Homework (3): 40%
* Tool Review and Presentation: 20%
* Final Project: 40%^

^591 students have the option of replicating prior work. A literature review is not required.
791 students will be expected to conduct original research and produce a final project report worthy of submission to a conference or workshop in software engineering. This includes a comprehensive literature review. 

There will be no final exam, but a final project will be delivered during the last week of classes (November 30). 

###Late Policy:
No late assignments will be accepted. Early assignments are always welcome! 
