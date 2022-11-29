---
toc: true
layout: post
description: Fun!
categories: [markdown]
title: Unit 3 Section 3-4 Notes 
---

# Hacks
- title: Homework Assignment for 3.3-4
- tags: [hw]
- toc: true
- comments: true

## 3.3 Video 1 Hacks

Show two examples and label which one is sequence, selection, iteration
numbers = [0,1,2,3,4,5,6,7,8,9,10]
evens = []

for i in numbers:
    if (numbers[i] % 2 == 0):
        evens.append(numbers[i])

print(evens)
### Answers 1
All the steps combined are sequencing

The step "for i in numbers:" is iteration because they go through all the numbers.

"if (numbers[i] % 2 == 0)" is selection because they sort each number to find the even ones.
i = 1
starString = "*"
while i <= 5:
  j = 1
  while j <= i:
    print ("*", end= "")
    j += 1
  print ()
  i += 1
<strong>Hack: code walkthrough</strong>

i = 1

1 < 5

j = 1

1 <= 1 

print --> * 

#iterate to next i 

i = 2 

2 < 5

j = 1 

1 <= 2 

print --> * 

2 <=2

print --> * 

#iterate to next i, keeps going like this until i = 6 and stops printing * 
### Answers 2

All the steps are a sequence

"While i <= 5:" is iteration because they repeat until i reaches 5

"While j <= i:" is selection because this is where they decide what j is



## 3.3 Video 2 Hacks
### Practice Problems 
1. given the following code segment below:

a ⟵ 7

b ⟵ 1

c ⟵ 3

d ⟵ 4

a ⟵ b

b ⟵ c + d

d ⟵ b 

find the value for a, b, c, d 
<details closed>
    <summary>Click for the answer!</summary>
       a = 1, b = 7, c = 3, d = 7
    </details>

2. consider the following code segment:

hot ⟵ true

cold ⟵ false

cold ⟵ hot 

hot ⟵ cold

what are the values of hot and cold after executing the code segment? 
1. the value of hot is true, the value of cold is true 
2. the value of hot is false, the value of cold is true
3. the value of hot is true, the value of cold is false
4. the value of hot is false, the value of cold is false 
<details closed>
    <summary>Click for the answer!</summary>
        1. the value of hot is true, the value of cold is true 
    </details>

3. Make TWO of your own code segments that contain at least 5 defined variables, then provide the answer and EXPLAIN why your answer is correct. 
4. Sequencing
num1 = 3
num2 = 1
num3 = 5
num1 = num2 + num3      
num2 = num1 + num3      # num2 is now the new num1 + num3
<strong>Hack: Problem 1-4 explanation</strong>

#1 

a = 7 

b = 1 

c = 3 

d = 4 

a = 1 

b = 3 + 4 = 7 

d = 7 

Answer: a = 1, b = 7, c = 3, d = 7 

#2 

hot = true 

cold = false

cold = hot = true 

hot = cold= true 

Answer: cold = true, hot = true 

#3 Own code segment with 5 variables 
a = 3

b = 7

c = 10

d = b + a 

e = c / d 

what is d * e ? 

Explanation: 

d = 7 + 3 = 10 

e = 10 / 10 = 1 

d * e = 10 * 1 = 10 

#4

num1 = 3

num2 = 1

num3 = 5

num1 = num2 + num3 = 1 + 5 = 6   

num2 = num1 + num3 = 3 + 6 = 9  

What is the value of num1 and num2?
<details closed>
    <summary>Click for the answer!</summary>
        num1 = 6, num2 = 11
    </details>
## 3.3 Video 3 Hacks


## 3.4 Video 1 Hacks

### String Homework
---------------------------------------------------------------


- Test 1

    firstName <- "Bob"
    lastName <- "Smith"
    var <- substring(firstName, 1, 1)
    name <- concat(lastName, var)
    email <- concat(name, "@gmail.com")
    DISPLAY(email)

- What would the result be?

 Hint:
 var = "B"
 name = "SmithB"

---------------------------------------------------------------
- Test 2

    word1 <- "computer"
    word2 <- "textbooks"
    length1 <- len(word1)/2
    length2 <- len(word2)/3
    first <- substring(word1, 2, len1)
    second <- substring(word2, len2+3, len2)
    newWord <- concat(first, second)
    DISPLAY(newWord)
---------------------------------------------------------------

#### Answers
 Test 1
- Result: "SmithB@gmail.com"

 Test 2
- Result: "ompuook"



<strong>String homework explanation</strong>

#1 

firstName = "Bob"

lastName = "Smith" 

var = substring(firstName, 1, 1) = "B"

name = concat(lastName, var) = "SmithB"

email = concat(name, "gmail.com") = SmithB@gmail.com

#2 

word1 = "computer" 

word2 = "textbooks"

length1 = len(word1)/2 = 8 / 2 = 4 

length2 = len(word2)/3 = 9 / 3 = 3 

first = substring(word1, 2, len1) = ompu (starting at 2nd letter, 4 letters)

second = substring(word2, len2 + 3, len2) = ook (starting 6th letter, 3 letters)

newWord = concat(first, second) 
