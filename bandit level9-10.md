#BANDIT LEVEL 9 TO 10
#OBJECTIVE
          To find the password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.
#STEPS
      strings data.txt | grep "=="
      Here I used strings command to find the printable text inside the files.Then I used grep == it searches for lines woth multiple = signs.
#PASSWORD:  B0s2khmbT9u0geKuOoVGW3JZKhndE3BG
