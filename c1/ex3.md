# Squares

Write a program that prints a dictionary where the keys are numbers between 1 and N, and the values are square of keys.

Input Specification:
- The first line of input contains N

Output Specification:
Print the dictionary

<strong>The output from your program, when called with the code in the Test column, should be exactly as shown in the Result column:<strong>
<table border="1" style="border-collapse: collapse; text-align: left; width: 100%;">
  <thead>
    <tr>
      <th>Syöte</th>
      <th>Tulos</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>10</td>
      <td>{1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64, 9: 81, 10: 100}</td>
    </tr>
  </tbody>
</table>

````python
def squares(num):
    sqrts = {}
    for i in range (1, 1+n):
        sqrts[i] = i * i
    print(sqrts)
    
if __name__ == "__main__":
    n = int(input().strip())
    squares(n)
        
````