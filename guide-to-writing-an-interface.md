# Guide to Writing an Interface

An interface is just a list of methods. 

* No visibility needed, because they are public by default.
* No need to write the word abstract, because they are abstract by default.

If you are asked to write an interface, find the **name** and **return type** \(or void if no return type\) of each method.

Note if there are any parameters, and be sure to include them.

#### Don't forget your semicolon!!!!!

Over-simplified example \(writing an interface is what you'll be asked to do, except all of the info will be buried in the text somewhere, or you will have to figure it out from writing Code.

---

Please write an interface called Computer. 

* It should have a method called wifi, that does not return anything and has no parameters.
* It should have a method called isPoweredOn, which takes a double as a parameter, and returns true or false.
* It should have a method called screenTime, which will return an int, and has two parameters, one boolean and one Monitor \(an object made up just for this example!\)
* It should have one more method, and it is called like this in another class:

```
                    boolean hasFan = false;
                    int batHours = myLaptop.hoursOfLife(hasFan);
```

Here's how the interface should look!

```
public interface Computer
{
   void wifi();
   boolean isPoweredOn(double pow);
   int screenTime(boolean screen, Monitor mon);
   int hoursOfLife(boolean isFan);
}
```

---

Notes on the above:

* I made up my own names for the parameters. The names of parameters don't matter.
* I used the order listed in the text for the order that my parameters are in.



