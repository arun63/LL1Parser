LL1 Parser

Developed using Java

===================================================

Instructions:
To run the project, simply compile `LL1Parser.java` and run `java LL1Parser [path to grammar file] [path to file to input file]`.

View the screenshot if need 
For example:

    cd code/
    javac LL1Parser.java
    java LL1Parser ../output/1/grammar.txt ../output/1/test.txt

	Use Command '-v' argument for verbose mode.
	
	Verbose mode prints the revised grammer , first and follow set , parsing table and the parsing operations

Output:

After successfully parsing a grammar, the program will create two files in the active directory:

1) A tokenized version of the input file will be written in the current working directory with the extension of `.tok`.
2) parsing_table.txt is the name of the parsing table containing text files

NOTE: Run the command 'less -S parsing_table.txt' for viewing the parsing table in the terminal.

This project is revised version of the existing project available. 

