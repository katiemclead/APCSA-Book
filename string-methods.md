# String Methods

### The following String methods are listed on the Java Quick Reference:

#### See if you can guess the output!

##### `int length()`        // returns the length of the String

```
String greeting = "Hello, there!";
int stringLength = greeting.length(); //stores 13 in stringLength        
System.out.println("String " + greeting + " has a length of " + stringLength + ".");
```

[See it here.](http://rextester.com/JDPIJN44765)

##### `String substring(int from,  int to)`         // returns the substring beginning at `from` and ending at `to-1`

```
String greeting = "Hello, there!";
String littleGreeting = greeting.substring(0,5); //stores characters 0 - 4 from greeting into littleGreeting
System.out.println(littleGreeting);
```

[See it here.](http://rextester.com/OOMF63020)

##### `String substring(int from)`   //returns the substring beginning at `from`through the end of the string.

```
String greeting = "Hello, there!";
String littleGreeting = greeting.substring(11); //stores characters 11 on from greeting into littleGreeting
System.out.println(littleGreeting);
```

[See it here.](http://rextester.com/EJOIN34736)

##### `int indexOf(String str)` //returns the index of the first occurrence of str \(specifically, the position of the first character\)

#####                                               //returns -1 if not found

#####                                               //also works with char

```
String greeting = "Hello, there!";
int value  = greeting.indexOf("th");
System.out.println("index of \"th\" is " + value + ".");
value = greeting.indexOf("z");
System.out.println("index of \"z\" is " + value + ".");
```

[See it here.](http://rextester.com/FULZLF50841)

##### `int compareTo(String other)`      //returns a value &lt; 0 if `this`is less than `other`

##### //returns a value = 0 if `this`is equal to `other`

##### //returns a value &gt; 0 is `this`is greater than `other`

```
String greeting = "Hello, there!";
int example1 = greeting.compareTo("Hi!");
int example2 = "Hi!".compareTo(greeting);
int example3 = "Hello, there!".compareTo(greeting);
System.out.println("Example 1: " + example1);
System.out.println("Example 2: " + example2);
System.out.println("Example 3: " + example3);
```

[See it here.](http://rextester.com/BPIU29395)

