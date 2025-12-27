# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
    def remove(str,n):
        a=""
        for i in range(len(str)):
            if i!=n:
                a+=str[i]
            else:
                pass
        return a
    str=input("Enter the string:")
    n=int(input("Enter the index of the element to be removed:"))
    print(remove(str,n))


## Output

<img width="1234" height="77" alt="image" src="https://github.com/user-attachments/assets/e0142b30-249b-4aae-8ce3-315ce5e8ced6" />


## Result

Thus the python program to accept a string and removes a character at a specified index is written and executed successfully. 
