# JsFuck-compiler
This is a similar project to the one by low level javascript, but i made it so this one can actually compile js code that lives inside a file and produce an output file in JsFuck

That is if you run this command:
### $ node index.js > out.js

But first you will need node.js installed or any other runtime

## Update !!!
#### On line 7 in the index.js file if you want this to work on windows you have to replace "input = input.replace(/(\r\n|\n|\r)/gm, "");" with "input = input.replace(/(\n|\n|\r)/gm, "");" because windows uses '\r\n' for a line break instead of '\n' 

## Installation
### For installing the executable on your system, you will need to copy this repo, then unzip the xz archive and inside you will find the executable

### Commnands:
#### $ git clone https://github.com/JohnCTilis/JsFuck-compiler
#### $ sudo apt install xz (you can use any package manager)
#### $ xz -d jsfc.xz
