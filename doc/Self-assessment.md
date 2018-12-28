# Review form for project Pentis

**Name of project to be reviewed:**
Tile Matching 4

**Names of reviewers:**
Juho Heimonen, Kalle Alaluusua, Rustam Latypov, Visa Lintunen

Provide short comments (2-4 sentences) for each item below.

## 1. Overall design and functionality (0-6p)

  * 1.1: The implementation corresponds to the selected topic and
scope. The extent of project is large enough to accommodate work for
everyone (2p)

The project is an interpretation of the original games that started the genre. 
The project is extensive, tested and tweaked to near perfection.

  * 1.2: The software structure is appropriate, clear and well
documented. e.g. class structure is justified, inheritance used where
appropriate, information hiding is implemented as appropriate. (2p)

Structure is justified in the software documentation.
Inheritance is intuitive and used to avoid repetition.
The class variables are private and used through functions.

  * 1.3: Use of external libraries is justified and well documented. (2p)

Simple and fast multimedia library is appropriate for the project. (SFML)
Use of SFML is documented.

## 2. Working practices (0-6p)

  * 2.1: Git is used appropriately (e.g., commits are logical and
frequent enough, commit logs are descriptive). (2 p)

Commits are frequent and comments are descriptive.


  * 2.2: Work is distributed and organised well. Everyone contributes to
the project and has a relevant role that matches his/her skills. The
distribution of roles is described well enough. (2p)

Roles and weekly tasks of team members are documented.
The roles are clearly distributed and correspond to personal interests and skills.

  * 2.3: Quality assurance is appropriate. Implementation is tested
comprehensively and those testing principles are well documented. (2p)

Testing was comprehensive and is well documented on project documentation.


## 3. Implementation aspects (0-8p)

  * 3.1: Building the software is easy and well documented. CMake or
such tool is highly recommended. (2p)

Building the software is easy using the provided Makefile.
Instructions are well documented.

  * 3.2: Memory management is robust, well-organised and
coherent. E.g., smart pointers are used where appropriate or RO3/5 is
followed. The memory management practices should be documented. (2p)

Memory management is bulletproof.
Static memory is used when possible since the project is compact and we wanted to achieve minimum latency.
RO3 is followed.

  * 3.3: C++ standard library is used where appropriate. For example,
containers are used instead of own solutions where it makes sense. (2
p)

We expanded on existing structures and used standard libraries when possible.

  * 3.4: Implementation works robustly also in exceptional
situations. E.g., functions can survive invalid inputs and exception
handling is used where appropriate. (2p)

Exception handling implemented on reading and writing external files.
The effect of user input is limited.

## 4. Project extensiveness (0-10p)
  * Project contains features beyond the minimal requirements: Most of
the projects list additional features which can be implemented for
more points. Teams can also suggest their own custom features, though
they have to be in the scope of the project and approved by the course
assistant who is overseeing the project. (0-10p)

A list of high scores that is saved locally (for both game-modes)
Sounds (Drop-sound, remove-sound, end-game-sound)
AI (Function that increases the difficulty by altering block distributions)
Special modes of play (Tetris and Pentis)