# Checklist

1. Is source code followed by coding rule/guideline completely?
2. Is each data structure properly initialized?
3. Are descriptive data structure names used?
4. Have all data structures been explicitly declared?
5. Is the initialization of a data structure consistent with its type?
6. Is a variable referenced whose value is uninitialized or not set to its proper value?
7. Are all defined variables used?
8. For expressions containing more than one operator, are the assumptions about order of evaluation and precedence correct? Are parentheses used to avoid ambiguity?
9. Is the correct variable used for the comparison condition (eg, X == TRUE instead of FOUND == TRUE)?
10. Are all comparison operators correct (eg, there is not “=” expression used in a comparison instead of “==”)?
11. Will all loops terminate?
12. Are there any unnecessary branches?
13. Are all loop terminations correct?
14. Does each switch statement have a default case?
15. Are statement lists properly enclosed in { }?
16. Have all files been opened before use?
17. Are the attributes of the open statement consistent with the use of the file(eg, read, write)?
18. Have all files been closed after use?
19. Is buffered data flushed?
20. Are these spelling or grammatical errors in any text printed or displayed by the function?
21. Are error conditions checked?
22. Is there commentary to allow the reader to understand the code? (comments of files, functions)
23. Is the underlying behavior of the function expressed in plain language?
24. Is the interface specification of the function consistent with the behavior of the function?
25. Are the comments and code consistent each other?
26. Do the comments help in understanding the code?
27. Are useful comments associated with each block of code?
28. Check static code tracking before commit source code
29. Naming rule
30. Encapsulation
31. Consitent with Design
32. Can test
33. Simplify
34. Rule of comment in head of file
35. Rule of mark rev
36. Are there any magic number in the source code?
37. Was the default value are set following the specification?
38. Did you confirm message list with PSKai?
39. Did you fix all ESLint errors?
40. Did you check all ESLint warning? (console.log, variables defined but never used…) ???
41. Did build tool run successfully?
42. Did all package.json and package-lock.json up to date?
