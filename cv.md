# Eugen Burkenia

## Contacts
- **location:** Bronx, NY
- **phone:** +1 (646) 262-0765
- **email:** burikievgen@gmail.com
- **git:** [forgetme4ever](https://github.com/forgetme4ever)

## Objective
Seeking a junior web developer position in IT company where I can utilize and upgrade my coding skills

## Skills
- HTML
- CSS
- Git
- Figma
- JavaScript
- Python

### Code example
> На вход программе подаются два натуральных числа n и m. Напишите программу, которая создает матрицу размером n×m заполнив её змейкой.
```
n, m = [int(i) for i in input().split()]
matrix = []
k = [int(i) for i in range(1, m + 1)]
cy = 0
for i in range(n):
    matrix.append(k[cy:] + k[:cy])
    cy += 1
    if cy > len(k):
        cy = 1
for i in range(n):
    for j in range(m):
        print(matrix[i][j], end = ' ')    
    print()
```

### Experience
Some study projects using JavaScript:
+ [Aim the target](https://github.com/forgetme4ever/aimthetarget)
+ [Colored cursor](https://github.com/forgetme4ever/coloredCursor)
+ [Slider](https://github.com/forgetme4ever/sliderUpnDown)

## Education
+ Brooklyn College, NY - M.S. in Business Economics, 2016
+ Kyiv Slavonic University, Kyiv - B.S. in Finance, 2009
+ Kyiv RailRoad College, Kyiv - A/C and refrigeration specialist, 2003

### Courses
- Python for beginners
- Introduction to manual testing
- JavaScript for beginners
- Python programming
- Introduction to Java

#### Languages:
- Ukrainian - Native
- Russian - Native
