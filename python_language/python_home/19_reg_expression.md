<h1 align="center">Regular Expression</h1>

* *Regex in python* - If we want to do string related task, we can use regex(re,regular expression) <br />
	*Eg*:	
```python
			import re 
			//Check if the string starts with "The" and ends with "Spain": 
			txt = "The rain in Spain" 
			x = re.search("^The.*Spain$", txt)  
			// ^ - beggin,	.* - to in between,	$- end  
			if x: 
			  print("YES! We have a match!") 
			else: 
			  print("No match")
```

* *Regex Functions* <br />

| **Function** | **Description** |
|--------------|------------------|
| findall      | Returns a list containing all matches |
| search       | Returns a Match object if there is a match anywhere in the string |
| split        | Returns a list where the string has been split at each match |
| sub          | Replaces one or many matches with a string|

* *Metacharecters* -  these are the characters with special meaning  <br />

| **Character** | **Description** | **Example** |
|----------------|-----------------|----------------|
| [] | A set of characters | "[a-m]" |
| \  | (Signals a special sequence (can also be used to escape special characters) | "\d" |
| .  | Any character (except newline character) | "he..o" |
| ^  | Starts with | "^hello" |
| $ | Ends with | "world$" |
| * | Zero or more occurrences | "aix*" |
| + | One or more occurrences | "aix+" |
| {} | Exactly the specified number of occurrences | "al{2}" |
| \| | Either or | "fallslstays" |
| () | Capture and group |   |
 

* *Special Sequence - a sequence start with \ followed the character and has special meaning  <br />

| **Character** | **Description** | **Example**|
|----------------|-----------------|----------------|
| \A | Returns a match if the specified characters are at the beginning of the string | "\AThe" |
| \b | Returns a match where the specified characters are at the beginning or at the end of a word(the "r" in the beginning is making sure that the string is being treated as a "raw string") | r"\bain" r"ain\b" |
| \B | Returns a match where the specified characters are present, but NOT at the beginning (or at the end) of a word (the "r" in the beginning is making sure that the string is being treated as a "raw string") | r"\Bain" r"ain\B"|
| \d | Returns a match where the string contains digits (numbers from 0-9) | "\d" |
| \D | Returns a match where the string DOES NOT contain digits | "\D" |
| \s | Returns a match where the string contains a white space character | "\s" |
| \S | Returns a match where the string DOES NOT contain a white space character | "\S" |
| \w | Returns a match where the string contains any word characters (characters from a to Z, digits from 0-9, and the underscore _ character) | "\w" |
| \W | Returns a match where the string DOES NOT contain any word characters | "\W" |
| \Z | Returns a match if the specified characters are at the end of the string | "Spain\Z" |
