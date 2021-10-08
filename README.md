Java files = All of our code

.md file = Text, definitions, etc;
## Into to Java 
A Jvaa program can be charactor as a **object** represented in a **class**.

Currently our program has a *Main* object. Inside of this object we have the *Main* class.

## Output
In Java to output an item to the concole we use: 'System.out.print()' and 'System.out.println()' 
`System.out.print()` prints the statment and moves to the next line, while `System.out.print()` just prints the statment.

## Comments 
A comment is used as user annotation with the purporse of being human readable.

**Line Comment** follow double backslashes `//`. (Single Line Comment)

**Block Comment** are contained within `/*Comment*/`. (Multiple Lines)

## Identifer 

In Java use the term **identifer** to describe a variable, parameter, constant, user-defined method or user-defined class.

- Cannot begin with digit 
- Can only contain letters, dights, and underscores
- Case-sensitive `age != Age` (age is bot equal) `Apple == Apple`

*Note:*

- class name starts with capital letter
- reserved words are entierely lowercare and may not be used as identifiers (Reserved words will show up in blue.)

## Types 
**Primitive or **built-in** types in Java are 

- `int` An integer 
- `boolean` True or False (boolean shirtColor = ture)
- `double` floating-point number (2.73)(compared to float in Python)
- `char` single character

*Note:*  Integers have a fixed amount of memory, so there is a limit to how many digits you can store(2^31 - 1)

## Variables
Variables are a type of identifer that stores a value of a specific type.

We can create variables using **declaration** 
- `int age;`
- `double x,y;`
- `boolean found;`
- `char letter;`

We can also initialize a variable in its **declaration**.
- `int count = 1;`
- `x = 2.0`
- `double p= 3.14;`
- `char c = '8';`

## Chars
[ASCII CHART](https://docs.google.com/document/d/1oubLTqAHmdkadtjbR8xxREG7auvuUqiQ/edit)

Each charaharacter is associated with an ASCII value.

## Type cast 

One type can be cast to another compatinle type if appropiate

`char letter = 'c'`
```

int total, n;
double average;
average = (double)total/n //total cast to double to ensure real division is used
```

*Note:* Casting a floating-point number to an integer simply truncates the number (rounds down)