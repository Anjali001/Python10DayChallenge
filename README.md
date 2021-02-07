# Python 6-Day Challenge
6 days of Python with brief intorductory question on varaious data structures in python and their functionality.

## Day 1
  Kaggle microcourse on Python : Done @ https://www.kaggle.com/learn/python

## Day 2 : (Using Builtin functions)
  1.	Write a program which accepts a sequence of comma-separated numbers from console and generate a list and a tuple which contains every number. Suppose the following input       is supplied to the program:
      34,67,55,33,12,98
      Then, the output should be:
      ['34', '67', '55', '33', '12', '98']
      ('34', '67', '55', '33', '12', '98')
  2.  Write a program that accepts sequence of lines as input and prints the lines after making all characters in the sentence capitalized.
      Suppose the following input is supplied to the program:
      Hello world
      Practice makes perfect
      Then, the output should be:
      HELLO WORLD
      PRACTICE MAKES PERFECT
  3.  Find the last element of a list. 
      Eg., l = [1, 2, 3, 4] 
      Last_elemnt(l) -> 4
  4.  Reverse a list and return it.
      Eg., l = [1, 2, 3, 4]
      reverse_list(l) -> [4, 3, 2, 1]
  5.	Write a program that accepts a comma separated sequence of words as input and prints the words in a comma-separated sequence after sorting them alphabetically.
      Suppose the following input is supplied to the program:
      Without,hello,bag,world
      Then, the output should be:
      Bag,hello,without,world

## Day 3 : (Learning Dictionary)
  6.	Write a Python script to add a key to a dictionary.
      Add_item({0: 10, 1: 20},2,30)-->{{0: 10, 1: 20, 2: 30}
  7.	Write a Python script to concatenate dictionaries to create a new one.
      Example:
      dic1={1:10, 2:20} 
      dic2={3:30, 4:40}
      dic3={5:50,6:60}
      def dict_concatenate(dict1,dict2,dict3)--> {1: 10, 2: 20, 3: 30, 4: 40, 5: 50, 6: 60}
  8.	Write a Python program to check if a given key already exists in a dictionary.
      Example-
      check_key({1:10,2:20,3:30},2)--> True
  9.	Write a Python program to check a dictionary is empty or not.
      Example-
      is_empty({})--> True
      is_empty({'a':'b','c':'d'})--> False
  10.	Write a Python program to combine two dictionary adding values for common keys.
      D1 = {'a': 100, 'b': 200, 'c':300}
      d2 = {'a': 300, 'b': 200, 'd':400}
      Example-
      combine_duplicates(d1,d2)-->>({'a': 400, 'b': 400, 'd': 400, 'c': 300})

## Day 4 : (Lists) 
  11.	Replace consecutive duplicate elements of list with single element.
      Eg., l = [a, a, a, b, b, c, a, a, d, d, d, x, x]
      compress(l) -> [a, b, c, a, d, x]
  12.	Pack consecutive duplicates of list elements into sublists.
      Eg., l = [1, 1, 1, 2, 2, 3, 3, 4] pack(l) -> [[1,1,1], [2,2], [3,3], [4]]
  13.	Given two indices, i and k, the slice is the list containing the elements between the i'th and k'th element of the original list (left limit included). Start counting the elements with 0.
      Eg., l = [1, 3, 9, 8, 7];
      Slice(l, 1, 3) --> [3, 9]
  14.	Given a list l, index i and element elem, return a new list with elem at index i
      Eg., l = [1, 3, 9, 8, 7];
      insert_element(l, 1, 3) --> [1, 3, 9, 1, 8, 7]

  15.	Remove the k'th element from a list. Example: remove_element([a,b,c,d],2)-->[a,c,d]

## Day 5 : 
16.	Find whether a list a palindrome -> a sequence that reads the same forwards and backwards
    is_palindrome([1, 2, 1]) -> True
    is_palindrome([1, 2, 3, 2, 1] -> True
    is_palindrome([1, 2, 3, 1]) -> False
17.	Rotate a list N places to the left. Examples:
    rotate_list([a,b,c,d,e,f,g,h],3)--> [d,e,f,g,h,a,b,c]
     rotate_list([a,b,c,d,e,f,g,h],-2)--> [g,h,a,b,c,d,e,f] # Can also try a right rotate
18.	Sorting a list of lists according to length of sublists
    We suppose that a list (inlist) contains elements that are lists themselves.
    The objective is to sort the elements of inlist according to their length.
    Example: def sort_list([[a,b,c],[d,e],[f,g,h],[d,e],[i,j,k,l],[m,n],[o]],L)--> [[o], [d, e], [d, e], [m, n], [a, b, c], [f, g, h], [i, j, k, l]]
19.	Determine whether a given integer number is prime. Example:
    is_prime(7)-->True
    is_prime(10)-->False
20.	Determine the greatest common divisor of two positive integer numbers. Use Euclid's algorithm.
    Example:
    gcd(36, 63)-->9

## Day 6 
Take this quiz : https://www.w3schools.com/python/python_quiz.asp
Solve all excercises from https://www.w3schools.com/python/python_exercises.asp

# Yayyyy... You did it. 🎊
Now, you know Python. Let's specialize in commonly used python packages to start solving Data Science questions. Complete this https://github.com/Anjali001/Python15DayChallenge to become a master in Pandas and Numpy.
