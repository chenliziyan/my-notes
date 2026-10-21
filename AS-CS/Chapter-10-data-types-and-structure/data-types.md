# Note 1 - Data Types
---
## **Record**
*composite data structure*

### Advantages
- Store different types of data
- one identifier & Fields are named
  - each item has meaningful identifier  
    - more structured
    - more readable
- Offers structured storage

### Pseudocode:
``` typescript
TYPE <Typename>
    DECLARE <identifier> : <data type>
    DECLARE <identifier> : <data type>
    DECLARE <identifier> : <data type>
ENDTYPE
```

Pseudocode Example
``` typescript
TYPE Student
    DECLARE name: STRING
    DECLARE age: INTEGER
    DECLARE birthday: DATE
ENDTYPE

DECLARE Sarah: Student
Sarah.name <-- "Sarah"
Sarah.age <-- 17
Sarah.birthday <-- 05/03/2008

OUTPUT "Sarah's age: ", Sarah.age
```
---
## **Array**
- Ordered, static set of elements
- One type of data
- Index
  - First element --> **LB** ：0/1
  - Last element --> **UB**

### Basics
#### One-Dimensional / Linear array 一维数组
##### Pseudocode Example
``` typescript
DECLARE <identifier>: ARRAY[LB:UB] OF <data type>

DECLARE Letters: ARRAY[0:4] OF CHAR
Letters[0] <-- 'a'
Letters[1] <-- 'b'
// ...
```

Example, OUTPUT whole array:
``` typescript
FOR Index <-- 0 TO 4
    OUTPUT Letters[Index]
NEXT Index
```

#### Two-Dimensional Array 二维数组
- LBR & UBR  (Row)
- LBC & UBC  (Column)
Declaration: `DECLARE <identifier> [LBR:UBR,LBC:UBC] OF <data type>`
##### Pseudocode Example
``` typescript
DECLARE Table[0:4,0:2] OF CHAR //四行两列

Table[0,0] <-- 'a'
```

### **Array Pseudocode-advanced**
#### 1. Linear Search
``` typescript
DECLARE IntList: ARRAY[1:5] OF INTEGER
DECLARE Index: INTEGER
DECLARE Found: BOOLEAN
DECLARE Target: INTEGER

OUTPUT "Enter the value trying to find: "
INPUT Target
Index <-- 1
Found <-- FALSE

WHILE Index <= 5 AND Found = FALSE DO
    IF IntList[Index] = Target THEN
        Found <-- TRUE
    ELSE
        Index = Index + 1
    ENDIF
ENDWHILE

IF Found = TRUE
    OUTPUT "The target's index is ", Index
ELSE
    OUTPUT "Target is not found in array."
ENDIF
```

#### 2. Bubble Sort
``` typescript
DECLARE List: ARRAY[1:8] OF INTEGER
DECLARE Swap: BOOLEAN
DECLARE Temp: INTEGER
DECLARE Index: INTEGER

//Initializing the array here
Swap <-- TRUE

WHILE Swap = TRUE DO
    Swap <-- FALSE
    FOR Index <-- 1 TO 7
        IF List[Index] > List[Index + 1] THEN
            Temp <-- List[Index]
            List[Index] <-- List [Index + 1]
            List[Index + 1] <-- Temp
            Swap <-- TRUE
        ENDIF
    NEXT Index
ENDWHILE

OUTPUT "Array after sort: "
FOR Index <-- 1 TO 8
    OUTPUT List[Index]
NEXT Index
```
---




