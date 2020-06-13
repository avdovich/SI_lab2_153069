# СОФТВЕРСКО ИНЖЕНЕРСТВО – 2 ЛАБОРАТОРИСКА

Изработила: Јасмина Авдовиќ 153069

Група на код: 6

### 1. Control Flow Diagram
Control Flow Diagram -от го направив со помош на апликацијата draw.io, а може да го погледнете на следната слика. 

![CFG](/Pictures/CFG.png)

### 2. Every Statement тестирање

![statement](/Pictures/statement.png)

Test 1: 1; 2; 17                                         -   Тест пример за кога:  2  e false

Test 2: 1; 2; 3; 4; 5; 6; 16; 17                 -   Тест пример за кога:  6 е false, 12 e false

Test 3: 1; 2; 3; 4; 5; 6; 7; 8; 17               -   Тест пример за кога:  6 e true, 7 e true

Test 4: 1; 2; 3; 4; 5; 6; 7; 9; 10; 17        -   Тест пример за кога:  6 e true, 7 e false, 9 e true

Test 5: 1; 2; 3; 4; 5; 6; 11; 17                 -   Тест пример за кога:  6 e true, 7 e false, 9 e false 

Test 6: 1; 2; 3; 4; 5; 6; 12; 13; 14; 17    -   Тест пример за кога: 6 e false, 12 e true, 13 e true

Test 7: 1; 2; 3; 4; 5; 6; 12; 13; 15; 17    -   Тест пример за кога: 6 e false, 12 e true, 13 e false 

### 3. Every Branch тестирање

![branch](/Pictures/branch.png)

Test 1: A; B; C; T                                              - Тест пример за кога: C e false

Test 2: A; B; C; D; E; F; G; H; I; S; C               - Тест пример за кога: G e true, H e true

Test 3: A; B; C; D; E; F; G; H; J; K; L; S; C      - Тест пример за кога: G e true, H e false, K e true

Test 3: A; B; C; D; E; F; G; H; J; K; M; S; C    - Тест пример за кога: G e true, H e false, K e false

Test 4: A; B; C; D; E; F; G; N; O; P; S; C        - Тест пример за кога: G e false, N e true, O e true

Test 5: A; B; C; D; E; F; G; N; O; Q; S; C       - Тест пример за кога: G e false, N e true, O e false 

Test 6: A; B; C; D; E; F; G; N; R; S                 - Тест пример за кога: G e false, N e false

### 4. Цикломатска комплексност
Цикломатската комплексност ја пресметав со помош на формулата, M = E – N + 2P, каде што, Е го претставува бројот на ребра во графот, N го претставува бројот на јазли во графот, а Р го претставува бројот на поврзани компоненти.

Е = 25

N = 20

Р = 1

М = 25 – 20 + 2*1 = 5 + 2 = 7

Цикломатската комплексност на овој граф е 7.
