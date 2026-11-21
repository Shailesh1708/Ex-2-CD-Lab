# Ex-2-GENERATION OF LEXICAL TOKENS LEX FLEX TOOL
## DATE: 21.11.2026
## NAME: Shailesh S S
## REG NO: 212225040397
# AIM
## To write a lex program to implement lexical analyzer to recognize a few patterns.
# ALGORITHM

1.	Start the program.

2.	Lex program consists of three parts.

     a.	Declaration %%

     b.	Translation rules %%

     c.	Auxilary procedure.

3.	The declaration section includes declaration of variables, maintest, constants and regular definitions.
4.	Translation rule of lex program are statements of the form

    a.	P1 {action}

    b.	P2 {action}

    c.	…

    d.	…

    e.	Pn {action}

5.	Write a program in the vi editor and save it with .l extension.

6.	Compile the lex program with lex compiler to produce output file as lex.yy.c. eg $ lex filename.l $ cc lex.yy.c
7.	Compile that file with C compiler and verify the output.

# INPUT
c=a+b*d
# OUTPUT
<img width="1467" height="755" alt="image" src="https://github.com/user-attachments/assets/2929f076-e7e6-49ae-a60f-1c364879e803" />

# RESULT
## The lexical analyzer is implemented using lex and the output is verified.
