# CMPSC 100 Practice Questions for the Final Exam
# Name:


##### Note: These are just some practice questions and the number of questions does not represent the length of the exam.


### Question 1
Here is a complete class named `Tree`:
```
       public class Tree {
           public String name;
           public boolean deciduous;

           public Tree(String newName, boolean status) {
               name = newName;
               deciduous = status;
           }

           public String getName() {
               return name;
           }

           public boolean isDeciduous() {
               return deciduous;
           }
       }
```
Write a `main` method that creates three `Tree` variables
named `oak`, `elm`, and `pine`.  The first two are
deciduous, the last is not. That's all---the method just declares
three variables and  doesn't do anything else.

### Question 2
What is the final value of `count` when each of the following loops is
finished executing?

```
int count = 0;
for (int j = 1; j < 10; j++) {
  count = count + 1;
}
```

```
int count = 0;
for (int j = 0; j <= 10; j++) {
  count ++;
}
```

```
int count = 0;
int value = 1;
while (value <= 5) {
  value += 2;
  count = count + value;
}
```

### Question 3
Write the Java statements needed to find the sum of the first 20 positive
odd integers, that is, the sum 1+3+5+ ... (20th terms in the sum). The
final value should be stored in an `int` variable named `sum`
which you must declare and initialize. Use some kind of loop structure;
don't simply type in all of the odd integers in a great big sum expression!


### Question 4
Write the Java statements needed to create a new `ArrayList` containing
integer values  and to fill it
with the first 1000 consecutive integers, starting with 0.


### Question 5
Given the following Java declaration:
```
        int [ ] nums = new int[25];
```
Write the Java statements needed to fill `nums` with the values of
the first 25 positive multiples of 3, that is, 3, 6, 9, ...

### Question 6
Convert the following for loop into an equivalent do while loop:

```
for(int i =100; i > 0; i--) {
	System.out.println(i);
}
```

### Question 7
What is the output of the following code segment:

```
ArrayList<String> list = new Arrayist<String>();
list.add("Meadville");
list.add("Cleveland");
list.add("Wooster");
list.add("Richmond");

Iterator iterator = list.iterator();
for(iterator.hasNext()) {
  switch(iterator.next())
	case "Meadville":
		System.out.println("Allegheny College");
		break;
	case "Wooster":
		System.out.println("Allegheny College");
		break;
	case "Richmond":
		System.out.println("Allegheny College");
		break;
	case "default":
		System.out.println("Not Found");
		break;
  }
}
```


### Question 8
Suppose a class contains an instance variable declared as follows:

`private boolean visible;`

Assume the value of `visible` has been assigned elsewhere in the program. Write a method that changes the value of `visible` to its opposite (so if `visible` is true, it will be set to false and vice-versa). Nothing is returned.

### Question 9
*True* or *False*. If an array named list has size 10, its final element is denoted by list.get(9).

### Question 10
Examine the following Java statements, then fill in the rest of the code as instructed. You do not need to write a complete program, just the Java statements to fulfill the following tasks.
* (a) Initialize the array list.
* (b) Using the scan variable and a loop, get thirteen names typed at the user?s keyboard and save them into the roster array list.
* (c) Print the contents of the roster array list, one name per line.
