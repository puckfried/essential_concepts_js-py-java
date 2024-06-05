# Essential Programming Concepts with Examples in JavaScript, Python, and Java

## creating a variable
- **Explanation**: Declaring a variable to store data.
- **Examples**:
  - **JavaScript**:
    ```javascript
    let x = 10;
    ```
  - **Python**:
    ```python
    x = 10
    ```
  - **Java**:
    ```java
    int x = 10;
    ```

## print command
- **Explanation**: Command to output text to console or display.
- **Examples**:
  - **JavaScript**:
    ```javascript
    console.log("Hello, world!");
    ```
  - **Python**:
    ```python
    print("Hello, world!")
    ```
  - **Java**:
    ```java
    System.out.println("Hello, world!");
    ```



## if statement
- **Explanation**: A conditional statement that runs code based on whether a condition is true.
- **Examples**:
  - **JavaScript**:
    ```javascript
    if (x > 10) {
      console.log("x is greater than 10");
    }
    ```
  - **Python**(Note: In Python, you use indentation for blocks instead of {} like in JavaScript or Java.):
    ```python
    if x > 10:
      print("x is greater than 10")
    ```
  - **Java**:
    ```java
    if (x > 10) {
      System.out.println("x is greater than 10");
    }
    ```

## comparison logic operators
- **Explanation**: Used to compare values and return true or false. <br>
    --> The symbol && is used for connecting two boolean values with logical AND <br>
    --> The symbol || is used for connecting two boolean values with logical OR
- **Examples**:
  - **JavaScript**:
    ```javascript
    x == 10
    x != 10
    x > 10
    x < 10
    x >= 10
    x <= 10
    x > 5 && x < 10 
    x == 5 || x == 10
    ```
  - **Python**:
    ```python
    x == 10
    x != 10
    x > 10
    x < 10
    x >= 10
    x <= 10
    x > 5 and x < 10
    x == 5 or x == 10
    ```
  - **Java**:
    ```java
    x == 10
    x != 10
    x > 10
    x < 10
    x >= 10
    x <= 10
    x > 5 && x < 10
    x == 5 || x == 10
    ```


## asking for input
- **Explanation**: Getting user input from a field or console.
- **Examples**:
  - **JavaScript (in a browser)**:
    ```javascript
    let value = document.getElementById("inputField").value;
    ```
  - **Python**:
    ```python
    x = input("Enter a value: ")
    ```
  - **Java**:
    ```java
    Scanner sc = new Scanner(System.in);
    int x = sc.nextInt();
    ```


## for loop
- **Explanation**: A loop that repeats code a set number of times.
- **Examples**:
  - **JavaScript**:
    ```javascript
    for (let i = 0; i < 10; i++) {
      console.log(i);
    }
    ```
  - **Python**:
    ```python
    for i in range(10):
      print(i)
    ```
  - **Java**:
    ```java
    for (int i = 0; i < 10; i++) {
      System.out.println(i);
    }
    ```

## while loop
- **Explanation**: A loop that repeats code while a condition is true.
- **Examples**:
  - **JavaScript**:
    ```javascript
    while (x < 10) {
      x++;
    }
    ```
  - **Python**:
    ```python
    while x < 10:
      x += 1
    ```
  - **Java**:
    ```java
    while (x < 10) {
      x++;
    }
    ```

## creating a function
- **Explanation**: A block of code designed to perform a particular task.
- **Examples**:
  - **JavaScript**:
    ```javascript
    function greet() {
      console.log("Hello, world!");
    }
    ```
  - **Python**:
    ```python
    def greet():
      print("Hello, world!")
    ```
  - **Java** (Note: In Java, functions are always part of a class):
    ```java
    public void greet() {
      System.out.println("Hello, world!");
    }
    ```

