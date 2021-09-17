Name: Manas Ranjan Parida
Roll No: 2019UGCS042R
Lab-1/
	Lex-Lab-1.1.l: Write a lex program to detect whether the character input is a digit or an alphabet
		       The expected input is a single character.
		       The output varies between cases of digit, alphabet or invalid characters.
Lab-2/
	Lex-Lab-2.1.l: Write a lex program to show whether the input is digit or alphabet or both.
		       The expected input is muktiple characters.
		       The output varies between cases of digit(s), alphabet(s), both or invalid characters.

	Lex-Lab-2.2.l: Write a lex program to show whether the given inout is a digit or not.
		       The expected input is a single character.
		       The output is "Digit" if the input is a digit else "Non Digit".

	Lex-Lab-2.3.l: Write a lex program to show whether thr input string contains only alphabets or not.
		       The expected input is a string of characters.
		       The output is "Only alphabets" if there are only alphabets in the string otherwise "Might contain characters other than alphabets".

	Lex-Lab-2.4.l: Write a lex program to show whether the input string contains only pper case, lower case characters.
		       The expected input is a string of characters.
		       The output is "Small letters only" for only lower case, "Capital letters only" for only upper case, "Both cases present" for both cases, otherwise "Characters other than alphabet".
Lab-3/
	Lex-Lab-3.1.l: Write a lex program to detect whether the input string contains consonants or vowels
		       The input is a string of characters.
		       The output is "This is a vowel." for vowel input, "The input is a conconant." for consonant input, "Both characters." for cases otherwise "Invalid characters." if containing any non-alphabet characters.

	Lex-Lab-3.2.l: Write a lex program to count characters, tabs and whitespaces in the given input string.
		       The expected input is string of characters.
		       The output prints characters, tabs and whitespaces count, each in a different line.

	Lex-Lab-3.3.l: Write a lex program to count consonants and vowels in the given string.
		       The expected input is a string containing several characters.
		       The output is prints consonant and vowel counts both in the same line.

	Lex-Lab-3.4.l: Write a lex program to count characters in a string.
		       The expected input is a string of characters.
		       The output prints the number of characters in the string.

	Lex-Lab-3.5.l: Write a lex program to detect keywords of C language.
		       The expected input is an array of characters.
		       The output is "This is a C keyword." for keywords otherwise "This is not a keyword.".

Lab-4/
	Lex-Lab-4.1.l: Write a lex program to detect and print keywords in C language.
		       The expected input is a an array of characters.
		       The expected output is "Keyword and it is: <the input" in case of keywords otherwise "Not a keyword".

	Lex-Lab-4.2.l: Write a lex program to check for valid identifiers in C language.
		       The expected input is an array of characters.
		       The expected output is "Not a valid identifier." in case of keywords and invalid combinations and "Valid identifiers." otherwise.

	Lex-Lab-4.3.l: Write a lex program to identify and print valid logical and arithmatic operators in C language.
		       The expected input is an array of symbols.
		       The output shows the validity of the operator, identifies its type and prints it in case of valid operators else it shows "Not a valid operator.".

	Lex-Lab-4.4.l: Write a lex program to detect integers and floating point numbers.
		       The expected input is a number.
		       The output is "FLOAT" in case of floating point numbers, "INTEGER" in case of integers and "INVALID" if anything other than a number is provided as input.

Lab-5/
	Lex-Lab-5.1.l: Write a lex program to count the number of lexemes in a string.
		       The input is a string containing different combination of arrays.
		       The output prints the number of lexemes present in the string by counting keywords, identifiers, operators, integers and floating point numbers.

	Lex-Lab-5.2.l: Write a lex program to count numbers, digits, letters, words, spaces and operators in the input string.
		       The input is a string containing various characters.
		       The output shows the number of letters, words, digits, numbers, spaces, and operators printing each in a different line.

	Lex-Lab-5.3.l: Write a lex program to chack for valid urls.
		       The input is a character array.
		       The output is "Valid URL: for inputs of the pattern "https://<combination of characters>.<TLD>.<ccTLD>" otherwise "Invalid URL".

Lab-6/
	Lex-Lab-6.1.l: Write a lex program to identify valid cell phone numbers.
		       The input is a string of digits and the symbol "+".
		       The output is "Vaid cell phone number." for combinations "+91 <a digit from 1 to 9><nine digits from 0 to 9>" otherwise "Invaid cell phone number.".

	Lex-Lab-6.2.l: Write a lex program to check for valid email addresses.
		       The input is a character string.
		       The output is "Valid email address." for combination of the pattern "<username>@<SLD>.<TLD>" else "Invalid email addresses." if containing any forbidden characters or not conforming to the pattern.

	Lex-Lab-6.3.l: Write a lex program to check for valid email address based on the number of characters in the username of the address.
		       The input is a character array.
		       The output provides the number of characters present in the username and prints "Valid email address." if the address conforms to the pattern and has more or equal number of characters than required else, "Invalid email address." if less number of characters or forbidden characters.

	Lex-Lab-6.4.l: Write a lex program to count the number of characters present in the contents of the file provided as input.
		       The input is the name of the file from which characters are to be counted, it is provided as a command line argument in the format ./<name of the output file generated by the compiled program> <name of the file containing characters>.
		       The output is "Program to count number of charaters in an input file." followed by the format in which the program is to be executed if the input format is not met, if met, the earlier output is followed by another line specifying the number of characters.

	Lex-Lab-6.5.l: Write a lex program to count the occurence of a specified word in a file.
		       The input is the file name and the word provided as command line arguments in the format ./<output file of compiled program> <name of file to be searched> <word to be searched>.
		       The output is "Program to count occurrrences of a word in an input file.". If the input format is not met, the string is followed by a message describing the usage format of the program, if the condition is met, the string is followed by another string in a new line specifying the nmber of occurrences of the word in the file.

