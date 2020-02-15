1. Ilya Trukhov
2. e-mail megafon2484@mail.ru
3. My goals is achieve programming skills and knowledge in many type's of programming like frontend, backend, and others.
4. Know programming languages C, C++, Java, C#, prolog, TypeScript, SQL, especially like programming on ASM microcontroler's as AVR, STM; frameworks: Spring Framework, Bootstrap, Angular; methodologies: RUP; version control: git.
5. array sort (ASM AVR):
maxsearch:
      clr r19
sortcycleagain:
      mov xh,r20
      mov xl,r21
      push length
      ld r16,x+
      dec length
      ld r17, x+
      dec length
sortcycle:
      ld r2,x+
      ld r3,x+
      cp r2,r16
      brlo sort
      breq nextcheck
      rjmp higher
nextcheck:
      cp r3,r17
      brlo sort
higher:
      mov r16,r2
      mov r17,r3
aftersort:
      dec length
      dec length
      brne sortcycle
      pop length
      inc r19
      cpi r19, 10
      brne sortcycleagain
      ret
sort:
      subi xl,4
      st x+,r2
      st x+,r3
      st x+,r16
      st x+,r17
      rjmp aftersort
6. Unviversity lab works.
7. Self-learning.
8. Intermediate level B.