# Quiz 7 Corrections

## Question 13
Which method(s) of the ArrayList class is being called in the code segment below?

    ArrayList<String> names = new ArrayList<String>();
    
    names.add("Paul");
    names.remove(0);

    System.out.println("There are " + names.size() + " elements in the ArrayList.");

Select all that apply.

## Answer(s)
    The remove method.
    The size method.
    The add method.

## Explanation
  An ArrayList is an object and as such, unlike many primitives, to figure out its size and other behaviors, methods must be called (instead of just retrieving their properties). Within the ArrayList class, there are certain methods that are commonly called. These include the size() method, the add() method, and the remove() method, all of which are called in this section of code. I had mistakenly answered that all three of these options, as well as the ArrayList default constructor, were methods that had been called. However, because a constructor is not considered a method (as it does not have a return type and can be evoked implicitly, amongst other things), it can not be included in the list of methods called in the code segment above. Thus, the correct answers are the three listed above. 
