n - liczba 8-bitowa z przedziału 0-255
nn - liczba 16-bitowa z przedziału 0-65535

06 n  - LD B, n
0E n  - LD C, n
16 n  - LD D, n
1E n  - LD E, n
26 n  - LD H, n
2E n  - LD L, n
3E n  - LD A, n

40    - LD B, B
41    - LD B, C
42    - LD B, D
43    - LD B, E
44    - LD B, H
45    - LD B, L
47    - LD B, A

48    - LD C, B
49    - LD C, C
4A    - LD C, D
4B    - LD C, E
4C    - LD C, H
4D    - LD C, L
4F    - LD C, A

50    - LD D, B
51    - LD D, C
52    - LD D, D
53    - LD D, E
54    - LD D, H
55    - LD D, L
57    - LD D, A

58    - LD E, B
59    - LD E, C
5A    - LD E, D
5B    - LD E, E
5C    - LD E, H
5D    - LD E, L
5F    - LD E, A

60    - LD H, B
61    - LD H, C
62    - LD H, D
63    - LD H, E
64    - LD H, H
65    - LD H, L
67    - LD H, A

68    - LD L, B
69    - LD L, C
6A    - LD L, D
6B    - LD L, E
6C    - LD L, H
6D    - LD L, L
6F    - LD L, A

78    - LD A, B
79    - LD A, C
7A    - LD A, D
7B    - LD A, E
7C    - LD A, H
7D    - LD A, L
7F    - LD A, A

C3 nn - JP nn

C6 n  - ADD A, n

E6 n  - AND n
