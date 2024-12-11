# Arithmetic

Write a program that takes two integers, a and b, as input.
Your program should compute and display:
- The sum of a and b
- The difference when b is subtracted from a
- The product of a and b
- The quotient when a is divided by b
- The remainder when a is divided by b
- The result of log10 a
- The result of a^b

<strong>The output from your program, when called with the code in the Test column, should be exactly as shown in the Result column<strong>
<table border="1" style="border-collapse: collapse; text-align: left;">
  <thead>
    <tr>
      <th>Syöte</th>
      <th>Tulos</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2">10<br>2</td>
      <td>
        10 + 2 is 12<br>
        10 - 2 is 8<br>
        10 * 2 is 20<br>
        10 / 2 is 5.0<br>
        10 % 2 is 0<br>
        10 ^ 2 is 100
      </td>
    </tr>
    <tr>
      <td></td>
    </tr>
    <tr>
      <td rowspan="2">4<br>2</td>
      <td>
        4 + 2 is 6<br>
        4 - 2 is 2<br>
        4 * 2 is 8<br>
        4 / 2 is 2.0<br>
        4 % 2 is 0<br>
        4 ^ 2 is 16
      </td>
    </tr>
    <tr>
      <td></td>
    </tr>
  </tbody>
</table>

````python
def arithmetic(a,b):
    print(f"{a} + {b} is {a + b}")
    print(f"{a} - {b} is {a - b}")
    print(f"{a} * {b} is {a * b}")
    print(f"{a} / {b} is {a / b}")
    print(f"{a} % {b} is {a % b}")
    print(f"{a} ^ {b} is {a ** b}")
    
if __name__ == "__main__":
    a = int(input().strip())
    b = int(input().strip())
    arithmetic(a,b)
````
