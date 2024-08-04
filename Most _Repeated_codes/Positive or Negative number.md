## logic :

- N > 0 then, number is Positive.
- N < 0 then, number is Negative.
- N = 0 then, number is Zero.

# Methods

## 1.using brute force

```java
class Main
{
  public static void main (String[]args)
  {

    int num = 5;

    //Conditions to check if the number is negative or positive
    if (num > 0)
        System.out.println ("The number is positive");
    else if (num < 0)
        System.out.println ("The number is negative");
    else
        System.out.println ("Zero");
  }
}
```

2 . 

## 2.using nested if

### **Algorithm**

This method uses a nested if-else Statements to check whether a given number is Positive or Negative.

- **Step 1** – Start
- **Step 2** – Insert the number.
- **Step 3** – If the number is greater or equal move to the inner nested loop
    - **Step 3.1** – If the number is zero, print Zero
    - **Step 3.2** – Else print The Number is Positive
- **Step 4** – Else the number has to be negative, Print The number is Negative
- **Step 5** – Stop

```java
//Using Nested If-else statement
class Main
{
  public static void main (String[]args)
  {

    int num = 5;
    
     //Condition to check if the number is negative or positive
    if (num >= 0)
    {
        if (num == 0)
            System.out.println ("Zero");
        else
            System.out.println ("The number is positive");
    }
    else
        System.out.println ("The number is negative");

  }
}
```

## **3.Using Ternary Operator**