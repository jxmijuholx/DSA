# Sort characters

Write a program that takes a single string as its input and sort its characters from the lowest Unicode value to the highest Unicode value. The program should print the new string.

<strong>The output from your program, when called with the code in the Test column, should be exactly as shown in the Result column:<strong>

| Syöte    | Tulos     |
|----------|-----------|
| wikipedia| adeiiikpw |
| assume   | aemssu    |

````python
def sort(input_string):
    result = ''.join(sorted(input_string))
    return result


if __name__ == "__main__":
    user_input = input().strip()
    print(sort(user_input))
````