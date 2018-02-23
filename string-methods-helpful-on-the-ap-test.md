# String Methods, Helpful on the AP Test

##### `char charAt(int pos)`   //returns the character at position pos

```
String greeting = "Hello, there!";
char thirdChar = greeting.charAt(2); //stores 'l' in thirdChar      
System.out.println("The third character in \"" + greeting + "\" is " + thirdChar + ".");
```

[See it here.](http://rextester.com/BJCZW78483)

##### `int indexOf(String str, int fromPos)` //returns the index of the first occurrence of str from the position fromPos

```
String greeting = "Hello, there!";
int secondE = greeting.indexOf("e",4); //stores '9' in seondE      
System.out.println("The second instance of e in \"" + greeting + "\" is " + secondE+ ".");
```

[See it here.](http://rextester.com/SDQUM60533)

##### `String trim()` //returns a String, str without leading or trailing spaces

```
String spaces = "     lots of spaces!            ";
String spacesRemoved = spaces.trim();
System.out.println("Before spaces, our String is \"" + spaces + "\", and, afterwards, it's \"" + spacesRemoved + "\".");
```

[See it here.](http://rextester.com/XODSR60900)

##### `String replace(char oldChar, char newChar)` //returns a String with all instances of oldChar replaced

##### //with newChar in the String calling the procedure

```
String oldWord = "goose";
String newWord = oldWord.replace('o','e');
System.out.println("\"" + oldWord + "\" becomes \"" + newWord + "\".");
```

[See it here.](http://rextester.com/XDAMF5829)

### Possibly helpful, behave as expected

##### `String toUpperCase()`

##### `String toLowerCase()`

##### `int lastIndexOf(String str)`  //also works for char

##### `int lastIndexOf(String str, int fromPos)`  //also works for char



