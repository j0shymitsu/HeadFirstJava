# NOTES

---

## Chapter 1

### Syntax notes
```java
int size = 27;                          // declare an integer variable named size adn give it the value 27
String name = "Fido";                   // declare a string of characters variable named 'name' and give it value "Fido"
Dog myDog = new Dog(name, size);        // declare a new Dog variable 'myDog' and make the new dog using 'name' and 'size'
if (x < 15) myDog.bark(8);              // if x is less than 15, tell the dog to bark 8 times

while (x > 3) {                         // keep looping as long as x is greater than 3    
    myDog.play();                       // tell the dog to play          
}                                       // end

int[] numList = {2, 4, 6, 8};           // declare a list of integers variable 'numList' and put 2, 4, 6, 8 into it
System.out.print("Hello");              // Print "Hello"
System.out.print("Dog: " + name);       // Print out "Dog Fido" (above)

String num = "8";                       // declare a character string variable 'num' and give it value of '8'
int z = Integer.parseInt(num)           // convert string "8" into actual numeric value 8

try {                                   // try do something
    readTheFile("myFile.txt");          // read a text file named "myFile.txt" 
}
catch(FileNotFoundException ex) {
    System.out.print("File not found")  // if failed, print "file not found    
}
```

### Code structure
- Put a **class** in a source file.
- Put **methods** in a class.
- Put **statements** in a method.

