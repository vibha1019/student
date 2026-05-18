---
layout: post
title: AP CSA Exam Preparation Evidence
codemirror: true
description: Review of FRQ and MCQ preparation leading up to the AP CSA exam.
permalink: /apcsa-review
---

# AP CSA Exam Preparation Evidence

## Overview

Leading up to the AP CSA exam on May 15th, I consistently reviewed FRQs, MCQs, and Java concepts through AP Classroom progress checks and practice problems. I focused especially on ArrayLists, 2D arrays, class construction, traversal patterns, and string methods like `.split()`.

---

# Study Timeline

## May 1
- Reviewed Unit 1 and Unit 2 MCQs
- Practiced constructors and instance variables
- Reviewed object-oriented programming basics

## May 3
- Practiced ArrayList FRQs
- Reviewed traversing and modifying ArrayLists
- Focused on indexing and loop logic

## May 5
- Completed AP Classroom progress checks
- Reviewed static variables and methods
- Practiced timed MCQ questions

## May 7
Completed:
- Objects and Instances of Classes Quiz (3/3)
- Static Variables and Methods Quiz (1/1)

Focused on Java fundamentals and AP-style logic problems.

## May 8
- Practiced 2D array FRQs
- Reviewed nested loops and traversal
- Worked on row/column indexing patterns

## May 10
- Practiced full class construction FRQs
- Reviewed constructors, methods, and instance variables
- Focused on writing complete classes independently

## May 12
Reviewed string methods including:
- `.substring()`
- `.equals()`
- `.length()`
- `.split()`

Practiced applying string methods in FRQ-style problems.

## May 14
Final review before the AP exam:
- ArrayLists
- Traversing 2D arrays
- Writing complete methods
- Common AP CSA patterns and edge cases

---

# FRQ Practice

## ArrayList and 2D Array FRQs

![ArrayList and 2D Array FRQ Practice]({{site.baseurl}}/images/frq34.png)

### Skills Practiced
- Traversing `ArrayList` objects
- Nested loops with 2D arrays
- Updating and searching through data
- AP-style method writing

---

## Full Class Construction FRQ

![Class Construction FRQ]({{site.baseurl}}/images/frq2.png)

### Skills Practiced
- Constructors
- Instance variables
- Method creation
- Object-oriented programming structure

---

# MCQ Practice

![MCQ Practice Evidence]({{site.baseurl}}/images/mcq.png)

| Assessment | Score |
|---|---|
| Unit 3 Progress Check Part A | 10/12 |
| Objects - Instances of Classes Quiz | 3/3 |
| Static Variables and Methods Quiz | 1/1 |
| Unit 2 Progress Check Part B | 16/21 |
| Unit 4 Progress Check Part B | 19/21 |
| Unit 1 Progress Check Part C | 17/18 |
| Unit 2 Progress Check Part A | 14/18 |
| Unit 1 Progress Check Part B | 13/15 |
| Unit 1 Progress Check Part A | 11/12 |
| Unit 4 Progress Check Part A | 17/18 |
| Practice Exam 2 MCQ | 34/42 |

---
## AP CSA Review: Traversing a 2D Array

{% capture challenge1 %}
This was one of the topics I reviewed before the AP CSA exam. The method traverses a 2D array and calculates the total sum of all elements.
{% endcapture %}

{% capture code1 %}
public class Main {
    public static int totalSum(int[][] values) {
        int sum = 0;

        for (int row = 0; row < values.length; row++) {
            for (int col = 0; col < values[row].length; col++) {
                sum += values[row][col];
            }
        }

        return sum;
    }

    public static void main(String[] args) {
        int[][] numbers = {
            {1, 2, 3},
            {4, 5, 6}
        };

        System.out.println(totalSum(numbers));
    }
}
{% endcapture %}

{% include code-runner.html
   runner_id="apcsa1"
   language="java"
   challenge=challenge1
   code=code1
%}

---

## AP CSA Review: ArrayList Traversal

{% capture challenge2 %}
I also reviewed ArrayList traversal patterns and modifying values during iteration.
{% endcapture %}

{% capture code2 %}
import java.util.ArrayList;

public class Main {
    public static void doubleValues(ArrayList<Integer> nums) {
        for (int i = 0; i < nums.size(); i++) {
            nums.set(i, nums.get(i) * 2);
        }
    }

    public static void main(String[] args) {
        ArrayList<Integer> numbers = new ArrayList<>();

        numbers.add(1);
        numbers.add(2);
        numbers.add(3);

        doubleValues(numbers);

        System.out.println(numbers);
    }
}
{% endcapture %}

{% include code-runner.html
   runner_id="apcsa2"
   language="java"
   challenge=challenge2
   code=code2
%}

---

## AP CSA Review: String Methods

{% capture challenge3 %}
Before the exam, I reviewed common String methods like `.substring()` and `.split()`.
{% endcapture %}

{% capture code3 %}
public class Main {
    public static void main(String[] args) {
        String sentence = "AP CSA Exam Review";

        String[] words = sentence.split(" ");

        for (String word : words) {
            System.out.println(word);
        }

        System.out.println(sentence.substring(0, 2));
    }
}
{% endcapture %}

{% include code-runner.html
   runner_id="apcsa3"
   language="java"
   challenge=challenge3
   code=code3
%}

---
# Post Test Reflection

Now that I’ve taken the AP CSA exam, I think reviewing ArrayLists, traversing 2D arrays, and string methods like `.split()` helped a lot. Repeated FRQ practice made it easier to recognize common patterns quickly, and the AP Classroom MCQs helped me get more comfortable with AP-style timing and problem solving.

