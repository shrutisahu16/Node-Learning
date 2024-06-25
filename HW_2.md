# Wcat
It is used to display or make a copy content of one or more files in terminal

## Commands:
1-wcat filepath => displays content of the file in the terminal
2-wcat fileopath1 filepath2 filepath3...=>displays content of all files in the terminal in the given order
3-wcat -s filepath => convert big line breaks into a singular line break;
4- wcat -n filepath => give numbering to all the lines
5- wcat -b filepath => give numbering to non-empty lines
6-wcat filepath =>filename2path ->put all the content of filename into filename2 by overriding and also creates file if it doesn't exits. //it is implemnt by command line (node wcat f1.txt f2.txt -b -s > f6.txt)

7- wcat filename2path => filename2path => append all the content of filename into filename2 ans:-(node wcat f1.txt f2.txt -b -s >> f6.txt)
8- node wcat -s filename => filename2 => get the file content of filenaem remove large spaces and save output in filename2
We can mix and match the options

## Edge cases:
1-If file entered is not found then it gives file does not exist error
2- -n and -b are 2 options available together then command should give you an error
