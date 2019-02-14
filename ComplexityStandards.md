# Complexity Guidelines

This document serves to outline the standards of complexity agreed upon by the
class in the development of the GatorGrouper tool. These standards are created
and followed in order to effectively implement GatorGrouper while minimizing the
complexity of the code base. The definition of complexity we will use is taken
from “A Philosophy of Software Design” by Chairman of Electric Cloud and
Professor of Computer Science at Stanford, John Ousterhout. John defines
complexity as anything “related to the structure of a software system that makes
it hard to understand and modify the system.” To this end, the standards here
will aim to minimize complexity by maximizing the clarity and ease of
modification of GatorGrouper.


## How to manage complexity in a software development project

*Minimize Complexity by Maximizing Clarity: Follow Code Writing Conduct Standards*

1. Changeability -
*Software will be easily changeable to allow for future scalability:*
	- Software must be easily changeable. If a change results in re-writing
	code or creating a new feature it can cause risks to the rest of the
	system. These frequent changes require software to be easily adjustable
	so that changes can be made efficiently.

2. Uniqueness -
*Software shall not contain redundant features or code snippets:*
	- In an effort to reduce the total code base, redundant code or systems that
	perform similar actions should be recognized and taken out.

3. Encapsulation -
*Software shall be structured such that related documents are grouped together:*
	- In order to keep code understandable, interacting code should be kept together.
	This allows for greater readability and less time spent searching for relevant
	code.

4. Constraints -
*Software constraints should be clear to avoid confusing or arbitrary use-cases:*
	- In order to keep code understandable, there should be at first glance; a
	limited amount of ways in which it can be used. Constraints can be cultural,
	semantic, logical or physical

5. Predictability -
*All software runs should have predictable and consistent outcomes:*
	- Every change should have a pre-evaluated outcome as the developer should be
	completely certain with their modifications. If a change effects elements
	outside the developers understanding it can cause unknown bugs and unwanted
	technical debt.

6. Feedback/Output -
*All software should have output that clearly displays the function attempted:*
	- The output of a program should clearly convey what the program does. Or at
	the very least, that the attempt to run the program was effective.

7.  Documentation -
*All software should be properly documented and commented as to clearly convey
the purpose of the code as outlined in the Assessment guidelines:*
	- Comments should focus on the developer's thought process as they code.
	Understanding why the code exists the way it does is just as important as what
	the code does. Avoid redundancy and adding too many comments when commenting
	code. Comments should only be used when the codes purpose couldn't be easily
	discerned.


The purpose of the code as outlined in the Assessment guidelines:
Comments should focus on the developer’s thought process as they code. Understanding why the
code exists the way it does is just as important as what the code does.
Avoid redundancy and adding too many comments when commenting code. Comments should only be
used when the codes purpose couldn’t be easily discerned.
