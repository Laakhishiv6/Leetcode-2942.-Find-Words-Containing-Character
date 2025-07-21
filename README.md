# Leetcode-2942.-Find-Words-Containing-Character
# Description
You are given a 0-indexed array of strings words and a character x.
Return an array of indices representing the words that contain the character x.
Note that the returned array may be in any order.


# Solution
Given :
1. An array named words with words in it.
2. A character as a variable x.
   
The goal in this question is to find the words in an array which contains the given character in it.

1. This can be achieved by looping through each word in the array and searching for the given character x.
2. If the character is found in any letter then append the index of the word in an array named res .
3. Return res.
