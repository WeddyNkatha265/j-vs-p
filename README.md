| **Feature**          | **Python Code**                                                                                     | **JavaScript Code**                                                                                 |
|----------------------|-----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| **Variable Declaration** | ```x = 10``` <br> No keyword needed, and type is inferred.                                        | ```let x = 10;``` <br> Uses `let`, `const`, or `var` for declaration.                                |
| **Function Definition**  | ```def greet(name):``` <br> ```return f"Hello, {name}!"```                                               | ```function greet(name) {``` <br> ```return `Hello, ${name}!`;``` <br>}```                                    |
| **Conditional Statements** | ```if x > 0:``` <br> ```print("Positive")```                                                           | ```if (x > 0) {``` <br> ```console.log("Positive");``` <br>}```                                               |
| **Loops**            | ```for i in range(5):``` <br> ```print(i)```                                                               | ```for (let i = 0; i < 5; i++) {``` <br> ```console.log(i);``` <br>}```                                       |
| **List/Array**       | ```numbers = [1, 2, 3, 4, 5]``` <br> Dynamic and can hold mixed types.                               | ```let numbers = [1, 2, 3, 4, 5];``` <br> Dynamic but typically holds similar types.                 |
| **Dictionary/Object**| ```person = {"name": "Alice", "age": 25}``` <br> Key-value pairs in a dictionary.                   | ```let person = {name: "Alice", age: 25};``` <br> Key-value pairs in an object.                     |
| **Print/Output**     | ```print("Hello, World!")```                                                                        | ```console.log("Hello, World!");```                                                                 |
| **Importing Modules**| ```import math``` <br> ```print(math.sqrt(16))```                                                          | ```import { sqrt } from 'mathjs';``` <br> ```console.log(sqrt(16));```                                     |
| **Exception Handling** | ```try:``` <br> ```result = 10 / 0``` <br> ```except ZeroDivisionError:``` <br> ```print("Cannot divide by zero!")``` | ```try {``` <br> ```let result = 10 / 0;``` <br>}``` ```catch (e) {``` <br> ```console.log("Cannot divide by zero!");``` <br>}``` |
