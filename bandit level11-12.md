#BANDIT LEVEL 11 TO 12
#OBJECTIVE
          To find the password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions
#STEPS
      tr 'A-Za-z' 'N-ZA-Mn-za-m' < data.txt
      Here I used tr command it is  translate tool used to replace the characters. 'A-Za-z' it is matches all upper and lower case.
      'N-ZA-Mn-za-m' it is used to shifting them forward by its 13th places.
#PASSWORD: GROozWPO8QyN0mGrjUkID0WCYkZiQxrN
