# 🐍 Study of Conditional Statements in Python

### AIM: Study of Conditional Statements in Python

### 6a. Check if a number is positive, negative, or zero
*Check if a number is positive, negative, or zero.*
1. **Start**
2. Input a number as variable `num`.
3. Check if `num > 0`:
    * **True:** Print "Number is positive".
4. If False, check if `num < 0`:
    * **True:** Print "Number is negative".
5. If both are False: Print "Number is zero".
6. **Stop**

### 6b. Even or Odd 
1. **Start**
2. Input variable `x`.
3. Calculate remainder of `x / 2` (using `x % 2`).
4. Check if remainder is `0`:
    * **True:** Print "Even".
    * **False:** Print "Odd".
6. **Stop**

### 6c. Finding the Greatest of Three
1. **Start**
2. Input variables `x`, `y`, and `z`.
3. If $x > y$ AND $x > z$: Print `x` is greatest.
4. Else if $y > x$ AND $y > z$: Print `y` is greatest.
5. Else: Print `z` is greatest.
6. **Stop**

---

## 🎓 2. Academic Grading Systems

### 6d. Get input from user for 1 subject and calculate grade using if-elif-else
1.**Start**

2.Get input of marks from user

3.Check if marks are >=90

4.If true : print "A GRADE"

5.Else if marks are >=75

6.If true : print "B GRADE"

7.Else if marks are >=60

8.If true : print "C GRADE"

9.Else if marks are >=40

10.If true : print "D GRADE"

11.Else if marks are < 40

12.If true : print "F GRADE"

13.**Stop**


| Criteria (Marks/Avg) | Resulting Grade |
| :--- | :--- |
| $\ge 90$ | 🌟 **A GRADE** |
| $\ge 75$ | 🥈 **B GRADE** |
| $\ge 60$ | 🥉 **C GRADE** |
| $\ge 40$ | 📉 **D GRADE** |
| $< 40$ | ❌ **F GRADE** |

---

### 6e. Get input of 3 subjects and calculate average and grade using if-elif-else

**Start**

+ Get input of marks of 3 subjects from user

+ Calculate avg of three subjects

+ Check if avg is >=90

+ If true : print "A GRADE"

+ Else if avg is >=75

+ If true : print "B GRADE"

+ Else if avg is >=60

+ If true : print "C GRADE"

+ Else if avg is >=40

+ If true : print "D GRADE"

+ Else if avg is < 40

+ If true : print "F GRADE"

 **Stop**



| Criteria (Marks/Avg) | Resulting Grade |
| :--- | :--- |
| $\ge 90$ | 🌟 **A GRADE** |
| $\ge 75$ | 🥈 **B GRADE** |
| $\ge 60$ | 🥉 **C GRADE** |
| $\ge 40$ | 📉 **D GRADE** |
| $< 40$ | ❌ **F GRADE** |

---

## 📅 3. Calendar & Date Logic

### 6f. Leap Year Verification
**Start**

* Input the year as variable year.
* **Condition 1:** Year is divisible by 400.
* **OR**
* **Condition 2:** Year is divisible by 4 **AND** NOT divisible by 100.
* **Result:** If either matches, it is a **Leap Year**.

**Stop**
  
### 6g. Date Increment Algorithm
1. Read date in `DD-MM-YYYY` format.
2. Separate day, month, and year.
3. Check for leap year to assign February days (28 or 29).
4. **Increment day by 1.**
5. If day exceeds month limit:
    * Set day to 1.
    * **Increment month.**
6. If month exceeds 12:
    * Set month to 1.
    * **Increment year.**
7. Display the updated date.

---

## 🔤 4. Character Analysis

### 6h. Vowel or Consonant
* **Input:** Character `ch`.
* **Process:** Check if `ch` exists in the sequence `'aeiouAEIOU'`.
* **Outcome:** * **True:** "Vowel" 
    * **False:** "Consonant"

---

## 💰 5. Financial & Tax Algorithms

### 6i. Gross Salary Calculation
 **Start**

+ Get Salary From user

+ Calculate the gross salary

+ If basic <= 10000 : HRA = 20%, DA = 80%

+ If basic <= 20000 : HRA = 25%, DA = 90%

+ Otherwise: HRA = 30%, DA = 95%

+ Calculate gross= basic + hra + da

+ Print gross salary

 **Stop**

| Basic Salary | HRA | DA |
| :--- | :--- | :--- |
| $\le 10,000$ | 20% | 80% |
| $\le 20,000$ | 25% | 90% |
| $> 20,000$ | 30% | 95% |

> **Formula:** $Gross = Basic + HRA + DA$

### 6j. Income Tax Brackets
+ **Start**

+ Get input of salary from user

+ If the salary is Up to 2,50,000: No Tax



+ If the salary is between 250000 - 500000: 5%

+ tax= 0.05*(income-250000)



+ If the salary is between 500001 - 1000000: 20%

+ tax =(250000*0.05)+  0.2*(income-500000)



+ Else:

+ tax=(250000*0.05)+  (0.2*500000)+0.3*(income-1000000)
+ Print tax to be paid
+ **Stop.**


* **Up to 2,50,000:** No Tax.
* **2,50,000 – 5,00,000:** $5\% \times (Income - 2,50,000)$
* **5,00,001 – 10,00,000:** $12,500 + 20\% \times (Income - 5,00,000)$
* **Above 10,00,000:** $1,12,500 + 30\% \times (Income - 1,000,000)$
