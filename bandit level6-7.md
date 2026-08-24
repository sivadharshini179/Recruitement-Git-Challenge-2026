#BANDIT LEVEL 6 TO 7
#OBJECTIVE
          To find the password for the next level is stored somewhere on the server
#STEPS
      'find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null'
      /var/lib/dpkg/info/bandit7.password
      'cat' /var/lib/dpkg/info/bandit7.password
      Here I used find / to searches across the root directory. -type f it take only the matches file on it.-user bandit7 it filters the own by bandit7.
      -group bandit6 it filters the belonging to bandi6. -size 33c it look the file exactly the 33 bytes. 2>/dev/null it hides the error lines so we can only see the result.
      at last i used cat command to read the directory.
#PASSWORD: Bmnnvf82KzQlfxgAI2d1zYbr1u9pr3E3
